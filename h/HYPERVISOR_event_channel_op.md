# Function: <code>HYPERVISOR_event_channel_op</code>

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
In drivers/xen/events/events_base.c (ffffffff814c7a00)
Location: arch/x86/include/asm/xen/hypercall.h:365
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:notify_remote_via_irq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
```
```
In drivers/xen/events/events_2l.c (ffffffff814ca30a)
Location: arch/x86/include/asm/xen/hypercall.h:365
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff814cab50)
Location: arch/x86/include/asm/xen/hypercall.h:365
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff814cb3b1)
Location: arch/x86/include/asm/xen/hypercall.h:365
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff814ccac3)
Location: arch/x86/include/asm/xen/hypercall.h:365
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81fa4ce7)
Location: arch/x86/include/asm/xen/hypercall.h:365
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff814d0d4c)
Location: arch/x86/include/asm/xen/hypercall.h:365
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff814feaa0)
Location: arch/x86/include/asm/xen/hypercall.h:365
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
In drivers/xen/events/events_base.c (ffffffff8151a5e7)
Location: arch/x86/include/asm/xen/hypercall.h:366
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:notify_remote_via_irq
```
```
In drivers/xen/events/events_2l.c (ffffffff8151ae76)
Location: arch/x86/include/asm/xen/hypercall.h:366
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff8151b699)
Location: arch/x86/include/asm/xen/hypercall.h:366
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8151bfa1)
Location: arch/x86/include/asm/xen/hypercall.h:366
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8151d972)
Location: arch/x86/include/asm/xen/hypercall.h:366
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81fd12b1)
Location: arch/x86/include/asm/xen/hypercall.h:366
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81521a8b)
Location: arch/x86/include/asm/xen/hypercall.h:366
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8154f621)
Location: arch/x86/include/asm/xen/hypercall.h:366
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
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
In drivers/xen/events/events_base.c (ffffffff81546ad9)
Location: arch/x86/include/asm/xen/hypercall.h:366
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:notify_remote_via_irq
```
```
In drivers/xen/events/events_2l.c (ffffffff81547346)
Location: arch/x86/include/asm/xen/hypercall.h:366
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff81547b89)
Location: arch/x86/include/asm/xen/hypercall.h:366
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81548471)
Location: arch/x86/include/asm/xen/hypercall.h:366
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81549e02)
Location: arch/x86/include/asm/xen/hypercall.h:366
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8200ec41)
Location: arch/x86/include/asm/xen/hypercall.h:366
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8154df5b)
Location: arch/x86/include/asm/xen/hypercall.h:366
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8157bea1)
Location: arch/x86/include/asm/xen/hypercall.h:366
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
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
In drivers/xen/events/events_base.c (ffffffff8155a896)
Location: arch/x86/include/asm/xen/hypercall.h:371
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:notify_remote_via_irq
```
```
In drivers/xen/events/events_2l.c (ffffffff8155b118)
Location: arch/x86/include/asm/xen/hypercall.h:371
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff8155b939)
Location: arch/x86/include/asm/xen/hypercall.h:371
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8155c091)
Location: arch/x86/include/asm/xen/hypercall.h:371
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8155dcef)
Location: arch/x86/include/asm/xen/hypercall.h:371
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff820f0709)
Location: arch/x86/include/asm/xen/hypercall.h:371
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff815623da)
Location: arch/x86/include/asm/xen/hypercall.h:371
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8159010f)
Location: arch/x86/include/asm/xen/hypercall.h:371
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
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
In drivers/xen/events/events_base.c (ffffffff815becf0)
Location: arch/x86/include/asm/xen/hypercall.h:371
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:notify_remote_via_irq
```
```
In drivers/xen/events/events_2l.c (ffffffff815bf448)
Location: arch/x86/include/asm/xen/hypercall.h:371
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff815bfc59)
Location: arch/x86/include/asm/xen/hypercall.h:371
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815c03a1)
Location: arch/x86/include/asm/xen/hypercall.h:371
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff815c2002)
Location: arch/x86/include/asm/xen/hypercall.h:371
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff826f9f13)
Location: arch/x86/include/asm/xen/hypercall.h:371
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff815c66da)
Location: arch/x86/include/asm/xen/hypercall.h:371
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f4c0f)
Location: arch/x86/include/asm/xen/hypercall.h:371
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
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
In drivers/xen/events/events_base.c (ffffffff815f7334)
Location: arch/x86/include/asm/xen/hypercall.h:371
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:notify_remote_via_irq
```
```
In drivers/xen/events/events_2l.c (ffffffff815f7b28)
Location: arch/x86/include/asm/xen/hypercall.h:371
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff815f8341)
Location: arch/x86/include/asm/xen/hypercall.h:371
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815f8a4f)
Location: arch/x86/include/asm/xen/hypercall.h:371
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff815fa7dd)
Location: arch/x86/include/asm/xen/hypercall.h:371
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8272429d)
Location: arch/x86/include/asm/xen/hypercall.h:371
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff815feebf)
Location: arch/x86/include/asm/xen/hypercall.h:371
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162e28b)
Location: arch/x86/include/asm/xen/hypercall.h:371
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
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
In drivers/xen/events/events_base.c (ffffffff816123d4)
Location: arch/x86/include/asm/xen/hypercall.h:338
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:notify_remote_via_irq
```
```
In drivers/xen/events/events_2l.c (ffffffff81612c03)
Location: arch/x86/include/asm/xen/hypercall.h:338
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff8161369f)
Location: arch/x86/include/asm/xen/hypercall.h:338
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81613aff)
Location: arch/x86/include/asm/xen/hypercall.h:338
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8161588d)
Location: arch/x86/include/asm/xen/hypercall.h:338
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828dc476)
Location: arch/x86/include/asm/xen/hypercall.h:338
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81619f8f)
Location: arch/x86/include/asm/xen/hypercall.h:338
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164c3bb)
Location: arch/x86/include/asm/xen/hypercall.h:338
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
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
In drivers/xen/events/events_base.c (ffffffff81646160)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
```
```
In drivers/xen/events/events_2l.c (ffffffff81646a28)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff8164724d)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81647869)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81649432)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828f6d65)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8164dd5f)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81680ca8)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
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
In drivers/xen/events/events_base.c (ffffffff816686e0)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
```
```
In drivers/xen/events/events_2l.c (ffffffff81668ec8)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff816696ed)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81669d09)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8166b8d3)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828ffdbc)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8167023f)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816a3358)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
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
In drivers/xen/events/events_base.c (ffffffff8171697a)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:restore_cpu_ipis
  - drivers/xen/events/events_base.c:restore_cpu_virqs
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
```
```
In drivers/xen/events/events_2l.c (ffffffff81718f98)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff81719c3e)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81719e19)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8171b41b)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff82d170b8)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenstored_local_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81720755)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_alloc
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81755fd8)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
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
In drivers/xen/events/events_base.c (ffffffff8173451a)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:restore_cpu_ipis
  - drivers/xen/events/events_base.c:restore_cpu_virqs
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
```
In drivers/xen/events/events_2l.c (ffffffff81736508)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff81736a17)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81736f19)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8173848b)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83004c98)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenstored_local_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8173d6b5)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_alloc
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81771248)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
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
In drivers/xen/events/events_base.c (ffffffff817198b0)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq_lateeoi
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
```
In drivers/xen/events/events_2l.c (ffffffff81719f48)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff8171a500)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171a94b)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8171c468)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:process_writes
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8320f7fa)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8172126f)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81754c48)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
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
In drivers/xen/events/events_base.c (ffffffff817977f1)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq_lateeoi
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
```
```
In drivers/xen/events/events_2l.c (ffffffff817983a8)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff81798c2f)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff817991ab)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8179b1d8)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:process_writes
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff832f87a1)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff817a008f)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817d85f2)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
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
In drivers/xen/events/events_base.c (ffffffff818d085f)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq_lateeoi
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
```
```
In drivers/xen/events/events_2l.c (ffffffff818d1109)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff818d19bd)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff818d26aa)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff818d408c)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff834b1032)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff818d9b57)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81916b7c)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
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
In drivers/xen/events/events_base.c (ffffffff81a2205c)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq_lateeoi
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
```
```
In drivers/xen/events/events_2l.c (ffffffff81a22a1d)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a2379f)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a2468a)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81a2631c)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83eeaf3a)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81a2c647)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81a71516)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
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
In drivers/xen/events/events_base.c (ffffffff81a6b3f3)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq_lateeoi
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
```
```
In drivers/xen/events/events_2l.c (ffffffff81a6bdad)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a6cc52)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a6dbca)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81a6f8fb)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8371094a)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81a75df7)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81abbd88)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
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
In drivers/xen/events/events_base.c (ffffffff81abd4c7)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq_lateeoi
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:notify_remote_via_irq
```
```
In drivers/xen/events/events_2l.c (ffffffff81abde4d)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff81abed0a)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81abfc6a)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81ac19fb)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff839442ca)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81ac7fe7)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0eac6)
Location: arch/x86/include/asm/xen/hypercall.h:426
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
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
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:notify_remote_via_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
```
**Symbols:**

```
ffff8000100f0d20-ffff8000100f0d2c: HYPERVISOR_event_channel_op (STB_GLOBAL)
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
In drivers/xen/events/events_base.c (ffffffff8162e410)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
```
```
In drivers/xen/events/events_2l.c (ffffffff8162ed38)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff8162f55d)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8162fb79)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81631743)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828e75d9)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff816362ff)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81668db8)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
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
In drivers/xen/events/events_base.c (ffffffff8165c520)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
```
```
In drivers/xen/events/events_2l.c (ffffffff8165cd08)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff8165d52d)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8165db49)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8165f713)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828fb0df)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8166407f)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81697198)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
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
In drivers/xen/events/events_base.c (ffffffff81676b10)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
```
```
In drivers/xen/events/events_2l.c (ffffffff81677308)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/events/events_fifo.c (ffffffff81677b3d)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_unmask
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81678159)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81679d0e)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xb_read
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff82900e10)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8167e63f)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816b1748)
Location: arch/x86/include/asm/xen/hypercall.h:356
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:domU_read_console
  - drivers/tty/hvc/hvc_xen.c:domU_write_console
```
</details>
</li>
</ul>

## Differences
