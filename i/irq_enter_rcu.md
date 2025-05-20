# Function: <code>irq_enter_rcu</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void irq_enter_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810af83e)
Location: kernel/softirq.c:345
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
Direct callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
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
  - arch/x86/kernel/smp.c:sysvec_reboot
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
  - arch/x86/platform/uv/tlb_uv.c:sysvec_uv_bau_message
```
**Symbols:**

```
ffffffff810af7e0-ffffffff810af82a: irq_enter_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void irq_enter_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810aafce)
Location: kernel/softirq.c:378
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
Direct callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
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
  - arch/x86/kernel/smp.c:sysvec_reboot
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
```
**Symbols:**

```
ffffffff810aaf80-ffffffff810aafbe: irq_enter_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void irq_enter_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810ac1be)
Location: kernel/softirq.c:595
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
Direct callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
  - arch/x86/kernel/irq.c:sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
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
  - arch/x86/kernel/smp.c:sysvec_reboot
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
```
**Symbols:**

```
ffffffff810ac170-ffffffff810ac1ae: irq_enter_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void irq_enter_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810bd83e)
Location: kernel/softirq.c:594
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
Direct callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
  - arch/x86/kernel/irq.c:sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
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
  - arch/x86/kernel/smp.c:sysvec_reboot
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
```
**Symbols:**

```
ffffffff810bd7f0-ffffffff810bd82e: irq_enter_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void irq_enter_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810d496e)
Location: kernel/softirq.c:607
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
Direct callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
  - arch/x86/kernel/irq.c:sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
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
  - arch/x86/kernel/smp.c:sysvec_reboot
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
```
**Symbols:**

```
ffffffff810d4910-ffffffff810d495a: irq_enter_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void irq_enter_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810f38ce)
Location: kernel/softirq.c:607
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
Direct callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
  - arch/x86/kernel/irq.c:sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
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
  - arch/x86/kernel/smp.c:sysvec_reboot
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
```
**Symbols:**

```
ffffffff810f3860-ffffffff810f38aa: irq_enter_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void irq_enter_rcu();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810ffc1e)
Location: kernel/softirq.c:589
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
Direct callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
  - arch/x86/kernel/irq.c:sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
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
  - arch/x86/kernel/smp.c:sysvec_reboot
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
```
**Symbols:**

```
ffffffff810ffbb0-ffffffff810ffbfa: irq_enter_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void irq_enter_rcu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/softirq.c (0)
Location: kernel/softirq.c:589
Inline: False
Direct callers:
  - arch/x86/entry/common.c:xen_pv_evtchn_do_upcall
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
  - arch/x86/hyperv/hv_init.c:sysvec_hyperv_reenlightenment
  - arch/x86/kernel/irq.c:sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_wakeup_ipi
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
  - arch/x86/kernel/smp.c:sysvec_reboot
  - arch/x86/kernel/apic/apic.c:sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:spurious_interrupt
  - arch/x86/kernel/apic/apic.c:sysvec_apic_timer_interrupt
  - arch/x86/kernel/kvm.c:sysvec_kvm_asyncpf_interrupt
  - kernel/softirq.c:irq_enter
```
**Symbols:**

```
ffffffff821af1f7-ffffffff821af20b: irq_enter_rcu.cold (STB_LOCAL)
ffffffff811092c0-ffffffff8110934d: irq_enter_rcu (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
