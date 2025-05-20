# Function: <code>irq_enter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81085ba0)
Location: kernel/softirq.c:325
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_irq_work_interrupt
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - kernel/sched/core.c:scheduler_ipi
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
**Symbols:**

```
ffffffff81085ba0-ffffffff81085bf3: irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810889f0)
Location: kernel/softirq.c:325
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_irq_work_interrupt
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - kernel/sched/core.c:scheduler_ipi
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
**Symbols:**

```
ffffffff810889f0-ffffffff81088a43: irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8108d940)
Location: kernel/softirq.c:336
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_irq_work_interrupt
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - kernel/sched/core.c:scheduler_ipi
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
**Symbols:**

```
ffffffff8108d940-ffffffff8108d98f: irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8108a970)
Location: kernel/softirq.c:336
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq_work.c:smp_trace_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_trace_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_trace_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_trace_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/smp.c:smp_trace_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_trace_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_trace_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - kernel/sched/core.c:scheduler_ipi
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
**Symbols:**

```
ffffffff8108a970-ffffffff8108a9bf: irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81091640)
Location: kernel/softirq.c:337
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - kernel/sched/core.c:scheduler_ipi
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
**Symbols:**

```
ffffffff81091640-ffffffff8109168f: irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81095110)
Location: kernel/softirq.c:344
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:smp_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/threshold.c:smp_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:smp_thermal_interrupt
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - kernel/sched/core.c:scheduler_ipi
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
**Symbols:**

```
ffffffff81095110-ffffffff8109515f: irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8109d480)
Location: kernel/softirq.c:345
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - kernel/sched/core.c:scheduler_ipi
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
**Symbols:**

```
ffffffff8109d480-ffffffff8109d4cf: irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a1a60)
Location: kernel/softirq.c:345
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_call_function_single_interrupt
  - arch/x86/xen/smp.c:xen_call_function_interrupt
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - kernel/sched/core.c:scheduler_ipi
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
**Symbols:**

```
ffffffff810a1a60-ffffffff810a1aaf: irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a8020)
Location: kernel/softirq.c:345
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_call_function_single_interrupt
  - arch/x86/xen/smp.c:xen_call_function_interrupt
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - kernel/sched/core.c:scheduler_ipi
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
**Symbols:**

```
ffffffff810a8020-ffffffff810a806f: irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810af830)
Location: kernel/softirq.c:362
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
**Symbols:**

```
ffffffff810af830-ffffffff810af87f: irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810aafc0)
Location: kernel/softirq.c:391
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
**Symbols:**

```
ffffffff810aafc0-ffffffff810ab004: irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810ac1b0)
Location: kernel/softirq.c:608
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
**Symbols:**

```
ffffffff810ac1b0-ffffffff810ac1f4: irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810bd830)
Location: kernel/softirq.c:607
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
**Symbols:**

```
ffffffff810bd830-ffffffff810bd874: irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810d4960)
Location: kernel/softirq.c:621
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
**Symbols:**

```
ffffffff810d4960-ffffffff810d49b0: irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810f38c0)
Location: kernel/softirq.c:621
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
**Symbols:**

```
ffffffff810f38c0-ffffffff810f3910: irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810ffc10)
Location: kernel/softirq.c:603
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
**Symbols:**

```
ffffffff810ffc10-ffffffff810ffc60: irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81109360)
Location: kernel/softirq.c:603
Inline: False
```
**Symbols:**

```
ffffffff81109360-ffffffff81109379: irq_enter (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffff8000100ff0f0)
Location: kernel/softirq.c:345
Inline: False
Direct callers:
  - arch/arm64/kernel/smp.c:handle_IPI
  - arch/arm64/kernel/smp.c:handle_IPI
  - arch/arm64/kernel/smp.c:handle_IPI
  - arch/arm64/kernel/smp.c:handle_IPI
  - arch/arm64/kernel/smp.c:handle_IPI
  - kernel/sched/core.c:scheduler_ipi
  - kernel/irq/irqdesc.c:__handle_domain_irq
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
**Symbols:**

```
ffff8000100ff0f0-ffff8000100ff160: irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (c035bde4)
Location: kernel/softirq.c:345
Inline: False
Direct callers:
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/smp.c:handle_IPI
  - kernel/sched/core.c:scheduler_ipi
  - kernel/irq/irqdesc.c:__handle_domain_irq
```
**Symbols:**

```
c035bde4-c035be64: irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (c0000000001463d0)
Location: kernel/softirq.c:345
Inline: False
Direct callers:
  - arch/powerpc/kernel/irq.c:__do_irq
  - arch/powerpc/kernel/time.c:timer_interrupt
  - arch/powerpc/kernel/traps.c:handle_hmi_exception
  - arch/powerpc/kernel/dbell.c:doorbell_exception
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_handle_events
  - arch/powerpc/perf/core-book3s.c:perf_event_interrupt
  - kernel/sched/core.c:scheduler_ipi
```
**Symbols:**

```
c0000000001463d0-c000000000146468: irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffe0000c7008)
Location: kernel/softirq.c:345
Inline: False
Direct callers:
  - arch/riscv/kernel/irq.c:do_IRQ
  - kernel/sched/core.c:scheduler_ipi
```
**Symbols:**

```
ffffffe0000c7008-ffffffe0000c7080: irq_enter (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a1940)
Location: kernel/softirq.c:345
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_call_function_single_interrupt
  - arch/x86/xen/smp.c:xen_call_function_interrupt
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - kernel/sched/core.c:scheduler_ipi
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
**Symbols:**

```
ffffffff810a1940-ffffffff810a198f: irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81090300)
Location: kernel/softirq.c:345
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - kernel/sched/core.c:scheduler_ipi
```
**Symbols:**

```
ffffffff81090300-ffffffff8109034f: irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a18f0)
Location: kernel/softirq.c:345
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_call_function_single_interrupt
  - arch/x86/xen/smp.c:xen_call_function_interrupt
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - kernel/sched/core.c:scheduler_ipi
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
**Symbols:**

```
ffffffff810a18f0-ffffffff810a193f: irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a98e0)
Location: kernel/softirq.c:345
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_call_function_single_interrupt
  - arch/x86/xen/smp.c:xen_call_function_interrupt
  - arch/x86/xen/smp_pv.c:xen_irq_work_interrupt
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - kernel/sched/core.c:scheduler_ipi
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
**Symbols:**

```
ffffffff810a98e0-ffffffff810a992f: irq_enter (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
