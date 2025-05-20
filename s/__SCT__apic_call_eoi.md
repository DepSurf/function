# Function: <code>__SCT__apic_call_eoi</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:__sysvec_xen_hvm_callback
  - arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:__sysvec_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__common_interrupt
  - arch/x86/kernel/irq.c:__common_interrupt
  - arch/x86/kernel/irq.c:ack_bad_irq
  - arch/x86/kernel/irq.c:ack_bad_irq
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_stimer0
  - arch/x86/kernel/cpu/mshyperv.c:__sysvec_hyperv_callback
  - arch/x86/kernel/cpu/acrn.c:__sysvec_acrn_hv_callback
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:__sysvec_reboot
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/io_apic.c:ack_lapic_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt
```
**Symbols:**

```
ffffffff8223e9e0-ffffffff8223e9e8: __SCT__apic_call_eoi (STB_GLOBAL)
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
