# Function: <code>irq_needs_irq_stack</code>

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
In arch/x86/entry/common.c (ffffffff81bbc923)
Location: arch/x86/include/asm/irq_stack.h:62
Inline: True
Inline callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff81bbca0e)
Location: arch/x86/include/asm/irq_stack.h:62
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81bbcace)
Location: arch/x86/include/asm/irq_stack.h:62
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/irq.c (ffffffff81bbdbde)
Location: arch/x86/include/asm/irq_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:common_interrupt
```
```
In arch/x86/kernel/irq_64.c (ffffffff81036ca5)
Location: arch/x86/include/asm/irq_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:do_softirq_own_stack
```
```
In arch/x86/kernel/irq_work.c (ffffffff81bbdfee)
Location: arch/x86/include/asm/irq_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:sysvec_irq_work
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81bbebae)
Location: arch/x86/include/asm/irq_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81bbec3e)
Location: arch/x86/include/asm/irq_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81bbecce)
Location: arch/x86/include/asm/irq_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:sysvec_thermal
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81bbedee)
Location: arch/x86/include/asm/irq_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81bbee7e)
Location: arch/x86/include/asm/irq_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/smp.c (ffffffff81bbf13e)
Location: arch/x86/include/asm/irq_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_call_function_single
  - arch/x86/kernel/smp.c:sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reboot
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81bbf41e)
Location: arch/x86/include/asm/irq_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81bbf4ae)
Location: arch/x86/include/asm/irq_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81bbf79e)
Location: arch/x86/include/asm/irq_stack.h:62
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
In arch/x86/entry/common.c (ffffffff81c34ec4)
Location: arch/x86/include/asm/irq_stack.h:61
Inline: True
Inline callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff81c34f90)
Location: arch/x86/include/asm/irq_stack.h:61
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81c35060)
Location: arch/x86/include/asm/irq_stack.h:61
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/irq.c (ffffffff81c36330)
Location: arch/x86/include/asm/irq_stack.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:common_interrupt
```
```
In arch/x86/kernel/irq_64.c (ffffffff81037e75)
Location: arch/x86/include/asm/irq_stack.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:do_softirq_own_stack
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c36890)
Location: arch/x86/include/asm/irq_stack.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:sysvec_irq_work
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c373b0)
Location: arch/x86/include/asm/irq_stack.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c37440)
Location: arch/x86/include/asm/irq_stack.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c374d0)
Location: arch/x86/include/asm/irq_stack.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:sysvec_thermal
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c375f0)
Location: arch/x86/include/asm/irq_stack.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c37680)
Location: arch/x86/include/asm/irq_stack.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback
```
```
In arch/x86/kernel/smp.c (ffffffff81c37920)
Location: arch/x86/include/asm/irq_stack.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_call_function_single
  - arch/x86/kernel/smp.c:sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reboot
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c37bf0)
Location: arch/x86/include/asm/irq_stack.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c37c80)
Location: arch/x86/include/asm/irq_stack.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
```
```
In arch/x86/kernel/kvm.c (ffffffff81c37de0)
Location: arch/x86/include/asm/irq_stack.h:61
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
