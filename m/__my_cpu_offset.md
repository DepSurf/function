# Function: <code>__my_cpu_offset</code>

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
long unsigned int __my_cpu_offset();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffff800010084f1c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
  - init/main.c:rest_init
Direct callers:
  - init/main.c:trace_initcall_level
```
```
In init/calibrate.c (ffff800010085874)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - init/calibrate.c:calibrate_delay
```
```
In arch/arm64/kernel/debug-monitors.c (ffff800010086314)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kernel/debug-monitors.c:disable_debug_monitors
  - arch/arm64/kernel/debug-monitors.c:disable_debug_monitors
  - arch/arm64/kernel/debug-monitors.c:enable_debug_monitors
  - arch/arm64/kernel/debug-monitors.c:enable_debug_monitors
```
```
In arch/arm64/kernel/irq.c (ffff800010086e4c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
```
```
In arch/arm64/kernel/fpsimd.c (ffff8000100887f0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kernel/fpsimd.c:__efi_fpsimd_end
  - arch/arm64/kernel/fpsimd.c:__efi_fpsimd_end
  - arch/arm64/kernel/fpsimd.c:__efi_fpsimd_end
  - arch/arm64/kernel/fpsimd.c:__efi_fpsimd_end
  - arch/arm64/kernel/fpsimd.c:__efi_fpsimd_begin
  - arch/arm64/kernel/fpsimd.c:__efi_fpsimd_begin
  - arch/arm64/kernel/fpsimd.c:__efi_fpsimd_begin
  - arch/arm64/kernel/fpsimd.c:__efi_fpsimd_begin
  - arch/arm64/kernel/fpsimd.c:__efi_fpsimd_begin
  - arch/arm64/kernel/fpsimd.c:fpsimd_flush_cpu_state
  - arch/arm64/kernel/fpsimd.c:fpsimd_bind_state_to_cpu
  - arch/arm64/kernel/fpsimd.c:fpsimd_bind_task_to_cpu
  - arch/arm64/kernel/fpsimd.c:fpsimd_bind_task_to_cpu
  - arch/arm64/kernel/fpsimd.c:fpsimd_thread_switch
  - arch/arm64/kernel/fpsimd.c:fpsimd_save
  - arch/arm64/kernel/fpsimd.c:fpsimd_save
  - arch/arm64/kernel/fpsimd.c:task_fpsimd_load
Direct callers:
  - arch/arm64/kernel/fpsimd.c:sve_verify_vq_map
  - arch/arm64/kernel/fpsimd.c:sve_verify_vq_map
```
```
In arch/arm64/kernel/process.c (ffff8000100894e4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kernel/process.c:__switch_to
  - arch/arm64/kernel/process.c:arch_cpu_idle
  - arch/arm64/kernel/process.c:arch_cpu_idle
  - arch/arm64/kernel/process.c:arch_cpu_idle
  - arch/arm64/kernel/process.c:arch_cpu_idle
```
```
In arch/arm64/kernel/ptrace.c (ffff80001008ef2c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:syscall_trace_exit
  - arch/arm64/kernel/ptrace.c:syscall_trace_enter
  - arch/arm64/kernel/ptrace.c:regs_get_kernel_stack_nth
  - arch/arm64/kernel/ptrace.c:perf_trace_sys_exit
  - arch/arm64/kernel/ptrace.c:perf_trace_sys_enter
```
```
In arch/arm64/kernel/stacktrace.c (ffff800010093a24)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kernel/stacktrace.c:unwind_frame
  - arch/arm64/kernel/stacktrace.c:unwind_frame
```
```
In arch/arm64/kernel/traps.c (ffff80001009583c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:do_serror
  - arch/arm64/kernel/traps.c:do_serror
Direct callers:
  - arch/arm64/kernel/traps.c:arm64_serror_panic
  - arch/arm64/kernel/traps.c:handle_bad_stack
  - arch/arm64/kernel/traps.c:handle_bad_stack
  - arch/arm64/kernel/traps.c:bad_mode
```
```
In arch/arm64/kernel/cpuinfo.c (ffff800010098178)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kernel/cpuinfo.c:cpuinfo_store_cpu
  - arch/arm64/kernel/cpuinfo.c:cpuinfo_store_cpu
  - arch/arm64/kernel/cpuinfo.c:__cpuinfo_store_cpu
```
```
In arch/arm64/kernel/cpu_errata.c (ffff800010098e50)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kernel/cpu_errata.c:has_ssbd_mitigation
```
```
In arch/arm64/kernel/cpufeature.c (ffff80001009a194)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kernel/cpufeature.c:kpti_install_ng_mappings
Direct callers:
  - arch/arm64/kernel/cpufeature.c:check_local_cpu_capabilities
  - arch/arm64/kernel/cpufeature.c:verify_local_elf_hwcaps
  - arch/arm64/kernel/cpufeature.c:verify_local_cpu_caps
```
```
In arch/arm64/kernel/alternative.c (ffff80001009b248)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Direct callers:
  - arch/arm64/kernel/alternative.c:apply_boot_alternatives
```
```
In arch/arm64/kernel/cacheinfo.c (ffff80001009b8f8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kernel/cacheinfo.c:_populate_cache_leaves
  - arch/arm64/kernel/cacheinfo.c:_init_cache_level
```
```
In arch/arm64/kernel/smp.c (ffff80001009d4d4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:cpus_are_stuck_in_kernel
  - arch/arm64/kernel/smp.c:crash_smp_send_stop
  - arch/arm64/kernel/smp.c:crash_smp_send_stop
  - arch/arm64/kernel/smp.c:crash_smp_send_stop
  - arch/arm64/kernel/smp.c:smp_send_stop
  - arch/arm64/kernel/smp.c:smp_send_stop
  - arch/arm64/kernel/smp.c:smp_send_stop
  - arch/arm64/kernel/smp.c:smp_send_stop
  - arch/arm64/kernel/smp.c:smp_send_stop
  - arch/arm64/kernel/smp.c:tick_broadcast
  - arch/arm64/kernel/smp.c:smp_send_reschedule
  - arch/arm64/kernel/smp.c:handle_IPI
  - arch/arm64/kernel/smp.c:handle_IPI
  - arch/arm64/kernel/smp.c:handle_IPI
  - arch/arm64/kernel/smp.c:handle_IPI
  - arch/arm64/kernel/smp.c:arch_irq_work_raise
  - arch/arm64/kernel/smp.c:arch_irq_work_raise
  - arch/arm64/kernel/smp.c:arch_send_wakeup_ipi_mask
  - arch/arm64/kernel/smp.c:arch_send_call_function_single_ipi
  - arch/arm64/kernel/smp.c:arch_send_call_function_ipi_mask
  - arch/arm64/kernel/smp.c:__cpu_disable
  - arch/arm64/kernel/smp.c:perf_trace_ipi_handler
  - arch/arm64/kernel/smp.c:perf_trace_ipi_raise
Direct callers:
  - arch/arm64/kernel/smp.c:crash_smp_send_stop
  - arch/arm64/kernel/smp.c:local_cpu_stop
  - arch/arm64/kernel/smp.c:smp_prepare_cpus
  - arch/arm64/kernel/smp.c:smp_prepare_cpus
  - arch/arm64/kernel/smp.c:smp_prepare_boot_cpu
  - arch/arm64/kernel/smp.c:cpu_die_early
  - arch/arm64/kernel/smp.c:cpu_die
```
```
In arch/arm64/kernel/syscall.c (ffff80001009da9c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
```
```
In arch/arm64/kernel/perf_event.c (ffff8000100a4860)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kernel/perf_event.c:armv8pmu_handle_irq
  - arch/arm64/kernel/perf_event.c:armv8pmu_stop
  - arch/arm64/kernel/perf_event.c:armv8pmu_start
  - arch/arm64/kernel/perf_event.c:armv8pmu_disable_event
  - arch/arm64/kernel/perf_event.c:armv8pmu_enable_event
Direct callers:
  - arch/arm64/kernel/perf_event.c:armv8pmu_write_counter
  - arch/arm64/kernel/perf_event.c:armv8pmu_read_counter
```
```
In arch/arm64/kernel/hw_breakpoint.c (ffff8000100a5e80)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_reset
  - arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_reset
  - arch/arm64/kernel/hw_breakpoint.c:reinstall_suspended_bps
  - arch/arm64/kernel/hw_breakpoint.c:watchpoint_handler
  - arch/arm64/kernel/hw_breakpoint.c:watchpoint_handler
  - arch/arm64/kernel/hw_breakpoint.c:breakpoint_handler
  - arch/arm64/kernel/hw_breakpoint.c:breakpoint_handler
  - arch/arm64/kernel/hw_breakpoint.c:toggle_bp_registers
  - arch/arm64/kernel/hw_breakpoint.c:toggle_bp_registers
  - arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_control
  - arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_control
```
```
In arch/arm64/kernel/suspend.c (ffff8000100a69ac)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
```
```
In arch/arm64/kernel/cpuidle.c (ffff8000100a6fcc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kernel/cpuidle.c:arm_cpuidle_suspend
```
```
In arch/arm64/kernel/kgdb.c (ffff8000100a7644)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kernel/kgdb.c:kgdb_arch_handle_exception
```
```
In arch/arm64/kernel/armv8_deprecated.c (ffff8000100a8f84)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kernel/armv8_deprecated.c:cp15barrier_handler
  - arch/arm64/kernel/armv8_deprecated.c:cp15barrier_handler
  - arch/arm64/kernel/armv8_deprecated.c:cp15barrier_handler
  - arch/arm64/kernel/armv8_deprecated.c:swp_handler
  - arch/arm64/kernel/armv8_deprecated.c:swp_handler
  - arch/arm64/kernel/armv8_deprecated.c:perf_trace_instruction_emulation
```
```
In arch/arm64/kernel/acpi.c (ffff8000100a944c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kernel/acpi.c:apei_claim_sea
  - arch/arm64/kernel/acpi.c:apei_claim_sea
```
```
In arch/arm64/kernel/acpi_parking_protocol.c (ffff8000100a97ac)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
```
```
In arch/arm64/kernel/machine_kexec.c (ffff8000100a9fb0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kernel/machine_kexec.c:machine_crash_shutdown
```
```
In arch/arm64/kernel/sdei.c (ffff800010da7e14)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kernel/sdei.c:__sdei_handler
  - arch/arm64/kernel/sdei.c:__sdei_handler
  - arch/arm64/kernel/sdei.c:_on_sdei_stack
  - arch/arm64/kernel/sdei.c:_on_sdei_stack
```
```
In arch/arm64/kernel/probes/kprobes.c (ffff800010da8074)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kernel/probes/kprobes.c:kprobe_breakpoint_handler
  - arch/arm64/kernel/probes/kprobes.c:kprobe_breakpoint_handler
  - arch/arm64/kernel/probes/kprobes.c:kprobe_breakpoint_handler
  - arch/arm64/kernel/probes/kprobes.c:kprobe_breakpoint_handler
  - arch/arm64/kernel/probes/kprobes.c:kprobe_breakpoint_handler
  - arch/arm64/kernel/probes/kprobes.c:kprobe_single_step_handler
  - arch/arm64/kernel/probes/kprobes.c:kprobe_fault_handler
  - arch/arm64/kernel/probes/kprobes.c:kprobe_fault_handler
  - arch/arm64/kernel/probes/kprobes.c:kprobe_fault_handler
  - arch/arm64/kernel/probes/kprobes.c:arch_simulate_insn
  - arch/arm64/kernel/probes/kprobes.c:post_kprobe_handler
  - arch/arm64/kernel/probes/kprobes.c:post_kprobe_handler
  - arch/arm64/kernel/probes/kprobes.c:post_kprobe_handler
  - arch/arm64/kernel/probes/kprobes.c:trampoline_probe_handler
  - arch/arm64/kernel/probes/kprobes.c:trampoline_probe_handler
  - arch/arm64/kernel/probes/kprobes.c:trampoline_probe_handler
```
```
In arch/arm64/mm/fault.c (ffff800010081264)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/mm/fault.c:do_debug_exception
  - arch/arm64/mm/fault.c:do_debug_exception
  - arch/arm64/mm/fault.c:do_sp_pc_abort
  - arch/arm64/mm/fault.c:do_el0_ia_bp_hardening
  - arch/arm64/mm/fault.c:do_el0_irq_bp_hardening
  - arch/arm64/mm/fault.c:do_page_fault
```
```
In arch/arm64/mm/context.c (ffff8000100afc60)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:check_and_switch_context
Direct callers:
  - arch/arm64/mm/context.c:verify_cpu_asid_bits
  - arch/arm64/mm/context.c:get_cpu_asid_bits
```
```
In virt/kvm/kvm_main.c (ffff8000100b8aa4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:hardware_disable_nolock
  - virt/kvm/kvm_main.c:hardware_enable_nolock
  - virt/kvm/kvm_main.c:kvm_vcpu_ioctl
  - virt/kvm/kvm_main.c:kvm_vcpu_kick
  - virt/kvm/kvm_main.c:kvm_vcpu_block
  - virt/kvm/kvm_main.c:kvm_vcpu_block
  - virt/kvm/kvm_main.c:kvm_vcpu_block
  - virt/kvm/kvm_main.c:kvm_make_vcpus_request_mask
  - virt/kvm/kvm_main.c:vcpu_load
  - virt/kvm/kvm_main.c:perf_trace_kvm_halt_poll_ns
  - virt/kvm/kvm_main.c:perf_trace_kvm_age_page
  - virt/kvm/kvm_main.c:perf_trace_kvm_fpu
  - virt/kvm/kvm_main.c:perf_trace_kvm_mmio
  - virt/kvm/kvm_main.c:perf_trace_kvm_ack_irq
  - virt/kvm/kvm_main.c:perf_trace_kvm_set_irq
  - virt/kvm/kvm_main.c:perf_trace_kvm_vcpu_wakeup
  - virt/kvm/kvm_main.c:perf_trace_kvm_userspace_exit
```
```
In virt/kvm/eventfd.c (ffff8000100c0e7c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - virt/kvm/eventfd.c:kvm_notify_acked_irq
```
```
In virt/kvm/arm/arm.c (ffff8000100c594c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:cpu_hyp_reinit
  - virt/kvm/arm/arm.c:cpu_hyp_reinit
  - virt/kvm/arm/arm.c:cpu_hyp_reinit
  - virt/kvm/arm/arm.c:cpu_hyp_reinit
  - virt/kvm/arm/arm.c:kvm_vm_ioctl_irq_line
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_put
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_load
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_load
  - virt/kvm/arm/arm.c:kvm_arm_get_running_vcpu
  - virt/kvm/arm/arm.c:perf_trace_kvm_timer_emulate
  - virt/kvm/arm/arm.c:perf_trace_kvm_timer_hrtimer_expire
  - virt/kvm/arm/arm.c:perf_trace_kvm_timer_restore_state
  - virt/kvm/arm/arm.c:perf_trace_kvm_timer_save_state
  - virt/kvm/arm/arm.c:perf_trace_kvm_get_timer_map
  - virt/kvm/arm/arm.c:perf_trace_kvm_timer_update_irq
  - virt/kvm/arm/arm.c:perf_trace_kvm_toggle_cache
  - virt/kvm/arm/arm.c:perf_trace_kvm_set_way_flush
  - virt/kvm/arm/arm.c:perf_trace_kvm_test_age_hva
  - virt/kvm/arm/arm.c:perf_trace_kvm_age_hva
  - virt/kvm/arm/arm.c:perf_trace_kvm_set_spte_hva
  - virt/kvm/arm/arm.c:perf_trace_kvm_unmap_hva_range
  - virt/kvm/arm/arm.c:perf_trace_kvm_mmio_emulate
  - virt/kvm/arm/arm.c:perf_trace_kvm_irq_line
  - virt/kvm/arm/arm.c:perf_trace_kvm_access_fault
  - virt/kvm/arm/arm.c:perf_trace_kvm_guest_fault
  - virt/kvm/arm/arm.c:perf_trace_kvm_exit
  - virt/kvm/arm/arm.c:perf_trace_kvm_entry
```
```
In virt/kvm/arm/mmu.c (ffff8000100cd314)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:kvm_toggle_cache
  - virt/kvm/arm/mmu.c:kvm_set_way_flush
  - virt/kvm/arm/mmu.c:kvm_test_age_hva
  - virt/kvm/arm/mmu.c:kvm_age_hva
  - virt/kvm/arm/mmu.c:kvm_set_spte_hva
  - virt/kvm/arm/mmu.c:kvm_unmap_hva_range
  - virt/kvm/arm/mmu.c:kvm_handle_guest_abort
  - virt/kvm/arm/mmu.c:kvm_handle_guest_abort
```
```
In virt/kvm/arm/mmio.c (ffff8000100cdd00)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - virt/kvm/arm/mmio.c:io_mem_abort
  - virt/kvm/arm/mmio.c:io_mem_abort
  - virt/kvm/arm/mmio.c:kvm_handle_mmio_return
```
```
In arch/arm64/kvm/handle_exit.c (ffff8000100d15c0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kvm/handle_exit.c:kvm_handle_wfx
  - arch/arm64/kvm/handle_exit.c:kvm_handle_wfx
  - arch/arm64/kvm/handle_exit.c:handle_hvc
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_set_guest_debug
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_sys_access
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_handle_sys_reg
  - arch/arm64/kvm/handle_exit.c:perf_trace_trap_reg
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_arm_set_regset
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_arm_set_dreg32
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_arm_clear_debug
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_arm_setup_debug
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_hvc_arm64
  - arch/arm64/kvm/handle_exit.c:perf_trace_kvm_wfx_arm64
```
```
In arch/arm64/kvm/guest.c (ffff8000100d3c10)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kvm/guest.c:kvm_arch_vcpu_ioctl_set_guest_debug
```
```
In arch/arm64/kvm/debug.c (ffff8000100d4494)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kvm/debug.c:kvm_arm_clear_debug
  - arch/arm64/kvm/debug.c:kvm_arm_clear_debug
  - arch/arm64/kvm/debug.c:kvm_arm_clear_debug
  - arch/arm64/kvm/debug.c:kvm_arm_clear_debug
  - arch/arm64/kvm/debug.c:kvm_arm_setup_debug
  - arch/arm64/kvm/debug.c:kvm_arm_setup_debug
  - arch/arm64/kvm/debug.c:kvm_arm_setup_debug
  - arch/arm64/kvm/debug.c:kvm_arm_setup_debug
  - arch/arm64/kvm/debug.c:kvm_arm_setup_debug
  - arch/arm64/kvm/debug.c:kvm_arm_setup_debug
  - arch/arm64/kvm/debug.c:kvm_arm_setup_debug
  - arch/arm64/kvm/debug.c:kvm_arm_setup_debug
  - arch/arm64/kvm/debug.c:kvm_arm_init_debug
```
```
In arch/arm64/kvm/reset.c (ffff8000100d4c34)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kvm/reset.c:kvm_reset_vcpu
```
```
In arch/arm64/kvm/sys_regs.c (ffff8000100d9604)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kvm/sys_regs.c:kvm_handle_sys_reg
  - arch/arm64/kvm/sys_regs.c:perform_access
  - arch/arm64/kvm/sys_regs.c:trap_xvr
  - arch/arm64/kvm/sys_regs.c:trap_wcr
  - arch/arm64/kvm/sys_regs.c:trap_wvr
  - arch/arm64/kvm/sys_regs.c:trap_bcr
  - arch/arm64/kvm/sys_regs.c:trap_bvr
  - arch/arm64/kvm/sys_regs.c:trap_debug_regs
```
```
In arch/arm64/kvm/pmu.c (ffff8000100db30c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kvm/pmu.c:kvm_clr_pmu_events
  - arch/arm64/kvm/pmu.c:kvm_set_pmu_events
```
```
In virt/kvm/arm/vgic/vgic.c (ffff8000100dc5e4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_inject_irq
  - virt/kvm/arm/vgic/vgic.c:perf_trace_vgic_update_irq_pending
```
```
In virt/kvm/arm/vgic/vgic-v4.c (ffff8000100e0ba8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_flush_hwstate
```
```
In virt/kvm/irqchip.c (ffff8000100ebd84)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - virt/kvm/irqchip.c:kvm_set_irq
```
```
In virt/kvm/arm/arch_timer.c (ffff8000100ed11c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_load
  - virt/kvm/arm/arch_timer.c:timer_restore_state
  - virt/kvm/arm/arch_timer.c:timer_save_state
  - virt/kvm/arm/arch_timer.c:kvm_hrtimer_expire
  - virt/kvm/arm/arch_timer.c:get_timer_map
```
```
In arch/arm64/kvm/hyp/switch.c (ffff8000100efc74)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/switch.c:activate_traps_vhe
```
```
In kernel/fork.c (ffff8000100f4d30)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/panic.c (ffff8000100f64c0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/panic.c:nmi_panic
Direct callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:__warn
  - kernel/panic.c:panic
```
```
In kernel/cpu.c (ffff8000100f9068)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_should_run
  - kernel/cpu.c:cpus_read_trylock
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
Direct callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
  - kernel/cpu.c:boot_cpu_hotplug_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:cpuhp_threads_init
```
```
In kernel/exit.c (ffff8000100fbb30)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:release_task
  - kernel/exit.c:delayed_put_task_struct
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffff8000100ff6f8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:ksoftirqd_should_run
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:__raise_softirq_irqoff
  - kernel/softirq.c:__raise_softirq_irqoff
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:ksoftirqd_running
  - kernel/softirq.c:wakeup_softirqd
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (ffff80001010fbc0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/sys.c (ffff80001011725c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_sys_getcpu
```
```
In kernel/workqueue.c (ffff800010122c30)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_delayed_work
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
Direct callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/kthread.c (ffff800010128648)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffff80001012fc74)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
Direct callers:
  - kernel/smpboot.c:idle_threads_init
  - kernel/smpboot.c:idle_thread_set_boot_cpu
```
```
In kernel/kmod.c (ffff8000101306dc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffff80001013d0a0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:single_task_running
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:migration_init
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_stat_template
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
```
```
In kernel/sched/loadavg.c (ffff80001013e980)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_load_nohz_stop
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/cputime.c (ffff80001013f41c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_idle_time
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/idle.c (ffff80001013fc2c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:sched_idle_set_state
```
```
In kernel/sched/fair.c (ffff800010145b4c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:attach_entity_load_avg
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffff8000101518c0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/deadline.c (ffff800010152500)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/sched/deadline.c:find_later_rq
```
```
In kernel/sched/pelt.c (ffff80001015ee44)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/sched/debug.c (0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: False
```
```
In kernel/sched/cpuacct.c (ffff8000101649a0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_account_field
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/sched/cpufreq.c (ffff800010164ac4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/sched/cpufreq.c:cpufreq_this_cpu_can_update
```
```
In kernel/sched/cpufreq_schedutil.c (ffff800010164dec)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
```
In kernel/sched/membarrier.c (ffff8000101662b4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__arm64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_exec_mmap
```
```
In kernel/sched/isolation.c (ffff800010166488)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Direct callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/sched/psi.c (ffff800010167864)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
```
In kernel/locking/percpu-rwsem.c (ffff80001016a454)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_up_read
```
```
In kernel/locking/osq_lock.c (ffff80001016a758)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffff80001016a938)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:queued_spin_lock_slowpath
```
```
In kernel/power/qos.c (ffff80001016e084)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffff80001016ff54)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffff800010170f48)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/printk/printk.c (ffff800010175fc0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/printk/printk.c:defer_console_output
  - kernel/printk/printk.c:defer_console_output
  - kernel/printk/printk.c:wake_up_klogd
  - kernel/printk/printk.c:wake_up_klogd
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:perf_trace_console
Direct callers:
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
```
```
In kernel/printk/printk_safe.c (ffff800010176ff4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk_func
  - kernel/printk/printk_safe.c:vprintk_func
  - kernel/printk/printk_safe.c:vprintk_func
  - kernel/printk/printk_safe.c:vprintk_func
  - kernel/printk/printk_safe.c:__printk_safe_exit
  - kernel/printk/printk_safe.c:__printk_safe_enter
  - kernel/printk/printk_safe.c:printk_nmi_direct_exit
  - kernel/printk/printk_safe.c:printk_nmi_direct_enter
  - kernel/printk/printk_safe.c:printk_nmi_direct_enter
  - kernel/printk/printk_safe.c:printk_nmi_exit
  - kernel/printk/printk_safe.c:printk_nmi_enter
```
```
In kernel/irq/irqdesc.c (ffff800010177fe8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:handle_domain_nmi
  - kernel/irq/irqdesc.c:handle_domain_nmi
  - kernel/irq/irqdesc.c:__handle_domain_irq
  - kernel/irq/irqdesc.c:__handle_domain_irq
Direct callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/handle.c (ffff8000101787cc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/manage.c (ffff80001017923c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
```
```
In kernel/irq/spurious.c (ffff80001017d0e4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:irq_wait_for_poll
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (ffff80001017ecd0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_fasteoi_mask_irq
  - kernel/irq/chip.c:handle_fasteoi_mask_irq
  - kernel/irq/chip.c:handle_fasteoi_ack_irq
  - kernel/irq/chip.c:handle_fasteoi_ack_irq
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:handle_nested_irq
```
```
In kernel/irq/cpuhotplug.c (ffff8000101863a4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In kernel/rcu/update.c (ffff800010188670)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/rcu/srcutree.c (ffff80001018b254)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:__srcu_read_unlock
  - kernel/rcu/srcutree.c:__srcu_read_lock
```
```
In kernel/rcu/tree.c (ffff8000101920d0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_needs_cpu
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_qs
  - kernel/rcu/tree.c:rcu_qs
  - kernel/rcu/tree.c:rcu_qs
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread_should_run
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_idle_exit
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_idle_enter
  - kernel/rcu/tree.c:rcu_idle_enter
  - kernel/rcu/tree.c:rcu_is_cpu_rrupt_from_idle
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
  - kernel/rcu/tree.c:rcu_dynticks_eqs_enter
Direct callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/dma/direct.c (ffff800010194edc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/dma/swiotlb.c (ffff800010196f4c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
```
```
In kernel/profile.c (ffff800010199364)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/profile.c:profile_tick
  - kernel/profile.c:__profile_flip_buffers
```
```
In kernel/time/timer.c (ffff8000101a0298)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:run_local_timers
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:timer_clear_idle
  - kernel/time/timer.c:get_next_timer_interrupt
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:detach_if_pending
  - kernel/time/timer.c:enqueue_timer
  - kernel/time/timer.c:round_jiffies_up_relative
  - kernel/time/timer.c:round_jiffies_up
  - kernel/time/timer.c:round_jiffies_relative
  - kernel/time/timer.c:round_jiffies
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/hrtimer.c (ffff8000101a27a4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_init
  - kernel/time/hrtimer.c:__hrtimer_init
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_get_next_event
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:retrigger_next_event
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
```
In kernel/time/alarmtimer.c (ffff8000101a96dc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101ad5f8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
```
```
In kernel/time/itimer.c (ffff8000101aff94)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/clockevents.c (ffff8000101b0cb4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/time/tick-common.c (ffff8000101b22e8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-common.c:tick_suspend_local
  - kernel/time/tick-common.c:tick_handover_do_timer
  - kernel/time/tick-common.c:tick_broadcast_oneshot_control
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_install_replacement
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-common.c:tick_periodic
  - kernel/time/tick-common.c:tick_is_oneshot_available
```
```
In kernel/time/tick-broadcast.c (ffff8000101b259c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_check_broadcast_expired
  - kernel/time/tick-broadcast.c:tick_resume_check_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-broadcast.c:tick_receive_broadcast
```
```
In kernel/time/tick-oneshot.c (ffff8000101b4840)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/time/tick-oneshot.c:tick_oneshot_mode_active
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
```
In kernel/time/tick-sched.c (ffff8000101b5e5c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_oneshot_notify
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_get_idle_calls
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_get_next_hrtimer
  - kernel/time/tick-sched.c:tick_nohz_idle_got_tick
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_retain_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_next_event
  - kernel/time/tick-sched.c:tick_nohz_stop_idle
  - kernel/time/tick-sched.c:tick_nohz_tick_stopped
  - kernel/time/tick-sched.c:tick_sched_do_timer
```
```
In kernel/smp.c (ffff8000101bccc8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:flush_smp_call_function_queue
  - kernel/smp.c:flush_smp_call_function_queue
  - kernel/smp.c:generic_exec_single
Direct callers:
  - kernel/smp.c:flush_smp_call_function_queue
  - kernel/smp.c:call_function_init
```
```
In kernel/module.c (ffff8000101c566c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/module.c:try_module_get
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/kexec_core.c (ffff8000101c99d0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/cgroup/cgroup.c (ffff8000101d0810)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
```
In kernel/cgroup/rstat.c (ffff8000101d9d50)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dc8b0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffff8000101ddb9c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de784)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffff8000101dfbb4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffff8000101e4a7c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
  - kernel/cgroup/cpuset.c:cpuset_read_lock
```
```
In kernel/stop_machine.c (ffff8000101e8cbc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:multi_cpu_stop
Direct callers:
  - kernel/stop_machine.c:cpu_stop_init
```
```
In kernel/kprobes.c (ffff8000101f67a0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/kprobes.c:aggr_fault_handler
  - kernel/kprobes.c:aggr_post_handler
  - kernel/kprobes.c:aggr_post_handler
  - kernel/kprobes.c:aggr_pre_handler
  - kernel/kprobes.c:aggr_pre_handler
```
```
In kernel/debug/debug_core.c (ffff8000101fa9ac)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/debug/gdbstub.c (ffff8000101fc960)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In kernel/debug/kdb/kdb_io.c (ffff8000101fcdfc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (ffff800010201108)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_print_state
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
```
```
In kernel/debug/kdb/kdb_support.c (ffff800010203dfc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
```
```
In kernel/hung_task.c (ffff800010206fdc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/watchdog.c (ffff80001020767c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/watchdog.c:softlockup_start_fn
  - kernel/watchdog.c:softlockup_stop_fn
  - kernel/watchdog.c:watchdog_disable
  - kernel/watchdog.c:watchdog_disable
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:softlockup_fn
  - kernel/watchdog.c:softlockup_fn
  - kernel/watchdog.c:is_hardlockup
  - kernel/watchdog.c:touch_softlockup_watchdog_sync
  - kernel/watchdog.c:touch_softlockup_watchdog_sync
  - kernel/watchdog.c:touch_softlockup_watchdog
  - kernel/watchdog.c:__touch_watchdog
Direct callers:
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/seccomp.c (ffff8000102092a8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/relay.c (ffff80001020ac9c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/relay.c:relay_late_setup_files
```
```
In kernel/taskstats.c (ffff80001020dac8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:prepare_reply
```
```
In kernel/trace/trace_clock.c (ffff80001020efb0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (ffff800010210db8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ignore_task_cpu
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:profile_graph_return
  - kernel/trace/ftrace.c:ftrace_pid_func
```
```
In kernel/trace/ring_buffer.c (ffff80001021c600)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_nest_end
  - kernel/trace/ring_buffer.c:ring_buffer_nest_start
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffff800010221f58)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:put_trace_buf
  - kernel/trace/trace.c:get_trace_buf
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:disable_trace_buffered_event
  - kernel/trace/trace.c:enable_trace_buffered_event
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
```
In kernel/trace/trace_functions.c (ffff800010230124)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_init
```
```
In kernel/trace/trace_sched_wakeup.c (ffff800010230670)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_hwlat.c (ffff800010231ce0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:trace_hwlat_callback
```
```
In kernel/trace/trace_stack.c (ffff8000102322e0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_stop
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
  - kernel/trace/trace_stack.c:stack_trace_call
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_functions_graph.c (ffff8000102333ac)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffff8000102370dc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
```
```
In kernel/trace/trace_events.c (ffff80001023ad58)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (ffff80001023d97c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffff80001023ec44)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/trace/trace_events_filter.c (ffff80001023f154)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:filter_pred_cpu
```
```
In kernel/trace/trace_events_hist.c (ffff80001024b6d4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_field_cpu
  - kernel/trace/trace_events_hist.c:action_trace
```
```
In kernel/trace/bpf_trace.c (ffff80001024c688)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:put_bpf_raw_tp_regs
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
```
```
In kernel/trace/trace_kprobe.c (ffff800010251804)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/power-traces.c (ffff8000102541c4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:perf_trace_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (ffff800010254cb4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (ffff800010259bd0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:uprobe_buffer_get
```
```
In kernel/irq_work.c (ffff80001025b338)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/core.c (ffff80001025cc2c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
  - kernel/bpf/core.c:trace_event_raw_event_xdp_cpumap_enqueue
  - kernel/bpf/core.c:trace_event_raw_event_xdp_cpumap_kthread
  - kernel/bpf/core.c:bpf_user_rnd_u32
```
```
In kernel/bpf/syscall.c (ffff80001026515c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/helpers.c (ffff800010276924)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_local_storage
  - kernel/bpf/helpers.c:bpf_get_local_storage
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_unlock
  - kernel/bpf/helpers.c:bpf_spin_lock
  - kernel/bpf/helpers.c:bpf_get_numa_node_id
  - kernel/bpf/helpers.c:bpf_get_smp_processor_id
```
```
In kernel/bpf/hashtab.c (ffff800010278b04)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
```
```
In kernel/bpf/arraymap.c (ffff80001027b8d8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/arraymap.c:percpu_array_map_lookup_elem
```
```
In kernel/bpf/percpu_freelist.c (ffff80001027c0fc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_push
```
```
In kernel/bpf/bpf_lru_list.c (ffff80001027c7ec)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
```
In kernel/bpf/devmap.c (ffff800010286f3c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:__dev_map_flush
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/cpumap.c (ffff800010288b34)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/xskmap.c (ffff80001028958c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:__xsk_map_flush
  - kernel/bpf/xskmap.c:__xsk_map_redirect
```
```
In kernel/bpf/offload.c (ffff80001028a928)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In kernel/bpf/stackmap.c (ffff80001028ba98)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/bpf/cgroup.c (ffff80001028e5e0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffff80001029cb88)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_pmu_cancel_txn
  - kernel/events/core.c:perf_pmu_commit_txn
  - kernel/events/core.c:perf_pmu_start_txn
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:___perf_sw_event
  - kernel/events/core.c:perf_swevent_put_recursion_context
  - kernel/events/core.c:perf_swevent_get_recursion_context
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:perf_sched_cb_inc
  - kernel/events/core.c:perf_sched_cb_inc
  - kernel/events/core.c:perf_sched_cb_inc
  - kernel/events/core.c:perf_sched_cb_dec
  - kernel/events/core.c:perf_sched_cb_dec
  - kernel/events/core.c:__perf_event_stop
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_event_disable_inatomic
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/core.c:event_function
Direct callers:
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:perf_event_read_local
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_del_event
  - kernel/events/core.c:list_add_event
```
```
In kernel/events/ring_buffer.c (ffff8000102a20a8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/callchain.c (ffff8000102a3848)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In kernel/events/uprobes.c (ffff8000102a7454)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/rseq.c (ffff8000102ad1ac)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
  - kernel/rseq.c:perf_trace_rseq_update
  - kernel/rseq.c:trace_event_raw_event_rseq_update
```
```
In mm/filemap.c (ffff8000102b2720)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (ffff8000102b7c68)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/page-writeback.c (ffff8000102be180)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (ffff8000102c1240)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_drain
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:pagevec_move_tail
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (ffff8000102ce6f0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:perf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/shmem.c (ffff8000102d3b24)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffff8000102dcde0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/vmstat.c:quiet_vmstat
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:inc_node_state
  - mm/vmstat.c:inc_node_state
  - mm/vmstat.c:inc_node_state
  - mm/vmstat.c:mod_node_page_state
  - mm/vmstat.c:mod_node_page_state
  - mm/vmstat.c:mod_node_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:mod_zone_page_state
  - mm/vmstat.c:mod_zone_page_state
  - mm/vmstat.c:mod_zone_page_state
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_zone_page_state
  - mm/vmstat.c:__mod_zone_page_state
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/backing-dev.c (ffff8000102dd980)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/mmu_context.c (ffff8000102dff94)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/percpu.c (ffff8000102e2ec4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffff8000102e68c0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_free
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (ffff8000102ed22c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:compaction_deferred
  - mm/compaction.c:defer_compaction
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/gup.c (ffff8000102f26f0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/memory.c (ffff8000102fa324)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mlock.c (ffff8000102fdb0c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mprotect.c (ffff800010305170)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffff800010311818)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/page_alloc.c (ffff800010313c24)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:drain_local_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:alloc_pages_exact_nid
Direct callers:
  - mm/page_alloc.c:show_free_areas
```
```
In mm/page_io.c (ffff800010320a1c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (ffff8000103224ec)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffff8000103258ec)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
```
```
In mm/swap_slots.c (ffff800010329e38)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:free_swap_slot
```
```
In mm/zswap.c (ffff80001032b96c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffff80001032f504)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffff80001033b724)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/sparse-vmemmap.c (ffff800010da09e4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffff800010341fc8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffff80001034c634)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:flush_cpu_slab
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:alloc_slab_page
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:bootstrap
  - mm/slub.c:kfree
  - mm/slub.c:kfree
  - mm/slub.c:kfree
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:set_track
```
```
In mm/memory_hotplug.c (ffff80001034dd60)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In mm/migrate.c (ffff800010352df4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/huge_memory.c (ffff80001035a5c4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffff80001035ed64)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:khugepaged_alloc_page
  - mm/khugepaged.c:khugepaged_alloc_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_swapin
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page_isolate
  - mm/khugepaged.c:perf_trace_mm_collapse_huge_page
  - mm/khugepaged.c:perf_trace_mm_khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffff800010367444)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
  - mm/memcontrol.c:__mod_memcg_state
  - mm/memcontrol.c:percpu_ref_put_many
  - mm/memcontrol.c:percpu_ref_tryget_live
Direct callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/hugetlb_cgroup.c (ffff80001036d708)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffff8000103708f4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_work_func
  - mm/memory-failure.c:memory_failure_queue
  - mm/memory-failure.c:memory_failure_queue
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffff800010372248)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/zsmalloc.c (ffff8000103750b0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/cma.c (ffff800010377318)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/cma.c:cma_release
  - mm/cma.c:cma_alloc
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In mm/balloon_compaction.c (ffff800010377a64)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/userfaultfd.c (ffff800010378250)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/hmm.c (ffff80001037b88c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/open.c (ffff80001037f15c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/super.c (ffff8000103862b0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/super.c:__sb_end_write
```
```
In fs/exec.c (ffff80001038f014)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/exec.c:__set_task_comm
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:do_open_execat
```
```
In fs/dcache.c (ffff8000103a6714)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_lru_shrink_move
  - fs/dcache.c:d_shrink_add
  - fs/dcache.c:d_shrink_del
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
  - fs/dcache.c:d_lru_add
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffff8000103acc88)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_list_add
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (ffff8000103b86bc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/namespace.c:__arm64_sys_fsmount
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:__arm64_sys_open_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_set_mountpoint
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_clone_write
  - fs/namespace.c:__mnt_want_write
  - fs/namespace.c:__mnt_want_write
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs-writeback.c (ffff8000103c8ae4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/buffer.c (ffff8000103d8044)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:alloc_buffer_head
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffff8000103e13f8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffff8000103e8f40)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/eventfd.c (ffff8000103f6144)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_signal
  - fs/eventfd.c:eventfd_signal
  - fs/eventfd.c:eventfd_signal
```
```
In fs/aio.c (ffff8000103fc514)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__arm64_sys_io_cancel
  - fs/aio.c:__arm64_compat_sys_io_submit
  - fs/aio.c:__arm64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__arm64_sys_io_destroy
  - fs/aio.c:__arm64_compat_sys_io_setup
  - fs/aio.c:__arm64_sys_io_setup
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:__get_reqs_available
  - fs/aio.c:put_reqs_available
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffff800010405a9c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_enter
  - fs/io_uring.c:__arm64_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
  - fs/io_uring.c:io_get_req
```
```
In fs/dax.c (ffff800010409278)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:perf_trace_dax_writeback_one
  - fs/dax.c:perf_trace_dax_writeback_range_class
  - fs/dax.c:perf_trace_dax_insert_mapping
  - fs/dax.c:perf_trace_dax_pte_fault_class
  - fs/dax.c:perf_trace_dax_pmd_insert_mapping_class
  - fs/dax.c:perf_trace_dax_pmd_load_hole_class
  - fs/dax.c:perf_trace_dax_pmd_fault_class
```
```
In fs/locks.c (ffff800010419928)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:leases_conflict
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_insert_global_locks
  - fs/locks.c:locks_insert_global_locks
  - fs/locks.c:locks_get_lock_context
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/drop_caches.c (ffff800010429174)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
```
```
In fs/proc/base.c (ffff80001043f7d8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/ext4/balloc.c (ffff800010460e8c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffff800010463bd8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (ffff80001046c6fc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/extents_status.c (ffff8000104703cc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/fsmap.c (ffff8000104724d0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/fsync.c (ffff8000104729b0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffff80001047509c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffff8000104778c8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffff800010484710)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:__ext4_journalled_invalidatepage
  - fs/ext4/inode.c:ext4_alloc_da_blocks
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffff80001048cc10)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
```
```
In fs/ext4/mballoc.c (ffff800010494224)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffff8000104a246c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
```
```
In fs/ext4/super.c (ffff8000104b8194)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_nfs_commit_metadata
  - fs/ext4/super.c:ext4_drop_inode
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/ext4/super.c:perf_trace_ext4_error
  - fs/ext4/super.c:perf_trace_ext4_shutdown
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:perf_trace_ext4_find_delalloc_range
  - fs/ext4/super.c:perf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:perf_trace_ext4_ext_put_in_cache
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_enter
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_nfs_commit_metadata
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/transaction.c (ffff8000104ca63c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
```
In fs/jbd2/commit.c (ffff8000104cf6a4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffff8000104d1050)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffff8000104d6ff8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (ffff800010546cc4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_node_kill
  - security/selinux/avc.c:avc_node_free
```
```
In security/selinux/netif.c (ffff800010558090)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/lsm_audit.c (ffff8000105773bc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In security/apparmor/capability.c (ffff80001058e568)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/domain.c (ffff8000105945b4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:profile_transition
```
```
In security/apparmor/file.c (ffff8000105a00ac)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
```
```
In security/apparmor/mount.c (ffff8000105a69cc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
```
In crypto/scompress.c (ffff8000105c5150)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - crypto/scompress.c:scomp_acomp_comp_decomp
```
```
In block/bio.c (ffff8000105dbd70)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:update_io_ticks
```
```
In block/blk-core.c (ffff8000105e3c94)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-merge.c (ffff8000105ea73c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-softirq.c (ffff8000105ec158)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-softirq.c:blk_softirq_cpu_dead
  - block/blk-softirq.c:trigger_softirq
  - block/blk-softirq.c:blk_done_softirq
```
```
In block/blk-mq.c (ffff8000105f2540)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_complete_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffff8000105f474c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-stat.c (ffff8000105f5170)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add
```
```
In block/blk-mq-sched.c (ffff8000105f7108)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
```
In block/genhd.c (ffff8000105fabcc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_inc_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In block/blk-cgroup.c (ffff80001060e878)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffff8000106119e8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (ffff800010618118)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (ffff8000106220d0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In lib/random32.c (ffff80001062a118)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes
  - lib/random32.c:prandom_u32
```
```
In lib/percpu-refcount.c (ffff800010635658)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/percpu_counter.c (ffff80001065eb04)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_add_batch
  - lib/percpu_counter.c:percpu_counter_add_batch
  - lib/percpu_counter.c:percpu_counter_add_batch
```
```
In lib/irq_poll.c (ffff800010667c94)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
```
```
In lib/sbitmap.c (ffff80001066a1cc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get
  - lib/sbitmap.c:__sbitmap_queue_get
  - lib/sbitmap.c:__sbitmap_queue_get
  - lib/sbitmap.c:__sbitmap_queue_get
```
```
In drivers/irqchip/irq-bcm2836.c (ffff8000100816bc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_handle_irq
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_unmask_pmu_irq
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_mask_pmu_irq
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_unmask_timer_irq
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_mask_timer_irq
```
```
In drivers/irqchip/irq-gic.c (ffff80001066c58c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/irqchip/irq-gic.c:gic_cpu_restore
  - drivers/irqchip/irq-gic.c:gic_cpu_save
  - drivers/irqchip/irq-gic.c:gic_cpu_save
  - drivers/irqchip/irq-gic.c:gic_cpu_save
  - drivers/irqchip/irq-gic.c:gic_cpu_init
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066f2f4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
  - drivers/irqchip/irq-gic-v3.c:gic_cpu_sys_reg_init
  - drivers/irqchip/irq-gic-v3.c:gic_populate_rdist
  - drivers/irqchip/irq-gic-v3.c:__gic_populate_rdist
  - drivers/irqchip/irq-gic-v3.c:gic_handle_irq
  - drivers/irqchip/irq-gic-v3.c:gic_handle_irq
  - drivers/irqchip/irq-gic-v3.c:gic_set_type
  - drivers/irqchip/irq-gic-v3.c:gic_irq_set_prio
  - drivers/irqchip/irq-gic-v3.c:gic_poke_irq
  - drivers/irqchip/irq-gic-v3.c:gic_peek_irq
  - drivers/irqchip/irq-gic-v3.c:gic_redist_wait_for_rwp
Direct callers:
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:__gic_populate_rdist
  - drivers/irqchip/irq-gic-v3.c:__gic_populate_rdist
  - drivers/irqchip/irq-gic-v3.c:__gic_populate_rdist
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010674ac0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_restore_enable
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
Direct callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
```
```
In drivers/irqchip/irq-partition-percpu.c (ffff800010675a04)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/irqchip/irq-partition-percpu.c:partition_handle_irq
  - drivers/irqchip/irq-partition-percpu.c:partition_irq_get_irqchip_state
  - drivers/irqchip/irq-partition-percpu.c:partition_irq_set_irqchip_state
  - drivers/irqchip/irq-partition-percpu.c:partition_irq_unmask
  - drivers/irqchip/irq-partition-percpu.c:partition_irq_mask
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff800010677190)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_cpu_offline
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_irq_handle
```
```
In drivers/irqchip/qcom-irq-combiner.c (ffff80001067bb08)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/irqchip/qcom-irq-combiner.c:combiner_handle_irq
```
```
In drivers/bus/fsl-mc/dprc-driver.c (ffff800010683b80)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/dprc-driver.c:dprc_irq0_handler_thread
```
```
In drivers/gpio/gpiolib.c (ffff8000106c3f34)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/gpio/gpio-mvebu.c (ffff8000106d1008)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_write_edge_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_write_edge_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_read_edge_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_read_edge_mask
```
```
In drivers/gpio/gpio-mxc.c (ffff8000106d2050)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
```
```
In drivers/pci/pcie/aer.c (ffff80001070544c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
```
```
In drivers/acpi/ec.c (ffff8000107717a8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/processor_idle.c (ffff8000107a2bec)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_lpi_enter
```
```
In drivers/clk/clk.c (ffff8000107c0088)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/dma/dmaengine.c (ffff8000107fbf78)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_find_channel
```
```
In drivers/dma/ipu/ipu_irq.c (ffff80001148f1cc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_attach_irq
```
```
In drivers/soc/fsl/qbman/bman.c (ffff800010811a54)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman.c:bman_acquire
  - drivers/soc/fsl/qbman/bman.c:bman_release
  - drivers/soc/fsl/qbman/bman.c:bman_release
  - drivers/soc/fsl/qbman/bman.c:bm_shutdown_pool
```
```
In drivers/soc/fsl/qbman/qman.c (ffff800010816e9c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:qman_delete_cgr_safe
  - drivers/soc/fsl/qbman/qman.c:qman_delete_cgr
  - drivers/soc/fsl/qbman/qman.c:qman_create_cgr
  - drivers/soc/fsl/qbman/qman.c:qman_enqueue
  - drivers/soc/fsl/qbman/qman.c:set_vdqcr
  - drivers/soc/fsl/qbman/qman.c:qman_query_fq_np
  - drivers/soc/fsl/qbman/qman.c:qman_query_fq
  - drivers/soc/fsl/qbman/qman.c:qman_oos_fq
  - drivers/soc/fsl/qbman/qman.c:qman_retire_fq
  - drivers/soc/fsl/qbman/qman.c:qman_schedule_fq
  - drivers/soc/fsl/qbman/qman.c:qman_init_fq
  - drivers/soc/fsl/qbman/qman.c:qman_affine_channel
  - drivers/soc/fsl/qbman/qman.c:qman_destroy_affine_portal
  - drivers/soc/fsl/qbman/qman.c:portal_isr
  - drivers/soc/fsl/qbman/qman.c:portal_isr
```
```
In drivers/soc/qcom/rpmh-rsc.c (ffff80001081bd2c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmh-rsc.c:__tcs_buffer_write
  - drivers/soc/qcom/rpmh-rsc.c:tcs_tx_done
  - drivers/soc/qcom/rpmh-rsc.c:perf_trace_rpmh_send_msg
  - drivers/soc/qcom/rpmh-rsc.c:perf_trace_rpmh_tx_done
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082b12c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/preempt.c (ffff80001082f730)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
```
```
In drivers/xen/time.c (ffff80001082fb64)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_get_runstate_snapshot
```
```
In drivers/xen/events/events_base.c (ffff80001083243c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffff800010833144)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffff800011491a78)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
```
```
In drivers/xen/swiotlb-xen.c (ffff80001083dd60)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffff8000108453cc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/tty/sysrq.c (ffff800010864094)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
```
In drivers/tty/vt/keyboard.c (ffff800010869c64)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (ffff8000108b02b4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:extract_crng
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/random.c:mix_pool_bytes
  - drivers/char/random.c:__mix_pool_bytes
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_xfer_secondary_pool
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_push_to_pool
  - drivers/char/random.c:perf_trace_credit_entropy_bits
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
```
```
In drivers/iommu/iommu.c (ffff8000108c5570)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_aux_detach_device
  - drivers/iommu/iommu.c:iommu_aux_attach_device
  - drivers/iommu/iommu.c:report_iommu_fault
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
  - drivers/iommu/iommu.c:__iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/iommu/iommu-traces.c (ffff8000108c8608)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/iommu/dma-iommu.c (ffff8000108ca594)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
```
```
In drivers/iommu/io-pgtable-arm.c (ffff8000108cb42c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
```
```
In drivers/iommu/iova.c (ffff8000108cdf4c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_rcache_get
  - drivers/iommu/iova.c:iova_rcache_insert
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/connector/cn_proc.c (ffff8000108de954)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/base/syscore.c (ffff8000108eb8b0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/qos.c (ffff8000108f9998)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffff8000108fc4bc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/main.c (ffff800010902e58)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/base/power/wakeup.c (ffff800010903b30)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffff80001091356c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/base/regmap/regcache.c (ffff80001091829c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_cache_bypass
  - drivers/base/regmap/regcache.c:regcache_cache_only
  - drivers/base/regmap/regcache.c:regcache_drop_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
```
```
In drivers/block/loop.c (ffff800010924f2c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/nvdimm/region_devs.c (ffff800010957a34)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
  - drivers/nvdimm/region_devs.c:nd_region_release_lane
  - drivers/nvdimm/region_devs.c:nd_region_acquire_lane
```
```
In drivers/dax/super.c (0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: False
```
```
In drivers/dma-buf/dma-fence.c (ffff800010966448)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (ffff80001096b450)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (ffff80001096e438)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_error.c (ffff800010973a4c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffff8000109792d4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/ata/libata-core.c (ffff80001099a5c4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/ata/libata-eh.c (ffff8000109aa188)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/spi/spi.c (ffff8000109c7388)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
Direct callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/loopback.c (ffff8000109d0228)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/phy/mdio_bus.c (ffff8000109d7aa0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/net/tun.c (ffff8000109dcd34)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_flow_update
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e4688)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_suspend
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109ea734)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a031d0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffff800010a08a58)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In drivers/usb/host/xhci.c (ffff800010a76a10)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
```
```
In drivers/usb/host/xhci-mem.c (ffff800010a794a8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a7cfe0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:inc_enq
  - drivers/usb/host/xhci-ring.c:inc_deq
```
```
In drivers/usb/host/xhci-hub.c (ffff800010a86600)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/usb/host/xhci-trace.c (ffff800010a89e90)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8b240)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:dbc_free_request
  - drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/usb/host/xhci-pci.c (ffff800010a90cdc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
```
```
In drivers/rtc/interface.c (ffff800010aaa0a8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_set_offset
  - drivers/rtc/interface.c:rtc_read_offset
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/interface.c:perf_trace_rtc_timer_class
  - drivers/rtc/interface.c:perf_trace_rtc_offset_class
  - drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class
```
```
In drivers/i2c/i2c-core-base.c (ffff800010ab0d9c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab40a0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/power/reset/sc27xx-poweroff.c (ffff800010acaa4c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/power/reset/sc27xx-poweroff.c:sc27xx_poweroff_shutdown
```
```
In drivers/hwmon/hwmon.c (ffff800010ad0f04)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/hwmon/hwmon.c:hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:hwmon_attr_show
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (ffff800010ad4638)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/thermal_helpers.c (ffff800010ad884c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:thermal_cdev_update
```
```
In drivers/thermal/fair_share.c (ffff800010ada030)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
```
```
In drivers/thermal/step_wise.c (ffff800010ada65c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/thermal/step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/power_allocator.c (ffff800010adb7e0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/thermal/cpu_cooling.c (ffff800010adbf9c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/thermal/cpu_cooling.c:cpufreq_power2state
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
```
```
In drivers/thermal/devfreq_cooling.c (ffff800010add008)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
```
In drivers/md/md.c (ffff800010aeaa8c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffff800010aff5b8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
```
```
In drivers/md/dm-stats.c (ffff800010b0c750)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__dm_stat_clear
  - drivers/md/dm-stats.c:__dm_stat_clear
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/md/dm-rq.c (ffff800010b0eaec)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (ffff800010b103e8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In drivers/edac/ghes_edac.c (ffff800010b14cb4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b20f94)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffff800010b23a00)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
```
In drivers/cpufreq/cpufreq_governor.c (ffff800010b2555c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_irq_work
```
```
In drivers/cpuidle/cpuidle.c (ffff800010b26f58)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
  - drivers/cpuidle/cpuidle.c:cpuidle_play_dead
```
```
In drivers/cpuidle/driver.c (ffff800010b276fc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_get_driver
```
```
In drivers/cpuidle/governors/ladder.c (ffff800010b292a0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/cpuidle/governors/ladder.c:ladder_select_state
```
```
In drivers/cpuidle/governors/menu.c (ffff800010b29524)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_reflect
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/cpuidle/cpuidle-psci.c (ffff800010b2a71c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-psci.c:psci_enter_idle_state
```
```
In drivers/mmc/core/core.c (ffff800010b2c42c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffff800010b4b1d8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In drivers/firmware/arm_sdei.c (ffff800010b4bdc4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/firmware/arm_sdei.c:_local_event_register
Direct callers:
  - drivers/firmware/arm_sdei.c:sdei_event_handler
  - drivers/firmware/arm_sdei.c:_ipi_private_reset
  - drivers/firmware/arm_sdei.c:sdei_unmask_local_cpu
  - drivers/firmware/arm_sdei.c:sdei_mask_local_cpu
```
```
In drivers/firmware/efi/arm-runtime.c (ffff800010b60fc4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
```
```
In drivers/clocksource/arm_arch_timer.c (ffff800010b67894)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_dying_cpu
  - drivers/clocksource/arm_arch_timer.c:arch_timer_dying_cpu
  - drivers/clocksource/arm_arch_timer.c:arch_timer_evtstrm_available
  - drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu
  - drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu
  - drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu
  - drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu
  - drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu
  - drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu
  - drivers/clocksource/arm_arch_timer.c:arch_timer_check_ool_workaround
  - drivers/clocksource/arm_arch_timer.c:arch_counter_get_cntvct_stable
  - drivers/clocksource/arm_arch_timer.c:arch_counter_get_cntpct_stable
Direct callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu
  - drivers/clocksource/arm_arch_timer.c:arch_timer_check_ool_workaround
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffff800010b78c64)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:send_command
```
```
In drivers/platform/chrome/cros_ec_trace.c (ffff800010b799f0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_cmd_class
```
```
In drivers/devfreq/devfreq.c (ffff800010b865f8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/perf/arm-cci.c (ffff800010b908f0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_probe
```
```
In drivers/perf/arm-ccn.c (ffff800010b93a2c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_probe
```
```
In drivers/perf/arm_pmu.c (ffff800010b9525c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:cpu_pm_pmu_notify
  - drivers/perf/arm_pmu.c:cpu_pm_pmu_notify
  - drivers/perf/arm_pmu.c:armpmu_filter_match
  - drivers/perf/arm_pmu.c:armpmu_enable
  - drivers/perf/arm_pmu.c:armpmu_enable
  - drivers/perf/arm_pmu.c:armpmu_add
  - drivers/perf/arm_pmu.c:armpmu_del
```
```
In drivers/perf/arm_pmu_platform.c (ffff800010b95bc8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe
```
```
In drivers/perf/arm_pmu_acpi.c (ffff800010b95e64)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/perf/arm_pmu_acpi.c:arm_pmu_acpi_cpu_starting
```
```
In drivers/ras/ras.c (ffff800010b9e464)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
  - drivers/ras/ras.c:perf_trace_memory_failure_event
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
```
```
In net/core/sock.c (ffff800010bab014)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/core/sock.c:sock_prot_inuse_add
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffff800010bb9b10)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__kfree_skb_flush
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:napi_alloc_frag
```
```
In net/core/datagram.c (ffff800010bbbdf4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/flow_dissector.c (ffff800010bc3658)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (ffff800010bd00b8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:__napi_schedule_irqoff
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:netif_rx
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:dev_pick_tx_cpu_id
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_index
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/ethtool.c (ffff800010bdcb9c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffff800010be097c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffff800010be4cd8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:pneigh_queue_purge
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/utils.c (ffff800010bf33ec)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (ffff800010bf3a34)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/filter.c (ffff800010c032ec)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_update_srh_state
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:bpf_xdp_redirect_map
  - net/core/filter.c:bpf_xdp_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_flush_map
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:bpf_get_raw_cpu_id
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffff800010c04e64)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/xdp.c (ffff800010c070d0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/net-sysfs.c (ffff800010c0c048)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/page_pool.c (ffff800010c0cc80)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_clean_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffff800010c0e36c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/core/netpoll.c (ffff800010c10aac)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/net-traces.c (ffff800010c19898)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_inflight
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_exit_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/core/drop_monitor.c (ffff800010c1b934)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_metadata_free
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
```
```
In net/core/ptp_classifier.c (ffff800010c1ce10)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
```
```
In net/core/netprio_cgroup.c (ffff800010c1d2c4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (ffff800010c1f1a4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/dst_cache.c (ffff800010c2222c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
```
In net/core/devlink.c (ffff800010c306b8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_health_report
  - net/core/devlink.c:devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/core/gro_cells.c (ffff800010c30bfc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (ffff800010c3a064)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_api.c (ffff800010c3c9a4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffff800010c4b6e0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffff800010c529f0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/netfilter/nf_queue.c (ffff800010c55b50)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffff800010c5d0a0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/ip_input.c (ffff800010c5eb8c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffff800010c5fd8c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (ffff800010c603bc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (ffff800010c6570c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/ip_sockglue.c (ffff800010c68d98)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6a610)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6be88)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6d168)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (ffff800010c7582c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffff800010c7a500)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_check_reno_reordering
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffff800010c84f24)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
Direct callers:
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_timer.c (ffff800010c88888)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_syn_ack_timeout
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_err
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8c290)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c905f0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c941b0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffff800010c9464c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
```
In net/ipv4/datagram.c (ffff800010c96088)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffff800010c97d4c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9f4d0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup2
Direct callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/arp.c (ffff800010ca2920)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (ffff800010ca4ea8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/ipv4/devinet.c (ffff800010ca8f54)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:in_dev_finish_destroy
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/af_inet.c (ffff800010cac3d4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:inet_sk_state_store
  - net/ipv4/af_inet.c:inet_sk_set_state
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv4/fib_semantics.c (ffff800010cb7de8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/fib_trie.c (ffff800010cbc548)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
```
```
In net/ipv4/ping.c (ffff800010cc0a1c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc25ac)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffff800010cccfc4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/syncookies.c (ffff800010cd20d4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_cubic.c (ffff800010cd2f78)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
```
In net/ipv4/xfrm4_policy.c (ffff800010cd7588)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffff800010cda860)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_state.c (ffff800010ce3638)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffff800010ce9ff0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffff800010cec7b0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_device.c (ffff800010cee1e8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/af_inet6.c (ffff800010cf5898)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
```
```
In net/ipv6/ip6_output.c (ffff800010cf8c64)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
Direct callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ip6_input.c (ffff800010cfde0c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/addrconf.c (ffff800010d083ec)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffff800010d171a4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/route.c:rt6_uncached_list_add
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1f6b4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
```
```
In net/ipv6/ndisc.c (ffff800010d21ed0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffff800010d25aec)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udp6_lib_lookup2
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/raw.c (ffff800010d29cb8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (ffff800010d2cb60)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (ffff800010d2fe60)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/reassembly.c (ffff800010d358ac)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38e4c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ping.c (ffff800010d3a5b8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (ffff800010d3b2d8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffff800010d42dd8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2_finish
  - net/ipv6/ip6mr.c:ip6mr_forward2_finish
  - net/ipv6/ip6mr.c:ip6mr_forward2_finish
  - net/ipv6/ip6mr.c:ip6mr_forward2_finish
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffff800010d48bd4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/xfrm6_input.c (ffff800010d491c8)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
```
In net/ipv6/xfrm6_output.c (ffff800010d496c0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (ffff800010d4a838)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (ffff800010d4c650)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/seg6_local.c (ffff800010d517c0)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh
```
```
In net/ipv6/seg6_hmac.c (ffff800010d520dc)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
```
In net/ipv6/addrconf_core.c (ffff800010d52f40)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d56058)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
```
In net/packet/af_packet.c (ffff800010d5aef4)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_direct_xmit
```
```
In net/8021q/vlan_core.c (ffff800010d60394)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d68f9c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (ffff800010d7410c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7c35c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
```
```
In net/xdp/xsk.c (ffff800010d7eb5c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_unbind_dev
```
```
In net/xdp/xdp_umem.c (ffff800010d81078)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
```
```
In lib/dump_stack.c (ffff800010d84a3c)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack_print_info
Direct callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/radix-tree.c (ffff800010d8e600)
Location: arch/arm64/include/asm/percpu.h:22
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_preload
  - lib/radix-tree.c:__radix_tree_preload
```
**Symbols:**

```
ffff800010093db8-ffff800010093dc0: __my_cpu_offset (STB_LOCAL)
ffff80001066d990-ffff80001066d998: __my_cpu_offset (STB_LOCAL)
ffff800010084670-ffff800010084678: __my_cpu_offset (STB_LOCAL)
ffff800010086f90-ffff800010086f98: __my_cpu_offset (STB_LOCAL)
ffff800010099150-ffff800010099158: __my_cpu_offset (STB_LOCAL)
ffff80001009b248-ffff80001009b250: __my_cpu_offset (STB_LOCAL)
ffff80001009ba78-ffff80001009ba80: __my_cpu_offset (STB_LOCAL)
ffff8000100a3a90-ffff8000100a3a98: __my_cpu_offset (STB_LOCAL)
ffff8000100af848-ffff8000100af850: __my_cpu_offset (STB_LOCAL)
ffff8000100f6010-ffff8000100f6018: __my_cpu_offset (STB_LOCAL)
ffff8000100f6cc0-ffff8000100f6cc8: __my_cpu_offset (STB_LOCAL)
ffff8000100fa3c8-ffff8000100fa3d0: __my_cpu_offset (STB_LOCAL)
ffff80001011b858-ffff80001011b860: __my_cpu_offset (STB_LOCAL)
ffff80001012f1e8-ffff80001012f1f0: __my_cpu_offset (STB_LOCAL)
ffff800010131438-ffff800010131440: __my_cpu_offset (STB_LOCAL)
ffff8000101400d8-ffff8000101400e0: __my_cpu_offset (STB_LOCAL)
ffff800010166488-ffff800010166490: __my_cpu_offset (STB_LOCAL)
ffff800010171c08-ffff800010171c10: __my_cpu_offset (STB_LOCAL)
ffff8000101771b8-ffff8000101771c0: __my_cpu_offset (STB_LOCAL)
ffff80001018bbf0-ffff80001018bbf8: __my_cpu_offset (STB_LOCAL)
ffff8000101a0638-ffff8000101a0640: __my_cpu_offset (STB_LOCAL)
ffff8000101bcb08-ffff8000101bcb10: __my_cpu_offset (STB_LOCAL)
ffff8000101cdda0-ffff8000101cdda8: __my_cpu_offset (STB_LOCAL)
ffff8000101e7e20-ffff8000101e7e28: __my_cpu_offset (STB_LOCAL)
ffff800010207150-ffff800010207158: __my_cpu_offset (STB_LOCAL)
ffff80001021df48-ffff80001021df50: __my_cpu_offset (STB_LOCAL)
ffff800010290b38-ffff800010290b40: __my_cpu_offset (STB_LOCAL)
ffff8000103128f0-ffff8000103128f8: __my_cpu_offset (STB_LOCAL)
ffff800010342bd8-ffff800010342be0: __my_cpu_offset (STB_LOCAL)
ffff800010360f60-ffff800010360f68: __my_cpu_offset (STB_LOCAL)
ffff80001038bb28-ffff80001038bb30: __my_cpu_offset (STB_LOCAL)
ffff80001047d300-ffff80001047d308: __my_cpu_offset (STB_LOCAL)
ffff8000104cd848-ffff8000104cd850: __my_cpu_offset (STB_LOCAL)
ffff80001066fdc8-ffff80001066fdd0: __my_cpu_offset (STB_LOCAL)
ffff8000109c18f8-ffff8000109c1900: __my_cpu_offset (STB_LOCAL)
ffff800010a6d440-ffff800010a6d448: __my_cpu_offset (STB_LOCAL)
ffff800010b4b4e0-ffff800010b4b4e8: __my_cpu_offset (STB_LOCAL)
ffff800010b66c90-ffff800010b66c98: __my_cpu_offset (STB_LOCAL)
ffff800010c6ea00-ffff800010c6ea08: __my_cpu_offset (STB_LOCAL)
ffff800010c76998-ffff800010c769a0: __my_cpu_offset (STB_LOCAL)
ffff800010c81520-ffff800010c81528: __my_cpu_offset (STB_LOCAL)
ffff800010c89d70-ffff800010c89d78: __my_cpu_offset (STB_LOCAL)
ffff800010c98c38-ffff800010c98c40: __my_cpu_offset (STB_LOCAL)
ffff800010cf8088-ffff800010cf8090: __my_cpu_offset (STB_LOCAL)
ffff800010d23660-ffff800010d23668: __my_cpu_offset (STB_LOCAL)
ffff800010d35cb8-ffff800010d35cc0: __my_cpu_offset (STB_LOCAL)
ffff800010d3a778-ffff800010d3a780: __my_cpu_offset (STB_LOCAL)
ffff800010d51a48-ffff800010d51a50: __my_cpu_offset (STB_LOCAL)
ffff800010d84a28-ffff800010d84a30: __my_cpu_offset (STB_LOCAL)
ffff800010d8d360-ffff800010d8d368: __my_cpu_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (c0302f5c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - init/main.c:perf_trace_initcall_finish
  - init/main.c:perf_trace_initcall_start
  - init/main.c:perf_trace_initcall_level
```
```
In arch/arm/kernel/ptrace.c (c030b770)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - arch/arm/kernel/ptrace.c:perf_trace_sys_exit
  - arch/arm/kernel/ptrace.c:perf_trace_sys_enter
```
```
In arch/arm/kernel/traps.c (c0302208)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - arch/arm/kernel/traps.c:handle_fiq_as_nmi
  - arch/arm/kernel/traps.c:handle_fiq_as_nmi
  - arch/arm/kernel/traps.c:handle_fiq_as_nmi
  - arch/arm/kernel/traps.c:handle_fiq_as_nmi
```
```
In arch/arm/kernel/smp.c (c03133d8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/smp.c:perf_trace_ipi_handler
  - arch/arm/kernel/smp.c:perf_trace_ipi_raise
```
```
In arch/arm/kernel/smp_twd.c (c0314800)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - arch/arm/kernel/smp_twd.c:twd_timer_dying_cpu
  - arch/arm/kernel/smp_twd.c:twd_timer_setup
  - arch/arm/kernel/smp_twd.c:twd_update_frequency
```
```
In arch/arm/kernel/machine_kexec.c (c03150c0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - arch/arm/kernel/machine_kexec.c:machine_crash_nonpanic_core
```
```
In arch/arm/kernel/hw_breakpoint.c (c0316e64)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - arch/arm/kernel/hw_breakpoint.c:hw_breakpoint_pending
  - arch/arm/kernel/hw_breakpoint.c:hw_breakpoint_pending
  - arch/arm/kernel/hw_breakpoint.c:hw_breakpoint_pending
  - arch/arm/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
  - arch/arm/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
  - arch/arm/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
  - arch/arm/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
```
```
In arch/arm/kernel/perf_event_v7.c (c031958c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - arch/arm/kernel/perf_event_v7.c:scorpion_pmu_enable_event
  - arch/arm/kernel/perf_event_v7.c:scorpion_pmu_disable_event
  - arch/arm/kernel/perf_event_v7.c:krait_pmu_enable_event
  - arch/arm/kernel/perf_event_v7.c:krait_pmu_disable_event
  - arch/arm/kernel/perf_event_v7.c:armv7pmu_stop
  - arch/arm/kernel/perf_event_v7.c:armv7pmu_start
  - arch/arm/kernel/perf_event_v7.c:armv7pmu_handle_irq
  - arch/arm/kernel/perf_event_v7.c:armv7pmu_handle_irq
  - arch/arm/kernel/perf_event_v7.c:armv7pmu_disable_event
  - arch/arm/kernel/perf_event_v7.c:armv7pmu_enable_event
```
```
In arch/arm/mm/fault.c (c0e9f864)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - arch/arm/mm/fault.c:do_page_fault
```
```
In arch/arm/mm/highmem.c (c0321d14)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - arch/arm/mm/highmem.c:kmap_atomic_pfn
  - arch/arm/mm/highmem.c:__kunmap_atomic
  - arch/arm/mm/highmem.c:__kunmap_atomic
```
```
In arch/arm/mm/proc-v7-bugs.c (c0322fac)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - arch/arm/mm/proc-v7-bugs.c:cpu_v7_ca15_ibe
  - arch/arm/mm/proc-v7-bugs.c:cpu_v7_ca8_ibe
```
```
In arch/arm/common/bL_switcher.c (c0326474)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - arch/arm/common/bL_switcher.c:perf_trace_cpu_migrate
```
```
In arch/arm/probes/kprobes/core.c (c0ea0aac)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - arch/arm/probes/kprobes/core.c:trampoline_handler
  - arch/arm/probes/kprobes/core.c:trampoline_handler
  - arch/arm/probes/kprobes/core.c:trampoline_handler
  - arch/arm/probes/kprobes/core.c:kprobe_fault_handler
  - arch/arm/probes/kprobes/core.c:kprobe_fault_handler
  - arch/arm/probes/kprobes/core.c:kprobe_fault_handler
  - arch/arm/probes/kprobes/core.c:kprobe_fault_handler
  - arch/arm/probes/kprobes/core.c:kprobe_handler
  - arch/arm/probes/kprobes/core.c:kprobe_handler
  - arch/arm/probes/kprobes/core.c:kprobe_handler
  - arch/arm/probes/kprobes/core.c:kprobe_handler
  - arch/arm/probes/kprobes/core.c:kprobe_handler
  - arch/arm/probes/kprobes/core.c:kprobe_handler
  - arch/arm/probes/kprobes/core.c:kprobe_handler
```
```
In arch/arm/probes/kprobes/opt-arm.c (c032848c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - arch/arm/probes/kprobes/opt-arm.c:optimized_callback
  - arch/arm/probes/kprobes/opt-arm.c:optimized_callback
  - arch/arm/probes/kprobes/opt-arm.c:optimized_callback
  - arch/arm/probes/kprobes/opt-arm.c:optimized_callback
```
```
In kernel/fork.c (c0352bcc)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:perf_trace_task_newtask
```
```
In kernel/cpu.c (c151c2e0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/cpu.c:cpuhp_should_run
  - kernel/cpu.c:cpus_read_trylock
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/cpu.c:perf_trace_cpuhp_exit
  - kernel/cpu.c:perf_trace_cpuhp_multi_enter
  - kernel/cpu.c:perf_trace_cpuhp_enter
```
```
In kernel/exit.c (c035aacc)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/softirq.c (c035c2f4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:ksoftirqd_should_run
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:__raise_softirq_irqoff
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:ksoftirqd_running
  - kernel/softirq.c:wakeup_softirqd
  - kernel/softirq.c:perf_trace_softirq
  - kernel/softirq.c:perf_trace_irq_handler_exit
  - kernel/softirq.c:perf_trace_irq_handler_entry
```
```
In kernel/signal.c (c0367944)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:perf_trace_signal_deliver
  - kernel/signal.c:perf_trace_signal_generate
```
```
In kernel/workqueue.c (c0372148)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:perf_trace_workqueue_execute_start
  - kernel/workqueue.c:perf_trace_workqueue_queue_work
  - kernel/workqueue.c:perf_trace_workqueue_work
```
```
In kernel/kthread.c (c037ad28)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_associate_blkcg
  - kernel/kthread.c:kthread_associate_blkcg
```
```
In kernel/sched/core.c (c0e99e44)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:single_task_running
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:perf_trace_sched_wake_idle_without_ipi
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_process_hang
  - kernel/sched/core.c:perf_trace_sched_pi_setprio
  - kernel/sched/core.c:perf_trace_sched_stat_runtime
  - kernel/sched/core.c:perf_trace_sched_stat_template
  - kernel/sched/core.c:perf_trace_sched_process_exec
  - kernel/sched/core.c:perf_trace_sched_process_fork
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_process_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
  - kernel/sched/core.c:perf_trace_sched_kthread_stop_ret
  - kernel/sched/core.c:perf_trace_sched_kthread_stop
```
```
In kernel/sched/loadavg.c (c038e8ec)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_load_nohz_stop
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/cputime.c (c038f354)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_idle_time
  - kernel/sched/cputime.c:account_idle_time
  - kernel/sched/cputime.c:account_steal_time
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/idle.c (c038fc08)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:sched_idle_set_state
```
```
In kernel/sched/fair.c (c039281c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/rt.c (c039eba8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/sched/deadline.c (c039f2e4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/sched/deadline.c:find_later_rq
```
```
In kernel/sched/cpuacct.c (c03b0fdc)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_account_field
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/sched/cpufreq.c (c03b1138)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/sched/cpufreq.c:cpufreq_this_cpu_can_update
```
```
In kernel/sched/membarrier.c (c03b2628)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_exec_mmap
```
```
In kernel/sched/psi.c (c03b4688)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
```
In kernel/locking/percpu-rwsem.c (c03b62bc)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_up_read
```
```
In kernel/locking/osq_lock.c (c03b67bc)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk.c (c03c821c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/printk/printk.c:defer_console_output
  - kernel/printk/printk.c:defer_console_output
  - kernel/printk/printk.c:wake_up_klogd
  - kernel/printk/printk.c:wake_up_klogd
  - kernel/printk/printk.c:perf_trace_console
```
```
In kernel/printk/printk_safe.c (c03c8d78)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk_func
  - kernel/printk/printk_safe.c:vprintk_func
  - kernel/printk/printk_safe.c:vprintk_func
  - kernel/printk/printk_safe.c:vprintk_func
  - kernel/printk/printk_safe.c:__printk_safe_exit
  - kernel/printk/printk_safe.c:__printk_safe_enter
  - kernel/printk/printk_safe.c:printk_nmi_direct_exit
  - kernel/printk/printk_safe.c:printk_nmi_direct_enter
  - kernel/printk/printk_safe.c:printk_nmi_direct_enter
  - kernel/printk/printk_safe.c:printk_nmi_exit
  - kernel/printk/printk_safe.c:printk_nmi_enter
```
```
In kernel/irq/irqdesc.c (c03c9918)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:handle_domain_nmi
  - kernel/irq/irqdesc.c:handle_domain_nmi
  - kernel/irq/irqdesc.c:handle_domain_nmi
  - kernel/irq/irqdesc.c:handle_domain_nmi
  - kernel/irq/irqdesc.c:__handle_domain_irq
  - kernel/irq/irqdesc.c:__handle_domain_irq
  - kernel/irq/irqdesc.c:__handle_domain_irq
  - kernel/irq/irqdesc.c:__handle_domain_irq
```
```
In kernel/irq/handle.c (c03c9ba0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/chip.c (c03cfdd0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_percpu_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/irq/chip.c:handle_nested_irq
```
```
In kernel/rcu/update.c (c03d6fbc)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/rcu/update.c:perf_trace_rcu_utilization
```
```
In kernel/rcu/srcutree.c (c03d90a0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (c03dfb0c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_needs_cpu
  - kernel/rcu/tree.c:rcu_needs_cpu
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_qs
  - kernel/rcu/tree.c:rcu_qs
  - kernel/rcu/tree.c:rcu_qs
  - kernel/rcu/tree.c:rcu_qs
  - kernel/rcu/tree.c:rcu_qs
  - kernel/rcu/tree.c:rcu_qs
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread_should_run
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcutree_dying_cpu
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_idle_exit
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_idle_enter
  - kernel/rcu/tree.c:rcu_idle_enter
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
  - kernel/rcu/tree.c:rcu_dynticks_eqs_enter
```
```
In kernel/profile.c (c03e410c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/timer.c (c03e9f44)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:run_local_timers
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:timer_clear_idle
  - kernel/time/timer.c:get_next_timer_interrupt
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:perf_trace_tick_stop
  - kernel/time/timer.c:perf_trace_itimer_expire
  - kernel/time/timer.c:perf_trace_itimer_state
  - kernel/time/timer.c:perf_trace_hrtimer_class
  - kernel/time/timer.c:perf_trace_hrtimer_expire_entry
  - kernel/time/timer.c:perf_trace_hrtimer_start
  - kernel/time/timer.c:perf_trace_hrtimer_init
  - kernel/time/timer.c:perf_trace_timer_expire_entry
  - kernel/time/timer.c:perf_trace_timer_start
  - kernel/time/timer.c:perf_trace_timer_class
```
```
In kernel/time/hrtimer.c (c03ec488)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_run_softirq
  - kernel/time/hrtimer.c:__hrtimer_init
  - kernel/time/hrtimer.c:hrtimer_next_event_without
  - kernel/time/hrtimer.c:hrtimer_get_next_event
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:retrigger_next_event
```
```
In kernel/time/alarmtimer.c (c03f3eec)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:perf_trace_alarm_class
  - kernel/time/alarmtimer.c:perf_trace_alarmtimer_suspend
```
```
In kernel/time/tick-common.c (c03fc84c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_suspend
  - kernel/time/tick-common.c:tick_resume_local
  - kernel/time/tick-common.c:tick_broadcast_oneshot_control
  - kernel/time/tick-common.c:tick_install_replacement
  - kernel/time/tick-common.c:tick_periodic
  - kernel/time/tick-common.c:tick_is_oneshot_available
```
```
In kernel/time/tick-broadcast.c (c03fd9c0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-broadcast.c:tick_receive_broadcast
```
```
In kernel/time/tick-oneshot.c (c03fe480)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/time/tick-oneshot.c:tick_oneshot_mode_active
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
```
In kernel/time/tick-sched.c (c03ffe20)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_oneshot_notify
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_get_idle_calls
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_get_next_hrtimer
  - kernel/time/tick-sched.c:tick_nohz_idle_got_tick
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_retain_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/time/tick-sched.c:can_stop_idle_tick
  - kernel/time/tick-sched.c:can_stop_idle_tick
  - kernel/time/tick-sched.c:can_stop_idle_tick
  - kernel/time/tick-sched.c:tick_nohz_next_event
  - kernel/time/tick-sched.c:tick_nohz_tick_stopped
```
```
In kernel/smp.c (c0405504)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/module.c (c0409058)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/module.c:perf_trace_module_request
  - kernel/module.c:perf_trace_module_refcnt
  - kernel/module.c:perf_trace_module_free
  - kernel/module.c:perf_trace_module_load
```
```
In kernel/cgroup/cgroup.c (c041bca0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_root
```
```
In kernel/cgroup/rstat.c (c041c698)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
```
```
In kernel/cgroup/cgroup-v1.c (c041ea40)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (c0420244)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (c0421500)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (c04258a8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
  - kernel/cgroup/cpuset.c:cpuset_read_lock
```
```
In kernel/kprobes.c (c0436528)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/kprobes.c:aggr_fault_handler
  - kernel/kprobes.c:aggr_post_handler
  - kernel/kprobes.c:aggr_post_handler
  - kernel/kprobes.c:aggr_pre_handler
  - kernel/kprobes.c:aggr_pre_handler
  - kernel/kprobes.c:opt_pre_handler
  - kernel/kprobes.c:opt_pre_handler
```
```
In kernel/debug/debug_core.c (c043ad1c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/watchdog.c (c04464b4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_disable
  - kernel/watchdog.c:watchdog_disable
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:softlockup_fn
  - kernel/watchdog.c:softlockup_fn
  - kernel/watchdog.c:softlockup_fn
  - kernel/watchdog.c:is_hardlockup
  - kernel/watchdog.c:is_hardlockup
  - kernel/watchdog.c:is_hardlockup
  - kernel/watchdog.c:touch_softlockup_watchdog_sync
  - kernel/watchdog.c:touch_softlockup_watchdog_sync
  - kernel/watchdog.c:__touch_watchdog
```
```
In kernel/seccomp.c (c0448030)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/taskstats.c (c044c4ac)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:prepare_reply
```
```
In kernel/trace/ftrace.c (c044eca0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ignore_task_cpu
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/ftrace.c:profile_graph_return
  - kernel/trace/ftrace.c:profile_graph_entry
  - kernel/trace/ftrace.c:ftrace_pid_func
```
```
In kernel/trace/trace.c (c045f940)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:disable_trace_buffered_event
  - kernel/trace/trace.c:enable_trace_buffered_event
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
```
In kernel/trace/trace_stack.c (c046dec4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_stop
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
  - kernel/trace/trace_stack.c:stack_trace_call
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_functions_graph.c (c046ed94)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (c0472acc)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
  - kernel/trace/blktrace.c:trace_note
```
```
In kernel/trace/trace_events.c (c0475544)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (c04789ec)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (c0479920)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
  - kernel/trace/trace_event_perf.c:perf_trace_buf_alloc
  - kernel/trace/trace_event_perf.c:perf_trace_add
```
```
In kernel/trace/bpf_trace.c (c047fa30)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/trace/trace_kprobe.c (c0483468)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kprobe_dispatcher
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/power-traces.c (c04863e4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/trace/power-traces.c:perf_trace_dev_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update
  - kernel/trace/power-traces.c:perf_trace_pm_qos_update_request_timeout
  - kernel/trace/power-traces.c:perf_trace_pm_qos_request
  - kernel/trace/power-traces.c:perf_trace_power_domain
  - kernel/trace/power-traces.c:perf_trace_clock
  - kernel/trace/power-traces.c:perf_trace_wakeup_source
  - kernel/trace/power-traces.c:perf_trace_suspend_resume
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_end
  - kernel/trace/power-traces.c:perf_trace_device_pm_callback_start
  - kernel/trace/power-traces.c:perf_trace_cpu_frequency_limits
  - kernel/trace/power-traces.c:perf_trace_pstate_sample
  - kernel/trace/power-traces.c:perf_trace_powernv_throttle
  - kernel/trace/power-traces.c:perf_trace_cpu
```
```
In kernel/trace/rpm-traces.c (c0487ee8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/trace/rpm-traces.c:perf_trace_rpm_return_int
  - kernel/trace/rpm-traces.c:perf_trace_rpm_internal
```
```
In kernel/trace/trace_uprobe.c (c048b280)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
```
In kernel/irq_work.c (c048e4f0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
```
```
In kernel/bpf/core.c (c048fa1c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_mem_return_failed
  - kernel/bpf/core.c:perf_trace_mem_connect
  - kernel/bpf/core.c:perf_trace_mem_disconnect
  - kernel/bpf/core.c:perf_trace_xdp_devmap_xmit
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:perf_trace_xdp_redirect_template
  - kernel/bpf/core.c:perf_trace_xdp_bulk_tx
  - kernel/bpf/core.c:perf_trace_xdp_exception
  - kernel/bpf/core.c:bpf_user_rnd_u32
```
```
In kernel/bpf/syscall.c (c0497bb8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/helpers.c (c04a8a18)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_local_storage
  - kernel/bpf/helpers.c:bpf_get_local_storage
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_unlock
  - kernel/bpf/helpers.c:bpf_spin_lock
```
```
In kernel/bpf/hashtab.c (c04ab0fc)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
```
```
In kernel/bpf/arraymap.c (c04ad334)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/arraymap.c:percpu_array_map_lookup_elem
```
```
In kernel/bpf/percpu_freelist.c (c04adc98)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
```
In kernel/bpf/devmap.c (c04b6a14)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:__dev_map_flush
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/cpumap.c (c04b883c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
```
In kernel/bpf/xskmap.c (c04b8f40)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:__xsk_map_flush
  - kernel/bpf/xskmap.c:__xsk_map_redirect
```
```
In kernel/bpf/offload.c (c04ba228)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In kernel/bpf/stackmap.c (c04bb140)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/bpf/cgroup.c (c04bd680)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (c04cc198)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_pmu_cancel_txn
  - kernel/events/core.c:perf_pmu_cancel_txn
  - kernel/events/core.c:perf_pmu_commit_txn
  - kernel/events/core.c:perf_pmu_commit_txn
  - kernel/events/core.c:perf_pmu_start_txn
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:___perf_sw_event
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:perf_sched_cb_inc
  - kernel/events/core.c:perf_sched_cb_inc
  - kernel/events/core.c:perf_sched_cb_inc
  - kernel/events/core.c:perf_sched_cb_dec
  - kernel/events/core.c:perf_sched_cb_dec
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:perf_group_detach
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/core.c:perf_sample_event_took
  - kernel/events/core.c:event_function
```
```
In kernel/events/callchain.c (c04d3038)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In kernel/events/uprobes.c (c04d6580)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
```
```
In kernel/rseq.c (c04d919c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - kernel/rseq.c:perf_trace_rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
```
```
In mm/filemap.c (c04df990)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:perf_trace_file_check_and_advance_wb_err
  - mm/filemap.c:perf_trace_filemap_set_wb_err
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
```
```
In mm/oom_kill.c (c04e4810)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:perf_trace_compact_retry
  - mm/oom_kill.c:perf_trace_skip_task_reaping
  - mm/oom_kill.c:perf_trace_finish_task_reaping
  - mm/oom_kill.c:perf_trace_start_task_reaping
  - mm/oom_kill.c:perf_trace_wake_reaper
  - mm/oom_kill.c:perf_trace_mark_victim
  - mm/oom_kill.c:perf_trace_reclaim_retry_zone
  - mm/oom_kill.c:perf_trace_oom_score_adj_update
```
```
In mm/page-writeback.c (c04ea474)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (c04ed3dc)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:pagevec_move_tail
  - mm/swap.c:perf_trace_mm_lru_activate
  - mm/swap.c:perf_trace_mm_lru_insertion
```
```
In mm/vmscan.c (c04f868c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:perf_trace_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:perf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:perf_trace_mm_vmscan_lru_isolate
  - mm/vmscan.c:perf_trace_mm_shrink_slab_end
  - mm/vmscan.c:perf_trace_mm_shrink_slab_start
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_end_template
  - mm/vmscan.c:perf_trace_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:perf_trace_mm_vmscan_wakeup_kswapd
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_wake
  - mm/vmscan.c:perf_trace_mm_vmscan_kswapd_sleep
```
```
In mm/shmem.c (c04fba80)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/vmstat.c (c05027f8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/vmstat.c:quiet_vmstat
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_zone_page_state
  - mm/vmstat.c:__mod_zone_page_state
  - mm/vmstat.c:__mod_zone_page_state
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/backing-dev.c (c05043e8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/percpu.c (c05055b4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/percpu.c:perf_trace_percpu_destroy_chunk
  - mm/percpu.c:perf_trace_percpu_create_chunk
  - mm/percpu.c:perf_trace_percpu_alloc_percpu_fail
  - mm/percpu.c:perf_trace_percpu_free_percpu
  - mm/percpu.c:perf_trace_percpu_alloc_percpu
```
```
In mm/slab_common.c (c050b8b8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:perf_trace_mm_page_pcpu_drain
  - mm/slab_common.c:perf_trace_mm_page
  - mm/slab_common.c:perf_trace_mm_page_alloc
  - mm/slab_common.c:perf_trace_mm_page_free_batched
  - mm/slab_common.c:perf_trace_mm_page_free
  - mm/slab_common.c:perf_trace_kmem_free
  - mm/slab_common.c:perf_trace_kmem_alloc_node
  - mm/slab_common.c:perf_trace_kmem_alloc
```
```
In mm/compaction.c (c0510e60)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:perf_trace_kcompactd_wake_template
  - mm/compaction.c:perf_trace_mm_compaction_kcompactd_sleep
  - mm/compaction.c:perf_trace_mm_compaction_defer_template
  - mm/compaction.c:perf_trace_mm_compaction_suitable_template
  - mm/compaction.c:perf_trace_mm_compaction_try_to_compact_pages
  - mm/compaction.c:perf_trace_mm_compaction_end
  - mm/compaction.c:perf_trace_mm_compaction_begin
  - mm/compaction.c:perf_trace_mm_compaction_migratepages
  - mm/compaction.c:perf_trace_mm_compaction_isolate_template
```
```
In mm/gup.c (0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
```
```
In mm/memory.c (c051bc6c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (c051cf58)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
```
```
In mm/vmalloc.c (c052b1c4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/page_alloc.c (c05342f4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/page_io.c (c0539408)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (c053ab08)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (c053cb70)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
```
```
In mm/swap_slots.c (c05406c0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:free_swap_slot
```
```
In mm/zswap.c (c0542158)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/slub.c (c05501ec)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:kfree
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (c0552b74)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:perf_trace_mm_migrate_pages
```
```
In mm/memcontrol.c (c055cae4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:drain_stock
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
  - mm/memcontrol.c:__mod_memcg_state
  - mm/memcontrol.c:__mod_memcg_state
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/page_isolation.c (c055e57c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/page_isolation.c:perf_trace_test_pages_isolated
```
```
In mm/zsmalloc.c (c0561b24)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/cma.c (c0562670)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/cma.c:perf_trace_cma_release
  - mm/cma.c:perf_trace_cma_alloc
```
```
In mm/balloon_compaction.c (c056342c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/hmm.c (c05665b4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/open.c (c05686f4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - fs/open.c:perf_trace_open_exec
  - fs/open.c:perf_trace_do_sys_open
```
```
In fs/super.c (c056f1e4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - fs/super.c:__sb_end_write
```
```
In fs/exec.c (c0574f34)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/dcache.c (c0588458)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:dentry_lru_isolate
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_lru_shrink_move
  - fs/dcache.c:d_shrink_add
  - fs/dcache.c:d_shrink_del
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_del
  - fs/dcache.c:d_lru_add
  - fs/dcache.c:d_lru_add
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (c058c550)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_list_add
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/inode.c:inode_init_always
```
```
In fs/namespace.c (c0598808)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_set_mountpoint
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_clone_write
  - fs/namespace.c:__mnt_want_write
  - fs/namespace.c:__mnt_want_write
  - fs/namespace.c:alloc_vfsmnt
```
```
In fs/fs-writeback.c (c05a7050)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:perf_trace_writeback_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_congest_waited_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_pages_written
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
```
```
In fs/buffer.c (c05b1694)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:alloc_buffer_head
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (c05b9930)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (c05c0664)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/eventfd.c (c05ca58c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_signal
  - fs/eventfd.c:eventfd_signal
  - fs/eventfd.c:eventfd_signal
```
```
In fs/aio.c (c05cfb10)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__se_sys_io_destroy
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:__get_reqs_available
  - fs/aio.c:put_reqs_available
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (c05d724c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
  - fs/io_uring.c:io_get_req
```
```
In fs/locks.c (c05e5ccc)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_insert_global_locks
  - fs/locks.c:perf_trace_leases_conflict
  - fs/locks.c:perf_trace_generic_add_lease
  - fs/locks.c:perf_trace_filelock_lease
  - fs/locks.c:perf_trace_filelock_lock
  - fs/locks.c:perf_trace_locks_get_lock_context
```
```
In fs/drop_caches.c (c05f1d38)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
```
```
In fs/ext4/inode.c (c06465f4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
```
```
In fs/ext4/mballoc.c (c064f79c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In fs/ext4/super.c (c0670b30)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_error
  - fs/ext4/super.c:perf_trace_ext4_shutdown
  - fs/ext4/super.c:perf_trace_ext4_getfsmap_class
  - fs/ext4/super.c:perf_trace_ext4_fsmap_class
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:perf_trace_ext4_insert_range
  - fs/ext4/super.c:perf_trace_ext4_collapse_range
  - fs/ext4/super.c:perf_trace_ext4_es_shrink_scan_exit
  - fs/ext4/super.c:perf_trace_ext4__es_shrink_enter
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_enter
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_enter
  - fs/ext4/super.c:perf_trace_ext4_es_remove_extent
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space_done
  - fs/ext4/super.c:perf_trace_ext4_ext_remove_space
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_idx
  - fs/ext4/super.c:perf_trace_ext4_ext_rm_leaf
  - fs/ext4/super.c:perf_trace_ext4_remove_blocks
  - fs/ext4/super.c:perf_trace_ext4_ext_show_extent
  - fs/ext4/super.c:perf_trace_ext4_get_reserved_cluster_alloc
  - fs/ext4/super.c:perf_trace_ext4_find_delalloc_range
  - fs/ext4/super.c:perf_trace_ext4_ext_in_cache
  - fs/ext4/super.c:perf_trace_ext4_ext_put_in_cache
  - fs/ext4/super.c:perf_trace_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:perf_trace_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:perf_trace_ext4__trim
  - fs/ext4/super.c:perf_trace_ext4_journal_start_reserved
  - fs/ext4/super.c:perf_trace_ext4_journal_start
  - fs/ext4/super.c:perf_trace_ext4_load_inode
  - fs/ext4/super.c:perf_trace_ext4_ext_load_extent
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_exit
  - fs/ext4/super.c:perf_trace_ext4__map_blocks_enter
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_fastpath
  - fs/ext4/super.c:perf_trace_ext4_ext_convert_to_initialized_enter
  - fs/ext4/super.c:perf_trace_ext4__truncate
  - fs/ext4/super.c:perf_trace_ext4_unlink_exit
  - fs/ext4/super.c:perf_trace_ext4_unlink_enter
  - fs/ext4/super.c:perf_trace_ext4_fallocate_exit
  - fs/ext4/super.c:perf_trace_ext4__fallocate_mode
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_exit
  - fs/ext4/super.c:perf_trace_ext4_direct_IO_enter
  - fs/ext4/super.c:perf_trace_ext4__bitmap_load
  - fs/ext4/super.c:perf_trace_ext4_da_release_space
  - fs/ext4/super.c:perf_trace_ext4_da_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_da_update_reserve_space
  - fs/ext4/super.c:perf_trace_ext4_forget
  - fs/ext4/super.c:perf_trace_ext4__mballoc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_prealloc
  - fs/ext4/super.c:perf_trace_ext4_mballoc_alloc
  - fs/ext4/super.c:perf_trace_ext4_alloc_da_blocks
  - fs/ext4/super.c:perf_trace_ext4_sync_fs
  - fs/ext4/super.c:perf_trace_ext4_sync_file_exit
  - fs/ext4/super.c:perf_trace_ext4_sync_file_enter
  - fs/ext4/super.c:perf_trace_ext4_free_blocks
  - fs/ext4/super.c:perf_trace_ext4_allocate_blocks
  - fs/ext4/super.c:perf_trace_ext4_request_blocks
  - fs/ext4/super.c:perf_trace_ext4_mb_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_discard_preallocations
  - fs/ext4/super.c:perf_trace_ext4_mb_release_group_pa
  - fs/ext4/super.c:perf_trace_ext4_mb_release_inode_pa
  - fs/ext4/super.c:perf_trace_ext4__mb_new_pa
  - fs/ext4/super.c:perf_trace_ext4_discard_blocks
  - fs/ext4/super.c:perf_trace_ext4_invalidatepage_op
  - fs/ext4/super.c:perf_trace_ext4__page_op
  - fs/ext4/super.c:perf_trace_ext4_writepages_result
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages_extent
  - fs/ext4/super.c:perf_trace_ext4_da_write_pages
  - fs/ext4/super.c:perf_trace_ext4_writepages
  - fs/ext4/super.c:perf_trace_ext4__write_end
  - fs/ext4/super.c:perf_trace_ext4__write_begin
  - fs/ext4/super.c:perf_trace_ext4_begin_ordered_truncate
  - fs/ext4/super.c:perf_trace_ext4_mark_inode_dirty
  - fs/ext4/super.c:perf_trace_ext4_nfs_commit_metadata
  - fs/ext4/super.c:perf_trace_ext4_drop_inode
  - fs/ext4/super.c:perf_trace_ext4_evict_inode
  - fs/ext4/super.c:perf_trace_ext4_allocate_inode
  - fs/ext4/super.c:perf_trace_ext4_request_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
```
```
In fs/jbd2/journal.c (c0695f5c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - fs/jbd2/journal.c:perf_trace_jbd2_lock_buffer_stall
  - fs/jbd2/journal.c:perf_trace_jbd2_write_superblock
  - fs/jbd2/journal.c:perf_trace_jbd2_update_log_tail
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_run_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_stats
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_extend
  - fs/jbd2/journal.c:perf_trace_jbd2_handle_start
  - fs/jbd2/journal.c:perf_trace_jbd2_submit_inode_data
  - fs/jbd2/journal.c:perf_trace_jbd2_end_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_commit
  - fs/jbd2/journal.c:perf_trace_jbd2_checkpoint
```
```
In security/selinux/avc.c (c06fc670)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_alloc_node
  - security/selinux/avc.c:avc_node_kill
  - security/selinux/avc.c:avc_node_free
```
```
In security/selinux/netif.c (c070ceb0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/lsm_audit.c (c072a048)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In security/apparmor/capability.c (c073f3a4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/domain.c (c074546c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:profile_transition
```
```
In security/apparmor/file.c (c0750d28)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
```
```
In security/apparmor/mount.c (c0756988)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
```
In crypto/scompress.c (c0771ce0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - crypto/scompress.c:scomp_acomp_comp_decomp
```
```
In block/bio.c (c0788334)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - block/bio.c:__bio_associate_blkg
  - block/bio.c:__bio_associate_blkg
```
```
In block/blk-core.c (c07915e8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:perf_trace_block_rq_remap
  - block/blk-core.c:perf_trace_block_bio_remap
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_complete
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:perf_trace_block_rq_complete
  - block/blk-core.c:perf_trace_block_rq_requeue
  - block/blk-core.c:perf_trace_block_buffer
```
```
In block/blk-merge.c (c0797c6c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
```
```
In block/blk-softirq.c (c07985fc)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - block/blk-softirq.c:__blk_complete_request
  - block/blk-softirq.c:blk_softirq_cpu_dead
  - block/blk-softirq.c:trigger_softirq
  - block/blk-softirq.c:blk_done_softirq
```
```
In block/blk-mq.c (c079aecc)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (c07a037c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-stat.c (c07a0ca4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add
```
```
In block/blk-mq-sched.c (c07a2858)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (c07b908c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (c07bc15c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (c07c0834)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - block/blk-iocost.c:perf_trace_iocost_ioc_vrate_adj
  - block/blk-iocost.c:perf_trace_iocg_inuse_update
  - block/blk-iocost.c:perf_trace_iocost_iocg_activate
```
```
In block/blk-wbt.c (c07c81b0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
```
```
In lib/random32.c (c07d16b0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
  - lib/random32.c:prandom_bytes
```
```
In lib/percpu-refcount.c (c07db4bc)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/percpu_counter.c (c080818c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_add_batch
  - lib/percpu_counter.c:percpu_counter_add_batch
  - lib/percpu_counter.c:percpu_counter_add_batch
```
```
In lib/irq_poll.c (c08102f8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
  - lib/irq_poll.c:irq_poll_softirq
```
```
In lib/sbitmap.c (c0812cdc)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get
  - lib/sbitmap.c:__sbitmap_queue_get
  - lib/sbitmap.c:__sbitmap_queue_get
  - lib/sbitmap.c:__sbitmap_queue_get
```
```
In drivers/irqchip/irq-gic.c (c0815aac)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_cpu_restore
  - drivers/irqchip/irq-gic.c:gic_cpu_restore
  - drivers/irqchip/irq-gic.c:gic_cpu_restore
  - drivers/irqchip/irq-gic.c:gic_cpu_save
  - drivers/irqchip/irq-gic.c:gic_cpu_save
  - drivers/irqchip/irq-gic.c:gic_cpu_save
```
```
In drivers/irqchip/irq-gic-v3.c (c0818098)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
  - drivers/irqchip/irq-gic-v3.c:__gic_populate_rdist
  - drivers/irqchip/irq-gic-v3.c:__gic_populate_rdist
  - drivers/irqchip/irq-gic-v3.c:__gic_populate_rdist
  - drivers/irqchip/irq-gic-v3.c:gic_set_type
  - drivers/irqchip/irq-gic-v3.c:gic_poke_irq
  - drivers/irqchip/irq-gic-v3.c:gic_peek_irq
  - drivers/irqchip/irq-gic-v3.c:gic_redist_wait_for_rwp
```
```
In drivers/irqchip/irq-gic-v3-its.c (c154cc34)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
```
```
In drivers/gpio/gpiolib.c (c085d13c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:perf_trace_gpio_value
  - drivers/gpio/gpiolib.c:perf_trace_gpio_direction
```
```
In drivers/clk/clk.c (c08ee514)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/clk/clk.c:perf_trace_clk_duty_cycle
  - drivers/clk/clk.c:perf_trace_clk_phase
  - drivers/clk/clk.c:perf_trace_clk_parent
  - drivers/clk/clk.c:perf_trace_clk_rate
  - drivers/clk/clk.c:perf_trace_clk
```
```
In drivers/dma/dmaengine.c (c091d704)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_find_channel
```
```
In drivers/dma/tegra20-apb-dma.c (c092c700)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:perf_trace_tegra_dma_isr
  - drivers/dma/tegra20-apb-dma.c:perf_trace_tegra_dma_complete_cb
  - drivers/dma/tegra20-apb-dma.c:perf_trace_tegra_dma_tx_status
```
```
In drivers/soc/qcom/spm.c (c0937ea8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/soc/qcom/spm.c:qcom_idle_enter
  - drivers/soc/qcom/spm.c:qcom_cpu_spc
```
```
In drivers/virtio/virtio_balloon.c (c09475ec)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/regulator/core.c (c094cb3c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/regulator/core.c:perf_trace_regulator_value
  - drivers/regulator/core.c:perf_trace_regulator_range
  - drivers/regulator/core.c:perf_trace_regulator_basic
```
```
In drivers/tty/sysrq.c (c0969668)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/keyboard.c (c096eeb8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (c09aa768)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:perf_trace_urandom_read
  - drivers/char/random.c:perf_trace_random_read
  - drivers/char/random.c:perf_trace_random__extract_entropy
  - drivers/char/random.c:perf_trace_random__get_random_bytes
  - drivers/char/random.c:perf_trace_xfer_secondary_pool
  - drivers/char/random.c:perf_trace_add_disk_randomness
  - drivers/char/random.c:perf_trace_add_input_randomness
  - drivers/char/random.c:perf_trace_debit_entropy
  - drivers/char/random.c:perf_trace_push_to_pool
  - drivers/char/random.c:perf_trace_credit_entropy_bits
  - drivers/char/random.c:perf_trace_random__mix_pool_bytes
  - drivers/char/random.c:perf_trace_add_device_randomness
```
```
In drivers/iommu/iommu-traces.c (c09bf5c0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_error
  - drivers/iommu/iommu-traces.c:perf_trace_unmap
  - drivers/iommu/iommu-traces.c:perf_trace_map
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_device_event
  - drivers/iommu/iommu-traces.c:perf_trace_iommu_group_event
```
```
In drivers/connector/cn_proc.c (c09cda6c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/base/regmap/regmap.c (c09f8fa0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
```
```
In drivers/block/loop.c (c0a07d0c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (c0a3df3c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
```
```
In drivers/dma-buf/sw_sync.c (c0a416d4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:perf_trace_sync_timeline
```
```
In drivers/scsi/scsi.c (c0a427a4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_eh_wakeup
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib.c (c0a4c060)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/ata/libata-core.c (c0a667a4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy_qc
  - drivers/ata/libata-core.c:perf_trace_ata_eh_link_autopsy
  - drivers/ata/libata-core.c:perf_trace_ata_qc_complete_template
  - drivers/ata/libata-core.c:perf_trace_ata_qc_issue
```
```
In drivers/spi/spi.c (c0ab1218)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/spi/spi.c:perf_trace_spi_transfer
  - drivers/spi/spi.c:perf_trace_spi_message_done
  - drivers/spi/spi.c:perf_trace_spi_message
  - drivers/spi/spi.c:perf_trace_spi_controller
```
```
In drivers/net/loopback.c (c0ab84ec)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/phy/mdio_bus.c (c0abe468)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:perf_trace_mdio_access
```
```
In drivers/net/tun.c (c0ac1564)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad3118)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
```
```
In drivers/net/ppp/ppp_generic.c (c0ade0f4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In drivers/usb/host/xhci-trace.c (c0b5ac98)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_dbc_log_request
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_portsc
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ring
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_slot_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ep_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_urb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_free_virt_dev
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_trb
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_ctx
  - drivers/usb/host/xhci-trace.c:perf_trace_xhci_log_msg
```
```
In drivers/usb/musb/musb_trace.c (c0b67e34)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/usb/musb/musb_trace.c:perf_trace_musb_req
  - drivers/usb/musb/musb_trace.c:perf_trace_musb_urb
  - drivers/usb/musb/musb_trace.c:perf_trace_musb_isr
  - drivers/usb/musb/musb_trace.c:perf_trace_musb_regl
  - drivers/usb/musb/musb_trace.c:perf_trace_musb_regw
  - drivers/usb/musb/musb_trace.c:perf_trace_musb_regb
  - drivers/usb/musb/musb_trace.c:perf_trace_musb_log
```
```
In drivers/usb/gadget/udc/trace.c (c0b74890)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/usb/gadget/udc/trace.c:perf_trace_udc_log_req
  - drivers/usb/gadget/udc/trace.c:perf_trace_udc_log_ep
  - drivers/usb/gadget/udc/trace.c:perf_trace_udc_log_gadget
```
```
In drivers/rtc/interface.c (c0b863f8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/rtc/interface.c:perf_trace_rtc_timer_class
  - drivers/rtc/interface.c:perf_trace_rtc_offset_class
  - drivers/rtc/interface.c:perf_trace_rtc_alarm_irq_enable
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_state
  - drivers/rtc/interface.c:perf_trace_rtc_irq_set_freq
  - drivers/rtc/interface.c:perf_trace_rtc_time_alarm_class
```
```
In drivers/i2c/i2c-core-base.c (c0b90284)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_result
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_reply
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_read
  - drivers/i2c/i2c-core-base.c:perf_trace_i2c_write
```
```
In drivers/i2c/i2c-core-smbus.c (c0b945a0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_result
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_reply
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_read
  - drivers/i2c/i2c-core-smbus.c:perf_trace_smbus_write
```
```
In drivers/hwmon/hwmon.c (c0bb201c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:perf_trace_hwmon_attr_class
```
```
In drivers/thermal/thermal_core.c (c0bb52e4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_devfreq_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_zone_trip
  - drivers/thermal/thermal_core.c:perf_trace_cdev_update
  - drivers/thermal/thermal_core.c:perf_trace_thermal_temperature
```
```
In drivers/thermal/power_allocator.c (c0bbac38)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator_pid
  - drivers/thermal/power_allocator.c:perf_trace_thermal_power_allocator
```
```
In drivers/md/md.c (c0bccc8c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
```
In drivers/md/dm-stats.c (c0bec198)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/cpuidle/cpuidle.c (c0c01910)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
  - drivers/cpuidle/cpuidle.c:cpuidle_play_dead
```
```
In drivers/cpuidle/governors/ladder.c (c0c03be8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/cpuidle/governors/ladder.c:ladder_select_state
```
```
In drivers/cpuidle/governors/menu.c (c0c03dbc)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_reflect
  - drivers/cpuidle/governors/menu.c:menu_select
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/cpuidle/cpuidle-psci.c (c0c05fa0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
```
```
In drivers/mmc/core/core.c (c0c08da0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:perf_trace_mmc_request_done
  - drivers/mmc/core/core.c:perf_trace_mmc_request_start
```
```
In drivers/leds/trigger/ledtrig-cpu.c (c0c34488)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In drivers/clocksource/timer-tegra.c (c15abb18)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/clocksource/timer-tegra.c:tegra_init_timer
```
```
In drivers/clocksource/arm_arch_timer.c (c0c4b338)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_dying_cpu
  - drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu
```
```
In drivers/clocksource/arm_global_timer.c (c0c4b9d0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/clocksource/arm_global_timer.c:gt_dying_cpu
  - drivers/clocksource/arm_global_timer.c:gt_starting_cpu
```
```
In drivers/platform/chrome/cros_ec_trace.c (c0c5f35c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_trace.c:perf_trace_cros_ec_cmd_class
```
```
In drivers/devfreq/devfreq.c (c0c696f4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:perf_trace_devfreq_monitor
```
```
In drivers/perf/arm_pmu.c (c0c7e848)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:cpu_pm_pmu_notify
  - drivers/perf/arm_pmu.c:cpu_pm_pmu_setup
  - drivers/perf/arm_pmu.c:armpmu_enable
  - drivers/perf/arm_pmu.c:armpmu_add
  - drivers/perf/arm_pmu.c:armpmu_del
```
```
In drivers/ras/ras.c (c0c7fa20)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_aer_event
  - drivers/ras/ras.c:perf_trace_non_standard_event
  - drivers/ras/ras.c:perf_trace_arm_event
  - drivers/ras/ras.c:perf_trace_mc_event
```
```
In sound/soc/soc-core.c (c0ca4a00)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - sound/soc/soc-core.c:perf_trace_snd_soc_jack_notify
  - sound/soc/soc-core.c:perf_trace_snd_soc_jack_report
  - sound/soc/soc-core.c:perf_trace_snd_soc_jack_irq
  - sound/soc/soc-core.c:perf_trace_snd_soc_dapm_connected
  - sound/soc/soc-core.c:perf_trace_snd_soc_dapm_path
  - sound/soc/soc-core.c:perf_trace_snd_soc_dapm_walk_done
  - sound/soc/soc-core.c:perf_trace_snd_soc_dapm_widget
  - sound/soc/soc-core.c:perf_trace_snd_soc_dapm_basic
  - sound/soc/soc-core.c:perf_trace_snd_soc_card
```
```
In net/core/sock.c (c0cc7a60)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/core/sock.c:sock_prot_inuse_add
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:__sk_free
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (c0cd6428)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:__kfree_skb_flush
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:napi_alloc_frag
```
```
In net/core/flow_dissector.c (c0cde8f4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (c0cf26e8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__napi_schedule_irqoff
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__dev_kfree_skb_irq
  - net/core/dev.c:__netif_schedule
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_index
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/ethtool.c (c0cf74a8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (c0cfa93c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (c0cfcf80)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_invalidate
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/utils.c (c0d0bc18)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (c0d0c380)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/filter.c (c0d1c818)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_update_srh_state
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_skb_set_tunnel_opt
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:bpf_xdp_redirect_map
  - net/core/filter.c:bpf_xdp_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_flush_map
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:bpf_csum_diff
  - net/core/filter.c:sk_filter_trim_cap
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (c0d1e3a0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/xdp.c (c0d201bc)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/net-sysfs.c (c0d245ac)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/skmsg.c (c0d2682c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_bpf_run
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/core/netpoll.c (c0d288e0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/core/net-traces.c (c0d2f2e0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_neigh__update
  - net/core/net-traces.c:perf_trace_neigh_update
  - net/core/net-traces.c:perf_trace_neigh_create
  - net/core/net-traces.c:perf_trace_page_pool_state_hold
  - net/core/net-traces.c:perf_trace_page_pool_state_release
  - net/core/net-traces.c:perf_trace_page_pool_inflight
  - net/core/net-traces.c:perf_trace_br_fdb_update
  - net/core/net-traces.c:perf_trace_fdb_delete
  - net/core/net-traces.c:perf_trace_br_fdb_external_learn_add
  - net/core/net-traces.c:perf_trace_br_fdb_add
  - net/core/net-traces.c:perf_trace_qdisc_dequeue
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_retransmit_synack
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:perf_trace_tcp_event_sk_skb
  - net/core/net-traces.c:perf_trace_udp_fail_queue_rcv_skb
  - net/core/net-traces.c:perf_trace_inet_sock_set_state
  - net/core/net-traces.c:perf_trace_sock_exceed_buf_limit
  - net/core/net-traces.c:perf_trace_sock_rcvqueue_full
  - net/core/net-traces.c:perf_trace_napi_poll
  - net/core/net-traces.c:perf_trace_net_dev_rx_exit_template
  - net/core/net-traces.c:perf_trace_net_dev_rx_verbose_template
  - net/core/net-traces.c:perf_trace_net_dev_template
  - net/core/net-traces.c:perf_trace_net_dev_xmit_timeout
  - net/core/net-traces.c:perf_trace_net_dev_xmit
  - net/core/net-traces.c:perf_trace_net_dev_start_xmit
  - net/core/net-traces.c:perf_trace_skb_copy_datagram_iovec
  - net/core/net-traces.c:perf_trace_consume_skb
  - net/core/net-traces.c:perf_trace_kfree_skb
```
```
In net/core/drop_monitor.c (c0d327a0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_metadata_free
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/drop_monitor.c:net_dm_hw_summary_probe
```
```
In net/core/ptp_classifier.c (c0d34cec)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
```
```
In net/core/netprio_cgroup.c (c0d351f8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (c0d363ec)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/dst_cache.c (c0d39620)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
```
In net/core/devlink.c (c0d476b4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_trap_stats_update
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
```
```
In net/core/gro_cells.c (c0d47a14)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/sched/sch_generic.c (c0d4c344)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/sched/sch_api.c (c0d4e1a4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (c0d5c020)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/bpf/test_run.c (c0d62b7c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:perf_trace_bpf_test_finish
```
```
In net/netfilter/nf_queue.c (c0d6555c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (c0d6c830)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_handle_martian_source
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
```
```
In net/ipv4/ip_input.c (c0d6d8a0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (c0d6f520)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (c0d6fd10)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (c0d75378)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/ip_sockglue.c (c0d7806c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
```
```
In net/ipv4/inet_hashtables.c (c0d793bc)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (c0d7acc0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
```
In net/ipv4/inet_connection_sock.c (c0d7b4fc)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (c0d7ed44)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_set_state
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (c0d87f10)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_newly_delivered
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_check_reno_reordering
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (c0d94224)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_probe_skb
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_event_new_data_sent
```
```
In net/ipv4/tcp_timer.c (c0d976ac)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_syn_ack_timeout
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_timer.c:tcp_write_err
```
```
In net/ipv4/tcp_ipv4.c (c0d9d7c8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (c0d9ed8c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
```
In net/ipv4/tcp_fastopen.c (c0da2a08)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (c0da2e78)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_mark_skb_lost
```
```
In net/ipv4/datagram.c (c0da485c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c0da5bcc)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (c0dac738)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:udp_send_skb
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/arp.c (c0daf790)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/icmp.c (c0db17b0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/ipv4/devinet.c (c0db56fc)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:in_dev_finish_destroy
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/af_inet.c (c0db70ac)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
```
```
In net/ipv4/fib_semantics.c (c0dc2ed4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/fib_trie.c (c0dc7db8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
```
```
In net/ipv4/ping.c (c0dcccf8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/ip_tunnel_core.c (c0dcde94)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (c0dd7624)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/syncookies.c (c0ddbf64)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv4/tcp_cubic.c (c0ddcaec)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
```
In net/ipv4/xfrm4_policy.c (c0de0f28)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (c0de2620)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_state.c (c0debbe8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (c0df1e80)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c0df46ec)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_device.c (c0df5de8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (c0dfeafc)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (c0e05880)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (c0e0ebb8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (c0e1cd64)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/route.c:rt6_uncached_list_add
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
```
```
In net/ipv6/ipv6_sockglue.c (c0e243f8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
```
```
In net/ipv6/ndisc.c (c0e26848)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (c0e29360)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (c0e2da90)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (c0e30a38)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (c0e3368c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/reassembly.c (c0e37ac4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (c0e3b9e8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (c0e3caa8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/exthdrs.c (c0e3d0d8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6mr.c (c0e4699c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (c0e49e48)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/xfrm6_input.c (c0e4a58c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
```
In net/ipv6/xfrm6_output.c (c0e4aa90)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
```
In net/ipv6/netfilter.c (c0e4b778)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/syncookies.c (c0e4d900)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/seg6_local.c (c0e52360)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh
```
```
In net/ipv6/seg6_hmac.c (c15ba458)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/addrconf_core.c (c0e53738)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/ipv6/inet6_hashtables.c (c0e5665c)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (c0e57bd0)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_destruct_skb
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/8021q/vlan_core.c (c0e5fe94)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
```
In net/netlabel/netlabel_unlabeled.c (c0e665f8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (c0e70268)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-netlink.c (c0e771f8)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
```
```
In net/xdp/xsk.c (c0e78dd4)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_unbind_dev
```
```
In net/xdp/xdp_umem.c (c0e7b580)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
```
```
In lib/radix-tree.c (c0e88874)
Location: arch/arm/include/asm/percpu.h:19
Inline: True
```
</details>
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
