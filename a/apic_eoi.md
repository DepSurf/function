# Function: <code>apic_eoi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8103008c)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:ack_bad_irq
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
```
```
In arch/x86/kernel/irq_work.c (ffffffff81033bb6)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81048f05)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff81049035)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81049855)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff81050ad6)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81052cb5)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81055976)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810561b5)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ack_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In drivers/iommu/irq_remapping.c (ffffffff8153e005)
Location: arch/x86/include/asm/apic.h:394
Inline: True
Inline callers:
  - drivers/iommu/irq_remapping.c:ir_ack_apic_edge
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8102fc46)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:ack_bad_irq
```
```
In arch/x86/kernel/irq_work.c (ffffffff81032dd6)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81049120)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff81049240)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81049a60)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff81050ee6)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81052de3)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81055c1d)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81056415)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ack_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In drivers/iommu/irq_remapping.c (ffffffff81592fd5)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - drivers/iommu/irq_remapping.c:ir_ack_apic_edge
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8102fc21)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:ack_bad_irq
```
```
In arch/x86/kernel/irq_work.c (ffffffff81032a5f)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104b1e6)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff8104b696)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104be56)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/smp.c (ffffffff8105379f)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81055ad3)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810589b8)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810591c5)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ack_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In drivers/iommu/irq_remapping.c (ffffffff815c0895)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - drivers/iommu/irq_remapping.c:ir_ack_apic_edge
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8190e111)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:ack_bad_irq
```
```
In arch/x86/kernel/irq_work.c (ffffffff8190e21f)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8190e336)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff8190e436)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8190e536)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810518ed)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff8190e7df)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81055503)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8190eb94)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81058825)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ack_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In drivers/iommu/irq_remapping.c (ffffffff815d63d5)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - drivers/iommu/irq_remapping.c:ir_ack_apic_edge
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8103015f)
Location: arch/x86/include/asm/apic.h:405
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:ack_bad_irq
```
```
In arch/x86/kernel/irq_work.c (ffffffff81a0276f)
Location: arch/x86/include/asm/apic.h:405
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81a0285c)
Location: arch/x86/include/asm/apic.h:405
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff81a0292c)
Location: arch/x86/include/asm/apic.h:405
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81a029fc)
Location: arch/x86/include/asm/apic.h:405
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81055470)
Location: arch/x86/include/asm/apic.h:405
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81a02c4f)
Location: arch/x86/include/asm/apic.h:405
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81a02fc6)
Location: arch/x86/include/asm/apic.h:405
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81a03142)
Location: arch/x86/include/asm/apic.h:405
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105cd45)
Location: arch/x86/include/asm/apic.h:405
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ack_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ir_ack_level
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In drivers/iommu/irq_remapping.c (ffffffff8163d185)
Location: arch/x86/include/asm/apic.h:405
Inline: True
Inline callers:
  - drivers/iommu/irq_remapping.c:ir_ack_apic_edge
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81a01bd4)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff810313d5)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:ack_bad_irq
```
```
In arch/x86/kernel/irq_work.c (ffffffff81a01def)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81a01ee4)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff81a01fc4)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81a020a4)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81a0218f)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81a0237f)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81a02701)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81a02878)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:apic_ack_irq
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105fd15)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ack_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01be4)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff81032675)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:ack_bad_irq
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c01e0f)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c01f04)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c01fe4)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c020c4)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c0222f)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81c0241f)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c027c1)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02938)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:apic_ack_irq
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81065985)
Location: arch/x86/include/asm/apic.h:400
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ack_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01dc4)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff81034385)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:ack_bad_irq
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c01fef)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c020e4)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c021c4)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c022a4)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c0240b)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c02475)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81c0266f)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02a2f)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02bb8)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:apic_ack_irq
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069135)
Location: arch/x86/include/asm/apic.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ack_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01de4)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff81034c45)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:ack_bad_irq
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c0201f)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c02114)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c021f4)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c022d4)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c0243b)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c024a5)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81c0269f)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02a5f)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02be8)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:apic_ack_irq
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069ab5)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ack_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81097aec)
Location: arch/x86/include/asm/apic.h:406
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
In arch/x86/hyperv/hv_init.c (ffffffff8102fa85)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/irq.c (ffffffff81bbdc82)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:__sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:common_interrupt
  - arch/x86/kernel/irq.c:ack_bad_irq
```
```
In arch/x86/kernel/irq_work.c (ffffffff81039bb5)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81055967)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81056f87)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81057777)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:__sysvec_thermal
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81067a0e)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81067c53)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:__sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/smp.c (ffffffff81069465)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106cf82)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:apic_check_and_ack
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8106ef9d)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__sysvec_irq_move_cleanup
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810709e5)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ack_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In arch/x86/platform/uv/tlb_uv.c (0)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:__sysvec_uv_bau_message
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
In arch/x86/hyperv/hv_init.c (ffffffff810306b5)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/irq.c (ffffffff81c363d4)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:__sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:common_interrupt
  - arch/x86/kernel/irq.c:ack_bad_irq
```
```
In arch/x86/kernel/irq_work.c (ffffffff8103a3e5)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81054886)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81055d76)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81056526)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:__sysvec_thermal
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810697be)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81069953)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:__sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/smp.c (ffffffff8106b125)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106e722)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:apic_check_and_ack
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8107052d)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__sysvec_irq_move_cleanup
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81071d25)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ack_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In arch/x86/kernel/kvm.c (ffffffff8107ee03)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
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
In arch/x86/hyperv/hv_init.c (ffffffff810311a5)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/irq.c (ffffffff810385bc)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:__sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__common_interrupt
  - arch/x86/kernel/irq.c:ack_bad_irq
```
```
In arch/x86/kernel/irq_work.c (ffffffff8103bdf5)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81056096)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff810575f6)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8106a20e)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff8106a3e3)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:__sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/smp.c (ffffffff8106b985)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106f212)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81071f9d)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__sysvec_irq_move_cleanup
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81072835)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ack_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In arch/x86/kernel/kvm.c (ffffffff8107fa13)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
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
In arch/x86/hyperv/hv_init.c (ffffffff810363f5)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/irq.c (ffffffff8103d956)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:__sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__common_interrupt
  - arch/x86/kernel/irq.c:ack_bad_irq
```
```
In arch/x86/kernel/irq_work.c (ffffffff810418d5)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105ec00)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81060440)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8107496e)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81074c23)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:__sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/smp.c (ffffffff81076465)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8107ac14)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8107ddbd)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__sysvec_irq_move_cleanup
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8107e7d5)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ack_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In arch/x86/kernel/kvm.c (ffffffff8108e7f3)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
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
In arch/x86/hyperv/hv_init.c (ffffffff8103c235)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/irq.c (ffffffff810454d9)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:__sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__common_interrupt
  - arch/x86/kernel/irq.c:ack_bad_irq
```
```
In arch/x86/kernel/irq_work.c (ffffffff810495a5)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8106b030)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff8106cbf0)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810832bc)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81083563)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:__sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/smp.c (ffffffff81085535)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81089ca4)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:apic_pending_intr_clear
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8108c00e)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__sysvec_irq_move_cleanup
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8108df75)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ack_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In arch/x86/kernel/kvm.c (ffffffff8109f873)
Location: arch/x86/include/asm/apic.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
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
In arch/x86/xen/enlighten_hvm.c (ffffffff81033481)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:__sysvec_xen_hvm_callback
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81044d85)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/irq.c (ffffffff8104f525)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:__sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__common_interrupt
  - arch/x86/kernel/irq.c:ack_bad_irq
```
```
In arch/x86/kernel/irq_work.c (ffffffff81054625)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107af90)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff8107ccf0)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81095e4c)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff810961c3)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:__sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/smp.c (ffffffff81098765)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109dbc4)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a052e)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__sysvec_irq_move_cleanup
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a2715)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ack_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In arch/x86/kernel/kvm.c (ffffffff810b7113)
Location: arch/x86/include/asm/apic.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
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
In arch/x86/xen/enlighten_hvm.c (ffffffff81033421)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:__sysvec_xen_hvm_callback
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81044ec5)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/irq.c (ffffffff810501d5)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:__sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__common_interrupt
  - arch/x86/kernel/irq.c:ack_bad_irq
```
```
In arch/x86/kernel/irq_work.c (ffffffff81055685)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107d230)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff8107f0a0)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81098d0c)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff810992e3)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:__sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/smp.c (ffffffff8109b675)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a0ba2)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a34ae)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__sysvec_irq_move_cleanup
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a5705)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ack_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In arch/x86/kernel/kvm.c (ffffffff810ba303)
Location: arch/x86/include/asm/apic.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
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
In arch/x86/xen/enlighten_hvm.c (ffffffff81039754)
Location: arch/x86/include/asm/apic.h:404
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:__sysvec_xen_hvm_callback
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8104b525)
Location: arch/x86/include/asm/apic.h:404
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/irq.c (ffffffff81057415)
Location: arch/x86/include/asm/apic.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:__sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__common_interrupt
  - arch/x86/kernel/irq.c:ack_bad_irq
```
```
In arch/x86/kernel/irq_work.c (ffffffff8105c8f5)
Location: arch/x86/include/asm/apic.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81084710)
Location: arch/x86/include/asm/apic.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81086590)
Location: arch/x86/include/asm/apic.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810a027c)
Location: arch/x86/include/asm/apic.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff810a099a)
Location: arch/x86/include/asm/apic.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:__sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/smp.c (ffffffff810a2c35)
Location: arch/x86/include/asm/apic.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a7db2)
Location: arch/x86/include/asm/apic.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810aa206)
Location: arch/x86/include/asm/apic.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810aca45)
Location: arch/x86/include/asm/apic.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ack_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In arch/x86/kernel/kvm.c (ffffffff810c174a)
Location: arch/x86/include/asm/apic.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01dc4)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff81034da5)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:ack_bad_irq
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c01fff)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c020f4)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c021d4)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c022b4)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c0241b)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c02485)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81c0267f)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02a3f)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02bc8)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:apic_ack_irq
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810695a5)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ack_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01c74)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff810246e5)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:ack_bad_irq
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c01eaf)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c01fa4)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c02084)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c02164)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c022cb)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c02335)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81c0252f)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c028ef)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02a78)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:apic_ack_irq
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81059905)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ack_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01da4)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff81034c05)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:ack_bad_irq
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c01fdf)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c020d4)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c021b4)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c02294)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c023fb)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81c025ef)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c029af)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02b38)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:apic_ack_irq
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069a55)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ack_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01e04)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff81035b65)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:ack_bad_irq
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c0206f)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c02194)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c022a4)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c023b4)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c0254b)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c025b5)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81c0280f)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02c6f)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02e28)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:apic_ack_irq
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b1d5)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ack_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81098fac)
Location: arch/x86/include/asm/apic.h:406
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_message_interrupt
```
</details>
</li>
</ul>

## Differences
