# Function: <code>entering_irq</code>

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
In arch/x86/kernel/irq.c (ffffffff81826eba)
Location: arch/x86/include/asm/apic.h:632
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81048ee9)
Location: arch/x86/include/asm/apic.h:632
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff81049019)
Location: arch/x86/include/asm/apic.h:632
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81049839)
Location: arch/x86/include/asm/apic.h:632
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8104f47a)
Location: arch/x86/include/asm/apic.h:632
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81826f8e)
Location: arch/x86/include/asm/apic.h:632
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
In arch/x86/kernel/apic/vector.c (ffffffff810559a7)
Location: arch/x86/include/asm/apic.h:632
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
In arch/x86/kernel/irq.c (ffffffff8102fc3c)
Location: arch/x86/include/asm/apic.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff810490fa)
Location: arch/x86/include/asm/apic.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff8104921a)
Location: arch/x86/include/asm/apic.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81049a3a)
Location: arch/x86/include/asm/apic.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8104f5ca)
Location: arch/x86/include/asm/apic.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105446a)
Location: arch/x86/include/asm/apic.h:639
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
In arch/x86/kernel/apic/vector.c (ffffffff81055c13)
Location: arch/x86/include/asm/apic.h:639
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
In arch/x86/kernel/irq.c (ffffffff8102fc1c)
Location: arch/x86/include/asm/apic.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104b1ca)
Location: arch/x86/include/asm/apic.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff8104b67a)
Location: arch/x86/include/asm/apic.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104be3a)
Location: arch/x86/include/asm/apic.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81051dca)
Location: arch/x86/include/asm/apic.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105716a)
Location: arch/x86/include/asm/apic.h:639
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
In arch/x86/kernel/apic/vector.c (ffffffff810589b3)
Location: arch/x86/include/asm/apic.h:639
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
In arch/x86/kernel/irq.c (ffffffff8190e10c)
Location: arch/x86/include/asm/apic.h:619
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
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8190e31a)
Location: arch/x86/include/asm/apic.h:619
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff8190e41a)
Location: arch/x86/include/asm/apic.h:619
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8190e51a)
Location: arch/x86/include/asm/apic.h:619
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810518ca)
Location: arch/x86/include/asm/apic.h:619
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8190eaca)
Location: arch/x86/include/asm/apic.h:619
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
In arch/x86/kernel/apic/vector.c (ffffffff8190eb8f)
Location: arch/x86/include/asm/apic.h:619
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
In arch/x86/kernel/irq.c (ffffffff8103015a)
Location: arch/x86/include/asm/apic.h:522
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81a0283a)
Location: arch/x86/include/asm/apic.h:522
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff81a0290a)
Location: arch/x86/include/asm/apic.h:522
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81a029da)
Location: arch/x86/include/asm/apic.h:522
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8105544a)
Location: arch/x86/include/asm/apic.h:522
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81a02f6e)
Location: arch/x86/include/asm/apic.h:522
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81a0313d)
Location: arch/x86/include/asm/apic.h:522
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
In arch/x86/hyperv/hv_init.c (ffffffff81a01bb5)
Location: arch/x86/include/asm/apic.h:515
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff810313ba)
Location: arch/x86/include/asm/apic.h:515
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81a01eb5)
Location: arch/x86/include/asm/apic.h:515
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/threshold.c (ffffffff81a01f95)
Location: arch/x86/include/asm/apic.h:515
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81a02075)
Location: arch/x86/include/asm/apic.h:515
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81a0216a)
Location: arch/x86/include/asm/apic.h:515
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81a02695)
Location: arch/x86/include/asm/apic.h:515
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81a0285d)
Location: arch/x86/include/asm/apic.h:515
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01bc5)
Location: arch/x86/include/asm/apic.h:515
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff8103265a)
Location: arch/x86/include/asm/apic.h:515
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c01ed5)
Location: arch/x86/include/asm/apic.h:515
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c01fb5)
Location: arch/x86/include/asm/apic.h:515
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c02095)
Location: arch/x86/include/asm/apic.h:515
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c0220a)
Location: arch/x86/include/asm/apic.h:515
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02755)
Location: arch/x86/include/asm/apic.h:515
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c0291d)
Location: arch/x86/include/asm/apic.h:515
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01da5)
Location: arch/x86/include/asm/apic.h:516
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff8103436a)
Location: arch/x86/include/asm/apic.h:516
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c020b5)
Location: arch/x86/include/asm/apic.h:516
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c02195)
Location: arch/x86/include/asm/apic.h:516
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c02275)
Location: arch/x86/include/asm/apic.h:516
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c023da)
Location: arch/x86/include/asm/apic.h:516
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c0245a)
Location: arch/x86/include/asm/apic.h:516
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c029c5)
Location: arch/x86/include/asm/apic.h:516
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02b9d)
Location: arch/x86/include/asm/apic.h:516
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01dc5)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff81034c2a)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c020e5)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c021c5)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c022a5)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c0240a)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c0248a)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c029f5)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02bcd)
Location: arch/x86/include/asm/apic.h:525
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01da5)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff81034d8a)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c020c5)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c021a5)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c02285)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c023ea)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c0246a)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c029d5)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02bad)
Location: arch/x86/include/asm/apic.h:525
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01c55)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff810246ca)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c01f75)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c02055)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c02135)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c0229a)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c0231a)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02885)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02a5d)
Location: arch/x86/include/asm/apic.h:525
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01d85)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff81034bea)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c020a5)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c02185)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c02265)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c023ca)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02945)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02b1d)
Location: arch/x86/include/asm/apic.h:525
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01de5)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff81035b4a)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c02165)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c02275)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c02385)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c0251a)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c0259a)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02c05)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02e0d)
Location: arch/x86/include/asm/apic.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
</details>
</li>
</ul>

## Differences
