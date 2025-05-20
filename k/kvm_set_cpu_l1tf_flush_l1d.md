# Function: <code>kvm_set_cpu_l1tf_flush_l1d</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81a01bbe)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff810313bf)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/irq_work.c (ffffffff81a01e05)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81a01ebf)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff81a01f9f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81a0207f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81a0216f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81a02395)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81a026a3)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81a02862)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01bce)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff8103265f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c01e25)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c01edf)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c01fbf)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c0209f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c0220f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81c02435)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02763)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02922)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01dae)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff8103436f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c02005)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c020bf)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c0219f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c0227f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c023df)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c0245f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81c02685)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c029d1)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02ba2)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01dce)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff81034c2f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c02035)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c020ef)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c021cf)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c022af)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c0240f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c0248f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81c026b5)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02a01)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02bd2)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81097afb)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_message_interrupt
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
In arch/x86/xen/enlighten_hvm.c (ffffffff81bbca06)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81bbcac6)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/irq.c (ffffffff81bbdc7a)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:common_interrupt
```
```
In arch/x86/kernel/irq_work.c (ffffffff81bbdfe6)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:sysvec_irq_work
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81bbeba6)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81bbec36)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81bbecc6)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:sysvec_thermal
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81bbede6)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81bbee76)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/smp.c (ffffffff81bbf136)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_call_function_single
  - arch/x86/kernel/smp.c:sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reboot
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81bbf416)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81bbf4a6)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109a859)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:__sysvec_uv_bau_message
  - arch/x86/platform/uv/tlb_uv.c:sysvec_uv_bau_message
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
In arch/x86/xen/enlighten_hvm.c (ffffffff81c34f88)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81c35058)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/irq.c (ffffffff81c363cc)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:common_interrupt
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c36888)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:sysvec_irq_work
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c373a8)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c37438)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c374c8)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:sysvec_thermal
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c375e8)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c37678)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/smp.c (ffffffff81c37918)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_call_function_single
  - arch/x86/kernel/smp.c:sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reboot
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c37be8)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c37c78)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
```
```
In arch/x86/kernel/kvm.c (ffffffff81c37dd8)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
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
In arch/x86/xen/enlighten_hvm.c (ffffffff81c273f3)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81c274f3)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/irq.c (ffffffff81c28813)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:common_interrupt
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c28d23)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:sysvec_irq_work
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c29b03)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c29b93)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c29cb3)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c29d43)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/smp.c (ffffffff81c29fe3)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_call_function_single
  - arch/x86/kernel/smp.c:sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reboot
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c2a233)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c2a2c3)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
```
```
In arch/x86/kernel/kvm.c (ffffffff81c2a423)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
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
In arch/x86/xen/enlighten_hvm.c (ffffffff81d45443)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81d45543)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/irq.c (ffffffff81d46983)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:common_interrupt
```
```
In arch/x86/kernel/irq_work.c (ffffffff81d46eb3)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:sysvec_irq_work
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81d48073)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81d48103)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81d48223)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81d482b3)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/smp.c (ffffffff81d48543)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_call_function_single
  - arch/x86/kernel/smp.c:sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reboot
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81d48793)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81d48823)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
```
```
In arch/x86/kernel/kvm.c (ffffffff81d489a3)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
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
In arch/x86/xen/enlighten_hvm.c (ffffffff81f133c2)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81f136a2)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/irq.c (ffffffff81f14e52)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:common_interrupt
```
```
In arch/x86/kernel/irq_work.c (ffffffff81f15432)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:sysvec_irq_work
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81f16e72)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81f16f42)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81f170e2)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81f171b2)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/smp.c (ffffffff81f17512)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_call_function_single
  - arch/x86/kernel/smp.c:sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reboot
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81f17832)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81f17902)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
```
```
In arch/x86/kernel/kvm.c (ffffffff81f17ae2)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
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
In arch/x86/xen/enlighten_hvm.c (ffffffff820ba442)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
```
```
In arch/x86/hyperv/hv_init.c (ffffffff820ba832)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/irq.c (ffffffff820bc2d2)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:common_interrupt
```
```
In arch/x86/kernel/irq_work.c (ffffffff820bc8e2)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:sysvec_irq_work
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff820be492)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff820be572)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff820be732)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff820be812)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/smp.c (ffffffff820bebb2)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_call_function_single
  - arch/x86/kernel/smp.c:sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reboot
```
```
In arch/x86/kernel/apic/apic.c (ffffffff820bef12)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff820beff2)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
```
```
In arch/x86/kernel/kvm.c (ffffffff820bf202)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
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
In arch/x86/xen/enlighten_hvm.c (ffffffff82139cf2)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8213a122)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/irq.c (ffffffff8213da12)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:common_interrupt
```
```
In arch/x86/kernel/irq_work.c (ffffffff8213e152)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:sysvec_irq_work
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8213ff22)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff82140002)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff82140292)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff82140372)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/smp.c (ffffffff82140712)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_call_function_single
  - arch/x86/kernel/smp.c:sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reboot
```
```
In arch/x86/kernel/apic/apic.c (ffffffff82140a72)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff82140b52)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
```
```
In arch/x86/kernel/kvm.c (ffffffff82140d62)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
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
In arch/x86/xen/enlighten_hvm.c (ffffffff8221bc62)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8221c092)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/irq.c (ffffffff8221fa12)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:common_interrupt
```
```
In arch/x86/kernel/irq_work.c (ffffffff82220122)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:sysvec_irq_work
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff82221f42)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff82222022)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff822222b2)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff82222392)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/smp.c (ffffffff82222722)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_call_function_single
  - arch/x86/kernel/smp.c:sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reboot
```
```
In arch/x86/kernel/apic/apic.c (ffffffff82222a82)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/kvm.c (ffffffff82222c92)
Location: arch/x86/include/asm/hardirq.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01dae)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff81034d8f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c02015)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c020cf)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c021af)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c0228f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c023ef)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c0246f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81c02695)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c029e1)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02bb2)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01c5e)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff810246cf)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c01ec5)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c01f7f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c0205f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c0213f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c0229f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c0231f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81c02545)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02891)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02a62)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01d8e)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff81034bef)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c01ff5)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c020af)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c0218f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c0226f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c023cf)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81c02605)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02951)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02b22)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01dee)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff81035b4f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c02085)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c0216f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c0227f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c0238f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c0251f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c0259f)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81c02825)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02c11)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02e12)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81098fbb)
Location: arch/x86/include/asm/hardirq.h:65
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_message_interrupt
```
</details>
</li>
</ul>

## Differences
