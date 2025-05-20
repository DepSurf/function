# Function: <code>irq_get_chip_data</code>

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
In arch/x86/kernel/apic/io_apic.c (ffffffff81056364)
Location: include/linux/irq.h:619
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
```
```
In drivers/pci/msi.c (ffffffff81453eec)
Location: include/linux/irq.h:619
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_teardown_msi_irq
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810586b4)
Location: include/linux/irq.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In drivers/pci/msi.c (ffffffff814a080c)
Location: include/linux/irq.h:648
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_teardown_msi_irq
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8105b444)
Location: include/linux/irq.h:665
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In drivers/pci/msi.c (ffffffff814c249c)
Location: include/linux/irq.h:665
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_teardown_msi_irq
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8105a9c1)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In drivers/pci/msi.c (ffffffff814cc9ac)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_teardown_msi_irq
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8105ef01)
Location: include/linux/irq.h:744
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In drivers/pci/msi.c (ffffffff8150cedc)
Location: include/linux/irq.h:744
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_teardown_msi_irq
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81061dbb)
Location: include/linux/irq.h:746
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In drivers/pci/msi.c (ffffffff81541db5)
Location: include/linux/irq.h:746
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_teardown_msi_irq
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81067a9b)
Location: include/linux/irq.h:747
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In drivers/pci/msi.c (ffffffff81559105)
Location: include/linux/irq.h:747
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_teardown_msi_irq
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b1f2)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In drivers/pci/msi.c (ffffffff815891c5)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_teardown_msi_irq
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106bb92)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In drivers/pci/msi.c (ffffffff815aab65)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_teardown_msi_irq
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81072e6f)
Location: include/linux/irq.h:808
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In drivers/pci/msi.c (ffffffff81653a25)
Location: include/linux/irq.h:808
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_teardown_msi_irq
```
```
In drivers/xen/events/events_base.c (ffffffff8171605c)
Location: include/linux/irq.h:808
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:restore_cpu_ipis
  - drivers/xen/events/events_base.c:restore_cpu_virqs
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:cpu_from_evtchn
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810742cf)
Location: include/linux/irq.h:821
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In drivers/xen/events/events_base.c (ffffffff817330bc)
Location: include/linux/irq.h:821
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:restore_cpu_ipis
  - drivers/xen/events/events_base.c:restore_cpu_virqs
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:cpu_from_evtchn
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81074d7f)
Location: include/linux/irq.h:823
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In drivers/xen/events/events_base.c (ffffffff817198d1)
Location: include/linux/irq.h:823
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:cpu_from_evtchn
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81082051)
Location: include/linux/irq.h:825
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In drivers/xen/events/events_base.c (ffffffff817979ca)
Location: include/linux/irq.h:825
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:pirq_needs_eoi_flag
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:cpu_from_evtchn
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81091baf)
Location: include/linux/irq.h:829
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In drivers/xen/events/events_base.c (ffffffff818d0a48)
Location: include/linux/irq.h:829
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:pirq_needs_eoi_flag
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:cpu_from_evtchn
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810a698f)
Location: include/linux/irq.h:831
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In drivers/xen/events/events_base.c (ffffffff81a2224d)
Location: include/linux/irq.h:831
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:pirq_needs_eoi_flag
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:cpu_from_evtchn
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810a9b92)
Location: include/linux/irq.h:844
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In drivers/xen/events/events_base.c (ffffffff81a6b5e4)
Location: include/linux/irq.h:844
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_set_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:pirq_needs_eoi_flag
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:cpu_from_evtchn
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810b0c22)
Location: include/linux/irq.h:826
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In drivers/xen/events/events_base.c (ffffffff81abd6a6)
Location: include/linux/irq.h:826
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_poll_irq
  - drivers/xen/events/events_base.c:xen_test_irq_pending
  - drivers/xen/events/events_base.c:xen_clear_irq_pending
  - drivers/xen/events/events_base.c:retrigger_dynirq
  - drivers/xen/events/events_base.c:lateeoi_mask_ack_dynirq
  - drivers/xen/events/events_base.c:lateeoi_ack_dynirq
  - drivers/xen/events/events_base.c:mask_ack_dynirq
  - drivers/xen/events/events_base.c:ack_dynirq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:xen_set_irq_priority
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:disable_pirq
  - drivers/xen/events/events_base.c:enable_pirq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:notify_remote_via_irq
  - drivers/xen/events/events_base.c:irq_evtchn_from_virq
  - drivers/xen/events/events_base.c:evtchn_to_info
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
In drivers/pci/msi.c (ffff800010714210)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_teardown_msi_irq
```
```
In drivers/dma/ipu/ipu_irq.c (ffff80001080a80c)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_status
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
In arch/arm/mach-imx/irq-common.c (c0331df8)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - arch/arm/mach-imx/irq-common.c:mxc_set_irq_fiq
```
```
In drivers/pci/msi.c (c089ec7c)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_teardown_msi_irq
```
```
In drivers/dma/ipu/ipu_irq.c (c0927130)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_status
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
In arch/powerpc/sysdev/mpic.c (c0000000000b5cec)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - arch/powerpc/sysdev/mpic.c:mpic_irq_set_priority
  - arch/powerpc/sysdev/mpic.c:mpic_host_map
  - arch/powerpc/sysdev/mpic.c:mpic_set_vector
```
```
In drivers/pci/msi.c (c000000000883b40)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_teardown_msi_irq
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
In drivers/pci/msi.c (ffffffe0004dde30)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_teardown_msi_irq
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b682)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In drivers/pci/msi.c (ffffffff8159e335)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_teardown_msi_irq
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8105b9b2)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In drivers/pci/msi.c (ffffffff8158d4c5)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_teardown_msi_irq
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106bb32)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In drivers/pci/msi.c (ffffffff8159e8b5)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_teardown_msi_irq
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106d232)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_unregister_ioapic
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In drivers/pci/msi.c (ffffffff815b8ce5)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_teardown_msi_irq
```
</details>
</li>
</ul>

## Differences
