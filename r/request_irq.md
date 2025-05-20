# Function: <code>request_irq</code>

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
In arch/x86/kernel/hpet.c (ffffffff81062409)
Location: include/linux/interrupt.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_work
```
```
In kernel/irq/manage.c (ffffffff810dcefc)
Location: include/linux/interrupt.h:134
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv.c (ffffffff8144b1f5)
Location: include/linux/interrupt.h:134
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
```
```
In drivers/pci/pcie/pme.c (ffffffff8144ba05)
Location: include/linux/interrupt.h:134
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8144cf5b)
Location: include/linux/interrupt.h:134
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814513ec)
Location: include/linux/interrupt.h:134
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
```
In drivers/acpi/osl.c (ffffffff81479fab)
Location: include/linux/interrupt.h:134
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_install_interrupt_handler
```
```
In drivers/acpi/apei/ghes.c (ffffffff814b63ee)
Location: include/linux/interrupt.h:134
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/pnp/resource.c (ffffffff814b8fb8)
Location: include/linux/interrupt.h:134
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
```
```
In drivers/virtio/virtio_mmio.c (ffffffff814c0ac3)
Location: include/linux/interrupt.h:134
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff814c2777)
Location: include/linux/interrupt.h:134
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_try_to_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_try_to_find_vqs
```
```
In drivers/xen/events/events_base.c (ffffffff814c8aeb)
Location: include/linux/interrupt.h:134
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
```
```
In drivers/xen/platform-pci.c (ffffffff814d40a7)
Location: include/linux/interrupt.h:134
Inline: True
```
```
In drivers/tty/hvc/hvc_irq.c (ffffffff814fe809)
Location: include/linux/interrupt.h:134
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_irq.c:notifier_add_irq
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8150555d)
Location: include/linux/interrupt.h:134
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/char/hpet.c (ffffffff815199b6)
Location: include/linux/interrupt.h:134
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff81533762)
Location: include/linux/interrupt.h:134
Inline: True
```
```
In drivers/net/phy/phy.c (ffffffff815ea396)
Location: include/linux/interrupt.h:134
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8160e424)
Location: include/linux/interrupt.h:134
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/host/xhci.c (ffffffff8164d059)
Location: include/linux/interrupt.h:134
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/input/serio/i8042.c (ffffffff81fb15f3)
Location: include/linux/interrupt.h:134
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81676d80)
Location: include/linux/interrupt.h:134
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
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
In arch/x86/kernel/hpet.c (ffffffff81062299)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_work
```
```
In kernel/irq/manage.c (ffffffff810e2644)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv.c (ffffffff81497485)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
```
```
In drivers/pci/pcie/pme.c (ffffffff81497c97)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8149968c)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8149dbfc)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
```
In drivers/acpi/osl.c (ffffffff814c8562)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_install_interrupt_handler
```
```
In drivers/acpi/apei/ghes.c (ffffffff81505dc6)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/pnp/resource.c (ffffffff81508a1e)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815110d0)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8151321b)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_try_to_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_try_to_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
```
```
In drivers/xen/events/events_base.c (ffffffff8151a159)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
```
In drivers/xen/platform-pci.c (ffffffff81524db3)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/tty/hvc/hvc_irq.c (ffffffff8154f349)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_irq.c:notifier_add_irq
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81556cec)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/char/hpet.c (ffffffff8156c6b9)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff81587da2)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/net/phy/phy.c (ffffffff81648d06)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8166dfdf)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/host/xhci.c (ffffffff816ad989)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/input/serio/i8042.c (ffffffff81fde121)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff816d7960)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
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
In arch/x86/kernel/hpet.c (ffffffff81065309)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_work
```
```
In kernel/irq/manage.c (ffffffff810e8f61)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv.c (ffffffff814b8dae)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
```
```
In drivers/pci/pcie/pme.c (ffffffff814b95d5)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814bb27c)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814bf81c)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
```
In drivers/acpi/osl.c (ffffffff814ea4a6)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_install_interrupt_handler
```
```
In drivers/acpi/apei/ghes.c (ffffffff81529fc6)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/pnp/resource.c (ffffffff8152cc3e)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8153d090)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8153f7f9)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/xen/events/events_base.c (ffffffff81546649)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
```
In drivers/xen/platform-pci.c (ffffffff81551321)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/tty/hvc/hvc_irq.c (ffffffff8157bbc9)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_irq.c:notifier_add_irq
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff815834ec)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/char/hpet.c (ffffffff81598e29)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff815b5462)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8169bcbf)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/host/xhci.c (ffffffff816dbb60)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_setup_msix
```
```
In drivers/input/serio/i8042.c (ffffffff8201bd38)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81707899)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
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
In arch/x86/kernel/hpet.c (ffffffff81064253)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_work
```
```
In kernel/irq/manage.c (ffffffff810e8481)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv.c (ffffffff814c35ce)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
```
```
In drivers/pci/pcie/pme.c (ffffffff814c3dc7)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814c5adc)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814c9f9c)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
```
In drivers/acpi/osl.c (ffffffff814f625c)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_install_interrupt_handler
```
```
In drivers/acpi/apei/ghes.c (ffffffff8153d2d4)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/pnp/resource.c (ffffffff8153fce7)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81550d24)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81553598)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/xen/events/events_base.c (ffffffff8155a46e)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
```
In drivers/xen/platform-pci.c (ffffffff81565ae0)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/tty/hvc/hvc_irq.c (ffffffff8158fe39)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_irq.c:notifier_add_irq
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff815978fe)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/char/hpet.c (ffffffff815acbb3)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff815cb2e2)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff816b0fb4)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/host/xhci.c (ffffffff816f0379)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/input/serio/i8042.c (ffffffff820fe6ab)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8171d481)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
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
In arch/x86/kernel/hpet.c (ffffffff810683d3)
Location: include/linux/interrupt.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_work
```
```
In kernel/irq/manage.c (ffffffff810f0851)
Location: include/linux/interrupt.h:146
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv.c (ffffffff8150380e)
Location: include/linux/interrupt.h:146
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
```
```
In drivers/pci/pcie/pme.c (ffffffff81504007)
Location: include/linux/interrupt.h:146
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8150607c)
Location: include/linux/interrupt.h:146
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8150a54c)
Location: include/linux/interrupt.h:146
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
```
In drivers/acpi/osl.c (ffffffff815369bc)
Location: include/linux/interrupt.h:146
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_install_interrupt_handler
```
```
In drivers/acpi/apei/ghes.c (ffffffff8159ff4f)
Location: include/linux/interrupt.h:146
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/pnp/resource.c (ffffffff815a2e07)
Location: include/linux/interrupt.h:146
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815b4544)
Location: include/linux/interrupt.h:146
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff815b6f18)
Location: include/linux/interrupt.h:146
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/xen/events/events_base.c (ffffffff815be8ae)
Location: include/linux/interrupt.h:146
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
```
In drivers/xen/platform-pci.c (ffffffff815c9c80)
Location: include/linux/interrupt.h:146
Inline: True
```
```
In drivers/tty/hvc/hvc_irq.c (ffffffff815f4939)
Location: include/linux/interrupt.h:146
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_irq.c:notifier_add_irq
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff815fc537)
Location: include/linux/interrupt.h:146
Inline: True
```
```
In drivers/char/hpet.c (ffffffff81613583)
Location: include/linux/interrupt.h:146
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff816320b2)
Location: include/linux/interrupt.h:146
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8171c5d8)
Location: include/linux/interrupt.h:146
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/host/xhci.c (ffffffff8175c539)
Location: include/linux/interrupt.h:146
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/input/serio/i8042.c (ffffffff82707f50)
Location: include/linux/interrupt.h:146
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8178e701)
Location: include/linux/interrupt.h:146
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
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
In arch/x86/kernel/hpet.c (ffffffff8106af49)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_work
```
```
In kernel/irq/manage.c (ffffffff810f8c11)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/pci/pcie/aer.c (ffffffff81533b58)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
```
```
In drivers/pci/pcie/pme.c (ffffffff81534e77)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81536f1a)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8153b467)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8153f2ea)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/acpi/osl.c (ffffffff8156c609)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_install_interrupt_handler
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d7b1f)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/pnp/resource.c (ffffffff815daab6)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815ec926)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff815ef405)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/xen/events/events_base.c (ffffffff815f6ed6)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
```
In drivers/xen/platform-pci.c (ffffffff81602524)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/tty/hvc/hvc_irq.c (ffffffff8162daca)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_irq.c:notifier_add_irq
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff816358c3)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/char/hpet.c (ffffffff8164d59c)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff8166d489)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8175b1e7)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/host/xhci.c (ffffffff8179cf1b)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/input/serio/i8042.c (ffffffff827322a7)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817d0da2)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/i2c/busses/i2c-amd-pci-mp2.c (ffffffff817dcef3)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
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
In arch/x86/kernel/hpet.c (ffffffff81070cd9)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_work
```
```
In kernel/irq/manage.c (ffffffff811043b1)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff8154c517)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8154e64a)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81556713)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/acpi/osl.c (ffffffff81584239)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_install_interrupt_handler
```
```
In drivers/acpi/apei/ghes.c (ffffffff815f13c7)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/pnp/resource.c (ffffffff815f4386)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81607516)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81609b15)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/xen/events/events_base.c (ffffffff81611f66)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
```
In drivers/xen/platform-pci.c (ffffffff8161d614)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/tty/hvc/hvc_irq.c (ffffffff8164bd4a)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_irq.c:notifier_add_irq
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81653b91)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/char/hpet.c (ffffffff8166b4bc)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff8168b899)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8177f703)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/host/xhci.c (ffffffff817c32fb)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/input/serio/i8042.c (ffffffff828eb7b8)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817f801a)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
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
In arch/x86/kernel/hpet.c (ffffffff81074cea)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/irq/manage.c (ffffffff8110cea2)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff8157c21b)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8157e4aa)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81586926)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/acpi/osl.c (ffffffff815b4e3a)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_install_interrupt_handler
```
```
In drivers/acpi/apei/ghes.c (ffffffff816231b0)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/pnp/resource.c (ffffffff816261b2)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8163b344)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8163d8ef)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/xen/events/events_base.c (ffffffff81645cc8)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
```
In drivers/xen/platform-pci.c (ffffffff81650826)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/tty/hvc/hvc_irq.c (ffffffff81680889)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_irq.c:notifier_add_irq
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff816885a1)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/char/hpet.c (ffffffff816a1063)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff816c328d)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff817bf4ec)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/host/xhci.c (ffffffff81802542)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/input/serio/i8042.c (ffffffff82905d6a)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81838d29)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
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
In arch/x86/kernel/hpet.c (ffffffff81075cba)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/irq/manage.c (ffffffff81119282)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff8159dc7b)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8159feea)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815a8302)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/acpi/osl.c (ffffffff815d606a)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_install_interrupt_handler
```
```
In drivers/acpi/apei/ghes.c (ffffffff81644c80)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/pnp/resource.c (ffffffff81647ca2)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8165d814)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8165fdcf)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/xen/events/events_base.c (ffffffff8166824e)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
```
In drivers/xen/platform-pci.c (ffffffff81672dc6)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/tty/hvc/hvc_irq.c (ffffffff816a2f39)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_irq.c:notifier_add_irq
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff816aac07)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/char/hpet.c (ffffffff816c3e03)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff816e61cd)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817d85f6)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
```
```
In drivers/usb/core/hcd.c (ffffffff817efe54)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/host/xhci.c (ffffffff818313af)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/input/serio/i8042.c (ffffffff8290f7a5)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8186a699)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
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
In arch/x86/kernel/time.c (ffffffff82ccf239)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - arch/x86/kernel/time.c:hpet_time_init
```
```
In arch/x86/kernel/irqinit.c (ffffffff82cd02dc)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
```
In arch/x86/kernel/hpet.c (ffffffff8107d0a0)
Location: include/linux/interrupt.h:157
Inline: True
```
```
In kernel/irq/manage.c (ffffffff81124b22)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_any_context_irq
```
```
In drivers/pci/pcie/pme.c (ffffffff8163de9b)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8164876a)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81651054)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/acpi/osl.c (ffffffff8167fd6a)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_install_interrupt_handler
```
```
In drivers/acpi/ec.c (ffffffff8169103b)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f1eb8)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/pnp/resource.c (ffffffff816f6a8e)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8170ceb2)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8170ef38)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_intx
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
```
```
In drivers/xen/events/events_base.c (ffffffff8171849a)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
```
In drivers/xen/platform-pci.c (ffffffff817234b5)
Location: include/linux/interrupt.h:157
Inline: True
```
```
In drivers/tty/hvc/hvc_irq.c (ffffffff817556ac)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_irq.c:notifier_add_irq
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8175d5fe)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_link_irq_chain
```
```
In drivers/char/hpet.c (ffffffff81778874)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_ioctl_ieon
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179c83d)
Location: include/linux/interrupt.h:157
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818a6147)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
```
```
In drivers/usb/core/hcd.c (ffffffff818bedae)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_request_irqs
```
```
In drivers/usb/host/xhci.c (ffffffff81903832)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_setup_msix
```
```
In drivers/input/serio/i8042.c (ffffffff82d23da6)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_setup_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8193e2c3)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff819c5565)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
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
In arch/x86/kernel/time.c (ffffffff82fbb0ff)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - arch/x86/kernel/time.c:hpet_time_init
```
```
In arch/x86/kernel/irqinit.c (ffffffff82fbc11c)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
```
In arch/x86/kernel/hpet.c (ffffffff8107cfc0)
Location: include/linux/interrupt.h:157
Inline: True
```
```
In kernel/irq/manage.c (ffffffff81120982)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_any_context_irq
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81639f72)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
```
```
In drivers/pci/pcie/pme.c (ffffffff81664544)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8166d81a)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81bfd97f)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/acpi/osl.c (ffffffff8169e81a)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_install_interrupt_handler
```
```
In drivers/acpi/ec.c (ffffffff816aed6b)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170f278)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/pnp/resource.c (ffffffff81713ace)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81729cd2)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8172bd08)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_intx
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
```
```
In drivers/xen/events/events_base.c (ffffffff81735a3a)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
```
In drivers/xen/platform-pci.c (ffffffff817400f5)
Location: include/linux/interrupt.h:157
Inline: True
```
```
In drivers/tty/hvc/hvc_irq.c (ffffffff8177091c)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_irq.c:notifier_add_irq
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff817784ce)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_link_irq_chain
```
```
In drivers/char/hpet.c (ffffffff81793354)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_ioctl_ieon
```
```
In drivers/iommu/intel/dmar.c (ffffffff817aa50d)
Location: include/linux/interrupt.h:157
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818b5037)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
```
```
In drivers/usb/core/hcd.c (ffffffff81c1c3db)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_request_irqs
```
```
In drivers/usb/host/xhci.c (ffffffff8190bda2)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_setup_msix
```
```
In drivers/input/serio/i8042.c (ffffffff83011e05)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_setup_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
```
```
In drivers/rtc/rtc-cmos.c (ffffffff819450d5)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff819c5795)
Location: include/linux/interrupt.h:157
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
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
In arch/x86/kernel/time.c (ffffffff831c5977)
Location: include/linux/interrupt.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/time.c:hpet_time_init
```
```
In arch/x86/kernel/irqinit.c (ffffffff831c68c7)
Location: include/linux/interrupt.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
```
In arch/x86/kernel/hpet.c (ffffffff8107e19a)
Location: include/linux/interrupt.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/irq/manage.c (ffffffff81120c52)
Location: include/linux/interrupt.h:161
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_any_context_irq
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161dbc6)
Location: include/linux/interrupt.h:161
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
```
```
In drivers/pci/pcie/pme.c (ffffffff816469b2)
Location: include/linux/interrupt.h:161
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8164fdaa)
Location: include/linux/interrupt.h:161
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81bef7ce)
Location: include/linux/interrupt.h:161
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/acpi/osl.c (ffffffff816814ca)
Location: include/linux/interrupt.h:161
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_install_interrupt_handler
```
```
In drivers/acpi/ec.c (ffffffff8169137b)
Location: include/linux/interrupt.h:161
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f0b58)
Location: include/linux/interrupt.h:161
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/pnp/resource.c (ffffffff816f4e7a)
Location: include/linux/interrupt.h:161
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8170dfb1)
Location: include/linux/interrupt.h:161
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8170fade)
Location: include/linux/interrupt.h:161
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
```
```
In drivers/xen/events/events_base.c (ffffffff817190b3)
Location: include/linux/interrupt.h:161
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
```
In drivers/xen/platform-pci.c (ffffffff81723b45)
Location: include/linux/interrupt.h:161
Inline: True
```
```
In drivers/tty/hvc/hvc_irq.c (ffffffff817543cc)
Location: include/linux/interrupt.h:161
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_irq.c:notifier_add_irq
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8175c1b1)
Location: include/linux/interrupt.h:161
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/char/hpet.c (ffffffff8177604f)
Location: include/linux/interrupt.h:161
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_ioctl_ieon
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178d2ad)
Location: include/linux/interrupt.h:161
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818984d8)
Location: include/linux/interrupt.h:161
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
```
```
In drivers/usb/core/hcd.c (ffffffff81c0eba2)
Location: include/linux/interrupt.h:161
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/host/xhci.c (ffffffff818ef398)
Location: include/linux/interrupt.h:161
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/input/serio/i8042.c (ffffffff8321ce24)
Location: include/linux/interrupt.h:161
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_check_aux
```
```
In drivers/rtc/rtc-cmos.c (ffffffff819288c5)
Location: include/linux/interrupt.h:161
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff819aa765)
Location: include/linux/interrupt.h:161
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
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
In arch/x86/kernel/time.c (ffffffff832a66f7)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/time.c:hpet_time_init
```
```
In arch/x86/kernel/irqinit.c (ffffffff832a76ed)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
```
In arch/x86/kernel/hpet.c (ffffffff8108cc2d)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/irq/manage.c (ffffffff811411d2)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_any_context_irq
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168d1de)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
```
```
In drivers/pci/pcie/pme.c (ffffffff816b8252)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff816c1afa)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81ceaadc)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/acpi/osl.c (ffffffff816f65ba)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_install_interrupt_handler
```
```
In drivers/acpi/ec.c (ffffffff81706e2b)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
```
```
In drivers/acpi/apei/ghes.c (ffffffff8176ac68)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/pnp/resource.c (ffffffff8176f397)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8178a9c1)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8178c46e)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
```
```
In drivers/xen/events/events_base.c (ffffffff81796d66)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
```
In drivers/xen/platform-pci.c (ffffffff817a2a11)
Location: include/linux/interrupt.h:165
Inline: True
```
```
In drivers/tty/hvc/hvc_irq.c (ffffffff817d7a8c)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_irq.c:notifier_add_irq
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff817dfd0e)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_link_irq_chain
```
```
In drivers/char/hpet.c (ffffffff817fbdce)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_ioctl_ieon
```
```
In drivers/iommu/intel/dmar.c (ffffffff818149fd)
Location: include/linux/interrupt.h:165
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff8192bd58)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
```
```
In drivers/usb/core/hcd.c (ffffffff81d15d3b)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/host/xhci.c (ffffffff8198bf58)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/input/serio/i8042.c (ffffffff819b36f1)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_setup_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
```
```
In drivers/rtc/rtc-cmos.c (ffffffff819cb237)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81a581a5)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
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
In arch/x86/kernel/time.c (ffffffff83455924)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/time.c:hpet_time_init
```
```
In arch/x86/kernel/irqinit.c (ffffffff83456a34)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
```
In arch/x86/kernel/hpet.c (ffffffff8109d864)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/irq/manage.c (ffffffff81164ba9)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_any_context_irq
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817ac3df)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
```
```
In drivers/pci/pcie/pme.c (ffffffff817dc67d)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff817e738a)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81eb1b48)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/acpi/osl.c (ffffffff818233c3)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_install_interrupt_handler
```
```
In drivers/acpi/ec.c (ffffffff81835036)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189f81b)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/pnp/resource.c (ffffffff818a4733)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
```
```
In drivers/virtio/virtio_mmio.c (ffffffff818c22ed)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff818c40bd)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
```
```
In drivers/xen/events/events_base.c (ffffffff818cfd1b)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
```
In drivers/xen/platform-pci.c (ffffffff818dccd2)
Location: include/linux/interrupt.h:165
Inline: True
```
```
In drivers/tty/hvc/hvc_irq.c (ffffffff81915c83)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_irq.c:notifier_add_irq
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8191e945)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/char/hpet.c (ffffffff8193a392)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_ioctl_ieon
```
```
In drivers/iommu/intel/dmar.c (ffffffff819558a2)
Location: include/linux/interrupt.h:165
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81a82453)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
```
```
In drivers/usb/core/hcd.c (ffffffff81ee083e)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/host/xhci.c (ffffffff81ae8142)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/input/serio/i8042.c (ffffffff81b128c5)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_setup_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81b2cf80)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81bc7d57)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
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
In arch/x86/kernel/time.c (ffffffff83e738bb)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/time.c:hpet_time_init
```
```
In arch/x86/kernel/irqinit.c (ffffffff83e75079)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
```
In arch/x86/kernel/hpet.c (ffffffff810b4974)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/irq/manage.c (ffffffff811989b9)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_any_context_irq
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c53a6)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
```
```
In drivers/pci/pcie/pme.c (ffffffff818fe42d)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8190c51a)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81915c5a)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/acpi/osl.c (ffffffff81954583)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_install_interrupt_handler
```
```
In drivers/acpi/ec.c (ffffffff81969186)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e8b7a)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/pnp/resource.c (ffffffff819ee233)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81a1222d)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81a1478f)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
```
```
In drivers/xen/events/events_base.c (ffffffff81a2148b)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
```
In drivers/xen/platform-pci.c (ffffffff81a30072)
Location: include/linux/interrupt.h:165
Inline: True
```
```
In drivers/tty/hvc/hvc_irq.c (ffffffff81a70fe3)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_irq.c:notifier_add_irq
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81a7a965)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/char/hpet.c (ffffffff81a9a7b2)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_ioctl_ieon
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abc36e)
Location: include/linux/interrupt.h:165
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff81c1fb5c)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/host/xhci.c (ffffffff81c740ff)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/input/serio/i8042.c (ffffffff81ca372d)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_setup_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81cc1122)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81d70978)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
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
In arch/x86/kernel/time.c (ffffffff8369537b)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/time.c:hpet_time_init
```
```
In arch/x86/kernel/irqinit.c (ffffffff83696b59)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
```
In arch/x86/kernel/hpet.c (ffffffff810b7a44)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/irq/manage.c (ffffffff811aa699)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_any_context_irq
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81908464)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
```
```
In drivers/pci/pcie/pme.c (ffffffff819418dd)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8194fb9a)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81959263)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/acpi/osl.c (ffffffff8199a993)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_install_interrupt_handler
```
```
In drivers/acpi/ec.c (ffffffff819af76e)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a31376)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/pnp/resource.c (ffffffff81a369af)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81a5b26d)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81a5d7ef)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
```
```
In drivers/xen/events/events_base.c (ffffffff81a6a81b)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
```
In drivers/xen/platform-pci.c (ffffffff81a79882)
Location: include/linux/interrupt.h:165
Inline: True
```
```
In drivers/tty/hvc/hvc_irq.c (ffffffff81abb7be)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_irq.c:notifier_add_irq
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81ac61dd)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/char/hpet.c (ffffffff81ae6052)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_ioctl_ieon
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b08c5e)
Location: include/linux/interrupt.h:165
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff81c86b05)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/input/serio/i8042.c (ffffffff81d0aded)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_setup_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81d28b7d)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81dde638)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
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
In arch/x86/kernel/time.c (ffffffff838c52bb)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/time.c:hpet_time_init
```
```
In arch/x86/kernel/irqinit.c (ffffffff838c6879)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:native_init_IRQ
```
```
In arch/x86/kernel/hpet.c (ffffffff810bee84)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/irq/manage.c (ffffffff811ba1e9)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_any_context_irq
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8194fc80)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
```
```
In drivers/pci/pcie/pme.c (ffffffff8198ab6c)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81998fca)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff819a27d3)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7c7e6)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/pnp/resource.c (ffffffff81a8209f)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81aac6dd)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81aaf79f)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
```
```
In drivers/xen/events/events_base.c (ffffffff81abca8e)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
```
In drivers/xen/platform-pci.c (ffffffff81acbcf2)
Location: include/linux/interrupt.h:165
Inline: True
```
```
In drivers/tty/hvc/hvc_irq.c (ffffffff81b0e51e)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_irq.c:notifier_add_irq
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81b1920c)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/char/hpet.c (ffffffff81b393e2)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_ioctl_ieon
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5cc7e)
Location: include/linux/interrupt.h:165
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff81d3b573)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/input/serio/i8042.c (ffffffff81dc0a7d)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_setup_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81dde9e2)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81e94547)
Location: include/linux/interrupt.h:165
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
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
In virt/kvm/arm/vgic/vgic-v4.c (ffff8000100e09fc)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_init
```
```
In kernel/irq/manage.c (ffff80001017bd94)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069ce98)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
```
```
In drivers/pci/pcie/pme.c (ffff800010705c6c)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffff800010708464)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffff800010711300)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/controller/dwc/pci-keystone.c (ffff8000114799e4)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
```
```
In drivers/acpi/osl.c (ffff8000107638e4)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_install_interrupt_handler
```
```
In drivers/acpi/apei/ghes.c (ffff8000107b0838)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/pnp/resource.c (ffff8000107b516c)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
```
```
In drivers/dma/amba-pl08x.c (ffff800010802874)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_probe
```
```
In drivers/dma/bcm2835-dma.c (ffff800010804194)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_alloc_chan_resources
```
```
In drivers/dma/mv_xor.c (ffff800010807708)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_channel_add
```
```
In drivers/dma/mxs-dma.c (ffff800010809f1c)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080d330)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
```
```
In drivers/soc/fsl/qbman/bman.c (ffff8000108120ec)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman.c:bman_create_portal
```
```
In drivers/soc/fsl/qbman/qman.c (ffff800010815ab0)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
```
```
In drivers/virtio/virtio_mmio.c (ffff800010826474)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (ffff800010828ce8)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/xen/events/events_base.c (ffff8000108322a0)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
```
In drivers/tty/hvc/hvc_irq.c (ffff80001087b2f4)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_irq.c:notifier_add_irq
```
```
In drivers/tty/serial/8250/8250_core.c (ffff800010885470)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/tty/serial/amba-pl011.c (ffff80001089402c)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_allocate_irq
```
```
In drivers/tty/serial/meson_uart.c (ffff80001089ee74)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_startup
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a227c)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_startup
```
```
In drivers/tty/serial/owl-uart.c (ffff8000108a6cc8)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e4144)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fb460)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
```
```
In drivers/usb/core/hcd.c (ffff800010a1de00)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/host/xhci.c (ffff800010a6d8b8)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/clocksource/timer-of.c (ffff8000114a7e80)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/clocksource/timer-of.c:timer_of_init
```
```
In drivers/clocksource/sh_cmt.c (ffff800010b64640)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b6599c)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
```
```
In drivers/clocksource/timer-rockchip.c (ffff8000114a8578)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/clocksource/timer-rockchip.c:rk_timer_init
```
```
In drivers/clocksource/timer-owl.c (ffff8000114a8a98)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/clocksource/timer-owl.c:owl_timer_init
```
```
In drivers/clocksource/arm_arch_timer.c (ffff8000114a9484)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_frame_register
```
```
In drivers/mailbox/pl320-ipc.c (ffff800010b7ad28)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/mailbox/pl320-ipc.c:pl320_probe
```
```
In drivers/mailbox/ti-msgmgr.c (ffff800010b7d0ec)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_queue_startup
```
```
In drivers/memory/fsl_ifc.c (ffff800010b8b7a4)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe
```
```
In drivers/perf/arm-cci.c (ffff800010b91d3c)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_event_init
```
```
In drivers/perf/arm_pmu.c (ffff800010b954e4)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_request_irq
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
In arch/arm/mach-omap2/pm34xx.c (c1515a44)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - arch/arm/mach-omap2/pm34xx.c:omap3_pm_init
  - arch/arm/mach-omap2/pm34xx.c:omap3_pm_init
```
```
In arch/arm/mach-vexpress/spc.c (c151b258)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - arch/arm/mach-vexpress/spc.c:ve_spc_init
```
```
In kernel/irq/manage.c (c03cce48)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/bus/omap_l3_smx.c (c0825c3c)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/bus/omap_l3_smx.c:omap3_l3_probe
  - drivers/bus/omap_l3_smx.c:omap3_l3_probe
```
```
In drivers/pinctrl/pinctrl-single.c (c08405fc)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
```
```
In drivers/pci/pcie/pme.c (c089d024)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/controller/pci-tegra.c (c08ac678)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources
```
```
In drivers/dma/amba-pl08x.c (c092160c)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_probe
```
```
In drivers/dma/mv_xor.c (c092586c)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_channel_add
```
```
In drivers/dma/mxs-dma.c (c0926cfc)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources
```
```
In drivers/dma/ipu/ipu_idmac.c (c0928050)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
```
```
In drivers/dma/tegra20-apb-dma.c (c092a710)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
```
```
In drivers/virtio/virtio_mmio.c (c09445ac)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (c09469d0)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/tty/serial/8250/8250_core.c (c0984108)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/tty/serial/amba-pl011.c (c0990254)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_allocate_irq
```
```
In drivers/tty/serial/meson_uart.c (c0998a48)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_startup
```
```
In drivers/tty/serial/msm_serial.c (c099bb5c)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_startup
```
```
In drivers/tty/serial/omap-serial.c (c09a0bfc)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/tty/serial/owl-uart.c (c09a33e8)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/tty/serial/rda-uart.c (c09a4068)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/rda-uart.c:rda_uart_startup
```
```
In drivers/auxdisplay/arm-charlcd.c (c159d204)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/auxdisplay/arm-charlcd.c:charlcd_probe
```
```
In drivers/usb/core/hcd.c (c0af5348)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/host/xhci.c (c0b41f44)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/usb/musb/musb_core.c (c0b6647c)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_init_controller
```
```
In drivers/rtc/rtc-pl031.c (c0b8dbf4)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/rtc/rtc-pl031.c:pl031_probe
```
```
In drivers/clocksource/timer-of.c (c15aa460)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/clocksource/timer-of.c:timer_of_init
```
```
In drivers/clocksource/sh_cmt.c (c0c450cc)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
```
```
In drivers/clocksource/sh_mtu2.c (c0c45604)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_setup
```
```
In drivers/clocksource/renesas-ostm.c (c15aa8f0)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/clocksource/renesas-ostm.c:ostm_init
```
```
In drivers/clocksource/sh_tmu.c (c0c468f4)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
```
```
In drivers/clocksource/timer-rockchip.c (c15ab1cc)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/clocksource/timer-rockchip.c:rk_timer_init
```
```
In drivers/clocksource/timer-tegra.c (c15abd80)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/clocksource/timer-tegra.c:tegra_init_timer
```
```
In drivers/clocksource/exynos_mct.c (c15ac1e0)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/clocksource/exynos_mct.c:mct_init_dt
```
```
In drivers/clocksource/timer-qcom.c (c0c4a644)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/clocksource/timer-qcom.c:msm_local_timer_starting_cpu
```
```
In drivers/clocksource/timer-owl.c (c15acac0)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/clocksource/timer-owl.c:owl_timer_init
```
```
In drivers/clocksource/arm_arch_timer.c (c15ad750)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init
```
```
In drivers/staging/emxx_udc/emxx_udc.c (c0c5bf34)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_probe
```
```
In drivers/mailbox/pl320-ipc.c (c0c603bc)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/mailbox/pl320-ipc.c:pl320_probe
```
```
In drivers/memory/omap-gpmc.c (c0c715e8)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/memory/omap-gpmc.c:gpmc_probe
```
```
In drivers/perf/arm-cci.c (c0c7b748)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_event_init
```
```
In drivers/perf/arm_pmu.c (c0c7ea84)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_request_irq
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
In arch/powerpc/kernel/smp.c (c000000000054e90)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:smp_request_message_ipi
```
```
In arch/powerpc/sysdev/fsl_lbc.c (c0000000000b8a0c)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_ctrl_probe
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_ctrl_probe
```
```
In arch/powerpc/sysdev/xics/xics-common.c (c000000001359280)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/xics-common.c:xics_smp_probe
```
```
In arch/powerpc/sysdev/xive/common.c (c000000001359bb0)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_smp_probe
```
```
In arch/powerpc/platforms/powernv/opal.c (c00000000135af60)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal.c:opal_init
```
```
In arch/powerpc/platforms/powernv/opal-irqchip.c (c00000000135dd84)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_init
```
```
In arch/powerpc/platforms/powernv/eeh-powernv.c (c0000000000deb70)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_post_init
```
```
In arch/powerpc/platforms/pseries/event_sources.c (c0000000000f1db0)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/event_sources.c:request_event_sources_irqs
```
```
In kernel/irq/manage.c (c0000000001d67e8)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/pinctrl/pinctrl-single.c (c00000000083559c)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (c000000000880e5c)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller
```
```
In drivers/virtio/virtio_mmio.c (c0000000008d1c08)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (c0000000008d5378)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/tty/hvc/hvsi.c (c0000000013a6894)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/hvc/hvsi.c:hvsi_init
```
```
In drivers/tty/hvc/hvc_irq.c (c000000000922800)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_irq.c:notifier_add_irq
```
```
In drivers/tty/serial/8250/8250_core.c (c00000000092c400)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/char/tpm/tpm_ibmvtpm.c (c00000000096918c)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (c000000000ab8048)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
```
```
In drivers/usb/core/hcd.c (c000000000ad6c98)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/host/xhci.c (c000000000b41970)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/input/serio/i8042.c (c0000000013b3374)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
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
In arch/riscv/kernel/perf_event.c (ffffffe0000b9796)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - arch/riscv/kernel/perf_event.c:riscv_event_init
```
```
In arch/riscv/mm/sifive_l2_cache.c (ffffffe000003ed2)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - arch/riscv/mm/sifive_l2_cache.c:sifive_l2_init
```
```
In kernel/irq/manage.c (ffffffe000115656)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/pinctrl/pinctrl-single.c (ffffffe0004a102c)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
```
```
In drivers/pci/pcie/pme.c (ffffffe0004d3b50)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffe0004d5e60)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffe0004dd1c0)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/virtio/virtio_mmio.c (ffffffe00051cea6)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (ffffffe00051f09c)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffe000550ac8)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/tty/serial/sifive.c (ffffffe00055dc06)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/sifive.c:sifive_serial_probe
```
```
In drivers/usb/core/hcd.c (ffffffe000640f7a)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/host/xhci.c (ffffffe000686d0c)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/clocksource/timer-of.c (ffffffe00003a308)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/clocksource/timer-of.c:timer_of_init
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
In arch/x86/kernel/hpet.c (ffffffff81074cba)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/irq/manage.c (ffffffff81111862)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff8159147b)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815936fa)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8159bb12)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/acpi/osl.c (ffffffff815c9dca)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_install_interrupt_handler
```
```
In drivers/pnp/resource.c (ffffffff8160dd02)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
```
```
In drivers/virtio/virtio_mmio.c (ffffffff816236b4)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81625c3f)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/xen/events/events_base.c (ffffffff8162df7e)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
```
In drivers/xen/platform-pci.c (ffffffff81638ab6)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/tty/hvc/hvc_irq.c (ffffffff81668999)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_irq.c:notifier_add_irq
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81670677)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/char/hpet.c (ffffffff81689853)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff816abcad)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff817a8234)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/host/xhci.c (ffffffff817e978f)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/input/serio/i8042.c (ffffffff828f6544)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8181d349)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
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
In arch/x86/kernel/hpet.c (ffffffff81064cea)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/irq/manage.c (ffffffff81102592)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff8158064b)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8158288a)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8158aca2)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/acpi/osl.c (ffffffff815b2e4a)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_install_interrupt_handler
```
```
In drivers/pnp/resource.c (ffffffff81602252)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81617d04)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8161a2bf)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8164f77b)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/char/hpet.c (ffffffff816672cd)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff8168960d)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817826a6)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
```
```
In drivers/usb/core/hcd.c (ffffffff81799c4d)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/host/xhci.c (ffffffff817ae89f)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/input/serio/i8042.c (ffffffff828ed9ab)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817e4a33)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
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
In arch/x86/kernel/hpet.c (ffffffff81074c6a)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/irq/manage.c (ffffffff8110f752)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff815919cb)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81593c3a)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8159c052)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/acpi/osl.c (ffffffff815ca34a)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_install_interrupt_handler
```
```
In drivers/acpi/apei/ghes.c (ffffffff81638ac0)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/pnp/resource.c (ffffffff8163bae2)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81651654)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81653c0f)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/xen/events/events_base.c (ffffffff8165c08e)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
```
In drivers/xen/platform-pci.c (ffffffff81666c06)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/tty/hvc/hvc_irq.c (ffffffff81696d79)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_irq.c:notifier_add_irq
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8169ea47)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/char/hpet.c (ffffffff816b7ac3)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff816d9e8d)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817cd476)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
```
```
In drivers/usb/core/hcd.c (ffffffff817e4cd4)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/host/xhci.c (ffffffff8182622f)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/input/serio/i8042.c (ffffffff8290a33c)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8185e829)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
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
In arch/x86/kernel/hpet.c (ffffffff81076cca)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/irq/manage.c (ffffffff8111ac82)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff815ac01b)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815ae0ba)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_controller
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815b6482)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/acpi/osl.c (ffffffff815e41aa)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_install_interrupt_handler
```
```
In drivers/acpi/apei/ghes.c (ffffffff81652e10)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/pnp/resource.c (ffffffff81655e32)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8166bce4)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8166e29f)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
```
In drivers/xen/events/events_base.c (ffffffff8167667e)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
```
In drivers/xen/platform-pci.c (ffffffff816811b6)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/tty/hvc/hvc_irq.c (ffffffff816b1329)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_irq.c:notifier_add_irq
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff816b8e98)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/char/hpet.c (ffffffff816d2316)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff816f443d)
Location: include/linux/interrupt.h:144
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817e7716)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
```
```
In drivers/usb/core/hcd.c (ffffffff817fef40)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/host/xhci.c (ffffffff8184010f)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/input/serio/i8042.c (ffffffff82910807)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8187a6fe)
Location: include/linux/interrupt.h:144
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
</details>
</li>
</ul>

## Differences
