# Function: <code>__preempt_count_dec_and_test</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81001683)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004b72)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100c1f2)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
```
```
In arch/x86/events/intel/ds.c (ffffffff810137ec)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/p4.c (ffffffff8101a8ad)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/xen/time.c (ffffffff8102be66)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_timerop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/xen/time.c:xen_sched_clock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81030f13)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/enlighten_pv.c:xen_mc_batch
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81032612)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_start
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
  - arch/x86/xen/mmu_pv.c:xen_mc_batch
```
```
In arch/x86/xen/multicalls.c (ffffffff81035f91)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8103c4da)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
```
```
In arch/x86/hyperv/mmu.c (ffffffff8103df60)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff8103e423)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8104006b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/process_64.c (ffffffff8104170d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/signal.c (ffffffff81042102)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/irq.c (ffffffff81045577)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
```
```
In arch/x86/kernel/ioport.c (ffffffff81046bcb)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In arch/x86/kernel/nmi.c (ffffffff81047a33)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff8104965d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
```
```
In arch/x86/kernel/tsc.c (ffffffff8104fd5e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In arch/x86/kernel/process.c (ffffffff810520f2)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:speculation_ctrl_update_current
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81053a0e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:kernel_fpu_end
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81054e09)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:fpregs_restore_userregs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8105561f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpregs_restore_userregs
```
```
In arch/x86/kernel/tls.c (ffffffff810593e2)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
```
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81062fe1)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8106791d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8106b0ce)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff8106cc8e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8106fe0f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81075599)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81079e9c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8107a818)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107c843)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l3_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l2_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107deb3)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107fab4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81080d9f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810823ce)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
```
```
In arch/x86/kernel/smp.c (ffffffff810855ed)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In arch/x86/kernel/smpboot.c (ffffffff83465ed3)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81089d40)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff83469407)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81092859)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
```
```
In arch/x86/kernel/ftrace.c (ffffffff810950ed)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8109a2c0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8109aae7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/kernel/kvmclock.c (ffffffff83470298)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a0b8a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/mm/fault.c (ffffffff81f18318)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In arch/x86/mm/tlb.c (ffffffff810af4d7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810b7d0e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:post
  - arch/x86/mm/mmio-mod.c:post
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In arch/x86/platform/efi/quirks.c (ffffffff810bc414)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810bd22f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff810bf10a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
```
```
In kernel/fork.c (ffffffff810cb7b1)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
```
```
In kernel/panic.c (ffffffff81e535a3)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/panic.c:__warn
```
```
In kernel/cpu.c (ffffffff810cf221)
Location: arch/x86/include/asm/preempt.h:93
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
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpus_read_trylock
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
```
```
In kernel/exit.c (ffffffff810d2351)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/softirq.c (ffffffff810d4a5e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/softirq.c:__raise_softirq_irqoff
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
```
```
In kernel/signal.c (ffffffff810e4ab1)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal_locked
```
```
In kernel/workqueue.c (ffffffff810ef7b7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_inactive_work
  - kernel/workqueue.c:wq_worker_running
```
```
In kernel/pid.c (ffffffff810f6ae1)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/kthread.c (ffffffff810fac10)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
```
```
In kernel/smpboot.c (ffffffff81103cfa)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
```
```
In kernel/kmod.c (ffffffff81105c28)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff8111ab7f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/sched/core.c:call_trace_sched_update_nr_running
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:send_call_function_single_ipi
  - kernel/sched/core.c:ttwu_do_wakeup
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:migrate_enable
  - kernel/sched/core.c:migrate_disable
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:raw_spin_rq_trylock
  - kernel/sched/core.c:raw_spin_rq_trylock
```
```
In kernel/sched/fair.c (ffffffff81121642)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff8113b211)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:play_idle_precise
  - kernel/sched/build_policy.c:default_idle_call
  - kernel/sched/build_policy.c:default_idle_call
```
```
In kernel/sched/build_utility.c (ffffffff81141993)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_wait_end
  - kernel/sched/build_utility.c:sched_clock_cpu
  - kernel/sched/build_utility.c:__sched_clock_work
```
```
In kernel/locking/mutex.c (ffffffff81f2387a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81f24e38)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_common
  - kernel/locking/semaphore.c:__down_common
```
```
In kernel/locking/rwsem.c (ffffffff81f25900)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/locking/percpu-rwsem.c (ffffffff81f25ee8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
```
```
In kernel/locking/spinlock.c (ffffffff81f29d6a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_irq
  - kernel/locking/spinlock.c:_raw_read_unlock_irq
  - kernel/locking/spinlock.c:_raw_write_unlock
  - kernel/locking/spinlock.c:_raw_read_unlock
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_spin_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_spin_unlock_irq
  - kernel/locking/spinlock.c:_raw_spin_unlock
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/qspinlock.c (ffffffff8114f58e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex_api.c (ffffffff81f27c3b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
```
```
In kernel/locking/qrwlock.c (ffffffff8114faf2)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/qos.c (ffffffff81150396)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_remove_request
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff81152335)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff81153172)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/power/hibernate.c (ffffffff81154111)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
```
```
In kernel/power/snapshot.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In kernel/printk/printk.c (ffffffff8347ee2b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:printk_sprint
```
```
In kernel/irq/handle.c (ffffffff81162111)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff81167e37)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
```
```
In kernel/irq/matrix.c (ffffffff811721d1)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_remove_reserved
  - kernel/irq/matrix.c:irq_matrix_reserve
  - kernel/irq/matrix.c:irq_matrix_assign
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_assign_system
  - kernel/irq/matrix.c:irq_matrix_offline
  - kernel/irq/matrix.c:irq_matrix_online
```
```
In kernel/rcu/update.c (ffffffff811750ad)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/rcu/update.c:exit_tasks_rcu_finish
  - kernel/rcu/update.c:exit_tasks_rcu_start
```
```
In kernel/rcu/tree.c (ffffffff8117e288)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:call_rcu
  - kernel/rcu/tree.c:call_rcu
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/core.c (ffffffff8118249d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_init_object
```
```
In kernel/livepatch/patch.c (ffffffff81182de0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/livepatch/transition.c (ffffffff81184250)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/dma/swiotlb.c (ffffffff8118918a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In kernel/entry/common.c (ffffffff8118a20d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/module/main.c (ffffffff81e61aef)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/module/main.c:print_modules
  - kernel/module/main.c:is_module_text_address
  - kernel/module/main.c:is_module_address
  - kernel/module/main.c:search_module_extables
  - kernel/module/main.c:load_module
  - kernel/module/main.c:__symbol_get
  - kernel/module/main.c:__symbol_get
  - kernel/module/main.c:free_module
  - kernel/module/main.c:module_put
  - kernel/module/main.c:module_put
  - kernel/module/main.c:try_module_get
  - kernel/module/main.c:try_module_get
  - kernel/module/main.c:symbol_put_addr
  - kernel/module/main.c:__symbol_put
  - kernel/module/main.c:__is_module_percpu_address
  - kernel/module/main.c:__is_module_percpu_address
```
```
In kernel/module/kallsyms.c (ffffffff81191d71)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:module_kallsyms_on_each_symbol
  - kernel/module/kallsyms.c:module_kallsyms_lookup_name
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:lookup_module_symbol_attrs
  - kernel/module/kallsyms.c:lookup_module_symbol_attrs
  - kernel/module/kallsyms.c:lookup_module_symbol_name
  - kernel/module/kallsyms.c:lookup_module_symbol_name
  - kernel/module/kallsyms.c:module_address_lookup
```
```
In kernel/module/version.c (ffffffff81192fdd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/module/version.c:check_modstruct_version
  - kernel/module/version.c:check_modstruct_version
```
```
In kernel/profile.c (ffffffff81193cef)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
```
```
In kernel/time/timer.c (ffffffff8119a27d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:detach_if_pending
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/time/hrtimer.c (ffffffff8119c59f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_init
  - kernel/time/hrtimer.c:hrtimer_try_to_cancel
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/time/timekeeping.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In kernel/time/clocksource.c (ffffffff811a1a5e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In kernel/time/alarmtimer.c (ffffffff811a3edb)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811a8bbd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/time/itimer.c (ffffffff811abdf5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-common.c (ffffffff811ae142)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff811b01e7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
```
In kernel/smp.c (ffffffff811b7c54)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/acct.c (ffffffff811bb66c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff811ccf47)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/rstat.c (ffffffff811ce39b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811d0cfd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff811d181b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/cgroup/cpuset.c (ffffffff811d9364)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
  - kernel/cgroup/cpuset.c:cpuset_read_lock
```
```
In kernel/stop_machine.c (ffffffff811dd56a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_work
```
```
In kernel/kprobes.c (ffffffff811ef487)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/kprobes.c:kprobe_busy_end
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811fcb4f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/hung_task.c (ffffffff811ff435)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_task
```
```
In kernel/relay.c (ffffffff81204bfd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/relay.c:relay_late_setup_files
```
```
In kernel/trace/trace_clock.c (ffffffff812087e0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_local
```
```
In kernel/trace/ftrace.c (ffffffff81208d94)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fpid_stop
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:function_trace_probe_call
  - kernel/trace/ftrace.c:ftrace_ops_trampoline
  - kernel/trace/ftrace.c:ftrace_ops_trampoline
```
```
In kernel/trace/ring_buffer.c (ffffffff81217db2)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_nest_end
  - kernel/trace/ring_buffer.c:ring_buffer_time_stamp
```
```
In kernel/trace/trace.c (ffffffff81220e71)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:saved_cmdlines_stop
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:__trace_puts
  - kernel/trace/trace.c:call_filter_check_discard
  - kernel/trace/trace.c:ftrace_exports
```
```
In kernel/trace/trace_functions.c (ffffffff8122e0e6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122f9be)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_stack.c (ffffffff81231451)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff812320c2)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81232bcd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff812368d6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
```
In kernel/trace/trace_events.c (ffffffff81238e54)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:p_stop
```
```
In kernel/trace/trace_event_perf.c (ffffffff8123ef4f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/trace_events_inject.c (ffffffff812478d6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:event_inject_write
```
```
In kernel/trace/bpf_trace.c (ffffffff81259b48)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
  - kernel/trace/bpf_trace.c:bpf_trace_vprintk
  - kernel/trace/bpf_trace.c:bpf_trace_printk
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125cf20)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff8126570d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/trace/fprobe.c (ffffffff81268653)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In kernel/trace/rethook.c (ffffffff812692c1)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_trampoline_handler
  - kernel/trace/rethook.c:rethook_flush_task
```
```
In kernel/irq_work.c (ffffffff812694f1)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/core.c (ffffffff8126e614)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
```
```
In kernel/bpf/syscall.c (ffffffff81275d70)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/helpers.c (ffffffff812982ff)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_snprintf
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/trampoline.c (ffffffff812aa0d7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
```
In kernel/bpf/btf.c (ffffffff812aaa1b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_alloc_id
```
```
In kernel/bpf/devmap.c (ffffffff812bba39)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff812bd654)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In kernel/bpf/offload.c (ffffffff812be1b0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In kernel/static_call_inline.c (ffffffff812cbfc7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/static_call_inline.c:static_call_text_reserved
```
```
In kernel/events/core.c (ffffffff812e1014)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_read
```
```
In kernel/events/ring_buffer.c (ffffffff812e2691)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In kernel/events/uprobes.c (ffffffff812e8164)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/user-return-notifier.c (ffffffff812e94e8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:fire_user_return_notifiers
```
```
In kernel/jump_label.c (ffffffff812eae29)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_update
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_add_module
```
```
In kernel/rseq.c (ffffffff812ec96f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_update_cpu_id
```
```
In kernel/watch_queue.c (ffffffff812ed01c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In mm/filemap.c (ffffffff812f1b46)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_set_wb_err
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/oom_kill.c (ffffffff812f953f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:wake_oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page-writeback.c (ffffffff812fcb09)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_wait_writeback_killable
  - mm/page-writeback.c:folio_wait_writeback
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (ffffffff8130346a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:lru_add_drain_cpu_zone
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:__folio_activate
```
```
In mm/vmscan.c (ffffffff81312c61)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:pageout
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/shmem.c (ffffffff8131cbf5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/util.c (ffffffff8131e5bc)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/backing-dev.c (ffffffff8132460d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
```
```
In mm/percpu.c (ffffffff813275f2)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
```
```
In mm/slab_common.c (ffffffff8132c420)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/compaction.c (ffffffff8133311c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:compaction_defer_reset
  - mm/compaction.c:compaction_deferred
  - mm/compaction.c:defer_compaction
```
```
In mm/mmap_lock.c (ffffffff8133c708)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
```
```
In mm/memory.c (ffffffff81348b6b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:do_set_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:add_mm_counter_fast
  - mm/memory.c:sync_mm_rss
```
```
In mm/mlock.c (ffffffff8134c48c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/mlock.c:munlock_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:mlock_page_drain_local
```
```
In mm/mmap.c (ffffffff8134f6a5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/mmap.c:vm_unmapped_area
```
```
In mm/rmap.c (ffffffff8135e753)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff813629d1)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In mm/page_alloc.c (ffffffff813703a2)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/memory_hotplug.c (ffffffff81373acd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In mm/swapfile.c (ffffffff8137e35e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff813856a6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In mm/mempolicy.c (ffffffff81395178)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/ksm.c (ffffffff8139e47a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff813a3862)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/slub.c (ffffffff813a74e0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:free_partial
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
```
```
In mm/kfence/core.c (ffffffff813aea98)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_protect_page
```
```
In mm/kfence/report.c (ffffffff81e748b7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/kfence/report.c:kfence_report_error
```
```
In mm/migrate.c (ffffffff813b5729)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff813c1f10)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
```
```
In mm/khugepaged.c (ffffffff813c73a6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff813d4aba)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In mm/memory-failure.c (ffffffff813d8dfc)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff813debb0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/zsmalloc.c (ffffffff813e2533)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In mm/userfaultfd.c (ffffffff813e475e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/open.c (ffffffff813ec26e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff813f30fc)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_write
```
```
In fs/exec.c (ffffffff813fa684)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:__set_task_comm
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff813fdd6c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
```
```
In fs/dcache.c (ffffffff8141324d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
  - fs/dcache.c:___d_drop
```
```
In fs/inode.c (ffffffff814195f6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
  - fs/inode.c:touch_atime
  - fs/inode.c:get_next_ino
```
```
In fs/file.c (ffffffff8141ab62)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/file.c:fd_install
  - fs/file.c:fd_install
```
```
In fs/namespace.c (ffffffff8141e738)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
  - fs/namespace.c:mnt_want_write
  - fs/namespace.c:__mnt_want_write
```
```
In fs/fs-writeback.c (ffffffff814334d6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:write_inode
  - fs/fs-writeback.c:write_inode
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/splice.c (ffffffff81439308)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
```
In fs/fs_struct.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In fs/remap_range.c (ffffffff8144263f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/buffer.c (ffffffff81442ebc)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/buffer.c:free_buffer_head
  - fs/buffer.c:alloc_buffer_head
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81451c98)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In fs/aio.c (ffffffff81465397)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_write
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_add_table
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff81469930)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_one
```
```
In fs/verity/verify.c (ffffffff81474442)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/locks.c (ffffffff8147b490)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
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
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_get_lock_context
```
```
In fs/mbcache.c (ffffffff81481e2c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/coredump.c (ffffffff81485ee9)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/iter.c (ffffffff81487d97)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/iomap/iter.c:iomap_iter
  - fs/iomap/iter.c:iomap_iter_done
  - fs/iomap/iter.c:iomap_iter_done
```
```
In fs/iomap/buffered-io.c (ffffffff8148a6b3)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
  - fs/iomap/buffered-io.c:iomap_release_folio
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_folio
```
```
In fs/iomap/direct-io.c (ffffffff8148d837)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/proc/base.c (ffffffff814a1657)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff814b3287)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/ext4/balloc.c (ffffffff814c0202)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff814c2e37)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (ffffffff814c9e81)
Location: arch/x86/include/asm/preempt.h:93
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
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/extents_status.c (ffffffff814d0c27)
Location: arch/x86/include/asm/preempt.h:93
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
In fs/ext4/file.c (ffffffff814d0f5b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/fsmap.c (ffffffff814d3711)
Location: arch/x86/include/asm/preempt.h:93
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
In fs/ext4/fsync.c (ffffffff814d3d02)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff814d697c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff814d956f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff814dd7fc)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff814ebfa7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_update_other_inode_time
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_release_folio
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
  - fs/ext4/inode.c:ext4_invalidate_folio
  - fs/ext4/inode.c:ext4_read_folio
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
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff814ed2db)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/ioctl.c:ext4_shutdown
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff814f6a33)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff814fda72)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8150825d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_unlink
```
```
In fs/ext4/super.c (ffffffff8152358d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_nfs_commit_metadata
  - fs/ext4/super.c:ext4_drop_inode
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/fast_commit.c (ffffffff81539721)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_update_stats
  - fs/ext4/fast_commit.c:ext4_fc_track_range
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
```
```
In fs/jbd2/transaction.c (ffffffff8153e8bb)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2__journal_start
```
```
In fs/jbd2/commit.c (ffffffff81540ea8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
```
In fs/jbd2/checkpoint.c (ffffffff815437a9)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8154c257)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_shrink_count
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff8154eb2b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81550c4a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/file_direct.c (ffffffff81551713)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff8155191c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_finish_page
  - fs/squashfs/page_actor.c:direct_next_page
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff81551cb5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompress
```
```
In fs/ecryptfs/mmap.c (ffffffff81568bdd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff81569a25)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dax.c (ffffffff8158abfa)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In ipc/util.c (ffffffff81593f81)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/selinux/avc.c (ffffffff815bf832)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_audit_post_callback
```
```
In security/tomoyo/domain.c (ffffffff816009ad)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/capability.c (ffffffff8160f715)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d898)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff8164e799)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In crypto/ahash.c (ffffffff81651d54)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff81653384)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff816727f6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_put
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
```
```
In block/blk-core.c (ffffffff81679c58)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:bdev_start_io_acct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-flush.c (ffffffff8167c183)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff8167da64)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-merge.c (ffffffff816813a0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-mq.c (ffffffff81688063)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_commit_rqs
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_add_rq_to_plug
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_complete_request_remote
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_account_io_done
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
```
```
In block/blk-stat.c (ffffffff8168de50)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add
```
```
In block/genhd.c (ffffffff816925fe)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
```
In block/blk-cgroup.c (ffffffff816a4ddc)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In block/blk-iocost.c (ffffffff816b232c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_wake_fn
  - block/blk-iocost.c:iocg_incur_debt
  - block/blk-iocost.c:iocg_activate
```
```
In block/mq-deadline.c (ffffffff816b4500)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In block/blk-wbt.c (ffffffff816bab27)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:rwb_trace_step
```
```
In io_uring/io_uring.c (ffffffff816d8d14)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_register
  - io_uring/io_uring.c:__x64_sys_io_uring_register
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_file_get_normal
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_arm_poll_handler
  - io_uring/io_uring.c:io_write
  - io_uring/io_uring.c:io_fail_links
  - io_uring/io_uring.c:io_fill_cqe_aux
  - io_uring/io_uring.c:io_cqring_event_overflow
  - io_uring/io_uring.c:io_queue_iowq
```
```
In io_uring/io-wq.c (ffffffff816db350)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wqe_worker
```
```
In lib/scatterlist.c (ffffffff816df4c4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff816e2e6b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
```
```
In lib/rhashtable.c (ffffffff816ea46d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/percpu_counter.c (ffffffff8175e5f3)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_add_batch
```
```
In arch/x86/lib/msr-smp.c (ffffffff81774fad)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
```
```
In arch/x86/lib/msr.c (ffffffff817758d3)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In lib/bug.c (ffffffff8177637f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:find_bug
```
```
In lib/buildid.c (ffffffff81776623)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In lib/flex_proportions.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In lib/nmi_backtrace.c (ffffffff8177c6c4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/radix-tree.c (ffffffff8177cc2e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_preload
```
```
In arch/x86/lib/delay.c (ffffffff8178eaec)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
```
In arch/x86/lib/usercopy_64.c (ffffffff817921dc)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
```
In drivers/gpio/gpiolib.c (ffffffff817a79dd)
Location: arch/x86/include/asm/preempt.h:93
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
```
```
In drivers/pwm/core.c (ffffffff817b5652)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_apply_state
  - drivers/pwm/core.c:pwm_device_request
```
```
In drivers/pci/pcie/aer.c (ffffffff817dae37)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_error
```
```
In drivers/acpi/sleep.c (ffffffff81826c0f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/prmt.c (ffffffff81842e84)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
```
```
In drivers/clk/clk.c (ffffffff818ad6b1)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_phase_nolock
  - drivers/clk/clk.c:clk_core_set_phase_nolock
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
```
```
In drivers/xen/events/events_2l.c (ffffffff818d10c5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818ddbcb)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff818e6612)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/char/virtio_console.c (ffffffff81936584)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/iommu/intel/dmar.c (ffffffff819574b6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/svm.c (ffffffff81961727)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/iommu/iommu.c (ffffffff81965cf3)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:report_iommu_fault
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/iommu/iommu.c:iommu_group_do_detach_device
  - drivers/iommu/iommu.c:__iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/connector/cn_proc.c (ffffffff81972be0)
Location: arch/x86/include/asm/preempt.h:93
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
In drivers/base/syscore.c (ffffffff8197e8d8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/devres.c (ffffffff81983bc4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/devres.c:devm_add_action
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_close_group
  - drivers/base/devres.c:devres_open_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
  - drivers/base/devres.c:devres_get
```
```
In drivers/base/power/qos.c (ffffffff8198e322)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff81991729)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/main.c (ffffffff8199680f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/base/power/wakeup.c (ffffffff81997136)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/regmap/regmap.c (ffffffff819a799b)
Location: arch/x86/include/asm/preempt.h:93
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
```
```
In drivers/base/regmap/regcache.c (ffffffff819acc61)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_cache_bypass
  - drivers/base/regmap/regcache.c:regcache_cache_only
  - drivers/base/regmap/regcache.c:regcache_drop_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_read
```
```
In drivers/block/loop.c (ffffffff819b6dce)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff819bb6e3)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/nvdimm/region_devs.c (ffffffff819d9a68)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_release_lane
  - drivers/nvdimm/region_devs.c:nd_region_release_lane
```
```
In drivers/dma-buf/dma-fence.c (ffffffff819eeaf9)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/dma-buf/sw_sync.c (ffffffff819f4801)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff819fd76c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a003d5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
  - drivers/scsi/scsi_lib.c:scsi_done_internal
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
```
In drivers/scsi/sg.c (ffffffff81a1bd62)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81a25969)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff81a3520a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_done
  - drivers/ata/libata-eh.c:ata_eh_about_to_do
  - drivers/ata/libata-eh.c:__ata_port_freeze
```
```
In drivers/ata/libata-sff.c (ffffffff81a3c7e7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_post_internal_cmd
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:__ata_sff_port_intr
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libata-sff.c:ata_tf_to_host
  - drivers/ata/libata-sff.c:ata_tf_to_host
```
```
In drivers/ata/ata_piix.c (ffffffff81a42629)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_irq_check
```
```
In drivers/spi/spi.c (ffffffff81a4f8e2)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81a5be87)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (ffffffff81a640d5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/xen-netfront.c (ffffffff81a7402f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81af1689)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81af4f78)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81af854d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_trb
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_ring_ep_doorbell
  - drivers/usb/host/xhci-ring.c:inc_enq
  - drivers/usb/host/xhci-ring.c:inc_deq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81b01aa5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b08299)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
  - drivers/usb/host/xhci-dbgcap.c:dbc_free_request
  - drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/rtc/interface.c (ffffffff81b298c8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_set_offset
  - drivers/rtc/interface.c:rtc_read_offset
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_alarm_disable
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_initialize_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b30a8c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b33f58)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff81b449e7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/hwmon/hwmon.c:hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:hwmon_attr_show
```
```
In drivers/thermal/thermal_core.c (ffffffff81b47de4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:handle_thermal_trip
```
```
In drivers/thermal/thermal_helpers.c (ffffffff81b4c106)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:__thermal_cdev_update
```
```
In drivers/thermal/gov_fair_share.c (ffffffff81b4e448)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/thermal/gov_fair_share.c:get_trip_level
```
```
In drivers/thermal/gov_step_wise.c (ffffffff81b4eca8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/thermal/gov_step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81b503c3)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:pid_controller
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81b510ed)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81b51907)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_count
```
```
In drivers/md/md.c (ffffffff81b5a1da)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_discard_bio
```
```
In drivers/md/md-bitmap.c (ffffffff81b6cb1f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/md/dm.c (ffffffff81b71216)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_submit_bio_remap
```
```
In drivers/md/dm-stats.c (ffffffff81b7f46f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/md/dm-rq.c (ffffffff81b810a6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (ffffffff81b824f5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b8ffa4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81b936e6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81b95a40)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81b9759f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_update
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9de10)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81ba0212)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
```
```
In drivers/cpuidle/driver.c (ffffffff81ba0923)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff81ba5b7e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/firmware/efi/capsule.c (ffffffff81bbf674)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81bc32bf)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81bc891b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:send_command
  - drivers/platform/chrome/cros_ec_proto.c:send_command
  - drivers/platform/chrome/cros_ec_proto.c:send_command
  - drivers/platform/chrome/cros_ec_proto.c:send_command
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd459d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
```
In drivers/ras/ras.c (ffffffff81bdec1b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
```
```
In drivers/interconnect/core.c (ffffffff81be3a35)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_set_bw
  - drivers/interconnect/core.c:icc_set_bw
```
```
In net/core/sock.c (ffffffff81bed813)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_error_report
```
```
In net/core/skbuff.c (ffffffff81bf5f4c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:__consume_stateless_skb
```
```
In net/core/datagram.c (ffffffff81c0024e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/gen_estimator.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81c045c6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81c1c59e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_qdisc_enqueue
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/neighbour.c (ffffffff81c2880c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/filter.c (ffffffff81c3db2c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_socket_ptr_cookie
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
```
```
In net/core/sock_diag.c (ffffffff81c4dfd9)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
```
```
In net/core/xdp.c (ffffffff81c51097)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/gro.c (ffffffff81c54621)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
  - net/core/gro.c:napi_gro_receive
```
```
In net/core/page_pool.c (ffffffff81c590bb)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/netpoll.c (ffffffff81c5b4e2)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:poll_one_napi
```
```
In net/core/net-traces.c (ffffffff81c66245)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
```
In net/core/devlink.c (ffffffff81c72802)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_health_report
  - net/core/devlink.c:devlink_health_report
```
```
In net/core/sock_map.c (ffffffff81c907e1)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem_sys
```
```
In net/sched/sch_generic.c (ffffffff81c95bfd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_api.c (ffffffff81c9b68e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81ca0ee4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff81ca53f8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_update_hw_stats
```
```
In net/netlink/af_netlink.c (ffffffff81ca9c6b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81cb6293)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_prog_test_run_tracing
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ipv4/tcp_input.c (ffffffff81cfbdb1)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_output.c (ffffffff81cfef37)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_rtx_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d09671)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_cong.c (ffffffff81d0fc26)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_ca_state
```
```
In net/ipv4/udp.c (ffffffff81d1ca0f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/af_inet.c (ffffffff81d2e1e3)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_state_store
  - net/ipv4/af_inet.c:inet_sk_set_state
```
```
In net/ipv4/fib_trie.c (ffffffff81d3f1c8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81d41b89)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d44c90)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81d56007)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d681fd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In net/ipv6/route.c (ffffffff81da222f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dccea9)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
```
In net/ipv6/ioam6.c (ffffffff81dd807b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81ddb746)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de717e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff81dea2a0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deaf93)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81dec416)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
```
In net/mptcp/protocol.c (ffffffff81e2172b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
```
In net/mptcp/subflow.c (ffffffff81e26d49)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff81e29c64)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/mptcp/options.c:ack_update_msk
```
```
In net/mctp/af_mctp.c (ffffffff81e375a7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In net/mctp/route.c (ffffffff81e3a946)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:__mctp_key_done_in
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
In init/main.c (ffffffff83e61a8e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810055e2)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/amd/ibs.c (ffffffff83e65afd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
```
```
In arch/x86/events/intel/ds.c (ffffffff810178ac)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/p4.c (ffffffff8101ea1d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/xen/time.c (ffffffff83e6af5d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_init_time_ops
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_timerop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/xen/time.c:xen_sched_clock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81038363)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/enlighten_pv.c:xen_mc_batch
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103a012)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_start
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
  - arch/x86/xen/mmu_pv.c:xen_mc_batch
```
```
In arch/x86/xen/multicalls.c (ffffffff8103dd81)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8104507a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
```
```
In arch/x86/hyperv/mmu.c (ffffffff81046cc8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff810472e7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8104929b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/process_64.c (ffffffff8104ae6d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/signal.c (ffffffff8104b19e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/irq.c (ffffffff8104f5d8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
```
```
In arch/x86/kernel/ioport.c (ffffffff81050cdb)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In arch/x86/kernel/nmi.c (ffffffff8105249f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff810546dd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
```
```
In arch/x86/kernel/tsc.c (ffffffff8105d0de)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In arch/x86/kernel/process.c (ffffffff8105f932)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:speculation_ctrl_update_current
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8106147e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:kernel_fpu_end
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81062970)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81063980)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
```
```
In arch/x86/kernel/tls.c (ffffffff81066d24)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
```
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81071e4a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81076e5d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107b02e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff8107cd8e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8108008f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81086005)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108af60)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108ba75)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108db73)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l3_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l2_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81091ba4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81094e2e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
```
```
In arch/x86/kernel/smp.c (ffffffff8109881d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In arch/x86/kernel/smpboot.c (ffffffff83e896db)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109dc8d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff83e8e5fe)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810a7975)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
```
```
In arch/x86/kernel/ftrace.c (ffffffff810aabcd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff810b0c60)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810b1527)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/kernel/kvmclock.c (ffffffff83e96d49)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b88ea)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/kernel/callthunks.c (ffffffff810bec1a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/callthunks.c:is_coretext
```
```
In arch/x86/mm/fault.c (ffffffff820bfb0b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In arch/x86/mm/tlb.c (ffffffff810c9959)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/kmmio.c (ffffffff810d1fc7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
  - arch/x86/mm/kmmio.c:kmmio_handler
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d334a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:post
  - arch/x86/mm/mmio-mod.c:post
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In arch/x86/platform/efi/quirks.c (ffffffff810d7858)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810d883f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff810dae3a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
```
```
In kernel/fork.c (ffffffff810e8d8f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
```
```
In kernel/panic.c (ffffffff810e9f9c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
```
```
In kernel/cpu.c (ffffffff810ed691)
Location: arch/x86/include/asm/preempt.h:93
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
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpus_read_trylock
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
```
```
In kernel/exit.c (ffffffff810f0dc1)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/softirq.c (ffffffff810f39ee)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/softirq.c:__raise_softirq_irqoff
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
```
```
In kernel/signal.c (ffffffff81105101)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal_locked
```
```
In kernel/workqueue.c (ffffffff81110f47)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_inactive_work
  - kernel/workqueue.c:wq_worker_running
```
```
In kernel/pid.c (ffffffff811191c1)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/kthread.c (ffffffff8111da5b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
```
```
In kernel/smpboot.c (ffffffff8112946a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
```
```
In kernel/kmod.c (ffffffff8112b748)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff811425cf)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/sched/core.c:call_trace_sched_update_nr_running
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:send_call_function_single_ipi
  - kernel/sched/core.c:ttwu_do_wakeup
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:migrate_enable
  - kernel/sched/core.c:migrate_disable
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:raw_spin_rq_trylock
  - kernel/sched/core.c:raw_spin_rq_trylock
```
```
In kernel/sched/fair.c (ffffffff8114ce61)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_cpu_capacity
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff81165bb4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:play_idle_precise
  - kernel/sched/build_policy.c:default_idle_call
  - kernel/sched/build_policy.c:default_idle_call
```
```
In kernel/sched/build_utility.c (ffffffff8116e391)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_wait_end
  - kernel/sched/build_utility.c:sched_clock_cpu
  - kernel/sched/build_utility.c:__sched_clock_work
```
```
In kernel/locking/mutex.c (ffffffff820ced5e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff820d0564)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_common
  - kernel/locking/semaphore.c:__down_common
```
```
In kernel/locking/rwsem.c (ffffffff8117d484)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/locking/percpu-rwsem.c (ffffffff820d196a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
```
```
In kernel/locking/spinlock.c (ffffffff820d5c9a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_irq
  - kernel/locking/spinlock.c:_raw_read_unlock_irq
  - kernel/locking/spinlock.c:_raw_write_unlock
  - kernel/locking/spinlock.c:_raw_read_unlock
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_spin_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_spin_unlock_irq
  - kernel/locking/spinlock.c:_raw_spin_unlock
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/qspinlock.c (ffffffff820d685e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex_api.c (ffffffff820d377b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
```
```
In kernel/locking/qrwlock.c (ffffffff820d6e52)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/qos.c (ffffffff8117ecd6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_remove_request
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff81181382)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff81182581)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/power/hibernate.c (ffffffff81183845)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
```
```
In kernel/power/snapshot.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In kernel/printk/printk.c (ffffffff83eab08a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:printk_sprint
```
```
In kernel/irq/handle.c (ffffffff81195b81)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff8119c2c7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
```
```
In kernel/irq/matrix.c (ffffffff811a88e1)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_remove_reserved
  - kernel/irq/matrix.c:irq_matrix_reserve
  - kernel/irq/matrix.c:irq_matrix_assign
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_assign_system
  - kernel/irq/matrix.c:irq_matrix_offline
  - kernel/irq/matrix.c:irq_matrix_online
```
```
In kernel/rcu/tree.c (ffffffff811b8dd8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/core.c (ffffffff811bd16d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_init_object
```
```
In kernel/livepatch/patch.c (ffffffff811bde30)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/livepatch/transition.c (ffffffff811bf4e0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/dma/swiotlb.c (ffffffff811c556a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In kernel/entry/common.c (ffffffff811c674d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/module/main.c (ffffffff811cd8e4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/module/main.c:print_modules
  - kernel/module/main.c:is_module_text_address
  - kernel/module/main.c:is_module_address
  - kernel/module/main.c:search_module_extables
  - kernel/module/main.c:load_module
  - kernel/module/main.c:__symbol_get
  - kernel/module/main.c:__symbol_get
  - kernel/module/main.c:free_module
  - kernel/module/main.c:module_put
  - kernel/module/main.c:module_put
  - kernel/module/main.c:try_module_get
  - kernel/module/main.c:try_module_get
  - kernel/module/main.c:symbol_put_addr
  - kernel/module/main.c:__symbol_put
  - kernel/module/main.c:__is_module_percpu_address
  - kernel/module/main.c:__is_module_percpu_address
```
```
In kernel/module/kallsyms.c (ffffffff811cf461)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:module_kallsyms_on_each_symbol
  - kernel/module/kallsyms.c:module_kallsyms_lookup_name
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:lookup_module_symbol_attrs
  - kernel/module/kallsyms.c:lookup_module_symbol_attrs
  - kernel/module/kallsyms.c:lookup_module_symbol_name
  - kernel/module/kallsyms.c:lookup_module_symbol_name
  - kernel/module/kallsyms.c:module_address_lookup
```
```
In kernel/module/version.c (ffffffff811d07fd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/module/version.c:check_modstruct_version
  - kernel/module/version.c:check_modstruct_version
```
```
In kernel/profile.c (ffffffff811d21c3)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/profile.c:profile_discard_flip_buffers
  - kernel/profile.c:profile_flip_buffers
```
```
In kernel/time/timer.c (ffffffff811d8987)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:detach_if_pending
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/time/hrtimer.c (ffffffff811daf6f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_init
  - kernel/time/hrtimer.c:hrtimer_try_to_cancel
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/time/timekeeping.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In kernel/time/clocksource.c (ffffffff811e0c3a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In kernel/time/alarmtimer.c (ffffffff811e376b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811e89dd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/time/itimer.c (ffffffff811ec095)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-common.c (ffffffff811ee7f2)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff811f0c87)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
```
In kernel/smp.c (ffffffff811f8ede)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/acct.c (ffffffff811fd48c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81210507)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/rstat.c (ffffffff81211b69)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81214845)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff81215408)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/cgroup/cpuset.c (ffffffff8121e5f4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
  - kernel/cgroup/cpuset.c:cpuset_read_lock
```
```
In kernel/stop_machine.c (ffffffff81222f9a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_work
```
```
In kernel/kprobes.c (ffffffff81235cd7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/kprobes.c:kprobe_busy_end
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81244277)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/hung_task.c (ffffffff81246e2b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_task
```
```
In kernel/relay.c (ffffffff8124c92e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/relay.c:relay_late_setup_files
```
```
In kernel/trace/trace_clock.c (ffffffff81250cc0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_local
```
```
In kernel/trace/ftrace.c (ffffffff81251374)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fpid_stop
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:function_trace_probe_call
  - kernel/trace/ftrace.c:ftrace_ops_trampoline
  - kernel/trace/ftrace.c:ftrace_ops_trampoline
```
```
In kernel/trace/ring_buffer.c (ffffffff812612d2)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_nest_end
  - kernel/trace/ring_buffer.c:ring_buffer_time_stamp
```
```
In kernel/trace/trace.c (ffffffff8126bd0e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_stop
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:__trace_puts
  - kernel/trace/trace.c:call_filter_check_discard
  - kernel/trace/trace.c:ftrace_exports
```
```
In kernel/trace/trace_functions.c (ffffffff81279fa6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127bb4e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_stack.c (ffffffff8127d9c1)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8127e712)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8127f324)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff812835c8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
```
In kernel/trace/trace_events.c (ffffffff81285dc4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:p_stop
```
```
In kernel/trace/trace_event_perf.c (ffffffff8128c9bf)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/trace_events_inject.c (ffffffff812959eb)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:trace_inject_entry
```
```
In kernel/trace/bpf_trace.c (ffffffff812a9db8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
  - kernel/trace/bpf_trace.c:bpf_trace_vprintk
  - kernel/trace/bpf_trace.c:bpf_trace_printk
```
```
In kernel/trace/trace_kprobe.c (ffffffff812abedf)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b8199)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/trace/fprobe.c (ffffffff812ba893)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In kernel/trace/rethook.c (ffffffff812bb621)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_trampoline_handler
  - kernel/trace/rethook.c:rethook_flush_task
```
```
In kernel/trace/rv/monitors/wwnr/wwnr.c (ffffffff812bd0a2)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr
```
```
In kernel/irq_work.c (ffffffff812be374)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/core.c (ffffffff812c3cb4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
```
```
In kernel/bpf/syscall.c (ffffffff812cbe90)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/helpers.c (ffffffff812f34af)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_snprintf
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff812fc39f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
```
```
In kernel/bpf/trampoline.c (ffffffff81309196)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
```
In kernel/bpf/btf.c (ffffffff8130a26b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_alloc_id
```
```
In kernel/bpf/devmap.c (ffffffff8131edc9)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff81320aef)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In kernel/bpf/offload.c (ffffffff8132176d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In kernel/static_call_inline.c (ffffffff813339b7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/static_call_inline.c:static_call_text_reserved
```
```
In kernel/events/core.c (ffffffff81342af5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_cgroup_move
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_read
```
```
In kernel/events/ring_buffer.c (ffffffff8134ad11)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134cdad)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81351eb4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/user-return-notifier.c (ffffffff81353278)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:fire_user_return_notifiers
```
```
In kernel/jump_label.c (ffffffff81354e39)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_update
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_add_module
```
```
In kernel/rseq.c (ffffffff81357050)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
```
```
In kernel/watch_queue.c (ffffffff8135739c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In mm/filemap.c (ffffffff8135cc00)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_set_wb_err
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/oom_kill.c (ffffffff813632bf)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:wake_oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page-writeback.c (ffffffff81366e69)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_wait_writeback_killable
  - mm/page-writeback.c:folio_wait_writeback
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (ffffffff81370d73)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:lru_add_drain_cpu_zone
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff813860aa)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:pageout
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/shmem.c (ffffffff81389ba1)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In mm/util.c (ffffffff8139209c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/backing-dev.c (ffffffff81398f3d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
```
```
In mm/percpu.c (ffffffff8139be19)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff813a1aae)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_large_node
  - mm/slab_common.c:kmalloc_large
  - mm/slab_common.c:kmalloc_node_trace
  - mm/slab_common.c:kmalloc_trace
  - mm/slab_common.c:kfree
  - mm/slab_common.c:__kmalloc_node_track_caller
  - mm/slab_common.c:__kmalloc_node_track_caller
  - mm/slab_common.c:__kmalloc
  - mm/slab_common.c:__kmalloc
  - mm/slab_common.c:__kmalloc_node
  - mm/slab_common.c:__kmalloc_node
```
```
In mm/compaction.c (ffffffff813a9cd9)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:compaction_defer_reset
  - mm/compaction.c:compaction_deferred
  - mm/compaction.c:defer_compaction
```
```
In mm/mmap_lock.c (ffffffff813b4178)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
```
```
In mm/memory.c (ffffffff813c0fd8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:do_set_pte
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff813c501c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/mlock.c:munlock_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:mlock_page_drain_local
```
```
In mm/mmap.c (ffffffff813ca0db)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_unmapped_area
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_mas_remove
  - mm/mmap.c:vma_mas_store
```
```
In mm/rmap.c (ffffffff813d97ac)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff813dc6da)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/page_alloc.c (ffffffff813eca42)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/memory_hotplug.c (ffffffff813f11fd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In mm/swapfile.c (ffffffff813fbf6e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff8140340f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In mm/mempolicy.c (ffffffff81414d18)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/ksm.c (ffffffff8141db9a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff8142364d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/slub.c (ffffffff8142ca87)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_alloc_bulk
  - mm/slub.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:__unfreeze_partials
```
```
In mm/kfence/core.c (ffffffff8142efcc)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_protect_page
```
```
In mm/kfence/report.c (ffffffff81431022)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/kfence/report.c:kfence_report_error
```
```
In mm/migrate.c (ffffffff81435731)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81444110)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:mm_get_huge_zero_page
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff8144ab49)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff8145a4fa)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In mm/memory-failure.c (ffffffff8145e878)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff81465870)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/zsmalloc.c (ffffffff81468339)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/zsmalloc.c:restore_freelist
  - mm/zsmalloc.c:restore_freelist
  - mm/zsmalloc.c:restore_freelist
  - mm/zsmalloc.c:restore_freelist
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:find_tagged_obj
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In fs/open.c (ffffffff8147473e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff8147bdea)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_write
```
```
In fs/exec.c (ffffffff814841b4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
  - fs/exec.c:__set_task_comm
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/pipe.c (ffffffff8148798c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
```
```
In fs/dcache.c (ffffffff8149e4f5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
  - fs/dcache.c:___d_drop
```
```
In fs/inode.c (ffffffff814a5036)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
  - fs/inode.c:touch_atime
  - fs/inode.c:get_next_ino
```
```
In fs/file.c (ffffffff814a6732)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/file.c:fd_install
  - fs/file.c:fd_install
```
```
In fs/namespace.c (ffffffff814aae48)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
  - fs/namespace.c:mnt_want_write
  - fs/namespace.c:__mnt_want_write
```
```
In fs/fs-writeback.c (ffffffff814c1820)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:write_inode
  - fs/fs-writeback.c:write_inode
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/splice.c (ffffffff814c75f8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
```
In fs/fs_struct.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In fs/remap_range.c (ffffffff814d132f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/buffer.c (ffffffff814d1fdc)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/buffer.c:free_buffer_head
  - fs/buffer.c:alloc_buffer_head
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e0a08)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In fs/aio.c (ffffffff814f53d7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_write
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_add_table
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff814fa6fd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_pmd_load_hole
  - fs/dax.c:dax_pmd_load_hole
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_one
```
```
In fs/locks.c (ffffffff8150e020)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
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
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_get_lock_context
```
```
In fs/mbcache.c (ffffffff81514fcf)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/coredump.c (ffffffff81519774)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/iter.c (ffffffff8151b9e5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/iomap/iter.c:iomap_iter
  - fs/iomap/iter.c:iomap_iter_done
  - fs/iomap/iter.c:iomap_iter_done
```
```
In fs/iomap/buffered-io.c (ffffffff8151e042)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
  - fs/iomap/buffered-io.c:iomap_release_folio
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_folio
```
```
In fs/iomap/direct-io.c (ffffffff81520df8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/proc/base.c (ffffffff81536677)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff81549ef7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/ext4/balloc.c (ffffffff8155824d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8155b1a7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (ffffffff81562516)
Location: arch/x86/include/asm/preempt.h:93
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
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/extents_status.c (ffffffff81569627)
Location: arch/x86/include/asm/preempt.h:93
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
In fs/ext4/file.c (ffffffff8156999b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/fsmap.c (ffffffff8156c312)
Location: arch/x86/include/asm/preempt.h:93
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
In fs/ext4/fsync.c (ffffffff8156c952)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff8156f732)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8157273d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8157682c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81585d14)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_update_other_inode_time
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_release_folio
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
  - fs/ext4/inode.c:ext4_invalidate_folio
  - fs/ext4/inode.c:ext4_read_folio
  - fs/ext4/inode.c:ext4_alloc_da_blocks
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff8158717f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/ioctl.c:ext4_shutdown
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff81590f0c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff81598262)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff815a2d42)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_unlink
```
```
In fs/ext4/super.c (ffffffff815c075d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_nfs_commit_metadata
  - fs/ext4/super.c:ext4_drop_inode
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/fast_commit.c (ffffffff815d7b2e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_update_stats
  - fs/ext4/fast_commit.c:ext4_fc_track_range
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
```
```
In fs/jbd2/transaction.c (ffffffff815dd2ae)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2__journal_start
```
```
In fs/jbd2/commit.c (ffffffff815dfffb)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
```
In fs/jbd2/checkpoint.c (ffffffff815e26f9)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff815ec06f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_shrink_count
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff815ef5ac)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff815f1926)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff815f2ea5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompress
```
```
In fs/ecryptfs/mmap.c (ffffffff8160c50d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff8160d658)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dax.c (ffffffff81631357)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In ipc/util.c (ffffffff8163cb41)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/selinux/avc.c (ffffffff8166bb92)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_audit_post_callback
```
```
In security/tomoyo/domain.c (ffffffff816b1914)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/capability.c (ffffffff816c2113)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/policy_unpack.c (ffffffff816d1354)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff816dae42)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - security/apparmor/lsm.c:aa_put_buffer
  - security/apparmor/lsm.c:aa_put_buffer
  - security/apparmor/lsm.c:aa_get_buffer
  - security/apparmor/lsm.c:aa_get_buffer
  - security/apparmor/lsm.c:aa_get_buffer
  - security/apparmor/lsm.c:aa_get_buffer
```
```
In crypto/scatterwalk.c (ffffffff81707bf9)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In crypto/ahash.c (ffffffff8170b784)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff8170d0a4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff8172e174)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_put_percpu_cache
  - block/bio.c:bio_put_percpu_cache
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
```
```
In block/blk-core.c (ffffffff817360b8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:bdev_start_io_acct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct_nocheck
```
```
In block/blk-flush.c (ffffffff81738a03)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff8173a674)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-merge.c (ffffffff8173e92e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:__bio_split_to_limits
```
```
In block/blk-mq.c (ffffffff81746441)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_commit_rqs
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_add_rq_to_plug
  - block/blk-mq.c:blk_add_rq_to_plug
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_complete_request_remote
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_account_io_done
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
```
```
In block/blk-stat.c (ffffffff8174c740)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add
```
```
In block/genhd.c (ffffffff817518fe)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
```
In block/blk-cgroup.c (ffffffff81763b92)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
  - block/blk-cgroup.c:blkcg_init_disk
  - block/blk-cgroup.c:blkcg_init_disk
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In block/blk-iocost.c (ffffffff8177185c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_wake_fn
  - block/blk-iocost.c:iocg_incur_debt
  - block/blk-iocost.c:iocg_activate
```
```
In block/mq-deadline.c (ffffffff81773f00)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In block/blk-wbt.c (ffffffff8177b12a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:rwb_trace_step
```
```
In io_uring/io_uring.c (ffffffff8178c8c7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_register
  - io_uring/io_uring.c:__x64_sys_io_uring_register
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_file_get_normal
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:io_fill_cqe_aux
  - io_uring/io_uring.c:io_cqring_event_overflow
  - io_uring/io_uring.c:io_queue_iowq
  - io_uring/io_uring.c:__io_fill_cqe_req
```
```
In io_uring/timeout.c (ffffffff817995ca)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - io_uring/timeout.c:io_disarm_next
```
```
In io_uring/poll.c (ffffffff8179db61)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - io_uring/poll.c:io_arm_poll_handler
  - io_uring/poll.c:__io_poll_execute
```
```
In io_uring/rw.c (ffffffff817a4b96)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_write
  - io_uring/rw.c:__io_fill_cqe_req
```
```
In io_uring/io-wq.c (ffffffff817a742c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wqe_worker
```
```
In lib/scatterlist.c (ffffffff817cf704)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff817d558b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
```
```
In lib/rhashtable.c (ffffffff817da686)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/percpu_counter.c (ffffffff8188bb63)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_add_batch
```
```
In arch/x86/lib/msr-smp.c (ffffffff818a5afd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
```
```
In arch/x86/lib/msr.c (ffffffff818a6583)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In drivers/gpio/gpiolib.c (ffffffff818bff94)
Location: arch/x86/include/asm/preempt.h:93
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
```
```
In drivers/pwm/core.c (ffffffff818cf99c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_apply_state
  - drivers/pwm/core.c:pwm_device_request
```
```
In drivers/pci/pcie/aer.c (ffffffff818fccac)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
```
In drivers/acpi/sleep.c (ffffffff81958b37)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/prmt.c (ffffffff81979f84)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
```
```
In drivers/clk/clk.c (ffffffff819f8e71)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_phase_nolock
  - drivers/clk/clk.c:clk_core_set_phase_nolock
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
```
In drivers/xen/events/events_2l.c (ffffffff81a229d7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a310bb)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff81a3b3ae)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/char/random.c (ffffffff81a94f26)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/char/virtio_console.c (ffffffff81a963c4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abe3c7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/svm.c (ffffffff81aca1b6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/iommu/iommu.c (ffffffff81acf2b3)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:report_iommu_fault
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/iommu/iommu.c:iommu_group_do_detach_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/connector/cn_proc.c (ffffffff81addf10)
Location: arch/x86/include/asm/preempt.h:93
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
In drivers/base/syscore.c (ffffffff81aebec9)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/devres.c (ffffffff81af1c74)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/devres.c:devm_add_action
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_close_group
  - drivers/base/devres.c:devres_open_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
  - drivers/base/devres.c:devres_get
```
```
In drivers/base/power/qos.c (ffffffff81afe532)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff81b01af9)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/main.c (ffffffff81b0758b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/base/power/wakeup.c (ffffffff81b08816)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/regmap/regmap.c (ffffffff81b1aa0b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:_regmap_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/base/regmap/regcache.c (ffffffff81b20421)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_cache_bypass
  - drivers/base/regmap/regcache.c:regcache_cache_only
  - drivers/base/regmap/regcache.c:regcache_drop_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_read
```
```
In drivers/block/loop.c (ffffffff81b2c02a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff81b30c33)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/nvdimm/region_devs.c (ffffffff81b54bc8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_release_lane
  - drivers/nvdimm/region_devs.c:nd_region_release_lane
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81b6c209)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81b71c31)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff81b7bb87)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7e9e5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
  - drivers/scsi/scsi_lib.c:scsi_done_internal
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b962d6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/scsi/sg.c (ffffffff81b9cf22)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81ba7b29)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff81bb9aef)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_done
  - drivers/ata/libata-eh.c:ata_eh_about_to_do
  - drivers/ata/libata-eh.c:__ata_port_freeze
```
```
In drivers/ata/libata-sff.c (ffffffff81bc1a87)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_post_internal_cmd
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:__ata_sff_port_intr
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libata-sff.c:ata_tf_to_host
  - drivers/ata/libata-sff.c:ata_tf_to_host
```
```
In drivers/ata/ata_piix.c (ffffffff81bc8a79)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_irq_check
```
```
In drivers/spi/spi.c (ffffffff81bd702a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_split_transfers_maxsize
  - drivers/spi/spi.c:spi_split_transfers_maxsize
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_wait
  - drivers/spi/spi.c:spi_transfer_wait
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81be62b7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (ffffffff81bef315)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/xen-netfront.c (ffffffff81c080c7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81c7e5d5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81c827c1)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81c8645d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_trb
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_ring_ep_doorbell
  - drivers/usb/host/xhci-ring.c:inc_enq
  - drivers/usb/host/xhci-ring.c:inc_deq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81c90aa6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c98082)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
  - drivers/usb/host/xhci-dbgcap.c:dbc_free_request
  - drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/rtc/interface.c (ffffffff81cbd4b8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_set_offset
  - drivers/rtc/interface.c:rtc_read_offset
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_alarm_disable
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_initialize_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc5354)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc8f14)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff81cdbabb)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/hwmon/hwmon.c:hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:hwmon_attr_show
```
```
In drivers/thermal/thermal_core.c (ffffffff81cddcd6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:handle_thermal_trip
```
```
In drivers/thermal/thermal_helpers.c (ffffffff81ce3ce6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:__thermal_cdev_update
```
```
In drivers/thermal/gov_fair_share.c (ffffffff81ce6378)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/thermal/gov_fair_share.c:get_trip_level
```
```
In drivers/thermal/gov_step_wise.c (ffffffff81ce6abc)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/thermal/gov_step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81ce8302)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:pid_controller
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81ce90fd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81ce9a27)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_count
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81ceb384)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81ced546)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff81cf295a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_discard_bio
```
```
In drivers/md/md-bitmap.c (ffffffff81d08c2f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/md/dm.c (ffffffff81d0e026)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_submit_bio_remap
```
```
In drivers/md/dm-stats.c (ffffffff81d1cd3f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/md/dm-rq.c (ffffffff81d1f3b6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (ffffffff81d20e50)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d3020b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d33da6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d36320)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81d38463)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_update
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3fc96)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81d41ee9)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
```
```
In drivers/cpuidle/driver.c (ffffffff81d42593)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In drivers/cpuidle/governors/haltpoll.c (ffffffff81d45cc6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff81d47e8e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/firmware/efi/capsule.c (ffffffff81d63e94)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81d67800)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81d718a3)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff81d805ad)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
```
In drivers/ras/ras.c (ffffffff81d8a07b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
```
```
In drivers/interconnect/core.c (ffffffff81d8f72e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_set_bw
  - drivers/interconnect/core.c:icc_set_bw
```
```
In net/core/sock.c (ffffffff81d9e387)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_error_report
```
```
In net/core/skbuff.c (ffffffff81da486c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:kfree_skb_reason
```
```
In net/core/datagram.c (ffffffff81daf65e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/gen_estimator.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81db4096)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81dcd5ba)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_qdisc_enqueue
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/neighbour.c (ffffffff81ddb4cd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/filter.c (ffffffff81df1a6c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_socket_ptr_cookie
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
```
```
In net/core/sock_diag.c (ffffffff81e02ff2)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
```
```
In net/core/xdp.c (ffffffff81e062f6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/gro.c (ffffffff81e09d71)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
  - net/core/gro.c:napi_gro_receive
```
```
In net/core/page_pool.c (ffffffff81e0f01b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
```
```
In net/core/netpoll.c (ffffffff81e117a6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:poll_one_napi
```
```
In net/core/net-traces.c (ffffffff81e1cfa2)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
```
In net/core/devlink.c (ffffffff81e2abee)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_health_report
  - net/core/devlink.c:devlink_health_report
```
```
In net/core/sock_map.c (ffffffff81e4bc41)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem_sys
```
```
In net/sched/sch_generic.c (ffffffff81e5178d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_api.c (ffffffff81e57b99)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/cls_api.c (ffffffff81e5cf24)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff81e61ed8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_update_hw_stats
```
```
In net/netlink/af_netlink.c (ffffffff81e66c5b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81e74768)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_prog_test_run_tracing
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ipv4/tcp_input.c (ffffffff81ec0931)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_output.c (ffffffff81ec3f87)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_rtx_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ece92f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_cong.c (ffffffff81ed5886)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_ca_state
```
```
In net/ipv4/udp.c (ffffffff81ee3aa8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/af_inet.c (ffffffff81ef6133)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_state_store
  - net/ipv4/af_inet.c:inet_sk_set_state
```
```
In net/ipv4/fib_trie.c (ffffffff81f07d8c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a998)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0df2f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81f20725)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f3329b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In net/ipv6/route.c (ffffffff81f715cf)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9dfb8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
```
In net/ipv6/ioam6.c (ffffffff81fa9a67)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81fae336)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fba00e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff81fbdb60)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbeb81)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fc0066)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
```
In net/mptcp/protocol.c (ffffffff81ff8bfb)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
```
In net/mptcp/subflow.c (ffffffff81ffe4da)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff82001d64)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/mptcp/options.c:ack_update_msk
```
```
In net/mctp/af_mctp.c (ffffffff820103f5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In net/mctp/route.c (ffffffff82013ef0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:__mctp_key_done_in
```
```
In lib/bug.c (ffffffff8201edaf)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:report_bug
  - lib/bug.c:find_bug
```
```
In lib/buildid.c (ffffffff8201f070)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In lib/flex_proportions.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In lib/maple_tree.c (ffffffff82030c4a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_find
  - lib/maple_tree.c:mtree_erase
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_load
  - lib/maple_tree.c:mas_store_prealloc
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_store
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_slot_store
  - lib/maple_tree.c:mas_wr_node_store
  - lib/maple_tree.c:mas_is_span_wr
```
```
In lib/nmi_backtrace.c (ffffffff82039194)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/radix-tree.c (ffffffff820396fe)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_preload
```
```
In arch/x86/lib/delay.c (ffffffff8204c49c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
```
In arch/x86/lib/usercopy_64.c (ffffffff8204ffac)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
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
In init/main.c (ffffffff83681eae)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004df1)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/amd/ibs.c (ffffffff8368617d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
```
```
In arch/x86/events/intel/ds.c (ffffffff8101724c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/p4.c (ffffffff8101e70d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/xen/time.c (ffffffff8368b9fd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_init_time_ops
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_timerop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff810382c3)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/enlighten_pv.c:xen_mc_batch
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103a0a2)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_start
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
  - arch/x86/xen/mmu_pv.c:xen_mc_batch
```
```
In arch/x86/xen/multicalls.c (ffffffff8103dc35)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/hyperv/hv_init.c (ffffffff810451ba)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
```
```
In arch/x86/hyperv/mmu.c (ffffffff8104706d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff81047667)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff810494fb)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/process_64.c (ffffffff8104b686)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/signal.c (ffffffff8104ba3e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/irq.c (ffffffff81050288)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
```
```
In arch/x86/kernel/ioport.c (ffffffff81051a0b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In arch/x86/kernel/nmi.c (ffffffff8105332f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff8105573d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
```
```
In arch/x86/kernel/tsc.c (ffffffff8105e971)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:cyc2ns_read_end
```
```
In arch/x86/kernel/process.c (ffffffff81061082)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:speculation_ctrl_update_current
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81062d4e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:kernel_fpu_end
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81064753)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:check_xstate_in_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810652d7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff81068444)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
```
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81073a3a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107905d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107d2ce)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff8107f13e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8108241e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108e000)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81090a23)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l3_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l2_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81094aae)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81097d1e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
```
```
In arch/x86/kernel/smp.c (ffffffff8109b72d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In arch/x86/kernel/smpboot.c (ffffffff836acbfb)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a0c69)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff836b1e9e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810aabd6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
```
```
In arch/x86/kernel/ftrace.c (ffffffff810adf9d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff810b3a00)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810b44e9)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/kernel/kvmclock.c (ffffffff836ba8f9)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bbaba)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/kernel/callthunks.c (ffffffff810c22d6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/callthunks.c:is_coretext
```
```
In arch/x86/mm/fault.c (ffffffff821417e8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In arch/x86/mm/tlb.c (ffffffff810ccfd4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/kmmio.c (ffffffff810d5437)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
  - arch/x86/mm/kmmio.c:kmmio_handler
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d672a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:post
  - arch/x86/mm/mmio-mod.c:post
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In arch/x86/platform/efi/quirks.c (ffffffff810e2de8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810e3dcf)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff810e63d7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
```
```
In kernel/fork.c (ffffffff810f499e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
```
```
In kernel/panic.c (ffffffff810f5b9c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
```
```
In kernel/cpu.c (ffffffff810f9221)
Location: arch/x86/include/asm/preempt.h:93
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
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpus_read_trylock
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
```
```
In kernel/exit.c (ffffffff810fcd71)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/softirq.c (ffffffff810ffd3e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/softirq.c:__raise_softirq_irqoff
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
```
```
In kernel/signal.c (ffffffff81111381)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal_locked
```
```
In kernel/workqueue.c (ffffffff8111d147)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_inactive_work
  - kernel/workqueue.c:wq_worker_running
```
```
In kernel/pid.c (ffffffff81126691)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/kthread.c (ffffffff8112ac4b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
```
```
In kernel/notifier.c (ffffffff811327e0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/notifier.c:notifier_call_chain
  - kernel/notifier.c:notifier_chain_unregister
```
```
In kernel/smpboot.c (ffffffff8113690a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
```
```
In kernel/sched/core.c (ffffffff8114e2df)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/sched/core.c:call_trace_sched_update_nr_running
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:call_function_single_prep_ipi
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:migrate_enable
  - kernel/sched/core.c:migrate_disable
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:raw_spin_rq_trylock
  - kernel/sched/core.c:raw_spin_rq_trylock
```
```
In kernel/sched/fair.c (ffffffff8115b2a6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff8116d2c4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:play_idle_precise
  - kernel/sched/build_policy.c:default_idle_call
  - kernel/sched/build_policy.c:default_idle_call
```
```
In kernel/sched/build_utility.c (ffffffff8117e9b7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_wait_end
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:running_clock
  - kernel/sched/build_utility.c:sched_clock_cpu
  - kernel/sched/build_utility.c:__sched_clock_work
```
```
In kernel/locking/mutex.c (ffffffff821531f1)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff821548f4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_common
  - kernel/locking/semaphore.c:__down_common
```
```
In kernel/locking/rwsem.c (ffffffff8118dfd4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (ffffffff82155cda)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
```
```
In kernel/locking/spinlock.c (ffffffff8215907a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_irq
  - kernel/locking/spinlock.c:_raw_read_unlock_irq
  - kernel/locking/spinlock.c:_raw_write_unlock
  - kernel/locking/spinlock.c:_raw_read_unlock
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_spin_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_spin_unlock_irq
  - kernel/locking/spinlock.c:_raw_spin_unlock
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/qspinlock.c (ffffffff82159c4d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex_api.c (ffffffff821579fb)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
```
```
In kernel/locking/qrwlock.c (ffffffff8215a1e2)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/qos.c (ffffffff8118f926)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_remove_request
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff81192282)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff8119343a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/power/hibernate.c (ffffffff811946b5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
```
```
In kernel/power/snapshot.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In kernel/printk/printk.c (ffffffff836d004a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:printk_sprint
```
```
In kernel/irq/handle.c (ffffffff811a7551)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff811ae127)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
```
```
In kernel/irq/matrix.c (ffffffff811ba5b8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_remove_reserved
  - kernel/irq/matrix.c:irq_matrix_reserve
  - kernel/irq/matrix.c:irq_matrix_assign
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_assign_system
  - kernel/irq/matrix.c:irq_matrix_offline
  - kernel/irq/matrix.c:irq_matrix_online
```
```
In kernel/rcu/tree.c (ffffffff811cb418)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/core.c (ffffffff811cf97d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_init_object
```
```
In kernel/livepatch/patch.c (ffffffff811d0831)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/livepatch/transition.c (ffffffff811d1fc0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/dma/swiotlb.c (ffffffff811d8142)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In kernel/entry/common.c (ffffffff811d936d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/module/main.c (ffffffff811e1284)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/module/main.c:print_modules
  - kernel/module/main.c:is_module_text_address
  - kernel/module/main.c:is_module_address
  - kernel/module/main.c:search_module_extables
  - kernel/module/main.c:load_module
  - kernel/module/main.c:__symbol_get
  - kernel/module/main.c:__symbol_get
  - kernel/module/main.c:free_module
  - kernel/module/main.c:module_put
  - kernel/module/main.c:try_module_get
  - kernel/module/main.c:symbol_put_addr
  - kernel/module/main.c:__symbol_put
  - kernel/module/main.c:__is_module_percpu_address
  - kernel/module/main.c:__is_module_percpu_address
```
```
In kernel/module/kmod.c (ffffffff811e188e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/module/kmod.c:__request_module
```
```
In kernel/module/kallsyms.c (ffffffff811e35e3)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:module_kallsyms_on_each_symbol
  - kernel/module/kallsyms.c:find_kallsyms_symbol_value
  - kernel/module/kallsyms.c:module_kallsyms_lookup_name
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:lookup_module_symbol_name
  - kernel/module/kallsyms.c:lookup_module_symbol_name
  - kernel/module/kallsyms.c:module_address_lookup
```
```
In kernel/module/version.c (ffffffff811e4a7d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/module/version.c:check_modstruct_version
  - kernel/module/version.c:check_modstruct_version
```
```
In kernel/profile.c (ffffffff811e64b1)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/profile.c:profile_discard_flip_buffers
  - kernel/profile.c:profile_flip_buffers
```
```
In kernel/time/timer.c (ffffffff811ecdb2)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:detach_if_pending
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/time/hrtimer.c (ffffffff811ef499)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_init
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/time/timekeeping.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In kernel/time/clocksource.c (ffffffff811f519a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In kernel/time/alarmtimer.c (ffffffff811f7ddb)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811fcfed)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/time/itimer.c (ffffffff812007c5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-common.c (ffffffff81202f22)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff812056aa)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
```
In kernel/smp.c (ffffffff8120db8e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:generic_exec_single
  - kernel/smp.c:generic_exec_single
  - kernel/smp.c:__smp_call_single_queue
  - kernel/smp.c:__smp_call_single_queue
```
```
In kernel/acct.c (ffffffff81212619)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8121ee3a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_put_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/rstat.c (ffffffff812274c9)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8122a165)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff8122ad38)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In kernel/stop_machine.c (ffffffff8123966a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_work
```
```
In kernel/kprobes.c (ffffffff8124caf7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/kprobes.c:kprobe_busy_end
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8125b357)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/hung_task.c (ffffffff8125dea9)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_task
```
```
In kernel/relay.c (ffffffff81263c95)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/relay.c:relay_late_setup_files
```
```
In kernel/trace/trace_clock.c (ffffffff81268050)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_local
```
```
In kernel/trace/ftrace.c (ffffffff812687f4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fpid_stop
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:function_trace_probe_call
  - kernel/trace/ftrace.c:ftrace_ops_trampoline
  - kernel/trace/ftrace.c:ftrace_ops_trampoline
```
```
In kernel/trace/ring_buffer.c (ffffffff81278362)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_nest_end
  - kernel/trace/ring_buffer.c:ring_buffer_time_stamp
```
```
In kernel/trace/trace.c (ffffffff81283075)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_stop
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:__trace_array_puts
  - kernel/trace/trace.c:call_filter_check_discard
  - kernel/trace/trace.c:ftrace_exports
```
```
In kernel/trace/trace_functions.c (ffffffff812919f9)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8129366e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_osnoise.c (ffffffff81297932)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:trace_sched_switch_callback
  - kernel/trace/trace_osnoise.c:trace_softirq_exit_callback
  - kernel/trace/trace_osnoise.c:osnoise_trace_irq_exit
  - kernel/trace/trace_osnoise.c:trace_osnoise_callback
```
```
In kernel/trace/trace_stack.c (ffffffff8129a441)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8129b192)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8129beb4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff812a0273)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
```
In kernel/trace/trace_events.c (ffffffff812a2a84)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:p_stop
```
```
In kernel/trace/trace_event_perf.c (ffffffff812a990f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/trace_events_inject.c (ffffffff812b28fb)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:trace_inject_entry
```
```
In kernel/trace/trace_events_user.c (ffffffff812c6037)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:update_enable_bit_for
  - kernel/trace/trace_events_user.c:user_event_ftrace
```
```
In kernel/trace/bpf_trace.c (ffffffff812ca4dc)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:get_modules_for_addrs
  - kernel/trace/bpf_trace.c:get_modules_for_addrs
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
  - kernel/trace/bpf_trace.c:bpf_trace_vprintk
  - kernel/trace/bpf_trace.c:bpf_trace_printk
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ce6df)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff812db7c0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/trace/fprobe.c (ffffffff812ddd99)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In kernel/trace/rethook.c (ffffffff812df244)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_trampoline_handler
  - kernel/trace/rethook.c:rethook_flush_task
```
```
In kernel/trace/rv/monitors/wwnr/wwnr.c (ffffffff812e3c72)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr
```
```
In kernel/irq_work.c (ffffffff812e4fb4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/core.c (ffffffff812eab04)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
```
```
In kernel/bpf/syscall.c (ffffffff812f3800)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/helpers.c (ffffffff81320189)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - kernel/bpf/helpers.c:bpf_bprintf_cleanup
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff8132ad7b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
```
```
In kernel/bpf/btf.c (ffffffff8133977b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_alloc_id
```
```
In kernel/bpf/devmap.c (ffffffff8134ebe9)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8135099f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In kernel/bpf/offload.c (ffffffff813513f3)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In kernel/static_call_inline.c (ffffffff813646dd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/static_call_inline.c:static_call_text_reserved
```
```
In kernel/events/core.c (ffffffff81373b55)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_cgroup_move
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_read
```
```
In kernel/events/ring_buffer.c (ffffffff8137bd41)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137dbfd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff813830c4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/user-return-notifier.c (ffffffff81384478)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:fire_user_return_notifiers
```
```
In kernel/jump_label.c (ffffffff81386329)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_update
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_add_module
```
```
In kernel/rseq.c (ffffffff813887a9)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_update_cpu_node_id
```
```
In kernel/watch_queue.c (ffffffff81388c23)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In mm/filemap.c (ffffffff8138ec33)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_set_wb_err
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/oom_kill.c (ffffffff813956ef)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:wake_oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page-writeback.c (ffffffff813994e9)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_wait_writeback_killable
  - mm/page-writeback.c:folio_wait_writeback
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (ffffffff813a2f53)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/swap.c:__folio_batch_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:lru_add_drain_cpu_zone
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:folio_deactivate
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff813b9377)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:pageout
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/shmem.c (ffffffff813bbd61)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In mm/util.c (ffffffff813c4a9c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/backing-dev.c (ffffffff813cbe9d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
```
```
In mm/percpu.c (ffffffff813cedf9)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff813d4d7e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_large_node
  - mm/slab_common.c:kmalloc_large
  - mm/slab_common.c:kmalloc_node_trace
  - mm/slab_common.c:kmalloc_trace
  - mm/slab_common.c:kfree
  - mm/slab_common.c:__kmalloc_node_track_caller
  - mm/slab_common.c:__kmalloc_node_track_caller
  - mm/slab_common.c:__kmalloc
  - mm/slab_common.c:__kmalloc
  - mm/slab_common.c:__kmalloc_node
  - mm/slab_common.c:__kmalloc_node
```
```
In mm/compaction.c (ffffffff813dcf94)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:compaction_defer_reset
  - mm/compaction.c:compaction_deferred
  - mm/compaction.c:defer_compaction
```
```
In mm/mmap_lock.c (ffffffff813e8df8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
```
```
In mm/memory.c (ffffffff813efe49)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__wp_page_copy_user
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff813f94ac)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/mlock.c:munlock_folio
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:mlock_drain_local
```
```
In mm/mmap.c (ffffffff813fe630)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_unmapped_area
```
```
In mm/rmap.c (ffffffff8140e098)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/vmalloc.c (ffffffff81410fc8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/page_alloc.c (ffffffff814219b4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/memory_hotplug.c (ffffffff81424c3d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In mm/swapfile.c (ffffffff8142f07e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff814368d6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In mm/mempolicy.c (ffffffff814482a8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/ksm.c (ffffffff81457c70)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:calc_checksum
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In mm/page_poison.c (ffffffff814588ed)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/slub.c (ffffffff81462081)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_alloc_bulk
  - mm/slub.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:__unfreeze_partials
```
```
In mm/kfence/core.c (ffffffff81464804)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
```
```
In mm/kfence/report.c (ffffffff81466927)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/kfence/report.c:kfence_report_error
```
```
In mm/migrate.c (ffffffff8146b539)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff814796a6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:mm_get_huge_zero_page
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff81480d4e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff8149015a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In mm/memory-failure.c (ffffffff814946c8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff8149b2f5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/zsmalloc.c (ffffffff8149e1b9)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In fs/open.c (ffffffff814a911b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff814b09b1)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_write
```
```
In fs/exec.c (ffffffff814b8ac7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
  - fs/exec.c:__set_task_comm
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/pipe.c (ffffffff814bc7f5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
```
```
In fs/dcache.c (ffffffff814d3815)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
  - fs/dcache.c:___d_drop
```
```
In fs/inode.c (ffffffff814da2b6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
  - fs/inode.c:touch_atime
  - fs/inode.c:get_next_ino
```
```
In fs/file.c (ffffffff814db6f2)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/file.c:fd_install
  - fs/file.c:fd_install
```
```
In fs/namespace.c (ffffffff814dfcfe)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
  - fs/namespace.c:mnt_want_write
  - fs/namespace.c:__mnt_want_write
```
```
In fs/fs-writeback.c (ffffffff814f6bb6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:write_inode
  - fs/fs-writeback.c:write_inode
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/splice.c (ffffffff814fd50f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
```
In fs/fs_struct.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In fs/remap_range.c (ffffffff81507625)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/buffer.c (ffffffff815088dc)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/buffer.c:free_buffer_head
  - fs/buffer.c:alloc_buffer_head
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/notify/inotify/inotify_user.c (ffffffff815172b8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In fs/aio.c (ffffffff8152855f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_complete_rw
```
```
In fs/dax.c (ffffffff81531b67)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_pmd_load_hole
  - fs/dax.c:dax_pmd_load_hole
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_one
```
```
In fs/locks.c (ffffffff815457f3)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
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
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_get_lock_context
```
```
In fs/mbcache.c (ffffffff8154c9cf)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/coredump.c (ffffffff8155104c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/iter.c (ffffffff81553ca5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/iomap/iter.c:iomap_iter
  - fs/iomap/iter.c:iomap_iter_done
  - fs/iomap/iter.c:iomap_iter_done
```
```
In fs/iomap/buffered-io.c (ffffffff815561a6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_release_folio
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_folio
```
```
In fs/iomap/direct-io.c (ffffffff815589a9)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/quota/quota.c (ffffffff8156096d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/quota/quota.c:quotactl_block
  - fs/quota/quota.c:quotactl_block
```
```
In fs/proc/base.c (ffffffff8156e836)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff81581b17)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/ext4/balloc.c (ffffffff8158ff6f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8159303a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (ffffffff8159a276)
Location: arch/x86/include/asm/preempt.h:93
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
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/extents_status.c (ffffffff815a139d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/file.c (ffffffff815a178b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/fsmap.c (ffffffff815a4150)
Location: arch/x86/include/asm/preempt.h:93
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
In fs/ext4/fsync.c (ffffffff815a47fc)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff815a757a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff815aa4df)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff815bc5cc)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_update_other_inode_time
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_release_folio
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
  - fs/ext4/inode.c:ext4_invalidate_folio
  - fs/ext4/inode.c:ext4_read_folio
  - fs/ext4/inode.c:ext4_alloc_da_blocks
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff815bd6df)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/ioctl.c:ext4_force_shutdown
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff815c7f63)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff815cee22)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff815d9722)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_unlink
```
```
In fs/ext4/super.c (ffffffff815f7eed)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_nfs_commit_metadata
  - fs/ext4/super.c:ext4_drop_inode
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/fast_commit.c (ffffffff8160f673)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_update_stats
  - fs/ext4/fast_commit.c:ext4_fc_track_range
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
```
```
In fs/jbd2/transaction.c (ffffffff81614d4e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2__journal_start
```
```
In fs/jbd2/commit.c (ffffffff81617317)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff8161a049)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81623b4f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_shrink_count
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff8162758c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81629a16)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff8162af95)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompress
```
```
In fs/ecryptfs/mmap.c (ffffffff816443fd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff81645517)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dax.c (ffffffff8166958d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In ipc/util.c (ffffffff81675051)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/selinux/avc.c (ffffffff816a4302)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_audit_post_callback
```
```
In security/tomoyo/domain.c (ffffffff816ea317)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/capability.c (ffffffff816fad3e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/policy_unpack.c (ffffffff8170a264)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff81714562)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - security/apparmor/lsm.c:aa_put_buffer
  - security/apparmor/lsm.c:aa_put_buffer
  - security/apparmor/lsm.c:aa_get_buffer
  - security/apparmor/lsm.c:aa_get_buffer
  - security/apparmor/lsm.c:aa_get_buffer
  - security/apparmor/lsm.c:aa_get_buffer
```
```
In block/bio.c (ffffffff8176a437)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_put_percpu_cache
  - block/bio.c:bio_put_percpu_cache
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
```
```
In block/blk-core.c (ffffffff81772633)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:bio_start_io_acct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct_nocheck
```
```
In block/blk-flush.c (ffffffff8177503a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff81776d72)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-merge.c (ffffffff8177ae8e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:__bio_split_to_limits
```
```
In block/blk-mq.c (ffffffff817838b1)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:blk_mq_insert_request
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_add_rq_to_plug
  - block/blk-mq.c:blk_add_rq_to_plug
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_complete_request_remote
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_account_io_done
  - block/blk-mq.c:blk_account_io_done
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
```
```
In block/blk-stat.c (ffffffff81788e80)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add
```
```
In block/genhd.c (ffffffff8178de7b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
```
In block/blk-cgroup.c (ffffffff817a2c51)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
  - block/blk-cgroup.c:blkcg_init_disk
  - block/blk-cgroup.c:blkcg_init_disk
```
```
In block/blk-iocost.c (ffffffff817b0b44)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_wake_fn
  - block/blk-iocost.c:iocg_incur_debt
  - block/blk-iocost.c:iocg_activate
```
```
In block/mq-deadline.c (ffffffff817b40f5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In block/blk-wbt.c (ffffffff817baca5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:rwb_trace_step
```
```
In io_uring/io_uring.c (ffffffff817cda78)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_register
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_file_get_normal
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:io_fill_cqe_aux
  - io_uring/io_uring.c:io_cqring_event_overflow
  - io_uring/io_uring.c:io_queue_iowq
  - io_uring/io_uring.c:__io_fill_cqe_req
```
```
In io_uring/timeout.c (ffffffff817da697)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - io_uring/timeout.c:io_disarm_next
```
```
In io_uring/poll.c (ffffffff817ded63)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - io_uring/poll.c:io_arm_poll_handler
  - io_uring/poll.c:__io_poll_execute
```
```
In io_uring/rw.c (ffffffff817e5b90)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_write
  - io_uring/rw.c:__io_fill_cqe_req
```
```
In lib/scatterlist.c (ffffffff8180dbb4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff81813fb1)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
```
```
In lib/rhashtable.c (ffffffff818198d0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In arch/x86/lib/msr-smp.c (ffffffff818e891d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
```
```
In arch/x86/lib/msr.c (ffffffff818e93f3)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In drivers/gpio/gpiolib.c (ffffffff81902f74)
Location: arch/x86/include/asm/preempt.h:93
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
```
```
In drivers/pwm/core.c (ffffffff819129d9)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_apply_state
  - drivers/pwm/core.c:pwm_device_request
```
```
In drivers/pci/pcie/aer.c (ffffffff8194012e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
```
In drivers/acpi/sleep.c (ffffffff8199eeff)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/prmt.c (ffffffff819c09f1)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
```
```
In drivers/clk/clk.c (ffffffff81a41931)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_phase_nolock
  - drivers/clk/clk.c:clk_core_set_phase_nolock
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
```
In drivers/xen/events/events_2l.c (ffffffff81a6bd67)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a7a8cb)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff81a8522e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/char/random.c (ffffffff81ae0765)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/char/virtio_console.c (ffffffff81ae1bd4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b0ad57)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/svm.c (ffffffff81b16d2e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/iommu/iommu.c (ffffffff81b1dcc3)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:report_iommu_fault
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:__iommu_group_release_device
```
```
In drivers/connector/cn_proc.c (ffffffff81b2c180)
Location: arch/x86/include/asm/preempt.h:93
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
In drivers/base/syscore.c (ffffffff81b3a0c0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/devres.c (ffffffff81b3fdf4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/devres.c:__devm_add_action
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_close_group
  - drivers/base/devres.c:devres_open_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
  - drivers/base/devres.c:devres_get
```
```
In drivers/base/power/qos.c (ffffffff81b4c8f2)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff81b4fbf0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/main.c (ffffffff81b555db)
Location: arch/x86/include/asm/preempt.h:93
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
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/base/power/wakeup.c (ffffffff81b56846)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/regmap/regmap.c (ffffffff81b6961b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:_regmap_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/base/regmap/regcache.c (ffffffff81b6f671)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_cache_bypass
  - drivers/base/regmap/regcache.c:regcache_cache_only
  - drivers/base/regmap/regcache.c:regcache_drop_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_read
```
```
In drivers/block/loop.c (ffffffff81b7c35f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff81b842f3)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/nvdimm/region_devs.c (ffffffff81ba8118)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_release_lane
  - drivers/nvdimm/region_devs.c:nd_region_release_lane
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81bbf9e9)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc5908)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff81bcf8aa)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd2815)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
  - drivers/scsi/scsi_lib.c:scsi_done_internal
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81becad0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/scsi/sg.c (ffffffff81bf3502)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81bfe7cf)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff81c11327)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_done
  - drivers/ata/libata-eh.c:ata_eh_about_to_do
  - drivers/ata/libata-eh.c:__ata_port_freeze
```
```
In drivers/ata/libata-sff.c (ffffffff81c19c57)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_post_internal_cmd
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:__ata_sff_port_intr
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libata-sff.c:ata_tf_to_host
  - drivers/ata/libata-sff.c:ata_tf_to_host
```
```
In drivers/ata/ata_piix.c (ffffffff81c20609)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_irq_check
```
```
In drivers/spi/spi.c (ffffffff81c2da5a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_split_transfer_maxsize
  - drivers/spi/spi.c:__spi_split_transfer_maxsize
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_take_timestamp_post
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81c3ec2b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (ffffffff81c473f5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/virtio_net.c (ffffffff81c4f941)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
```
In drivers/net/xen-netfront.c (ffffffff81c6d804)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81ce5941)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81ce9479)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81ced28d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_trb
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_ring_ep_doorbell
  - drivers/usb/host/xhci-ring.c:inc_enq
  - drivers/usb/host/xhci-ring.c:inc_deq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81cf724d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cff3e3)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
  - drivers/usb/host/xhci-dbgcap.c:dbc_free_request
  - drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/rtc/interface.c (ffffffff81d24dc8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_set_offset
  - drivers/rtc/interface.c:rtc_read_offset
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_alarm_disable
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_initialize_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2cf40)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d30c30)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff81d43e1b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/hwmon/hwmon.c:hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:hwmon_attr_show
```
```
In drivers/thermal/thermal_core.c (ffffffff81d47675)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (ffffffff81d4c316)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:__thermal_cdev_update
```
```
In drivers/thermal/gov_fair_share.c (ffffffff81d4ec64)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/thermal/gov_fair_share.c:fair_share_throttle
```
```
In drivers/thermal/gov_step_wise.c (ffffffff81d4f281)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/thermal/gov_step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81d50ae2)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:pid_controller
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81d518bd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81d51db7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_count
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81d53fcc)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81d5629a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff81d5a81a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_discard_bio
```
```
In drivers/md/md-bitmap.c (ffffffff81d71da2)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/md/dm.c (ffffffff81d77626)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_submit_bio_remap
```
```
In drivers/md/dm-stats.c (ffffffff81d85f5f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/md/dm-rq.c (ffffffff81d88599)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (ffffffff81d8a05a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d994eb)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d9d126)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d9f690)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81da2866)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_update
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81daa806)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff82142666)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
```
```
In drivers/cpuidle/driver.c (ffffffff81dac773)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In drivers/cpuidle/governors/haltpoll.c (ffffffff81db0456)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff81db26ee)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/firmware/efi/capsule.c (ffffffff81dcefe4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81dd27cf)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81ddf583)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff81dee93d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
```
In drivers/ras/ras.c (ffffffff81df867b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
```
```
In drivers/interconnect/core.c (ffffffff81dfdd0e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_set_bw
  - drivers/interconnect/core.c:icc_set_bw
```
```
In net/socket.c (ffffffff81e013e3)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/socket.c:call_trace_sock_recv_length
```
```
In net/core/sock.c (ffffffff81e09546)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_error_report
```
```
In net/core/skbuff.c (ffffffff81e1340c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_reason
```
```
In net/core/datagram.c (ffffffff81e1f89e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/gen_estimator.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81e24746)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81e3e11b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_qdisc_enqueue
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/dst.c (ffffffff81e45149)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff81e4c293)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/filter.c (ffffffff81e639fc)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_socket_ptr_cookie
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
```
```
In net/core/sock_diag.c (ffffffff81e75592)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
```
```
In net/core/xdp.c (ffffffff81e78a36)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/gro.c (ffffffff81e7c536)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
  - net/core/gro.c:napi_gro_receive
```
```
In net/core/page_pool.c (ffffffff81e827db)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
```
```
In net/core/netpoll.c (ffffffff81e850b6)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:poll_one_napi
```
```
In net/core/net-traces.c (ffffffff81e918a2)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
```
In net/core/skmsg.c (ffffffff81ea1a59)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
```
```
In net/sched/sch_generic.c (ffffffff81eacfdd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_api.c (ffffffff81eb1edf)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/cls_api.c (ffffffff81eb9acc)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff81ebdd84)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_update_hw_stats
```
```
In net/netlink/af_netlink.c (ffffffff81ec2a1b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81ed0541)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_prog_test_run_tracing
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ipv4/tcp_input.c (ffffffff81f1eea1)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_output.c (ffffffff81f22297)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_rtx_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2dce5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_cong.c (ffffffff81f34566)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_ca_state
```
```
In net/ipv4/udp.c (ffffffff81f43358)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/af_inet.c (ffffffff81f55b93)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_state_store
  - net/ipv4/af_inet.c:inet_sk_set_state
```
```
In net/ipv4/fib_trie.c (ffffffff81f67877)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a4c8)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6dbdf)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81f800fb)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f9261b)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81fa75dd)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_data_ready
```
```
In net/ipv6/route.c (ffffffff81fd169d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
```
```
In net/ipv6/udp.c (ffffffff81fe863c)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffea17)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
```
In net/ipv6/ioam6.c (ffffffff8200a3ee)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff8200e98f)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8201a741)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff8201eb80)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201f99d)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020fe4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
```
In net/devlink/leftover.c (ffffffff8202eb0e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_trap_report
```
```
In net/devlink/health.c (ffffffff82047dca)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_health_report
  - net/devlink/health.c:devlink_health_report
```
```
In net/mptcp/protocol.c (ffffffff820750ca)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
```
In net/mptcp/subflow.c (ffffffff8207be5a)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff8207e224)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/mptcp/options.c:ack_update_msk
```
```
In net/mctp/af_mctp.c (ffffffff8208d7c5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In net/mctp/route.c (ffffffff82090d72)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:__mctp_key_done_in
```
```
In net/handshake/netlink.c (ffffffff820928fa)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_nl_done_doit
  - net/handshake/netlink.c:handshake_nl_done_doit
  - net/handshake/netlink.c:handshake_nl_accept_doit
  - net/handshake/netlink.c:handshake_nl_accept_doit
```
```
In net/handshake/request.c (ffffffff820938b5)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_complete
  - net/handshake/request.c:handshake_req_submit
  - net/handshake/request.c:handshake_req_submit
  - net/handshake/request.c:handshake_req_submit
  - net/handshake/request.c:handshake_sk_destruct
```
```
In lib/bug.c (ffffffff8209edbf)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:report_bug
  - lib/bug.c:find_bug
```
```
In lib/buildid.c (ffffffff8209f083)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In lib/flex_proportions.c (0)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
```
```
In lib/maple_tree.c (ffffffff820ac5f7)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_find
  - lib/maple_tree.c:mtree_erase
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_load
  - lib/maple_tree.c:mas_store_prealloc
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_store
  - lib/maple_tree.c:mas_wr_modify
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_node_store
  - lib/maple_tree.c:mas_is_span_wr
```
```
In lib/nmi_backtrace.c (ffffffff820b74a4)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/radix-tree.c (ffffffff820b7a1e)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_preload
```
```
In arch/x86/lib/delay.c (ffffffff820cadac)
Location: arch/x86/include/asm/preempt.h:93
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
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
In init/main.c (ffffffff838b0ee3)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81007701)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/amd/ibs.c (ffffffff838b530d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
```
```
In arch/x86/events/intel/ds.c (ffffffff8101cd8c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/p4.c (ffffffff8102454d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/xen/time.c (ffffffff838bb5bd)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_init_time_ops
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_timerop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8103e633)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/enlighten_pv.c:xen_mc_batch
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81040562)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
  - arch/x86/xen/mmu_pv.c:xen_flush_lazy_mmu
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_start
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
  - arch/x86/xen/mmu_pv.c:xen_mc_batch
```
```
In arch/x86/xen/multicalls.c (ffffffff810440f5)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8104b79a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
```
```
In arch/x86/hyperv/mmu.c (ffffffff8104d722)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff8104dd9e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8105045f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/process_64.c (ffffffff81052932)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/signal.c (ffffffff81052cbe)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/irq.c (ffffffff810574b7)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
```
```
In arch/x86/kernel/ioport.c (ffffffff81058c2b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In arch/x86/kernel/nmi.c (ffffffff8105a54f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff8105c99c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
```
```
In arch/x86/kernel/tsc.c (ffffffff81065a21)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:cyc2ns_read_end
```
```
In arch/x86/kernel/process.c (ffffffff81068152)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:speculation_ctrl_update_current
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8106a03e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:fpregs_lock_and_load
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:kernel_fpu_end
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106bc13)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:check_xstate_in_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106c97e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8106f8c4)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
```
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8107af7a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8108072d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81084799)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81086619)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81089f2e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81095390)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81097db3)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l3_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l2_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109bf8e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f28e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
```
```
In arch/x86/kernel/smp.c (ffffffff810a2cdc)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a38df)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a7e6f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff838e1cd9)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810b1bb1)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
```
```
In arch/x86/kernel/ftrace.c (ffffffff810b4b1d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff810bae60)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810bb949)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/kernel/kvmclock.c (ffffffff838eb2fe)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/callthunks.c (ffffffff810c9746)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/callthunks.c:is_coretext
```
```
In arch/x86/mm/fault.c (ffffffff82223768)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff810d0de0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810d27a2)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810d3dca)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In arch/x86/mm/tlb.c (ffffffff810d56a4)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/kmmio.c (ffffffff810ddc07)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
  - arch/x86/mm/kmmio.c:kmmio_handler
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810def5a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:post
  - arch/x86/mm/mmio-mod.c:post
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810ebe61)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:arch_efi_call_virt_teardown
```
```
In kernel/fork.c (ffffffff810fdd3e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
```
```
In kernel/panic.c (ffffffff810fef4c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
```
```
In kernel/cpu.c (ffffffff81102631)
Location: arch/x86/include/asm/preempt.h:92
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
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpus_read_trylock
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
```
```
In kernel/exit.c (ffffffff81107281)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/softirq.c (ffffffff8110945e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/softirq.c:__raise_softirq_irqoff
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
```
```
In kernel/signal.c (ffffffff8111ad11)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal_locked
```
```
In kernel/workqueue.c (ffffffff81126bba)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_inactive_work
  - kernel/workqueue.c:wq_worker_running
```
```
In kernel/pid.c (ffffffff81130c81)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/kthread.c (ffffffff8113536b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
```
```
In kernel/notifier.c (ffffffff8113d6f0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/notifier.c:notifier_call_chain
  - kernel/notifier.c:notifier_chain_unregister
```
```
In kernel/smpboot.c (ffffffff81141b0a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
```
```
In kernel/sched/core.c (ffffffff8115a11f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/sched/core.c:call_trace_sched_update_nr_running
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:call_function_single_prep_ipi
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migrate_enable
  - kernel/sched/core.c:migrate_disable
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:raw_spin_rq_trylock
  - kernel/sched/core.c:raw_spin_rq_trylock
```
```
In kernel/sched/fair.c (ffffffff8116c4c3)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:update_curr_common
```
```
In kernel/sched/build_policy.c (ffffffff81179cbb)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:play_idle_precise
  - kernel/sched/build_policy.c:default_idle_call
  - kernel/sched/build_policy.c:default_idle_call
```
```
In kernel/sched/build_utility.c (ffffffff8118fc7b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_wait_end
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:running_clock
  - kernel/sched/build_utility.c:sched_clock_cpu
  - kernel/sched/build_utility.c:__sched_clock_work
```
```
In kernel/locking/mutex.c (ffffffff82236031)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff82237734)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_common
  - kernel/locking/semaphore.c:__down_common
```
```
In kernel/locking/rwsem.c (ffffffff8119c984)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (ffffffff82238b1a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
```
```
In kernel/locking/spinlock.c (ffffffff8223c8fa)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_irq
  - kernel/locking/spinlock.c:_raw_read_unlock_irq
  - kernel/locking/spinlock.c:_raw_write_unlock
  - kernel/locking/spinlock.c:_raw_read_unlock
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_spin_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_spin_unlock_irq
  - kernel/locking/spinlock.c:_raw_spin_unlock
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/qspinlock.c (ffffffff8223d4cd)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex_api.c (ffffffff8223a86b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
```
```
In kernel/locking/qrwlock.c (ffffffff8223da62)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/qos.c (ffffffff8119e2e6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_remove_request
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff811a0c72)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff811a1e2a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/power/hibernate.c (ffffffff811a30a5)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
```
```
In kernel/power/snapshot.c (ffffffff811a7b0c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/printk/printk.c (ffffffff8390145a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:printk_sprint
```
```
In kernel/irq/handle.c (ffffffff811b70b1)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff811bdd27)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
```
```
In kernel/irq/matrix.c (ffffffff811ca478)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_remove_reserved
  - kernel/irq/matrix.c:irq_matrix_reserve
  - kernel/irq/matrix.c:irq_matrix_assign
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_assign_system
  - kernel/irq/matrix.c:irq_matrix_offline
  - kernel/irq/matrix.c:irq_matrix_online
```
```
In kernel/rcu/tree.c (ffffffff811dd728)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/core.c (ffffffff811e45cd)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_init_object
```
```
In kernel/livepatch/patch.c (ffffffff811e5481)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/livepatch/transition.c (ffffffff811e6c40)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/dma/swiotlb.c (ffffffff811edb6f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In kernel/entry/common.c (ffffffff811eed70)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_to_user_mode_prepare
  - kernel/entry/common.c:syscall_exit_work
  - kernel/entry/common.c:syscall_trace_enter
```
```
In kernel/module/main.c (ffffffff811f6fb4)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/module/main.c:print_modules
  - kernel/module/main.c:is_module_text_address
  - kernel/module/main.c:is_module_address
  - kernel/module/main.c:search_module_extables
  - kernel/module/main.c:load_module
  - kernel/module/main.c:__symbol_get
  - kernel/module/main.c:__symbol_get
  - kernel/module/main.c:free_module
  - kernel/module/main.c:module_put
  - kernel/module/main.c:try_module_get
  - kernel/module/main.c:symbol_put_addr
  - kernel/module/main.c:__symbol_put
  - kernel/module/main.c:__is_module_percpu_address
  - kernel/module/main.c:__is_module_percpu_address
```
```
In kernel/module/kmod.c (ffffffff811f75e2)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/module/kmod.c:__request_module
```
```
In kernel/module/kallsyms.c (ffffffff811f9343)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:module_kallsyms_on_each_symbol
  - kernel/module/kallsyms.c:find_kallsyms_symbol_value
  - kernel/module/kallsyms.c:module_kallsyms_lookup_name
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:lookup_module_symbol_name
  - kernel/module/kallsyms.c:lookup_module_symbol_name
  - kernel/module/kallsyms.c:module_address_lookup
```
```
In kernel/module/version.c (ffffffff811fa7cd)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/module/version.c:check_modstruct_version
  - kernel/module/version.c:check_modstruct_version
```
```
In kernel/profile.c (ffffffff811fc201)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/profile.c:profile_discard_flip_buffers
  - kernel/profile.c:profile_flip_buffers
```
```
In kernel/time/timer.c (ffffffff81202f0c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:timer_clear_idle
  - kernel/time/timer.c:get_next_timer_interrupt
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:detach_if_pending
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/time/hrtimer.c (ffffffff81205621)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_cpu_dying
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_init
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/time/timekeeping.c (0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In kernel/time/clocksource.c (ffffffff8120b33a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In kernel/time/alarmtimer.c (ffffffff8120df7b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (ffffffff812131dd)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/time/itimer.c (ffffffff81216c65)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-common.c (ffffffff812194e2)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff8121c10a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_dep_set_cpu
  - kernel/time/tick-sched.c:tick_nohz_dep_set
  - kernel/time/tick-sched.c:check_tick_dependency
```
```
In kernel/smp.c (ffffffff8122531e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:generic_exec_single
  - kernel/smp.c:generic_exec_single
  - kernel/smp.c:__smp_call_single_queue
  - kernel/smp.c:__smp_call_single_queue
```
```
In kernel/acct.c (ffffffff81229c99)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81236aca)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_put_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/rstat.c (ffffffff8123f2d9)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81242005)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff81242cf8)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In kernel/stop_machine.c (ffffffff8125333a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_work
```
```
In kernel/kprobes.c (ffffffff812669f7)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/kprobes.c:kprobe_busy_end
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff812751d6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/hung_task.c (ffffffff81277dea)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_task
```
```
In kernel/relay.c (ffffffff8127da85)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/relay.c:relay_late_setup_files
```
```
In kernel/trace/trace_clock.c (ffffffff812822c0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_local
```
```
In kernel/trace/ftrace.c (ffffffff81282a64)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fpid_stop
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:function_trace_probe_call
  - kernel/trace/ftrace.c:ftrace_ops_trampoline
  - kernel/trace/ftrace.c:ftrace_ops_trampoline
```
```
In kernel/trace/ring_buffer.c (ffffffff81292e62)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_nest_end
  - kernel/trace/ring_buffer.c:ring_buffer_time_stamp
```
```
In kernel/trace/trace.c (ffffffff8129e3f4)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_stop
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:__trace_array_puts
  - kernel/trace/trace.c:call_filter_check_discard
  - kernel/trace/trace.c:ftrace_exports
```
```
In kernel/trace/trace_functions.c (ffffffff812ad009)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812ae64e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b2f84)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:trace_sched_switch_callback
  - kernel/trace/trace_osnoise.c:trace_softirq_exit_callback
  - kernel/trace/trace_osnoise.c:osnoise_trace_irq_exit
  - kernel/trace/trace_osnoise.c:trace_osnoise_callback
```
```
In kernel/trace/trace_stack.c (ffffffff812b5ac1)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff812b6842)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
```
```
In kernel/trace/trace_functions_graph.c (ffffffff812b7594)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff812bb9a3)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
```
In kernel/trace/trace_events.c (ffffffff812be454)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:p_stop
```
```
In kernel/trace/trace_event_perf.c (ffffffff812c561f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/trace_events_inject.c (ffffffff812ceeab)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:trace_inject_entry
```
```
In kernel/trace/trace_events_user.c (ffffffff812e28a7)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:update_enable_bit_for
  - kernel/trace/trace_events_user.c:user_event_ftrace
```
```
In kernel/trace/bpf_trace.c (ffffffff812e777c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:get_modules_for_addrs
  - kernel/trace/bpf_trace.c:get_modules_for_addrs
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
  - kernel/trace/bpf_trace.c:bpf_trace_vprintk
  - kernel/trace/bpf_trace.c:bpf_trace_printk
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ec0df)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f98a8)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/trace/fprobe.c (ffffffff812fbe89)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In kernel/trace/rethook.c (ffffffff812fd195)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_trampoline_handler
  - kernel/trace/rethook.c:rethook_flush_task
```
```
In kernel/trace/rv/monitors/wwnr/wwnr.c (ffffffff81301cf2)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr
```
```
In kernel/irq_work.c (ffffffff81303064)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/core.c (ffffffff81309024)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
```
```
In kernel/bpf/syscall.c (ffffffff81312690)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/helpers.c (ffffffff81342679)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - kernel/bpf/helpers.c:bpf_bprintf_cleanup
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff8134f167)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/hashtab.c:htab_lock_bucket
```
```
In kernel/bpf/btf.c (ffffffff8135f8ab)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_alloc_id
```
```
In kernel/bpf/devmap.c (ffffffff813760e6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff81377dcf)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In kernel/bpf/offload.c (ffffffff81378853)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In kernel/static_call_inline.c (ffffffff8138d60d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/static_call_inline.c:static_call_text_reserved
```
```
In kernel/events/core.c (ffffffff8139c9f5)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_cgroup_move
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_read
```
```
In kernel/events/ring_buffer.c (ffffffff813a4f81)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a6e5d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff813ac494)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/user-return-notifier.c (ffffffff813ad888)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:fire_user_return_notifiers
```
```
In kernel/jump_label.c (ffffffff813af7e9)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_update
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_add_module
```
```
In kernel/context_tracking.c (ffffffff822245d0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/context_tracking.c:__ct_user_exit
  - kernel/context_tracking.c:__ct_user_enter
```
```
In kernel/iomem.c (ffffffff813b0de3)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In kernel/rseq.c (ffffffff813b2209)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_update_cpu_node_id
```
```
In kernel/watch_queue.c (ffffffff813b2683)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In mm/filemap.c (ffffffff813b8023)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_set_wb_err
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/oom_kill.c (ffffffff813bf4af)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:wake_oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page-writeback.c (ffffffff813c32e8)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_wait_writeback_killable
  - mm/page-writeback.c:folio_wait_writeback
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (ffffffff813ccbd3)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/swap.c:__folio_batch_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:lru_add_drain_cpu_zone
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:folio_deactivate
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff813e23a2)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:pageout
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/shrinker.c (ffffffff813e4132)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/shrinker.c:do_shrink_slab
  - mm/shrinker.c:do_shrink_slab
```
```
In mm/shmem.c (ffffffff813e6811)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In mm/backing-dev.c (ffffffff813f680d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
```
```
In mm/mm_init.c (ffffffff83912da4)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:reserve_bootmem_region
```
```
In mm/percpu.c (ffffffff813f9959)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/compaction.c (ffffffff81406ef4)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:compaction_defer_reset
  - mm/compaction.c:compaction_deferred
  - mm/compaction.c:defer_compaction
```
```
In mm/mmap_lock.c (ffffffff81413a68)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
```
```
In mm/memory.c (ffffffff8141b3e2)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/memory.c:set_pte_range
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff81425049)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/mlock.c:munlock_folio
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:mlock_drain_local
```
```
In mm/mmap.c (ffffffff8142aa63)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_unmapped_area
```
```
In mm/rmap.c (ffffffff8143a7e8)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8143eea6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff8144e7e4)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/memory_hotplug.c (ffffffff8222a0c5)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In mm/slub.c (ffffffff8145e4fa)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_alloc_bulk
  - mm/slub.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmalloc_node_trace
  - mm/slub.c:kmalloc_node_trace
  - mm/slub.c:kmalloc_trace
  - mm/slub.c:kmalloc_trace
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:kmalloc_large
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In mm/mempolicy.c (ffffffff81485af8)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_mpol
```
```
In mm/ksm.c (ffffffff81492740)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:scan_time_advisor
```
```
In mm/kfence/core.c (ffffffff8149392c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In mm/kfence/report.c (ffffffff81495b38)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/kfence/report.c:kfence_report_error
```
```
In mm/migrate.c (ffffffff8149a4e0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff814a8c3b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:mm_get_huge_zero_page
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff814aed28)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff814bf96a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In mm/memory-failure.c (ffffffff814c927a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure_queue
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff814ca9ce)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/zsmalloc.c (ffffffff814cd2db)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:migrate_zspage
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In mm/bootmem_info.c (ffffffff839206d2)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/open.c (ffffffff814da16d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff814e2173)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
  - fs/read_write.c:vfs_iter_write
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_write
```
```
In fs/exec.c (ffffffff814eafd7)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
  - fs/exec.c:__set_task_comm
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/pipe.c (ffffffff814eed37)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
```
```
In fs/dcache.c (ffffffff81505f95)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:___d_drop
  - fs/dcache.c:___d_drop
```
```
In fs/inode.c (ffffffff8150c8a1)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
  - fs/inode.c:touch_atime
  - fs/inode.c:get_next_ino
```
```
In fs/file.c (ffffffff8150de08)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/file.c:fd_install
  - fs/file.c:fd_install
```
```
In fs/namespace.c (ffffffff81512bfe)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
  - fs/namespace.c:mnt_want_write
  - fs/namespace.c:mnt_get_write_access
```
```
In fs/fs-writeback.c (ffffffff8152b2f6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:write_inode
  - fs/fs-writeback.c:write_inode
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/splice.c (ffffffff81532167)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
  - fs/splice.c:direct_splice_actor
```
```
In fs/fs_struct.c (0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In fs/remap_range.c (ffffffff8153c852)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/buffer.c (ffffffff8153d78c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/buffer.c:free_buffer_head
  - fs/buffer.c:alloc_buffer_head
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154b6a8)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In fs/aio.c (ffffffff8155d5df)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_complete_rw
```
```
In fs/dax.c (ffffffff81566a4b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_pmd_load_hole
  - fs/dax.c:dax_pmd_load_hole
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_one
```
```
In fs/locks.c (ffffffff8157ad53)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
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
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_get_lock_context
```
```
In fs/backing-file.c (ffffffff81581c90)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/backing-file.c:backing_aio_rw_complete
```
```
In fs/mbcache.c (ffffffff815827ff)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/coredump.c (ffffffff81586edd)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/iter.c (ffffffff81589c65)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/iomap/iter.c:iomap_iter
  - fs/iomap/iter.c:iomap_iter_done
  - fs/iomap/iter.c:iomap_iter_done
```
```
In fs/iomap/buffered-io.c (ffffffff8158c681)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_release_folio
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_folio
```
```
In fs/iomap/direct-io.c (ffffffff8158f0d6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/quota/quota.c (ffffffff8159705d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/quota/quota.c:quotactl_block
  - fs/quota/quota.c:quotactl_block
```
```
In fs/proc/base.c (ffffffff815a71f6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In fs/proc/kcore.c (ffffffff815b5a01)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In fs/kernfs/dir.c (ffffffff815ba5b7)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/ext4/balloc.c (ffffffff815c8afe)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff815cbd2a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (ffffffff815d30c6)
Location: arch/x86/include/asm/preempt.h:92
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
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/extents_status.c (ffffffff815da164)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/file.c (ffffffff815da53b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/fsmap.c (ffffffff815dcf90)
Location: arch/x86/include/asm/preempt.h:92
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
In fs/ext4/fsync.c (ffffffff815dd63a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff815e03b0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff815e327f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff815f53ac)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_update_other_inode_time
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_release_folio
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
  - fs/ext4/inode.c:ext4_invalidate_folio
  - fs/ext4/inode.c:ext4_read_folio
  - fs/ext4/inode.c:ext4_alloc_da_blocks
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff815f649f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/ioctl.c:ext4_force_shutdown
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff815ffbb3)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff816076b2)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff81611dd2)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_unlink
```
```
In fs/ext4/super.c (ffffffff81630a9d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_nfs_commit_metadata
  - fs/ext4/super.c:ext4_drop_inode
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/fast_commit.c (ffffffff81648433)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_update_stats
  - fs/ext4/fast_commit.c:ext4_fc_track_range
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
```
```
In fs/jbd2/transaction.c (ffffffff8164db3e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2__journal_start
```
```
In fs/jbd2/commit.c (ffffffff81650232)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff81652fa6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8165cbef)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_shrink_count
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
```
```
In fs/squashfs/file.c (ffffffff816606ec)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81662c66)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff81664365)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompress
```
```
In fs/fuse/dax.c (ffffffff816a388d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In ipc/util.c (ffffffff816b1411)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/selinux/avc.c (ffffffff816e0d62)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_audit_post_callback
```
```
In security/tomoyo/domain.c (ffffffff81727027)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/capability.c (ffffffff8173794e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/policy_unpack.c (ffffffff81747d64)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff81752fb7)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - security/apparmor/lsm.c:aa_put_buffer
  - security/apparmor/lsm.c:aa_put_buffer
  - security/apparmor/lsm.c:aa_put_buffer
  - security/apparmor/lsm.c:aa_get_buffer
  - security/apparmor/lsm.c:aa_get_buffer
  - security/apparmor/lsm.c:aa_get_buffer
  - security/apparmor/lsm.c:aa_get_buffer
```
```
In block/bio.c (ffffffff817ac89a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_put_percpu_cache
  - block/bio.c:bio_put_percpu_cache
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
```
```
In block/blk-core.c (ffffffff817b49d3)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:bio_start_io_acct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct_nocheck
```
```
In block/blk-flush.c (ffffffff817b735c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffff817b8f9f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-merge.c (ffffffff817bd276)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:__bio_split_to_limits
```
```
In block/blk-mq.c (ffffffff817c5c21)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:blk_mq_insert_request
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_add_rq_to_plug
  - block/blk-mq.c:blk_add_rq_to_plug
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_complete_request_remote
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_account_io_done
  - block/blk-mq.c:blk_account_io_done
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
```
```
In block/blk-stat.c (ffffffff817cb5a6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add
```
```
In block/genhd.c (ffffffff817d06db)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
```
In block/blk-cgroup.c (ffffffff817e6791)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
  - block/blk-cgroup.c:blkcg_init_disk
  - block/blk-cgroup.c:blkcg_init_disk
```
```
In block/blk-iocost.c (ffffffff817f4954)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_wake_fn
  - block/blk-iocost.c:iocg_incur_debt
  - block/blk-iocost.c:iocg_activate
```
```
In block/mq-deadline.c (ffffffff817f808b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In block/blk-wbt.c (ffffffff817ff412)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:rwb_trace_step
```
```
In io_uring/io_uring.c (ffffffff81816ba8)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_file_get_normal
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:io_fill_cqe_aux
  - io_uring/io_uring.c:io_cqring_event_overflow
  - io_uring/io_uring.c:io_queue_iowq
```
```
In io_uring/timeout.c (ffffffff8181e987)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - io_uring/timeout.c:io_disarm_next
```
```
In io_uring/poll.c (ffffffff8182313a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - io_uring/poll.c:io_arm_poll_handler
  - io_uring/poll.c:__io_poll_execute
```
```
In io_uring/rw.c (ffffffff81829e52)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_write
```
```
In io_uring/register.c (ffffffff8182bf94)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - io_uring/register.c:__do_sys_io_uring_register
```
```
In lib/scatterlist.c (ffffffff81853864)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff818583bf)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
```
```
In lib/rhashtable.c (ffffffff8185ec20)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/stackdepot.c (ffffffff819289cd)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_save_flags
  - lib/stackdepot.c:stack_depot_save_flags
```
```
In arch/x86/lib/msr-smp.c (ffffffff8192fdbd)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
```
```
In arch/x86/lib/msr.c (ffffffff81930893)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In drivers/gpio/gpiolib.c (ffffffff8194ab34)
Location: arch/x86/include/asm/preempt.h:92
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
```
```
In drivers/pwm/core.c (ffffffff8195a702)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/pwm/core.c:__pwm_apply
  - drivers/pwm/core.c:pwm_device_request
```
```
In drivers/pci/pcie/aer.c (ffffffff8198897e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
```
In drivers/acpi/sleep.c (ffffffff819e759f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7b37c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81a8d341)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_phase_nolock
  - drivers/clk/clk.c:clk_core_set_phase_nolock
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
```
In drivers/xen/events/events_2l.c (ffffffff81abde07)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acca2f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/regulator/core.c (ffffffff81ad7a0e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/tty/sysrq.c (0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In drivers/char/random.c (ffffffff81b33b65)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/char/virtio_console.c (ffffffff81b34fc4)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5eda7)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/svm.c (ffffffff81b6c40e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/iommu/iommu.c (ffffffff81b74953)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:report_iommu_fault
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/iommu/iommu.c:iommu_group_alloc_device
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7b18f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
```
In drivers/connector/cn_proc.c (ffffffff81b8390b)
Location: arch/x86/include/asm/preempt.h:92
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
In drivers/base/syscore.c (ffffffff81b91b80)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/devres.c (ffffffff81b97c74)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/devres.c:__devm_add_action
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_close_group
  - drivers/base/devres.c:devres_open_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
  - drivers/base/devres.c:devres_get
```
```
In drivers/base/power/qos.c (ffffffff81ba4dc2)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff81ba8170)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/main.c (ffffffff81badb9b)
Location: arch/x86/include/asm/preempt.h:92
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
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/base/power/wakeup.c (ffffffff81baee36)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/regmap/regmap.c (ffffffff81bbd2db)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:_regmap_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/base/regmap/regcache.c (ffffffff81bc3241)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_cache_bypass
  - drivers/base/regmap/regcache.c:regcache_cache_only
  - drivers/base/regmap/regcache.c:regcache_drop_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_read
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd8223)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81c14169)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c1a2e8)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff81c2450a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c27485)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
  - drivers/scsi/scsi_lib.c:scsi_done_internal
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c421a4)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/scsi/sg.c (ffffffff81c48e21)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81c544c0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff81c66500)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_done
  - drivers/ata/libata-eh.c:ata_eh_about_to_do
  - drivers/ata/libata-eh.c:ata_eh_thaw_port
  - drivers/ata/libata-eh.c:__ata_port_freeze
```
```
In drivers/ata/libata-sff.c (ffffffff81c6ed47)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_post_internal_cmd
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:__ata_sff_port_intr
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libata-sff.c:ata_tf_to_host
  - drivers/ata/libata-sff.c:ata_tf_to_host
```
```
In drivers/ata/ata_piix.c (ffffffff81c757c9)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_irq_check
```
```
In drivers/gpu/drm/drm_cache.c (ffffffff81c812c6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_cache.c:drm_clflush_page
```
```
In drivers/gpu/drm/drm_drv.c (ffffffff81c8b44e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_drv.c:drm_minor_alloc
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9d4dd)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_handle_create_tail
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb11b6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_get_handle
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb69e7)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_handle_vblank_events
  - drivers/gpu/drm/drm_vblank.c:drm_queue_vblank_event
  - drivers/gpu/drm/drm_vblank.c:send_vblank_event
```
```
In drivers/spi/spi.c (ffffffff81ce0459)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_split_transfer_maxsize
  - drivers/spi/spi.c:__spi_split_transfer_maxsize
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_take_timestamp_post
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_wait
  - drivers/spi/spi.c:spi_transfer_wait
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81cf370b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (ffffffff81cfccf5)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/virtio_net.c (ffffffff81d0561f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
```
In drivers/net/xen-netfront.c (ffffffff81d2214a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81d9a9bf)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81d9ec69)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81da277d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_trb
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_ring_ep_doorbell
  - drivers/usb/host/xhci-ring.c:inc_enq
  - drivers/usb/host/xhci-ring.c:inc_deq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81dacb7a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db44e3)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
  - drivers/usb/host/xhci-dbgcap.c:dbc_free_request
  - drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/rtc/interface.c (ffffffff81ddab28)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_set_offset
  - drivers/rtc/interface.c:rtc_read_offset
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_alarm_disable
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_initialize_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de2e21)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de6bec)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff81dfa7eb)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/hwmon/hwmon.c:hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:hwmon_attr_show
```
```
In drivers/thermal/thermal_core.c (ffffffff81dfdc74)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (ffffffff81e03095)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:__thermal_cdev_update
```
```
In drivers/thermal/gov_fair_share.c (ffffffff81e05708)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/thermal/gov_fair_share.c:fair_share_throttle
```
```
In drivers/thermal/gov_step_wise.c (ffffffff81e05ca3)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/thermal/gov_step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81e0734d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:pid_controller
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81e0863d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81e08b27)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_count
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81e0ae9c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0d1aa)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff81e11c4a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_discard_bio
```
```
In drivers/md/md-bitmap.c (ffffffff81e28e75)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/md/dm.c (ffffffff81e2e856)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_submit_bio_remap
```
```
In drivers/md/dm-stats.c (ffffffff81e3d69f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/md/dm-rq.c (ffffffff81e3fca9)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (ffffffff81e417aa)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e5116b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81e54e45)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81e574a0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81e5a975)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_update
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81e6294a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff82224d56)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
```
```
In drivers/cpuidle/driver.c (ffffffff81e64813)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In drivers/cpuidle/governors/haltpoll.c (ffffffff81e687e6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff81e6aa7e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/firmware/efi/capsule.c (ffffffff81e87d14)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81e954b3)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea4eb9)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
```
In drivers/ras/ras.c (ffffffff81eaed8b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
```
```
In drivers/ras/cec.c (ffffffff81eaf3c4)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
```
In drivers/interconnect/core.c (ffffffff81eb476e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_set_bw
  - drivers/interconnect/core.c:icc_set_bw
```
```
In net/socket.c (ffffffff81ebdd93)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/socket.c:call_trace_sock_recv_length
```
```
In net/core/sock.c (ffffffff81ec5f36)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_error_report
```
```
In net/core/skbuff.c (ffffffff81ed05cc)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_reason
```
```
In net/core/datagram.c (ffffffff81edcf4e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/gen_estimator.c (0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81ee2396)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81efecee)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_qdisc_enqueue
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/dst.c (ffffffff81f03dc9)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff81f0afa0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/filter.c (ffffffff81f22bdc)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_socket_ptr_cookie
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
```
```
In net/core/sock_diag.c (ffffffff81f34e42)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
```
```
In net/core/xdp.c (ffffffff81f38906)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/gro.c (ffffffff81f3c886)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
  - net/core/gro.c:napi_gro_receive
```
```
In net/core/page_pool.c (ffffffff81f43a72)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_return_page
  - net/core/page_pool.c:page_pool_inflight
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
```
```
In net/core/netpoll.c (ffffffff81f470a6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:poll_one_napi
```
```
In net/core/net-traces.c (ffffffff81f53c62)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
```
In net/core/skmsg.c (ffffffff81f64269)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
```
```
In net/sched/sch_generic.c (ffffffff81f6fa71)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_api.c (ffffffff81f7498e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/cls_api.c (ffffffff81f7ccd6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff81f80d84)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_update_hw_stats
```
```
In net/netlink/af_netlink.c (ffffffff81f85d6b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81f93ea1)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_prog_test_run_tracing
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ipv4/tcp_input.c (ffffffff81fe353e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_output.c (ffffffff81fe5f57)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_rtx_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7578)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_cong.c (ffffffff81ffa6e6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_ca_state
```
```
In net/ipv4/udp.c (ffffffff820092c3)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/af_inet.c (ffffffff8201c073)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_state_store
  - net/ipv4/af_inet.c:inet_sk_set_state
```
```
In net/ipv4/fib_trie.c (ffffffff8202de59)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff82030b78)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8203436c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff8204677b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8206038b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff8207488d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_data_ready
```
```
In net/ipv6/route.c (ffffffff8209ed5d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
```
```
In net/ipv6/udp.c (ffffffff820b7192)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cd726)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
```
In net/ipv6/ioam6.c (ffffffff820d938f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff820dd91f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e96fb)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff820edcb0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eeacd)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820f0111)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
```
In net/devlink/health.c (ffffffff82113e21)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_health_report
  - net/devlink/health.c:devlink_health_report
```
```
In net/devlink/trap.c (ffffffff8211493e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_trap_report
```
```
In net/mptcp/protocol.c (ffffffff821499d8)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
```
In net/mptcp/subflow.c (ffffffff8215126c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff82153714)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/mptcp/options.c:ack_update_msk
```
```
In net/mctp/af_mctp.c (ffffffff82163c85)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In net/mctp/route.c (ffffffff821672b2)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:__mctp_key_done_in
```
```
In net/handshake/alert.c (ffffffff821688bb)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/handshake/alert.c:tls_alert_recv
  - net/handshake/alert.c:tls_alert_send
```
```
In net/handshake/netlink.c (ffffffff821691f2)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_nl_done_doit
  - net/handshake/netlink.c:handshake_nl_done_doit
  - net/handshake/netlink.c:handshake_nl_accept_doit
  - net/handshake/netlink.c:handshake_nl_accept_doit
```
```
In net/handshake/request.c (ffffffff8216a165)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_complete
  - net/handshake/request.c:handshake_req_submit
  - net/handshake/request.c:handshake_req_submit
  - net/handshake/request.c:handshake_req_submit
  - net/handshake/request.c:handshake_sk_destruct
```
```
In lib/bug.c (ffffffff82176dbf)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:report_bug
  - lib/bug.c:find_bug
```
```
In lib/buildid.c (ffffffff82177083)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In lib/flex_proportions.c (0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In lib/maple_tree.c (ffffffff8218df22)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_find
  - lib/maple_tree.c:mtree_erase
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_load
  - lib/maple_tree.c:mas_store_prealloc
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_store
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_append
  - lib/maple_tree.c:mas_wr_slot_store
  - lib/maple_tree.c:mas_wr_walk
```
```
In lib/nmi_backtrace.c (ffffffff82191654)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/radix-tree.c (ffffffff8219232e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_preload
```
```
In arch/x86/lib/delay.c (ffffffff821a55dc)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81002965)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/entry/common.c (ffffffff8100436d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810054af)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/amd/ibs.c (ffffffff828a13b6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fa7c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/p4.c (ffffffff81013e51)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/xen/time.c (ffffffff8101e377)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_read_wallclock
  - arch/x86/xen/time.c:xen_clocksource_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff810230c8)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102457e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_start
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
```
```
In arch/x86/xen/irq.c (ffffffff810293ec)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_irq_enable
  - arch/x86/xen/irq.c:xen_restore_fl
```
```
In arch/x86/xen/multicalls.c (ffffffff81029a62)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102f5f8)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102ff11)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff810303b4)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/process_64.c (ffffffff81031178)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/signal.c (ffffffff81031e89)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/traps.c (ffffffff81033604)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_bounds
```
```
In arch/x86/kernel/irq.c (ffffffff81c0203d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
```
```
In arch/x86/kernel/ioport.c (ffffffff81036324)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/nmi.c (ffffffff81037162)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c02141)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103c8e8)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
```
```
In arch/x86/kernel/tsc.c (ffffffff8103d691)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In arch/x86/kernel/process.c (ffffffff8103f0e8)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:speculation_ctrl_update_current
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
  - arch/x86/kernel/process.c:exit_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103f7a1)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_end
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81040f5e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81041943)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/kernel/tls.c (ffffffff81044487)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e7e6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c0224c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c0235c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c0246c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:therm_throt_device_show_package_power_limit_count
  - arch/x86/kernel/cpu/mce/therm_throt.c:therm_throt_device_show_package_throttle_count
  - arch/x86/kernel/cpu/mce/therm_throt.c:therm_throt_device_show_core_power_limit_count
  - arch/x86/kernel/cpu/mce/therm_throt.c:therm_throt_device_show_core_throttle_count
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81056ba2)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105cc4b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105f869)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff810604d2)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81062147)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l3_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l2_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/smp.c (ffffffff81c028e1)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b72bb)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02d14)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b9f6c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106e470)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81073b38)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81074bf8)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81079348)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/paravirt.c (ffffffff81079e7a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/mm/fault.c (ffffffff81082193)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_page_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8108687c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
```
```
In arch/x86/mm/tlb.c (ffffffff8108a380)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/kmmio.c (ffffffff8108c9d7)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:kmmio_handler
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108d74b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In arch/x86/mm/mpx.c (ffffffff8108ef6b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_fault_info
```
```
In arch/x86/mm/pkeys.c (ffffffff8108fbb2)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In arch/x86/platform/efi/quirks.c (ffffffff8109307d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810939d6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81096c79)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:tunables_write
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff8109946d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
```
```
In kernel/fork.c (ffffffff810a1a42)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810a4f3c)
Location: arch/x86/include/asm/preempt.h:92
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
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpus_read_trylock
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
```
```
In kernel/exit.c (ffffffff810a7334)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/softirq.c (ffffffff810a984e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
```
```
In kernel/signal.c (ffffffff810b5650)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffff810c1afc)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/pid.c (ffffffff810c7d41)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/kthread.c (ffffffff810cadb6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810d105f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
```
```
In kernel/kmod.c (ffffffff810d1f86)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810df169)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/clock.c (ffffffff810e0ff0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/sched/clock.c:__sched_clock_work
```
```
In kernel/sched/idle.c (ffffffff810e209b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/sched/fair.c (ffffffff810ea1e3)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/deadline.c (ffffffff810f6632)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
```
```
In kernel/sched/pelt.c (ffffffff810fba98)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81101c10)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
```
In kernel/sched/membarrier.c (ffffffff81102ac5)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/locking/mutex.c (ffffffff81ae8e9e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff8110572a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/locking/spinlock.c (ffffffff81aec6b9)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_read_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_write_unlock_irq
  - kernel/locking/spinlock.c:_raw_read_unlock_irq
  - kernel/locking/spinlock.c:_raw_write_unlock
  - kernel/locking/spinlock.c:_raw_read_unlock
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_spin_unlock_irqrestore
  - kernel/locking/spinlock.c:_raw_spin_unlock_irq
  - kernel/locking/spinlock.c:_raw_spin_unlock
  - kernel/locking/spinlock.c:_raw_spin_trylock
```
```
In kernel/locking/rtmutex.c (ffffffff81aeaca4)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
```
```
In kernel/power/qos.c (ffffffff81108967)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff8110a0a6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff8110afa8)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff8110bdf1)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/power/snapshot.c (ffffffff8110dc36)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/printk/printk.c (ffffffff8111682c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/printk/printk.c:defer_console_output
  - kernel/printk/printk.c:wake_up_klogd
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/irq/handle.c (ffffffff81118150)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/chip.c (ffffffff8111d5b0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
```
```
In kernel/irq/matrix.c (ffffffff8112503b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_remove_reserved
  - kernel/irq/matrix.c:irq_matrix_reserve
  - kernel/irq/matrix.c:irq_matrix_assign
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_assign_system
  - kernel/irq/matrix.c:irq_matrix_offline
  - kernel/irq/matrix.c:irq_matrix_online
```
```
In kernel/rcu/update.c (ffffffff81125a3c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/rcu/update.c:exit_tasks_rcu_finish
  - kernel/rcu/update.c:exit_tasks_rcu_start
```
```
In kernel/rcu/tree.c (ffffffff8112af44)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/patch.c (ffffffff8112fa86)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/livepatch/transition.c (ffffffff811309a0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/dma/swiotlb.c (ffffffff8113317f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In kernel/profile.c (ffffffff81133f9e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
```
```
In kernel/time/timer.c (ffffffff81139eff)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:detach_if_pending
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/time/hrtimer.c (ffffffff8113bba0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_init
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
```
In kernel/time/alarmtimer.c (ffffffff81142aab)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114645f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In kernel/time/itimer.c (ffffffff81148651)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-common.c (ffffffff8114a2c2)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff8114c1a5)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In kernel/smp.c (ffffffff81151c38)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:on_each_cpu
  - kernel/smp.c:smp_call_function
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/module.c (ffffffff8115a44a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/module.c:print_modules
  - kernel/module.c:is_module_text_address
  - kernel/module.c:is_module_address
  - kernel/module.c:search_module_extables
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:module_address_lookup
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
  - kernel/module.c:free_module
  - kernel/module.c:try_module_get
  - kernel/module.c:try_module_get
  - kernel/module.c:__is_module_percpu_address
  - kernel/module.c:__is_module_percpu_address
```
```
In kernel/kexec_core.c (ffffffff8115c7ed)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/cgroup/cgroup.c (ffffffff8116a555)
Location: arch/x86/include/asm/preempt.h:92
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
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/rstat.c (ffffffff8116aae5)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116cbdc)
Location: arch/x86/include/asm/preempt.h:92
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
In kernel/cgroup/freezer.c (ffffffff8116d917)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116e0eb)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8116f085)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81174e72)
Location: arch/x86/include/asm/preempt.h:92
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
In kernel/stop_machine.c (ffffffff81177651)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
```
```
In kernel/kprobes.c (ffffffff8118580a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/kprobes.c:show_kprobe_addr
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811906aa)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/hung_task.c (ffffffff811936c8)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/seccomp.c (ffffffff8119552d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/relay.c (ffffffff81196da7)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/relay.c:relay_late_setup_files
```
```
In kernel/trace/trace_clock.c (ffffffff8119a8c0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_local
```
```
In kernel/trace/ftrace.c (ffffffff8119adb4)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fpid_stop
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:function_trace_probe_call
  - kernel/trace/ftrace.c:ftrace_ops_trampoline
  - kernel/trace/ftrace.c:ftrace_ops_trampoline
```
```
In kernel/trace/ring_buffer.c (ffffffff811a5a2b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_nest_end
  - kernel/trace/ring_buffer.c:ring_buffer_time_stamp
```
```
In kernel/trace/trace.c (ffffffff811a6f72)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_cmdlines_stop
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:trace_find_cmdline
```
```
In kernel/trace/trace_functions.c (ffffffff811b5d2c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_init
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b6b4f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_stack.c (ffffffff811b8283)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811b8e50)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811b9404)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff811bcc93)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_events.c (ffffffff811bf014)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:p_stop
```
```
In kernel/trace/bpf_trace.c (ffffffff811d0e7b)
Location: arch/x86/include/asm/preempt.h:92
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
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dcd85)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In kernel/irq_work.c (ffffffff811df150)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/core.c (ffffffff811e2b14)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
```
```
In kernel/bpf/syscall.c (ffffffff811e72db)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/helpers.c (ffffffff811f76e3)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff811f8306)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
```
```
In kernel/bpf/arraymap.c (ffffffff811fb483)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/btf.c (ffffffff81202fc5)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/devmap.c (ffffffff812039ae)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
```
In kernel/bpf/cpumap.c (ffffffff81204a77)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff812067d0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/bpf/stackmap.c (ffffffff81208303)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/bpf/cgroup.c (ffffffff81209fc8)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
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
In kernel/events/core.c (ffffffff81214dc2)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_event_read
```
```
In kernel/events/ring_buffer.c (ffffffff8121c781)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_put_handle
```
```
In kernel/events/uprobes.c (ffffffff81220f24)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/user-return-notifier.c (ffffffff8122230a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:fire_user_return_notifiers
```
```
In kernel/jump_label.c (ffffffff812246d6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_module_notify
```
```
In kernel/rseq.c (ffffffff81225572)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
```
```
In mm/filemap.c (ffffffff81228b11)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/oom_kill.c (ffffffff8122f27b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page-writeback.c (ffffffff81234643)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
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
In mm/swap.c (ffffffff81237bae)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_drain
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
```
```
In mm/truncate.c (ffffffff81239bfe)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81241f6a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/shmem.c (ffffffff81245c10)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff8124b78c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/backing-dev.c (ffffffff8124e6ba)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/percpu.c (ffffffff81252066)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
```
```
In mm/slab_common.c (ffffffff81254a13)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/compaction.c (ffffffff8125ba43)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:compaction_deferred
  - mm/compaction.c:defer_compaction
```
```
In mm/gup.c (ffffffff8125f21c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/memory.c (ffffffff8126b6cc)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff81279e9e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8127d31b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/page_alloc.c (ffffffff812871cc)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:drain_local_pages_wq
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (ffffffff8128de9a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff812950e4)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/mempolicy.c (ffffffff8129e3fd)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/ksm.c (ffffffff812a880c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff812a8c4e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/slub.c (ffffffff812ae40b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
```
```
In mm/memory_hotplug.c (ffffffff812b241a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In mm/migrate.c (ffffffff812b7e9b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812ba6f7)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812c2d07)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812cf35d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
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
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812d0d33)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812d118c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff812d4bf0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/zsmalloc.c (ffffffff812d7b91)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:unpin_tag
```
```
In mm/cma.c (ffffffff812d8a5d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/cma.c:cma_release
  - mm/cma.c:cma_alloc
```
```
In mm/userfaultfd.c (ffffffff812d9991)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/memremap.c (ffffffff812db4c1)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812ddb47)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/open.c (ffffffff812e101e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/read_write.c (ffffffff812e29e5)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/super.c (ffffffff812e6c47)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/super.c:__sb_end_write
```
```
In fs/exec.c (ffffffff812edfb7)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/exec.c:__set_task_comm
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:do_open_execat
```
```
In fs/dcache.c (ffffffff81300582)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
  - fs/dcache.c:___d_drop
```
```
In fs/inode.c (ffffffff813036d1)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
  - fs/inode.c:__destroy_inode
```
```
In fs/file.c (ffffffff81307be5)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In fs/namespace.c (ffffffff81308d4c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_clone_write
  - fs/namespace.c:__mnt_want_write
```
```
In fs/libfs.c (ffffffff81313d47)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/fs-writeback.c (ffffffff8131a01f)
Location: arch/x86/include/asm/preempt.h:92
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
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
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
```
```
In fs/buffer.c (ffffffff813282fc)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/block_dev.c (ffffffff8132eaa9)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/direct-io.c (ffffffff81330ba1)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81332bdd)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/notify/group.c (ffffffff81334f3f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81337b96)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
```
In fs/aio.c (ffffffff81345d4f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx_users
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff8134d76c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
  - fs/io_uring.c:io_get_req
```
```
In fs/dax.c (ffffffff813512bb)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/verity/verify.c (ffffffff8135a4a0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/locks.c (ffffffff813603eb)
Location: arch/x86/include/asm/preempt.h:92
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
  - fs/locks.c:locks_get_lock_context
```
```
In fs/mbcache.c (ffffffff81368dcb)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff8136e03a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/proc/base.c (ffffffff8137ee38)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/kernfs/dir.c (ffffffff8138d284)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/ext4/balloc.c (ffffffff813986c4)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8139ad27)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (ffffffff813a3a80)
Location: arch/x86/include/asm/preempt.h:92
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
In fs/ext4/extents_status.c (ffffffff813a71eb)
Location: arch/x86/include/asm/preempt.h:92
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
In fs/ext4/fsmap.c (ffffffff813a9107)
Location: arch/x86/include/asm/preempt.h:92
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
In fs/ext4/fsync.c (ffffffff813a9645)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff813abf0c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff813ae3b5)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff813b1817)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813ba1fc)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff813c19d9)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
```
```
In fs/ext4/mballoc.c (ffffffff813c7dc0)
Location: arch/x86/include/asm/preempt.h:92
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
In fs/ext4/move_extent.c (ffffffff813cd0bf)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/namei.c (ffffffff813d5464)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff813d6c63)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813d73d4)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff813e4a9f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_nfs_commit_metadata
  - fs/ext4/super.c:ext4_drop_inode
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/verity.c (ffffffff813f9ac2)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813fd48a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
```
In fs/jbd2/commit.c (ffffffff813fe8b0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
```
In fs/jbd2/checkpoint.c (ffffffff81400935)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81406c03)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff81409357)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff8140b1a2)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8140b9a4)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff8140bc1c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_finish_page
  - fs/squashfs/page_actor.c:direct_next_page
```
```
In fs/ecryptfs/mmap.c (ffffffff814200be)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff814206ae)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8142c2bd)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (ffffffff81433d03)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff8143b739)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In ipc/util.c (ffffffff8144237a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/tomoyo/domain.c (ffffffff81498fe2)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/capability.c (ffffffff814a4e0a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/domain.c (ffffffff814aaeb7)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:profile_transition
```
```
In security/apparmor/policy_unpack.c (ffffffff814af548)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In security/apparmor/file.c (ffffffff814b6534)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
```
```
In security/apparmor/mount.c (ffffffff814bc329)
Location: arch/x86/include/asm/preempt.h:92
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
In crypto/scatterwalk.c (ffffffff814cdf76)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814cfc2f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In crypto/ahash.c (ffffffff814d24ed)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff814d3b1c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff814ec547)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
```
```
In block/blk-core.c (ffffffff814f399c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-ioc.c (ffffffff814f7dee)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_create_icq
```
```
In block/blk-merge.c (ffffffff814f923a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-mq.c (ffffffff814ff17a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_complete_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff81501f23)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-stat.c (ffffffff8150277d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add
```
```
In block/blk-mq-sched.c (ffffffff815040a9)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
```
```
In block/genhd.c (ffffffff815071b3)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In block/bounce.c (ffffffff81513932)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:__blk_queue_bounce
```
```
In block/blk-cgroup.c (ffffffff8151875a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff8151b73b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (ffffffff8151f6e7)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
```
```
In block/bio-integrity.c (ffffffff81523cbd)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff815254db)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-wbt.c (ffffffff815280f8)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
```
In lib/random32.c (ffffffff8152ea58)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes
  - lib/random32.c:prandom_u32
```
```
In lib/scatterlist.c (ffffffff815309df)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff8153641c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In lib/percpu-refcount.c (ffffffff8153822c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/rhashtable.c (ffffffff8153967f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/percpu_counter.c (ffffffff81560dc7)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_add_batch
```
```
In arch/x86/lib/msr-smp.c (ffffffff8156b258)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rwmsr_on_cpus
```
```
In arch/x86/lib/msr.c (ffffffff8156b896)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In drivers/gpio/gpiolib.c (ffffffff8157c6d5)
Location: arch/x86/include/asm/preempt.h:92
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
```
```
In drivers/pci/pcie/aer.c (ffffffff815ab54d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In drivers/acpi/sleep.c (ffffffff815e7bbc)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/clk/clk.c (ffffffff8165b352)
Location: arch/x86/include/asm/preempt.h:92
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
```
```
In drivers/xen/grant-table.c (ffffffff81671425)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81672e54)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/events/events_base.c (ffffffff8167493e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff816772d6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/swiotlb-xen.c (ffffffff816815ef)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff81687657)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/char/random.c (ffffffff816cdc6f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/random.c:mix_pool_bytes
  - drivers/char/random.c:__mix_pool_bytes
```
```
In drivers/char/virtio_console.c (ffffffff816d0144)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/iommu/iommu.c (ffffffff816e79bf)
Location: arch/x86/include/asm/preempt.h:92
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
In drivers/iommu/intel-iommu.c (ffffffff816fc020)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_single
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
```
In drivers/iommu/intel-pasid.c (ffffffff816fe3a9)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
```
```
In drivers/connector/cn_proc.c (ffffffff81703881)
Location: arch/x86/include/asm/preempt.h:92
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
In drivers/base/syscore.c (ffffffff8170eaf5)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/qos.c (ffffffff817198bd)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff8171ad02)
Location: arch/x86/include/asm/preempt.h:92
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
In drivers/base/power/main.c (ffffffff81720a56)
Location: arch/x86/include/asm/preempt.h:92
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
In drivers/base/power/wakeup.c (ffffffff817216f0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff8172ce9e)
Location: arch/x86/include/asm/preempt.h:92
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
```
```
In drivers/base/regmap/regcache.c (ffffffff8173200e)
Location: arch/x86/include/asm/preempt.h:92
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
In drivers/block/loop.c (ffffffff8173ad1a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:lo_rw_aio_complete
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff8173d038)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/nvdimm/region_devs.c (ffffffff81762fa8)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_release_lane
  - drivers/nvdimm/region_devs.c:nd_region_release_lane
```
```
In drivers/dax/super.c (ffffffff817722d6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8177505f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8177736d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff817784c6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff8177f1ce)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff81780705)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/sd.c (ffffffff8179325b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/scsi/sg.c (ffffffff81797045)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/ata/libata-core.c (ffffffff8179f5e5)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff817ad382)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-sff.c (ffffffff817b4d3c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/spi/spi.c (ffffffff817c4d93)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817cd2d7)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (ffffffff817d1de6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/usb/host/xhci.c (ffffffff81847267)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8184a78e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8184e62c)
Location: arch/x86/include/asm/preempt.h:92
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
In drivers/usb/host/xhci-hub.c (ffffffff81856b0f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185b674)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:dbc_free_request
  - drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/usb/host/xhci-pci.c (ffffffff8185f601)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In drivers/rtc/interface.c (ffffffff818777e7)
Location: arch/x86/include/asm/preempt.h:92
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
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8187cfb7)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8187ffc6)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff8189528a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/hwmon/hwmon.c:hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:hwmon_attr_show
```
```
In drivers/thermal/thermal_core.c (ffffffff818970ac)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (ffffffff8189bb5b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:thermal_cdev_update
```
```
In drivers/thermal/fair_share.c (ffffffff8189c45a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
```
```
In drivers/thermal/step_wise.c (ffffffff8189ca8f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/thermal/step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/power_allocator.c (ffffffff8189dba1)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff8189e46b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
```
In drivers/md/md.c (ffffffff818aa143)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/md-bitmap.c (ffffffff818b7891)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/md/dm.c (ffffffff818ba26e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
```
```
In drivers/md/dm-stats.c (ffffffff818c73a9)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/md/dm-rq.c (ffffffff818c8220)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (ffffffff818c976f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/edac/ghes_edac.c (ffffffff818cda35)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818d4d77)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818d7216)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818d9994)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818decb8)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818e0aa9)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
```
```
In drivers/cpuidle/driver.c (ffffffff818e13c3)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_driver_unref
  - drivers/cpuidle/driver.c:cpuidle_driver_ref
```
```
In drivers/mmc/core/core.c (ffffffff818e4cac)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff818ff8ca)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8190273d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:send_command
```
```
In drivers/devfreq/devfreq.c (ffffffff81909993)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffff81913e86)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
```
```
In net/core/sock.c (ffffffff819246e0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8192963c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:kfree_skb
```
```
In net/core/datagram.c (ffffffff819338e3)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/flow_dissector.c (ffffffff81939284)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (ffffffff81948604)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
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
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/neighbour.c (ffffffff81958805)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/filter.c (ffffffff8196d6e5)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81973f2e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/xdp.c (ffffffff81975c80)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81977121)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/page_pool.c (ffffffff8197a832)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_clean_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff8197b54a)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/core/netpoll.c (ffffffff8197dd86)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/core/lwt_bpf.c (ffffffff8198ad0d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
```
```
In net/core/sock_map.c (ffffffff8198c023)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_sk_release
```
```
In net/core/devlink.c (ffffffff81990dbc)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_report
  - net/core/devlink.c:devlink_health_report
```
```
In net/sched/sch_generic.c (ffffffff819a0475)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/sched/cls_api.c (ffffffff819aa28e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/netlink/af_netlink.c (ffffffff819b42d0)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/bpf/test_run.c (ffffffff819b82ab)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/tcp_input.c (ffffffff819e1746)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_output.c (ffffffff819e913f)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819eb826)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/udp.c (ffffffff819fd0e7)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/af_inet.c (ffffffff81a0ad8d)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_state_store
  - net/ipv4/af_inet.c:inet_sk_set_state
```
```
In net/ipv4/fib_trie.c (ffffffff81a18bde)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b801)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e2c1)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81a27b36)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a36f17)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/route.c (ffffffff81a6447c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a8697b)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
```
In net/ipv6/ip6mr.c (ffffffff81a91980)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9ad5c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81a9c66e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9d072)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/packet/af_packet.c (ffffffff81aa20df)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In lib/bug.c (ffffffff81ac4fcf)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:module_find_bug
```
```
In lib/nmi_backtrace.c (ffffffff81aca394)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/radix-tree.c (ffffffff81acae2e)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_preload
```
```
In arch/x86/lib/delay.c (ffffffff81ad8789)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81adaf1c)
Location: arch/x86/include/asm/preempt.h:92
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
</details>
</li>
</ul>

## Differences
