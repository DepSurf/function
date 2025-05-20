# Function: <code>exiting_irq</code>

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
In arch/x86/kernel/irq.c (ffffffff81826edf)
Location: arch/x86/include/asm/apic.h:650
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
```
```
In arch/x86/kernel/irq_work.c (ffffffff81033bde)
Location: arch/x86/include/asm/apic.h:650
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8104f499)
Location: arch/x86/include/asm/apic.h:650
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81050b69)
Location: arch/x86/include/asm/apic.h:650
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81826f9d)
Location: arch/x86/include/asm/apic.h:650
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81055a3f)
Location: arch/x86/include/asm/apic.h:650
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
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
In arch/x86/kernel/irq.c (ffffffff8102fc79)
Location: arch/x86/include/asm/apic.h:657
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/irq_work.c (ffffffff81032e09)
Location: arch/x86/include/asm/apic.h:657
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8104f5e9)
Location: arch/x86/include/asm/apic.h:657
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81050f19)
Location: arch/x86/include/asm/apic.h:657
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81054483)
Location: arch/x86/include/asm/apic.h:657
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81055d3f)
Location: arch/x86/include/asm/apic.h:657
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
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
In arch/x86/kernel/irq.c (ffffffff8102fc54)
Location: arch/x86/include/asm/apic.h:656
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/irq_work.c (ffffffff81032a89)
Location: arch/x86/include/asm/apic.h:656
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81051de4)
Location: arch/x86/include/asm/apic.h:656
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff810537c9)
Location: arch/x86/include/asm/apic.h:656
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105717e)
Location: arch/x86/include/asm/apic.h:656
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81058ae3)
Location: arch/x86/include/asm/apic.h:656
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
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
In arch/x86/kernel/irq.c (ffffffff8190e144)
Location: arch/x86/include/asm/apic.h:636
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/irq_work.c (ffffffff8190e249)
Location: arch/x86/include/asm/apic.h:636
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81051901)
Location: arch/x86/include/asm/apic.h:636
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff8190e809)
Location: arch/x86/include/asm/apic.h:636
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8190eade)
Location: arch/x86/include/asm/apic.h:636
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8190ec2c)
Location: arch/x86/include/asm/apic.h:636
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
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
In arch/x86/kernel/irq.c (ffffffff8103017c)
Location: arch/x86/include/asm/apic.h:539
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/irq_work.c (ffffffff81a0279b)
Location: arch/x86/include/asm/apic.h:539
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81055486)
Location: arch/x86/include/asm/apic.h:539
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81a02c7b)
Location: arch/x86/include/asm/apic.h:539
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81a03028)
Location: arch/x86/include/asm/apic.h:539
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81a031de)
Location: arch/x86/include/asm/apic.h:539
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
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
In arch/x86/hyperv/hv_init.c (ffffffff81a01c00)
Location: arch/x86/include/asm/apic.h:534
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff810313e4)
Location: arch/x86/include/asm/apic.h:534
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/irq_work.c (ffffffff81a01e23)
Location: arch/x86/include/asm/apic.h:534
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81a021a5)
Location: arch/x86/include/asm/apic.h:534
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81a023b3)
Location: arch/x86/include/asm/apic.h:534
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81a02779)
Location: arch/x86/include/asm/apic.h:534
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81a028fe)
Location: arch/x86/include/asm/apic.h:534
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01c10)
Location: arch/x86/include/asm/apic.h:534
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff81032684)
Location: arch/x86/include/asm/apic.h:534
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c01e43)
Location: arch/x86/include/asm/apic.h:534
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c02245)
Location: arch/x86/include/asm/apic.h:534
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81c02453)
Location: arch/x86/include/asm/apic.h:534
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02839)
Location: arch/x86/include/asm/apic.h:534
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c029be)
Location: arch/x86/include/asm/apic.h:534
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01df0)
Location: arch/x86/include/asm/apic.h:535
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff81034394)
Location: arch/x86/include/asm/apic.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c02023)
Location: arch/x86/include/asm/apic.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c02421)
Location: arch/x86/include/asm/apic.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c02495)
Location: arch/x86/include/asm/apic.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81c026a3)
Location: arch/x86/include/asm/apic.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02a83)
Location: arch/x86/include/asm/apic.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02c46)
Location: arch/x86/include/asm/apic.h:535
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01e10)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff81034c54)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c02053)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c02451)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c024c5)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81c026d3)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02ab3)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02c76)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
</details>
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01df0)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff81034db4)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c02033)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c02431)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c024a5)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81c026b3)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02a93)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02c56)
Location: arch/x86/include/asm/apic.h:544
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01ca0)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff810246f4)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c01ee3)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c022e1)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c02355)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81c02563)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02943)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02b06)
Location: arch/x86/include/asm/apic.h:544
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01dd0)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff81034c14)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c02013)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c02411)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81c02623)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02a03)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02bc6)
Location: arch/x86/include/asm/apic.h:544
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01e30)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff81035b74)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c020a3)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c02561)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c025d5)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/smp.c (ffffffff81c02843)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02cc3)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02eb4)
Location: arch/x86/include/asm/apic.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
</details>
</li>
</ul>

## Differences
