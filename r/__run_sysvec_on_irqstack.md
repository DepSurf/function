# Function: <code>__run_sysvec_on_irqstack</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff81bbca47)
Location: arch/x86/include/asm/irq_stack.h:32
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81bbcb07)
Location: arch/x86/include/asm/irq_stack.h:32
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/irq.c (ffffffff81bbdc17)
Location: arch/x86/include/asm/irq_stack.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_x86_platform_ipi
```
```
In arch/x86/kernel/irq_work.c (ffffffff81bbe027)
Location: arch/x86/include/asm/irq_stack.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:sysvec_irq_work
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81bbebe7)
Location: arch/x86/include/asm/irq_stack.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81bbec77)
Location: arch/x86/include/asm/irq_stack.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81bbed07)
Location: arch/x86/include/asm/irq_stack.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:sysvec_thermal
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81bbee27)
Location: arch/x86/include/asm/irq_stack.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81bbeeb7)
Location: arch/x86/include/asm/irq_stack.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/smp.c (ffffffff81bbf177)
Location: arch/x86/include/asm/irq_stack.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_call_function_single
  - arch/x86/kernel/smp.c:sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reboot
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81bbf457)
Location: arch/x86/include/asm/irq_stack.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81bbf4e7)
Location: arch/x86/include/asm/irq_stack.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81bbf7d7)
Location: arch/x86/include/asm/irq_stack.h:32
Inline: True
Inline callers:
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
In arch/x86/xen/enlighten_hvm.c (ffffffff81c34fca)
Location: arch/x86/include/asm/irq_stack.h:31
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81c3509a)
Location: arch/x86/include/asm/irq_stack.h:31
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/irq.c (ffffffff81c3636a)
Location: arch/x86/include/asm/irq_stack.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_x86_platform_ipi
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c368ca)
Location: arch/x86/include/asm/irq_stack.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:sysvec_irq_work
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c373ea)
Location: arch/x86/include/asm/irq_stack.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c3747a)
Location: arch/x86/include/asm/irq_stack.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c3750a)
Location: arch/x86/include/asm/irq_stack.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:sysvec_thermal
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c3762a)
Location: arch/x86/include/asm/irq_stack.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c376ba)
Location: arch/x86/include/asm/irq_stack.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/smp.c (ffffffff81c3795a)
Location: arch/x86/include/asm/irq_stack.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_call_function_single
  - arch/x86/kernel/smp.c:sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reboot
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c37c2a)
Location: arch/x86/include/asm/irq_stack.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c37cba)
Location: arch/x86/include/asm/irq_stack.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
```
```
In arch/x86/kernel/kvm.c (ffffffff81c37e1a)
Location: arch/x86/include/asm/irq_stack.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
```
</details>
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
