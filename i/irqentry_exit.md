# Function: <code>irqentry_exit</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irqentry_exit(struct pt_regs *regs, irqentry_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81c38a40)
Location: kernel/entry/common.c:396
Inline: False
Direct callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
  - arch/x86/kernel/traps.c:exc_device_not_available
  - arch/x86/kernel/traps.c:exc_spurious_interrupt_bug
  - arch/x86/kernel/traps.c:exc_simd_coprocessor_error
  - arch/x86/kernel/traps.c:exc_coprocessor_error
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:exc_stack_segment
  - arch/x86/kernel/traps.c:exc_segment_not_present
  - arch/x86/kernel/traps.c:exc_invalid_tss
  - arch/x86/kernel/traps.c:exc_coproc_segment_overrun
  - arch/x86/kernel/traps.c:exc_invalid_op
  - arch/x86/kernel/traps.c:exc_overflow
  - arch/x86/kernel/traps.c:exc_divide_error
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:common_interrupt
  - arch/x86/kernel/irq_work.c:sysvec_irq_work
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold
  - arch/x86/kernel/cpu/mce/therm_throt.c:sysvec_thermal
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback
  - arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback
  - arch/x86/kernel/smp.c:sysvec_call_function_single
  - arch/x86/kernel/smp.c:sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reboot
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
  - arch/x86/kernel/kvm.c:__kvm_handle_async_pf
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff81c38a40-ffffffff81c38a62: irqentry_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irqentry_exit(struct pt_regs *regs, irqentry_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81c2ae40)
Location: kernel/entry/common.c:400
Inline: False
Direct callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
  - arch/x86/kernel/traps.c:exc_device_not_available
  - arch/x86/kernel/traps.c:exc_spurious_interrupt_bug
  - arch/x86/kernel/traps.c:exc_simd_coprocessor_error
  - arch/x86/kernel/traps.c:exc_coprocessor_error
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:exc_stack_segment
  - arch/x86/kernel/traps.c:exc_segment_not_present
  - arch/x86/kernel/traps.c:exc_invalid_tss
  - arch/x86/kernel/traps.c:exc_coproc_segment_overrun
  - arch/x86/kernel/traps.c:exc_invalid_op
  - arch/x86/kernel/traps.c:exc_overflow
  - arch/x86/kernel/traps.c:exc_divide_error
  - arch/x86/kernel/irq.c:sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:common_interrupt
  - arch/x86/kernel/irq_work.c:sysvec_irq_work
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback
  - arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback
  - arch/x86/kernel/smp.c:sysvec_call_function_single
  - arch/x86/kernel/smp.c:sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reboot
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
  - arch/x86/kernel/kvm.c:__kvm_handle_async_pf
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff81c2ae40-ffffffff81c2ae62: irqentry_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irqentry_exit(struct pt_regs *regs, irqentry_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81d493d0)
Location: kernel/entry/common.c:398
Inline: False
Direct callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
  - arch/x86/kernel/traps.c:exc_device_not_available
  - arch/x86/kernel/traps.c:exc_spurious_interrupt_bug
  - arch/x86/kernel/traps.c:exc_simd_coprocessor_error
  - arch/x86/kernel/traps.c:exc_coprocessor_error
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:exc_stack_segment
  - arch/x86/kernel/traps.c:exc_segment_not_present
  - arch/x86/kernel/traps.c:exc_invalid_tss
  - arch/x86/kernel/traps.c:exc_coproc_segment_overrun
  - arch/x86/kernel/traps.c:exc_invalid_op
  - arch/x86/kernel/traps.c:exc_overflow
  - arch/x86/kernel/traps.c:exc_divide_error
  - arch/x86/kernel/irq.c:sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:common_interrupt
  - arch/x86/kernel/irq_work.c:sysvec_irq_work
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback
  - arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback
  - arch/x86/kernel/smp.c:sysvec_call_function_single
  - arch/x86/kernel/smp.c:sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reboot
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
  - arch/x86/kernel/kvm.c:__kvm_handle_async_pf
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff81d493d0-ffffffff81d493f2: irqentry_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irqentry_exit(struct pt_regs *regs, irqentry_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81f18860)
Location: kernel/entry/common.c:402
Inline: False
Direct callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
  - arch/x86/kernel/traps.c:exc_virtualization_exception
  - arch/x86/kernel/traps.c:exc_device_not_available
  - arch/x86/kernel/traps.c:exc_spurious_interrupt_bug
  - arch/x86/kernel/traps.c:exc_simd_coprocessor_error
  - arch/x86/kernel/traps.c:exc_coprocessor_error
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:exc_stack_segment
  - arch/x86/kernel/traps.c:exc_segment_not_present
  - arch/x86/kernel/traps.c:exc_invalid_tss
  - arch/x86/kernel/traps.c:exc_coproc_segment_overrun
  - arch/x86/kernel/traps.c:exc_invalid_op
  - arch/x86/kernel/traps.c:exc_overflow
  - arch/x86/kernel/traps.c:exc_divide_error
  - arch/x86/kernel/irq.c:sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:common_interrupt
  - arch/x86/kernel/irq_work.c:sysvec_irq_work
  - arch/x86/kernel/irq_work.c:sysvec_irq_work
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold
  - arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback
  - arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback
  - arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback
  - arch/x86/kernel/smp.c:sysvec_call_function_single
  - arch/x86/kernel/smp.c:sysvec_call_function_single
  - arch/x86/kernel/smp.c:sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reboot
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
  - arch/x86/kernel/kvm.c:__kvm_handle_async_pf
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff81f18860-ffffffff81f188ad: irqentry_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irqentry_exit(struct pt_regs *regs, irqentry_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff820bfeb0)
Location: kernel/entry/common.c:406
Inline: False
Direct callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
  - arch/x86/kernel/traps.c:exc_virtualization_exception
  - arch/x86/kernel/traps.c:exc_device_not_available
  - arch/x86/kernel/traps.c:exc_spurious_interrupt_bug
  - arch/x86/kernel/traps.c:exc_simd_coprocessor_error
  - arch/x86/kernel/traps.c:exc_coprocessor_error
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:exc_stack_segment
  - arch/x86/kernel/traps.c:exc_segment_not_present
  - arch/x86/kernel/traps.c:exc_invalid_tss
  - arch/x86/kernel/traps.c:exc_coproc_segment_overrun
  - arch/x86/kernel/traps.c:exc_invalid_op
  - arch/x86/kernel/traps.c:exc_overflow
  - arch/x86/kernel/traps.c:exc_divide_error
  - arch/x86/kernel/irq.c:sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:common_interrupt
  - arch/x86/kernel/irq_work.c:sysvec_irq_work
  - arch/x86/kernel/irq_work.c:sysvec_irq_work
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold
  - arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback
  - arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback
  - arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback
  - arch/x86/kernel/smp.c:sysvec_call_function_single
  - arch/x86/kernel/smp.c:sysvec_call_function_single
  - arch/x86/kernel/smp.c:sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reboot
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
  - arch/x86/kernel/kvm.c:__kvm_handle_async_pf
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff820bfeb0-ffffffff820bfefd: irqentry_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irqentry_exit(struct pt_regs *regs, irqentry_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff82141cf0)
Location: kernel/entry/common.c:407
Inline: False
Direct callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
  - arch/x86/kernel/traps.c:exc_virtualization_exception
  - arch/x86/kernel/traps.c:exc_device_not_available
  - arch/x86/kernel/traps.c:exc_spurious_interrupt_bug
  - arch/x86/kernel/traps.c:exc_simd_coprocessor_error
  - arch/x86/kernel/traps.c:exc_coprocessor_error
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:exc_stack_segment
  - arch/x86/kernel/traps.c:exc_segment_not_present
  - arch/x86/kernel/traps.c:exc_invalid_tss
  - arch/x86/kernel/traps.c:exc_coproc_segment_overrun
  - arch/x86/kernel/traps.c:exc_invalid_op
  - arch/x86/kernel/traps.c:exc_overflow
  - arch/x86/kernel/traps.c:exc_divide_error
  - arch/x86/kernel/irq.c:sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:common_interrupt
  - arch/x86/kernel/irq_work.c:sysvec_irq_work
  - arch/x86/kernel/irq_work.c:sysvec_irq_work
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold
  - arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback
  - arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback
  - arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback
  - arch/x86/kernel/smp.c:sysvec_call_function_single
  - arch/x86/kernel/smp.c:sysvec_call_function_single
  - arch/x86/kernel/smp.c:sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reboot
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
  - arch/x86/kernel/kvm.c:__kvm_handle_async_pf
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff82141cf0-ffffffff82141d3d: irqentry_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irqentry_exit(struct pt_regs *regs, irqentry_state_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff82224070)
Location: kernel/entry/common.c:322
Inline: False
Direct callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
  - arch/x86/kernel/traps.c:exc_virtualization_exception
  - arch/x86/kernel/traps.c:exc_device_not_available
  - arch/x86/kernel/traps.c:exc_spurious_interrupt_bug
  - arch/x86/kernel/traps.c:exc_simd_coprocessor_error
  - arch/x86/kernel/traps.c:exc_coprocessor_error
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:exc_bounds
  - arch/x86/kernel/traps.c:exc_alignment_check
  - arch/x86/kernel/traps.c:exc_stack_segment
  - arch/x86/kernel/traps.c:exc_segment_not_present
  - arch/x86/kernel/traps.c:exc_invalid_tss
  - arch/x86/kernel/traps.c:exc_coproc_segment_overrun
  - arch/x86/kernel/traps.c:exc_invalid_op
  - arch/x86/kernel/traps.c:exc_overflow
  - arch/x86/kernel/traps.c:exc_divide_error
  - arch/x86/kernel/irq.c:sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:common_interrupt
  - arch/x86/kernel/irq_work.c:sysvec_irq_work
  - arch/x86/kernel/irq_work.c:sysvec_irq_work
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold
  - arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback
  - arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback
  - arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback
  - arch/x86/kernel/smp.c:sysvec_call_function_single
  - arch/x86/kernel/smp.c:sysvec_call_function_single
  - arch/x86/kernel/smp.c:sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reboot
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
  - arch/x86/kernel/kvm.c:__kvm_handle_async_pf
  - arch/x86/kernel/cet.c:exc_control_protection
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff82224070-ffffffff822240bd: irqentry_exit (STB_GLOBAL)
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
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
