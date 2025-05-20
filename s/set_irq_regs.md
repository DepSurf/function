# Function: <code>set_irq_regs</code>

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
In arch/x86/kernel/irq.c (ffffffff81826ea8)
Location: arch/x86/include/asm/irq_regs.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8104f46a)
Location: arch/x86/include/asm/irq_regs.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81826f73)
Location: arch/x86/include/asm/irq_regs.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
```
```
In drivers/xen/events/events_base.c (ffffffff814c97da)
Location: arch/x86/include/asm/irq_regs.h:21
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
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
In arch/x86/kernel/irq.c (ffffffff8102fc2c)
Location: arch/x86/include/asm/irq_regs.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8104f5ba)
Location: arch/x86/include/asm/irq_regs.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff818a19bc)
Location: arch/x86/include/asm/irq_regs.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In drivers/xen/events/events_base.c (ffffffff8151a30a)
Location: arch/x86/include/asm/irq_regs.h:21
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
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
In arch/x86/kernel/irq.c (ffffffff8102fc0c)
Location: arch/x86/include/asm/irq_regs.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81051dba)
Location: arch/x86/include/asm/irq_regs.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff818d6f0c)
Location: arch/x86/include/asm/irq_regs.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In drivers/xen/events/events_base.c (ffffffff815467fa)
Location: arch/x86/include/asm/irq_regs.h:21
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
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
In arch/x86/kernel/irq.c (ffffffff8190e0fc)
Location: arch/x86/include/asm/irq_regs.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810518ba)
Location: arch/x86/include/asm/irq_regs.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8190e8ec)
Location: arch/x86/include/asm/irq_regs.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In drivers/xen/events/events_base.c (ffffffff8155a61a)
Location: arch/x86/include/asm/irq_regs.h:21
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
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
In arch/x86/kernel/irq.c (ffffffff8103014a)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8105543a)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81a02d1c)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In drivers/xen/events/events_base.c (ffffffff815bea5a)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
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
In arch/x86/kernel/irq.c (ffffffff810313a5)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81a02155)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81a02445)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In drivers/xen/events/events_base.c (ffffffff815f7085)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
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
In arch/x86/kernel/irq.c (ffffffff81032645)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c021f5)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c024e5)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In drivers/xen/events/events_base.c (ffffffff81612115)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
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
In arch/x86/kernel/irq.c (ffffffff81034355)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c023c5)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c02445)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02735)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In drivers/xen/events/events_base.c (ffffffff81645ea5)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
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
In arch/x86/kernel/irq.c (ffffffff81034c15)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c023f5)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c02475)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02765)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In drivers/xen/events/events_base.c (ffffffff81668425)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
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
In arch/x86/entry/common.c (ffffffff81bbc913)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff81021065)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:__sysvec_xen_hvm_callback
  - arch/x86/xen/enlighten_hvm.c:__sysvec_xen_hvm_callback
```
```
In arch/x86/kernel/irq.c (ffffffff81035815)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:common_interrupt
  - arch/x86/kernel/irq.c:common_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810679d5)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_callback
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81067c35)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:__sysvec_acrn_hv_callback
  - arch/x86/kernel/cpu/acrn.c:__sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106cc35)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In drivers/xen/events/events_base.c (ffffffff817185b5)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
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
In arch/x86/entry/common.c (ffffffff81c34eb4)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff810218d5)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:__sysvec_xen_hvm_callback
  - arch/x86/xen/enlighten_hvm.c:__sysvec_xen_hvm_callback
```
```
In arch/x86/kernel/irq.c (ffffffff81036a25)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:common_interrupt
  - arch/x86/kernel/irq.c:common_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81069785)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_callback
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81069935)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:__sysvec_acrn_hv_callback
  - arch/x86/kernel/cpu/acrn.c:__sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106e3f5)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/kvm.c (ffffffff8107ede5)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
```
```
In drivers/xen/events/events_base.c (ffffffff81735c75)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
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
In arch/x86/entry/common.c (ffffffff81c2733f)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff81023c65)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:__sysvec_xen_hvm_callback
  - arch/x86/xen/enlighten_hvm.c:__sysvec_xen_hvm_callback
```
```
In arch/x86/kernel/irq.c (ffffffff810384d5)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__common_interrupt
  - arch/x86/kernel/irq.c:__common_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8106a1d5)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_callback
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff8106a3c5)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:__sysvec_acrn_hv_callback
  - arch/x86/kernel/cpu/acrn.c:__sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106eea5)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f9f5)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
```
```
In drivers/xen/events/events_base.c (ffffffff81719485)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
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
In arch/x86/entry/common.c (ffffffff81d4538f)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff81027f05)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:__sysvec_xen_hvm_callback
  - arch/x86/xen/enlighten_hvm.c:__sysvec_xen_hvm_callback
```
```
In arch/x86/kernel/irq.c (ffffffff8103d875)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__common_interrupt
  - arch/x86/kernel/irq.c:__common_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81074935)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_callback
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81074c05)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:__sysvec_acrn_hv_callback
  - arch/x86/kernel/cpu/acrn.c:__sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8107a8a5)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/kvm.c (ffffffff8108e7d5)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
```
```
In drivers/xen/events/events_base.c (ffffffff81797335)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
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
In arch/x86/entry/common.c (ffffffff81f1331d)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff8102c455)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:__sysvec_xen_hvm_callback
  - arch/x86/xen/enlighten_hvm.c:__sysvec_xen_hvm_callback
```
```
In arch/x86/kernel/irq.c (ffffffff81045595)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__common_interrupt
  - arch/x86/kernel/irq.c:__common_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81083285)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_callback
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81083545)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:__sysvec_acrn_hv_callback
  - arch/x86/kernel/cpu/acrn.c:__sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81089875)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/kvm.c (ffffffff8109f855)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
```
```
In drivers/xen/events/events_base.c (ffffffff818d0315)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
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
In arch/x86/entry/common.c (ffffffff820ba38d)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff81033455)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:__sysvec_xen_hvm_callback
  - arch/x86/xen/enlighten_hvm.c:__sysvec_xen_hvm_callback
```
```
In arch/x86/kernel/irq.c (ffffffff8104f3f5)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__common_interrupt
  - arch/x86/kernel/irq.c:__common_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81095e15)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_callback
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff810961a5)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:__sysvec_acrn_hv_callback
  - arch/x86/kernel/cpu/acrn.c:__sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109d565)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/kvm.c (ffffffff810b70f5)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
```
```
In drivers/xen/events/events_base.c (ffffffff81a21ac5)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
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
In arch/x86/entry/common.c (ffffffff82139b9d)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff810333f5)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:__sysvec_xen_hvm_callback
  - arch/x86/xen/enlighten_hvm.c:__sysvec_xen_hvm_callback
```
```
In arch/x86/kernel/irq.c (ffffffff810500a5)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__common_interrupt
  - arch/x86/kernel/irq.c:__common_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81098cd5)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_callback
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff810992c5)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:__sysvec_acrn_hv_callback
  - arch/x86/kernel/cpu/acrn.c:__sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a0545)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/kvm.c (ffffffff810ba2e5)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
```
```
In drivers/xen/events/events_base.c (ffffffff81a6ae55)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
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
In arch/x86/entry/common.c (ffffffff8221bb0d)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff81039705)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:__sysvec_xen_hvm_callback
  - arch/x86/xen/enlighten_hvm.c:__sysvec_xen_hvm_callback
```
```
In arch/x86/kernel/irq.c (ffffffff810572f5)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__common_interrupt
  - arch/x86/kernel/irq.c:__common_interrupt
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810a0245)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_callback
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff810a0985)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:__sysvec_acrn_hv_callback
  - arch/x86/kernel/cpu/acrn.c:__sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a8095)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/kvm.c (ffffffff810c1735)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
```
</details>
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
In arch/arm64/kernel/smp.c (ffff80001009cb08)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:handle_IPI
  - arch/arm64/kernel/smp.c:handle_IPI
```
```
In kernel/irq/irqdesc.c (ffff800010177cb8)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:handle_domain_nmi
  - kernel/irq/irqdesc.c:handle_domain_nmi
  - kernel/irq/irqdesc.c:__handle_domain_irq
  - kernel/irq/irqdesc.c:__handle_domain_irq
```
```
In drivers/xen/events/events_base.c (ffff80001083243c)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
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
In arch/arm/kernel/traps.c (c03021f0)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/arm/kernel/traps.c:handle_fiq_as_nmi
  - arch/arm/kernel/traps.c:handle_fiq_as_nmi
```
```
In arch/arm/kernel/smp.c (c03133d8)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/smp.c:handle_IPI
```
```
In kernel/irq/irqdesc.c (c03c9674)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:handle_domain_nmi
  - kernel/irq/irqdesc.c:handle_domain_nmi
  - kernel/irq/irqdesc.c:__handle_domain_irq
  - kernel/irq/irqdesc.c:__handle_domain_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/irq.c (c00000000001c0dc)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/powerpc/kernel/irq.c:do_IRQ
  - arch/powerpc/kernel/irq.c:do_IRQ
  - arch/powerpc/kernel/irq.c:do_IRQ
```
```
In arch/powerpc/kernel/time.c (c00000000002b984)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/powerpc/kernel/time.c:timer_interrupt
  - arch/powerpc/kernel/time.c:timer_interrupt
```
```
In arch/powerpc/kernel/traps.c (c00000000002e788)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/powerpc/kernel/traps.c:handle_hmi_exception
  - arch/powerpc/kernel/traps.c:handle_hmi_exception
```
```
In arch/powerpc/kernel/dbell.c (c0000000000502d8)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/powerpc/kernel/dbell.c:doorbell_exception
  - arch/powerpc/kernel/dbell.c:doorbell_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/irq.c (ffffffe0008c9a44)
Location: include/asm-generic/irq_regs.h:24
Inline: True
Inline callers:
  - arch/riscv/kernel/irq.c:do_IRQ
  - arch/riscv/kernel/irq.c:do_IRQ
```
</details>
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
In arch/x86/kernel/irq.c (ffffffff81034d75)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c023d5)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c02455)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02745)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In drivers/xen/events/events_base.c (ffffffff8162e155)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
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
In arch/x86/kernel/irq.c (ffffffff810246b5)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c02285)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c02305)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c025f5)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
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
In arch/x86/kernel/irq.c (ffffffff81034bd5)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c023b5)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c026b5)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In drivers/xen/events/events_base.c (ffffffff8165c265)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
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
In arch/x86/kernel/irq.c (ffffffff81035b35)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c02505)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c02585)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02905)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In drivers/xen/events/events_base.c (ffffffff81676855)
Location: arch/x86/include/asm/irq_regs.h:22
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
</details>
</li>
</ul>

## Differences
