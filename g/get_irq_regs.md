# Function: <code>get_irq_regs</code>

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
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:do_IRQ
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039967)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:irq_fpu_usable
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8104f46a)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81826f73)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81055b05)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_complete_move
```
```
In kernel/profile.c (ffffffff810ea935)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/tick-common.c (ffffffff810fc451)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff810fe501)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
```
In kernel/watchdog.c (ffffffff8113a994)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff81183abb)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/xen/events/events_base.c (ffffffff814c97da)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff814ca706)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/tty/sysrq.c (ffffffff814ed836)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/keyboard.c (ffffffff814f2055)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (ffffffff81515312)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81038959)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:irq_fpu_usable
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8104f5ba)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff818a19bc)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81055757)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In kernel/profile.c (ffffffff810f15e5)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/tick-common.c (ffffffff81103791)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81105891)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
```
In kernel/watchdog.c (ffffffff81142ec4)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff8118ab51)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/xen/events/events_base.c (ffffffff8151a30a)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff8151b266)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/tty/sysrq.c (ffffffff8153e4a6)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/keyboard.c (ffffffff81542c65)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (ffffffff8156749e)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810386c3)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81051dba)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff818d6f0c)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810586d7)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In kernel/profile.c (ffffffff810f8765)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/tick-common.c (ffffffff8110ae81)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8110d051)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
```
In kernel/watchdog.c (ffffffff8114cb72)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff8119a871)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/xen/events/events_base.c (ffffffff815467fa)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff81547738)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/tty/sysrq.c (ffffffff8156aaf6)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/keyboard.c (ffffffff8156f2a5)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (ffffffff81593bce)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
Location: arch/x86/include/asm/irq_regs.h:16
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
In arch/x86/kernel/fpu/core.c (ffffffff81036820)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810518ba)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8190e8ec)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810576bf)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In kernel/profile.c (ffffffff810fa795)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/tick-common.c (ffffffff8110cd81)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8110eeb1)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
```
In kernel/watchdog.c (ffffffff8114eaf2)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff811a3400)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/xen/events/events_base.c (ffffffff8155a61a)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff8155b4e9)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/tty/sysrq.c (ffffffff8157f126)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/keyboard.c (ffffffff81583825)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (ffffffff815a794e)
Location: arch/x86/include/asm/irq_regs.h:16
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81038bf1)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8105543a)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81a02d1c)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105ba7f)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In kernel/profile.c (ffffffff81105116)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/tick-common.c (ffffffff81118031)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8111a5a1)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
```
In kernel/watchdog.c (ffffffff8115b33c)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff811b73c6)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/xen/events/events_base.c (ffffffff815bea5a)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff815bf812)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/tty/sysrq.c (ffffffff815e3ca7)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/keyboard.c (ffffffff815e8326)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (ffffffff8160e24e)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
Location: arch/x86/include/asm/irq_regs.h:17
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
In arch/x86/kernel/fpu/core.c (ffffffff8103a3a1)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81a02155)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81a02445)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105f68a)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In kernel/profile.c (ffffffff8110fea5)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/tick-common.c (ffffffff81124b61)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81126ee5)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
```
In kernel/watchdog.c (ffffffff81169f51)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff811d6ace)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/xen/events/events_base.c (ffffffff815f7085)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff815f7c23)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/tty/sysrq.c (ffffffff8161cf57)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/keyboard.c (ffffffff81621575)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (ffffffff81647d1e)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
Location: arch/x86/include/asm/irq_regs.h:17
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
In arch/x86/kernel/fpu/core.c (ffffffff8103ba31)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c021f5)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c024e5)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810652fa)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In kernel/profile.c (ffffffff8111b4e5)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/tick-common.c (ffffffff81130261)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff811325d5)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
```
In kernel/debug/debug_core.c (ffffffff8116c395)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/watchdog.c (ffffffff81176e3a)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff811e7108)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/xen/events/events_base.c (ffffffff81612115)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff81612cce)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/tty/sysrq.c (ffffffff8163a1b7)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/keyboard.c (ffffffff8163ea55)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (ffffffff816661be)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
Location: arch/x86/include/asm/irq_regs.h:17
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
In arch/x86/kernel/fpu/core.c (ffffffff8103dd37)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c023c5)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c02445)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02735)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810689db)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In kernel/profile.c (ffffffff81125bc5)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/tick-common.c (ffffffff8113ad91)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8113d155)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
```
In kernel/debug/debug_core.c (ffffffff811791b5)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/watchdog.c (ffffffff81183ca5)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff811fe73a)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/xen/events/events_base.c (ffffffff81645ea5)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff81646b00)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/tty/sysrq.c (ffffffff8166e4e7)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/keyboard.c (ffffffff81672fa5)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (ffffffff8169beb0)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
Location: arch/x86/include/asm/irq_regs.h:17
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
In arch/x86/kernel/fpu/core.c (ffffffff8103e4f7)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c023f5)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c02475)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02765)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8106934b)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In kernel/profile.c (ffffffff81131b95)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/tick-common.c (ffffffff811469c1)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81148ce5)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
```
In kernel/debug/debug_core.c (ffffffff81185005)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/watchdog.c (ffffffff8118fb15)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff8120b8ca)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/xen/events/events_base.c (ffffffff81668425)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff81668fa0)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/tty/sysrq.c (ffffffff81690b27)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/keyboard.c (ffffffff81695725)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (ffffffff816bebe0)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In arch/x86/kernel/fpu/core.c (ffffffff810418ea)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In kernel/sched/cpuacct.c (ffffffff8110a925)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/profile.c (ffffffff81140fb5)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/tick-common.c (ffffffff81156881)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81158bc5)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
```
In kernel/debug/debug_core.c (ffffffff81198d1c)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/watchdog.c (ffffffff811a4744)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff812370a0)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/xen/events/events_2l.c (ffffffff81719070)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/tty/sysrq.c (ffffffff81743317)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/keyboard.c (ffffffff81748055)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (ffffffff817738a0)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In arch/x86/kernel/fpu/core.c (ffffffff810413cd)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:irq_fpu_usable
```
```
In kernel/sched/cpuacct.c (ffffffff81107835)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/profile.c (ffffffff8113d2e5)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/tick-common.c (ffffffff811529a1)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81154cc2)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
```
In kernel/debug/debug_core.c (ffffffff8119600c)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/watchdog.c (ffffffff811a17e4)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff81240ca0)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/xen/events/events_2l.c (ffffffff81c0502a)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/tty/sysrq.c (ffffffff8175f197)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/keyboard.c (ffffffff817639a5)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (ffffffff8178e860)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In arch/x86/kernel/fpu/core.c (ffffffff81042dcd)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:irq_fpu_usable
```
```
In kernel/sched/cpuacct.c (ffffffff81109905)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/profile.c (ffffffff8113e535)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/tick-common.c (ffffffff81153de1)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81156292)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
```
In kernel/debug/debug_core.c (ffffffff81196fdc)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/watchdog.c (ffffffff811a23e5)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff81244a50)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/xen/events/events_2l.c (ffffffff81bf6cb0)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/tty/sysrq.c (ffffffff81743007)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/keyboard.c (ffffffff81747615)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (ffffffff817714db)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In arch/x86/kernel/fpu/core.c (ffffffff8104913d)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:irq_fpu_usable
```
```
In kernel/profile.c (ffffffff811619c5)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/tick-common.c (ffffffff811784d1)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8117af42)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
```
In kernel/debug/debug_core.c (ffffffff811c0863)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/watchdog.c (ffffffff811cbbc5)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff8127f9f0)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/xen/events/events_2l.c (ffffffff8179855a)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/tty/sysrq.c (ffffffff817c3a37)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/keyboard.c (ffffffff817c8675)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (ffffffff817f708b)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In kernel/profile.c (ffffffff811947e5)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/tick-common.c (ffffffff811ad691)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff811aff11)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
```
In kernel/debug/debug_core.c (ffffffff811f3d73)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/watchdog.c (ffffffff811ff955)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff812d4a45)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/xen/events/events_2l.c (ffffffff818d168e)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/tty/sysrq.c (ffffffff81900657)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/keyboard.c (ffffffff81905985)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (ffffffff81933dc9)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In kernel/sched/core.c (ffffffff81142542)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/sched/core.c:dump_cpu_task
```
```
In kernel/profile.c (ffffffff811d2315)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/tick-common.c (ffffffff811edc31)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff811f0991)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
```
In kernel/debug/debug_core.c (ffffffff8123abb3)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/watchdog.c (ffffffff81247375)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff8133d004)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/xen/events/events_2l.c (ffffffff81a2301d)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/tty/sysrq.c (ffffffff81a5a207)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/keyboard.c (ffffffff81a5fd55)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (ffffffff81a92b79)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In kernel/sched/core.c (ffffffff8114e255)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/sched/core.c:dump_cpu_task
```
```
In kernel/profile.c (ffffffff811e6605)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/tick-common.c (ffffffff81202361)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff812053a1)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
```
In kernel/debug/debug_core.c (ffffffff81251bc3)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/watchdog.c (ffffffff8125e425)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff8136e17d)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/xen/events/events_2l.c (ffffffff81a6c3df)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/tty/sysrq.c (ffffffff81aa4837)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/keyboard.c (ffffffff81aaa415)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (ffffffff81ade3f9)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In kernel/sched/core.c (ffffffff8115a095)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/sched/core.c:dump_cpu_task
```
```
In kernel/profile.c (ffffffff811fc355)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/tick-common.c (ffffffff81218851)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8121baa1)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_highres_handler
  - kernel/time/tick-sched.c:tick_nohz_lowres_handler
```
```
In kernel/debug/debug_core.c (ffffffff8126ba13)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/watchdog.c (ffffffff81278365)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff813972ad)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/xen/events/events_2l.c (ffffffff81abe49f)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/tty/sysrq.c (ffffffff81af7237)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/keyboard.c (ffffffff81afce75)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (ffffffff81b31819)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In arch/arm64/kernel/perf_event.c (ffff8000100a48a8)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - arch/arm64/kernel/perf_event.c:armv8pmu_handle_irq
```
```
In kernel/profile.c (ffff800010199668)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/tick-common.c (ffff8000101b1858)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffff8000101b4f94)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
```
In kernel/debug/debug_core.c (ffff8000101fac0c)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/watchdog.c (ffff8000102072b0)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffff80001029aa60)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/xen/events/events_2l.c (ffff800010833208)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/tty/sysrq.c (ffff800010864088)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
```
In drivers/tty/vt/keyboard.c (ffff800010869c58)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (ffff8000108b06ac)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In arch/arm/kernel/machine_kexec.c (c03150b0)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - arch/arm/kernel/machine_kexec.c:machine_crash_nonpanic_core
```
```
In arch/arm/kernel/perf_event_v7.c (c03187c0)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - arch/arm/kernel/perf_event_v7.c:armv7pmu_handle_irq
```
```
In kernel/profile.c (c03e40fc)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/tick-common.c (c03fbf14)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (c03feb74)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
```
In kernel/debug/debug_core.c (c043ad08)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/watchdog.c (c044601c)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (c04c502c)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/tty/sysrq.c (c096965c)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/keyboard.c (c096eeac)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (c09ab04c)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In arch/powerpc/kernel/watchdog.c (c000000000037040)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
```
```
In arch/powerpc/kernel/smp.c (c000000000055438)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:smp_ipi_demux_relaxed
```
```
In arch/powerpc/xmon/xmon.c (c000000000111454)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:xmon_irq
```
```
In kernel/profile.c (c0000000001f95b8)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/tick-common.c (c0000000002166bc)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (c00000000021a6e8)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
```
In kernel/debug/debug_core.c (c000000000272750)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/watchdog.c (c000000000283854)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (c000000000342ab4)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/tty/sysrq.c (c00000000090294c)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/keyboard.c (c000000000909df0)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (c00000000094740c)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/profile.c (ffffffe000129d14)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/tick-common.c (ffffffe00013a0f0)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffe00013b352)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
```
In kernel/watchdog.c (ffffffe0001699da)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffe0001c6844)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/tty/sysrq.c (ffffffe00053a396)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
```
In drivers/tty/vt/keyboard.c (ffffffe00053ea60)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (ffffffe0005632f8)
Location: include/asm-generic/irq_regs.h:19
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
Location: arch/x86/include/asm/irq_regs.h:17
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
In arch/x86/kernel/fpu/core.c (ffffffff8103e677)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c023d5)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c02455)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02745)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81068e3b)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In kernel/profile.c (ffffffff8112a345)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/tick-common.c (ffffffff8113f1a1)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81141305)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
```
In kernel/debug/debug_core.c (ffffffff8117d625)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/watchdog.c (ffffffff81188135)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff81203eea)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/xen/events/events_base.c (ffffffff8162e155)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff8162ee10)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/tty/sysrq.c (ffffffff816565a7)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/keyboard.c (ffffffff8165b185)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (ffffffff81684650)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
Location: arch/x86/include/asm/irq_regs.h:17
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
In arch/x86/kernel/fpu/core.c (ffffffff8102de77)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c02285)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c02305)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c025f5)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810591ab)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In kernel/profile.c (ffffffff8111cbb5)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/tick-common.c (ffffffff81131c71)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff81134185)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
```
In kernel/debug/debug_core.c (ffffffff81170775)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/watchdog.c (ffffffff8117b275)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff811f6c7a)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/tty/sysrq.c (ffffffff81636937)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/keyboard.c (ffffffff8163b505)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (ffffffff816622d0)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
Location: arch/x86/include/asm/irq_regs.h:17
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
In arch/x86/kernel/fpu/core.c (ffffffff8103e4b7)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c023b5)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c026b5)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810692eb)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In kernel/profile.c (ffffffff81128065)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/tick-common.c (ffffffff8113ce91)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8113f1b5)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
```
In kernel/debug/debug_core.c (ffffffff8117b3f5)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/watchdog.c (ffffffff81185f05)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff81201cba)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/xen/events/events_base.c (ffffffff8165c265)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff8165cde0)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/tty/sysrq.c (ffffffff81684967)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/keyboard.c (ffffffff81689565)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (ffffffff816b2a20)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
Location: arch/x86/include/asm/irq_regs.h:17
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
In arch/x86/kernel/fpu/core.c (ffffffff8103f64e)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81c02505)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hv_stimer0_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
  - arch/x86/kernel/cpu/mshyperv.c:hyperv_vector_handler
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c02585)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02905)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8106a9eb)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
```
In kernel/profile.c (ffffffff811346f5)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/profile.c:profile_tick
```
```
In kernel/time/tick-common.c (ffffffff81149981)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_periodic
```
```
In kernel/time/tick-sched.c (ffffffff8114bc15)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
```
```
In kernel/debug/debug_core.c (ffffffff81188d15)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/watchdog.c (ffffffff81193855)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff8121138a)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/xen/events/events_base.c (ffffffff81676855)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
  - drivers/xen/events/events_base.c:xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff816773f0)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/tty/sysrq.c (ffffffff8169ef77)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/keyboard.c (ffffffff816a3bc5)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
```
In drivers/char/random.c (ffffffff816ccf70)
Location: arch/x86/include/asm/irq_regs.h:17
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
</details>
</li>
</ul>

## Differences
