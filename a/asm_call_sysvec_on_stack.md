# Function: <code>asm_call_sysvec_on_stack</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_x86_platform_ipi
  - arch/x86/kernel/irq_work.c:sysvec_irq_work
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold
  - arch/x86/kernel/cpu/mce/therm_throt.c:sysvec_thermal
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback
  - arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback
  - arch/x86/kernel/smp.c:sysvec_call_function_single
  - arch/x86/kernel/smp.c:sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reboot
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
  - arch/x86/platform/uv/tlb_uv.c:sysvec_uv_bau_message
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_x86_platform_ipi
  - arch/x86/kernel/irq_work.c:sysvec_irq_work
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/threshold.c:sysvec_threshold
  - arch/x86/kernel/cpu/mce/therm_throt.c:sysvec_thermal
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:sysvec_hyperv_callback
  - arch/x86/kernel/cpu/acrn.c:sysvec_acrn_hv_callback
  - arch/x86/kernel/smp.c:sysvec_call_function_single
  - arch/x86/kernel/smp.c:sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reboot
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
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
