# Function: <code>HYPERVISOR_sched_op</code>

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
In arch/x86/xen/enlighten.c (ffffffff8101c585)
Location: arch/x86/include/asm/xen/hypercall.h:292
Inline: True
```
```
In arch/x86/xen/irq.c (ffffffff81023370)
Location: arch/x86/include/asm/xen/hypercall.h:292
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff8102b5fd)
Location: arch/x86/include/asm/xen/hypercall.h:292
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/events/events_base.c (ffffffff814c87ab)
Location: arch/x86/include/asm/xen/hypercall.h:292
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff814fece0)
Location: arch/x86/include/asm/xen/hypercall.h:292
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In arch/x86/xen/enlighten.c (ffffffff8101b815)
Location: arch/x86/include/asm/xen/hypercall.h:293
Inline: True
```
```
In arch/x86/xen/irq.c (ffffffff810226f1)
Location: arch/x86/include/asm/xen/hypercall.h:293
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff8102aab3)
Location: arch/x86/include/asm/xen/hypercall.h:293
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/events/events_base.c (ffffffff815192eb)
Location: arch/x86/include/asm/xen/hypercall.h:293
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8154fb2d)
Location: arch/x86/include/asm/xen/hypercall.h:293
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In arch/x86/xen/enlighten.c (ffffffff8101ba6c)
Location: arch/x86/include/asm/xen/hypercall.h:293
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_pin_vcpu
```
```
In arch/x86/xen/irq.c (ffffffff81022e41)
Location: arch/x86/include/asm/xen/hypercall.h:293
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff8102ac43)
Location: arch/x86/include/asm/xen/hypercall.h:293
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In drivers/xen/events/events_base.c (ffffffff815457bb)
Location: arch/x86/include/asm/xen/hypercall.h:293
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8157c3ad)
Location: arch/x86/include/asm/xen/hypercall.h:293
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In arch/x86/xen/enlighten.c (ffffffff81019dba)
Location: arch/x86/include/asm/xen/hypercall.h:298
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_pin_vcpu
```
```
In arch/x86/xen/irq.c (ffffffff8101ab21)
Location: arch/x86/include/asm/xen/hypercall.h:298
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff81028e9e)
Location: arch/x86/include/asm/xen/hypercall.h:298
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
```
In arch/x86/xen/smp_pv.c (ffffffff810294fd)
Location: arch/x86/include/asm/xen/hypercall.h:298
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/events/events_base.c (ffffffff8155963b)
Location: arch/x86/include/asm/xen/hypercall.h:298
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81590640)
Location: arch/x86/include/asm/xen/hypercall.h:298
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In arch/x86/xen/enlighten.c (ffffffff8101a64a)
Location: arch/x86/include/asm/xen/hypercall.h:298
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_pin_vcpu
```
```
In arch/x86/xen/irq.c (ffffffff8101b421)
Location: arch/x86/include/asm/xen/hypercall.h:298
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff810290a4)
Location: arch/x86/include/asm/xen/hypercall.h:298
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102971d)
Location: arch/x86/include/asm/xen/hypercall.h:298
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/events/events_base.c (ffffffff815bda8b)
Location: arch/x86/include/asm/xen/hypercall.h:298
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f5230)
Location: arch/x86/include/asm/xen/hypercall.h:298
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In arch/x86/xen/enlighten.c (ffffffff8101b00a)
Location: arch/x86/include/asm/xen/hypercall.h:298
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_pin_vcpu
```
```
In arch/x86/xen/irq.c (ffffffff8101be20)
Location: arch/x86/include/asm/xen/hypercall.h:298
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff81029b04)
Location: arch/x86/include/asm/xen/hypercall.h:298
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a3d1)
Location: arch/x86/include/asm/xen/hypercall.h:298
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/events/events_base.c (ffffffff815f6118)
Location: arch/x86/include/asm/xen/hypercall.h:298
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162e146)
Location: arch/x86/include/asm/xen/hypercall.h:298
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In arch/x86/xen/enlighten.c (ffffffff8101b7da)
Location: arch/x86/include/asm/xen/hypercall.h:265
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_pin_vcpu
```
```
In arch/x86/xen/irq.c (ffffffff81026040)
Location: arch/x86/include/asm/xen/hypercall.h:265
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff8102a0e4)
Location: arch/x86/include/asm/xen/hypercall.h:265
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102aab4)
Location: arch/x86/include/asm/xen/hypercall.h:265
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In drivers/xen/events/events_base.c (ffffffff816111d8)
Location: arch/x86/include/asm/xen/hypercall.h:265
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164c546)
Location: arch/x86/include/asm/xen/hypercall.h:265
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In arch/x86/xen/enlighten.c (ffffffff8101d30b)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_pin_vcpu
```
```
In arch/x86/xen/irq.c (ffffffff81027d60)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff8102bea8)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102c60a)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff81644f38)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81680baf)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In arch/x86/xen/enlighten.c (ffffffff8101dcab)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_pin_vcpu
```
```
In arch/x86/xen/irq.c (ffffffff81028670)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff8102c788)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ceda)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff816674e8)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816a325f)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In arch/x86/xen/enlighten.c (ffffffff8102009b)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_pin_vcpu
```
```
In arch/x86/xen/irq.c (ffffffff8102a5d0)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff8102e770)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102f2bc)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff81718853)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_poll_irq
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81756165)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In arch/x86/xen/enlighten.c (ffffffff81020b3b)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_pin_vcpu
```
```
In arch/x86/xen/irq.c (ffffffff8102aef0)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff8102f5d0)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
```
In arch/x86/xen/smp_pv.c (ffffffff810300cc)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff81735ec8)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_poll_irq
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817713d5)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In arch/x86/xen/enlighten.c (ffffffff81022edb)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_pin_vcpu
```
```
In arch/x86/xen/irq.c (ffffffff8102bad0)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff810300ec)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
```
In arch/x86/xen/smp_pv.c (ffffffff81030bfa)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff817196f8)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_poll_irq
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81754dd5)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In arch/x86/xen/enlighten.c (ffffffff8102703b)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_pin_vcpu
  - arch/x86/xen/enlighten.c:xen_reboot
```
```
In arch/x86/xen/irq.c (ffffffff81030220)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff81034f1c)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
```
In arch/x86/xen/smp_pv.c (ffffffff81035b44)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff8179760e)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_poll_irq
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817d8378)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In arch/x86/xen/enlighten.c (ffffffff8102b203)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_pin_vcpu
  - arch/x86/xen/enlighten.c:xen_reboot
```
```
In arch/x86/xen/irq.c (ffffffff8103588b)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_halt
```
```
In arch/x86/xen/smp.c (ffffffff8103ac56)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103b965)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff818d065a)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_poll_irq
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8191690d)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In arch/x86/xen/enlighten.c (ffffffff81031ef3)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_pin_vcpu
  - arch/x86/xen/enlighten.c:xen_reboot
```
```
In arch/x86/xen/irq.c (ffffffff8103d51d)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_halt
```
```
In arch/x86/xen/smp.c (ffffffff8104332e)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
```
In arch/x86/xen/smp_pv.c (ffffffff81044145)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff81a21e4a)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_poll_irq
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81a713f2)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In arch/x86/xen/enlighten.c (ffffffff81031ef3)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_pin_vcpu
  - arch/x86/xen/enlighten.c:xen_reboot
```
```
In arch/x86/xen/irq.c (ffffffff82139f60)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_safe_halt
```
```
In arch/x86/xen/smp.c (ffffffff8104352e)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043965)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_poll_sync_state
```
```
In drivers/xen/events/events_base.c (ffffffff81a6b1da)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_poll_irq
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81abbc25)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In arch/x86/xen/enlighten.c (ffffffff810381e3)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_pin_vcpu
  - arch/x86/xen/enlighten.c:xen_reboot
```
```
In arch/x86/xen/irq.c (ffffffff8221bed0)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_safe_halt
```
```
In arch/x86/xen/smp.c (ffffffff81049a2e)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
```
In arch/x86/xen/smp_pv.c (ffffffff81049e65)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_poll_sync_state
```
```
In drivers/xen/events/events_base.c (ffffffff81abd2aa)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_poll_irq
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0e970)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_poll_irq_timeout
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
```
**Symbols:**

```
ffff8000100f0d14-ffff8000100f0d20: HYPERVISOR_sched_op (STB_GLOBAL)
```
</details>
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
In arch/x86/xen/enlighten.c (ffffffff8101dcab)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_pin_vcpu
```
```
In arch/x86/xen/irq.c (ffffffff810287d0)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff8102c8e8)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102d03a)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff8162d218)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81668cbf)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101dc6b)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_pin_vcpu
```
```
In arch/x86/xen/irq.c (ffffffff81028630)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff8102c748)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ce9a)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff8165b328)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8169709f)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
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
In arch/x86/xen/enlighten.c (ffffffff8101debb)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_pin_vcpu
```
```
In arch/x86/xen/irq.c (ffffffff810292c0)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff8102d538)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102dc8a)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff81675918)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816b164f)
Location: arch/x86/include/asm/xen/hypercall.h:284
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
```
</details>
</li>
</ul>

## Differences
