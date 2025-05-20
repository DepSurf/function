# Function: <code>pci_name</code>

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
In drivers/gpio/gpio-intel-mid.c (ffffffff81429daa)
Location: include/linux/pci.h:1554
Inline: True
Inline callers:
  - drivers/gpio/gpio-intel-mid.c:intel_gpio_probe
```
```
In drivers/pci/probe.c (ffffffff8142fc64)
Location: include/linux/pci.h:1554
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff814377c2)
Location: include/linux/pci.h:1554
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_ea_init
```
```
In drivers/pci/pci-driver.c (ffffffff8143952f)
Location: include/linux/pci.h:1554
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_uevent
```
```
In drivers/pci/pci-sysfs.c (ffffffff8143c8c3)
Location: include/linux/pci.h:1554
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff81443967)
Location: include/linux/pci.h:1554
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_io_region
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff81448c80)
Location: include/linux/pci.h:1554
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff8144a02e)
Location: include/linux/pci.h:1554
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8144eba3)
Location: include/linux/pci.h:1554
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8144ff6b)
Location: include/linux/pci.h:1554
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81450617)
Location: include/linux/pci.h:1554
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
```
```
In drivers/pci/hotplug-pci.c (ffffffff81453695)
Location: include/linux/pci.h:1554
Inline: True
```
```
In drivers/pci/iov.c (ffffffff8145664e)
Location: include/linux/pci.h:1554
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
```
In drivers/pnp/quirks.c (ffffffff814bb378)
Location: include/linux/pci.h:1554
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff814c2f60)
Location: include/linux/pci.h:1554
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8150a190)
Location: include/linux/pci.h:1554
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:moan_device
```
```
In drivers/char/agp/isoch.c (ffffffff8151e910)
Location: include/linux/pci.h:1554
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/iommu/dmar.c (ffffffff81533ca8)
Location: include/linux/pci.h:1554
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff8153f37a)
Location: include/linux/pci.h:1554
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/gpu/vga/vgaarb.c:__vga_set_legacy_decoding
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81540c26)
Location: include/linux/pci.h:1554
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8161f894)
Location: include/linux/pci.h:1554
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81662450)
Location: include/linux/pci.h:1554
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In arch/x86/pci/irq.c (ffffffff816f9d57)
Location: include/linux/pci.h:1554
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_enable_irq
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
In drivers/pci/probe.c (ffffffff8147b3c4)
Location: include/linux/pci.h:1612
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff814833f2)
Location: include/linux/pci.h:1612
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_ea_init
```
```
In drivers/pci/pci-driver.c (ffffffff814853df)
Location: include/linux/pci.h:1612
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_uevent
```
```
In drivers/pci/pci-sysfs.c (ffffffff81488855)
Location: include/linux/pci.h:1612
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8148fa05)
Location: include/linux/pci.h:1612
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff81494ead)
Location: include/linux/pci.h:1612
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814962f6)
Location: include/linux/pci.h:1612
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8149b3b4)
Location: include/linux/pci.h:1612
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8149c8a6)
Location: include/linux/pci.h:1612
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8149cf17)
Location: include/linux/pci.h:1612
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
```
```
In drivers/pci/hotplug-pci.c (ffffffff8149ff35)
Location: include/linux/pci.h:1612
Inline: True
```
```
In drivers/pci/iov.c (ffffffff814a2e8a)
Location: include/linux/pci.h:1612
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pnp/quirks.c (ffffffff8150adf1)
Location: include/linux/pci.h:1612
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff815134d0)
Location: include/linux/pci.h:1612
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8155c570)
Location: include/linux/pci.h:1612
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:moan_device
```
```
In drivers/char/agp/isoch.c (ffffffff8157175f)
Location: include/linux/pci.h:1612
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/iommu/dmar.c (ffffffff81588ea0)
Location: include/linux/pci.h:1612
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff81fdc579)
Location: include/linux/pci.h:1612
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/gpu/vga/vgaarb.c:__vga_set_legacy_decoding
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff816419bf)
Location: include/linux/pci.h:1612
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8168027c)
Location: include/linux/pci.h:1612
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816c267c)
Location: include/linux/pci.h:1612
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In arch/x86/pci/irq.c (ffffffff8175ee46)
Location: include/linux/pci.h:1612
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
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
In drivers/pci/probe.c (ffffffff8149c844)
Location: include/linux/pci.h:1674
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff814a4b52)
Location: include/linux/pci.h:1674
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_ea_init
```
```
In drivers/pci/pci-driver.c (ffffffff814a6b9f)
Location: include/linux/pci.h:1674
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_uevent
```
```
In drivers/pci/pci-sysfs.c (ffffffff814aa01d)
Location: include/linux/pci.h:1674
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff814b1255)
Location: include/linux/pci.h:1674
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff814b685d)
Location: include/linux/pci.h:1674
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814b7c96)
Location: include/linux/pci.h:1674
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff814bcf94)
Location: include/linux/pci.h:1674
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff814be426)
Location: include/linux/pci.h:1674
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814beac8)
Location: include/linux/pci.h:1674
Inline: True
```
```
In drivers/pci/hotplug-pci.c (ffffffff814c1ab5)
Location: include/linux/pci.h:1674
Inline: True
```
```
In drivers/pci/iov.c (ffffffff814c4b52)
Location: include/linux/pci.h:1674
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pnp/quirks.c (ffffffff8152f011)
Location: include/linux/pci.h:1674
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8153f8e0)
Location: include/linux/pci.h:1674
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81588eb0)
Location: include/linux/pci.h:1674
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:moan_device
```
```
In drivers/char/agp/isoch.c (ffffffff8159de1f)
Location: include/linux/pci.h:1674
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/iommu/dmar.c (ffffffff815b6560)
Location: include/linux/pci.h:1674
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff816714cc)
Location: include/linux/pci.h:1674
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81672a9f)
Location: include/linux/pci.h:1674
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff816adfac)
Location: include/linux/pci.h:1674
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816f063c)
Location: include/linux/pci.h:1674
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In arch/x86/pci/irq.c (ffffffff8178b376)
Location: include/linux/pci.h:1674
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
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
In drivers/pci/probe.c (ffffffff814a698f)
Location: include/linux/pci.h:1706
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff814aebe1)
Location: include/linux/pci.h:1706
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_ea_init
```
```
In drivers/pci/pci-driver.c (ffffffff814b0b8f)
Location: include/linux/pci.h:1706
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_uevent
```
```
In drivers/pci/pci-sysfs.c (ffffffff814b4386)
Location: include/linux/pci.h:1706
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff814bb92b)
Location: include/linux/pci.h:1706
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff814c10c1)
Location: include/linux/pci.h:1706
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814c2527)
Location: include/linux/pci.h:1706
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff814c7779)
Location: include/linux/pci.h:1706
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff814c8c24)
Location: include/linux/pci.h:1706
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814c9183)
Location: include/linux/pci.h:1706
Inline: True
```
```
In drivers/pci/hotplug-pci.c (ffffffff814cc095)
Location: include/linux/pci.h:1706
Inline: True
```
```
In drivers/pci/iov.c (ffffffff814ced9a)
Location: include/linux/pci.h:1706
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pnp/quirks.c (ffffffff81541fe3)
Location: include/linux/pci.h:1706
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81553680)
Location: include/linux/pci.h:1706
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8159d326)
Location: include/linux/pci.h:1706
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:moan_device
```
```
In drivers/char/agp/isoch.c (ffffffff815b1911)
Location: include/linux/pci.h:1706
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/iommu/dmar.c (ffffffff815cc4cd)
Location: include/linux/pci.h:1706
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff81685b25)
Location: include/linux/pci.h:1706
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81687134)
Location: include/linux/pci.h:1706
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff816c39c3)
Location: include/linux/pci.h:1706
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81705e87)
Location: include/linux/pci.h:1706
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/edac/edac_pci.c (ffffffff8175fdd3)
Location: include/linux/pci.h:1706
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff817601bc)
Location: include/linux/pci.h:1706
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In arch/x86/pci/irq.c (ffffffff817aa2bf)
Location: include/linux/pci.h:1706
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
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
In drivers/pci/probe.c (ffffffff814e6e8d)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff814edfb1)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_ea_init
```
```
In drivers/pci/pci-driver.c (ffffffff814f00ff)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_uevent
```
```
In drivers/pci/pci-sysfs.c (ffffffff814f3bac)
Location: include/linux/pci.h:1762
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff814fbd9b)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff815014f1)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff8150275a)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
  - drivers/pci/pcie/aer/aerdrv_core.c:do_recovery
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff81507d13)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815091e4)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81509743)
Location: include/linux/pci.h:1762
Inline: True
```
```
In drivers/pci/iov.c (ffffffff8150efe5)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/acpi/pci_irq.c (ffffffff8154988a)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
```
In drivers/pnp/quirks.c (ffffffff815a5103)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff815b7000)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81602836)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:moan_device
```
```
In drivers/char/agp/isoch.c (ffffffff81618541)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/iommu/dmar.c (ffffffff8163329d)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff816ef385)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff816f09c4)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8172f7a3)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81777057)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/edac/edac_pci.c (ffffffff817d1e53)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff817d224c)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In arch/x86/pci/irq.c (ffffffff8182178f)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
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
In drivers/pci/probe.c (ffffffff81516668)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff8151f0d7)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_print_link_status
  - drivers/pci/pci.c:pci_ea_init
```
```
In drivers/pci/pci-driver.c (ffffffff81520d2b)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_uevent
```
```
In drivers/pci/quirks.c (ffffffff8152dc62)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_gpu_hda
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff81530508)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/err.c (ffffffff8153106a)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_fatal_recovery
  - drivers/pci/pcie/err.c:pcie_do_fatal_recovery
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81539fac)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff8153da8c)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8153efa9)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/iov.c (ffffffff81543eb3)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/acpi/pci_irq.c (ffffffff8157fab1)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
```
In drivers/pnp/quirks.c (ffffffff815dcd23)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff815ef4fc)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8163bb13)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:moan_device
```
```
In drivers/char/agp/isoch.c (ffffffff816527b7)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/iommu/dmar.c (ffffffff8166f423)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff8172bdf9)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8172d5a1)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8176e047)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817b7e02)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-amd-pci-mp2.c (ffffffff817dcf70)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
```
```
In drivers/edac/edac_pci.c (ffffffff8181ab43)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8181b3c9)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In arch/x86/pci/irq.c (ffffffff8186b9fa)
Location: include/linux/pci.h:1762
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
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
In drivers/pci/probe.c (ffffffff8152bf4d)
Location: include/linux/pci.h:1796
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff81535068)
Location: include/linux/pci.h:1796
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pcie_print_link_status
  - drivers/pci/pci.c:pci_ea_init
```
```
In drivers/pci/pci-driver.c (ffffffff81536b5b)
Location: include/linux/pci.h:1796
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_uevent
```
```
In drivers/pci/quirks.c (ffffffff81544ab2)
Location: include/linux/pci.h:1796
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_gpu_hda
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff815479c8)
Location: include/linux/pci.h:1796
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/err.c (ffffffff81548557)
Location: include/linux/pci.h:1796
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815512ea)
Location: include/linux/pci.h:1796
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff81554e3c)
Location: include/linux/pci.h:1796
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815563d7)
Location: include/linux/pci.h:1796
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/iov.c (ffffffff8155b233)
Location: include/linux/pci.h:1796
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/acpi/pci_irq.c (ffffffff815977c8)
Location: include/linux/pci.h:1796
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
```
In drivers/pnp/quirks.c (ffffffff815f64c3)
Location: include/linux/pci.h:1796
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81609c1c)
Location: include/linux/pci.h:1796
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81659d43)
Location: include/linux/pci.h:1796
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:moan_device
```
```
In drivers/char/agp/isoch.c (ffffffff816709b7)
Location: include/linux/pci.h:1796
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/iommu/dmar.c (ffffffff8168d983)
Location: include/linux/pci.h:1796
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff8174e599)
Location: include/linux/pci.h:1796
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8174fdc1)
Location: include/linux/pci.h:1796
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817926c7)
Location: include/linux/pci.h:1796
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817de4ee)
Location: include/linux/pci.h:1796
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/edac/edac_pci.c (ffffffff81846333)
Location: include/linux/pci.h:1796
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81846bb9)
Location: include/linux/pci.h:1796
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In arch/x86/pci/irq.c (ffffffff8188bada)
Location: include/linux/pci.h:1796
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
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
In drivers/pci/probe.c (ffffffff8155d2f4)
Location: include/linux/pci.h:1870
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff81564e1b)
Location: include/linux/pci.h:1870
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pcie_print_link_status
  - drivers/pci/pci.c:pci_ea_init
```
```
In drivers/pci/pci-driver.c (ffffffff8156643b)
Location: include/linux/pci.h:1870
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_uevent
```
```
In drivers/pci/quirks.c (ffffffff81572fd9)
Location: include/linux/pci.h:1870
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff81577ab8)
Location: include/linux/pci.h:1870
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/err.c (ffffffff81578734)
Location: include/linux/pci.h:1870
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8158125f)
Location: include/linux/pci.h:1870
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff81584fd2)
Location: include/linux/pci.h:1870
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815867ed)
Location: include/linux/pci.h:1870
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/iov.c (ffffffff8158b555)
Location: include/linux/pci.h:1870
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/acpi/pci_irq.c (ffffffff815c896f)
Location: include/linux/pci.h:1870
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
```
In drivers/pnp/quirks.c (ffffffff8162895a)
Location: include/linux/pci.h:1870
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8163d9fd)
Location: include/linux/pci.h:1870
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8169142f)
Location: include/linux/pci.h:1870
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:moan_device
```
```
In drivers/char/agp/isoch.c (ffffffff816a64c9)
Location: include/linux/pci.h:1870
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/iommu/dmar.c (ffffffff816c53aa)
Location: include/linux/pci.h:1870
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff8178a31a)
Location: include/linux/pci.h:1870
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8178bba9)
Location: include/linux/pci.h:1870
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817d1847)
Location: include/linux/pci.h:1870
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff8181ef6c)
Location: include/linux/pci.h:1870
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/edac/edac_pci.c (ffffffff818890df)
Location: include/linux/pci.h:1870
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81889986)
Location: include/linux/pci.h:1870
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In arch/x86/pci/irq.c (ffffffff818d65d0)
Location: include/linux/pci.h:1870
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
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
In drivers/pci/probe.c (ffffffff8157e3ae)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff81586182)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pcie_print_link_status
  - drivers/pci/pci.c:pci_ea_init
```
```
In drivers/pci/pci-driver.c (ffffffff8158779b)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_uevent
```
```
In drivers/pci/quirks.c (ffffffff81594629)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff81599238)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/err.c (ffffffff81599ec5)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815a2d5f)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff815a69c5)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815a81df)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/iov.c (ffffffff815ad105)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/acpi/pci_irq.c (ffffffff815e9b8f)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
```
In drivers/pnp/quirks.c (ffffffff8164a44a)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8165fedd)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816b3f3d)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:moan_device
```
```
In drivers/char/agp/isoch.c (ffffffff816c91f9)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/iommu/dmar.c (ffffffff816e82e1)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff817adf1a)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff817af7c9)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817d8572)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81802717)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff8185042c)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/edac/edac_pci.c (ffffffff818bb08f)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818bb936)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In arch/x86/pci/irq.c (ffffffff8190895f)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
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
In drivers/pci/probe.c (ffffffff8162305d)
Location: include/linux/pci.h:1874
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff8162c2fc)
Location: include/linux/pci.h:1874
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pcie_print_link_status
  - drivers/pci/pci.c:pci_ea_read
```
```
In drivers/pci/pci-driver.c (ffffffff8162d59b)
Location: include/linux/pci.h:1874
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff81638b6d)
Location: include/linux/pci.h:1874
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_device_init
```
```
In drivers/pci/quirks.c (ffffffff81642af9)
Location: include/linux/pci.h:1874
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8164b8df)
Location: include/linux/pci.h:1874
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff8164f6d3)
Location: include/linux/pci.h:1874
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81650f98)
Location: include/linux/pci.h:1874
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/iov.c (ffffffff81656976)
Location: include/linux/pci.h:1874
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/acpi/pci_irq.c (ffffffff81695522)
Location: include/linux/pci.h:1874
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
```
In drivers/pnp/quirks.c (ffffffff816f952a)
Location: include/linux/pci.h:1874
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8170f0cd)
Location: include/linux/pci.h:1874
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817676ea)
Location: include/linux/pci.h:1874
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:moan_device
```
```
In drivers/char/agp/isoch.c (ffffffff8177dd99)
Location: include/linux/pci.h:1874
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179ee59)
Location: include/linux/pci.h:1874
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_insert_dev_scope
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff81873efa)
Location: include/linux/pci.h:1874
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81875c7a)
Location: include/linux/pci.h:1874
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a5cba)
Location: include/linux/pci.h:1874
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_bus_notifier
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_bus_notifier
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_match
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818a60bb)
Location: include/linux/pci.h:1874
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818d31ca)
Location: include/linux/pci.h:1874
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/edac/edac_pci.c (ffffffff8198b85f)
Location: include/linux/pci.h:1874
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8198c1ea)
Location: include/linux/pci.h:1874
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In arch/x86/pci/irq.c (ffffffff81bb92c6)
Location: include/linux/pci.h:1874
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
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
In drivers/pci/probe.c (ffffffff81bf7243)
Location: include/linux/pci.h:1882
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff8165205c)
Location: include/linux/pci.h:1882
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pcie_print_link_status
  - drivers/pci/pci.c:pci_ea_read
```
```
In drivers/pci/pci-driver.c (ffffffff81652c9e)
Location: include/linux/pci.h:1882
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff8165f67d)
Location: include/linux/pci.h:1882
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_device_init
```
```
In drivers/pci/pcie/rcec.c (ffffffff8166040a)
Location: include/linux/pci.h:1882
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:link_rcec_helper
```
```
In drivers/pci/quirks.c (ffffffff81668f59)
Location: include/linux/pci.h:1882
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8166fc5f)
Location: include/linux/pci.h:1882
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff81bfcfaa)
Location: include/linux/pci.h:1882
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81bfd8c3)
Location: include/linux/pci.h:1882
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/iov.c (ffffffff81676f2f)
Location: include/linux/pci.h:1882
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/acpi/pci_irq.c (ffffffff816b2772)
Location: include/linux/pci.h:1882
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
```
In drivers/pnp/quirks.c (ffffffff81c03d6e)
Location: include/linux/pci.h:1882
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8172be9d)
Location: include/linux/pci.h:1882
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81c07f2f)
Location: include/linux/pci.h:1882
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:moan_device
```
```
In drivers/char/agp/isoch.c (ffffffff81796aa9)
Location: include/linux/pci.h:1882
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/iommu/intel/dmar.c (ffffffff81c0c2a1)
Location: include/linux/pci.h:1882
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_insert_dev_scope
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff81882a9a)
Location: include/linux/pci.h:1882
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8188455a)
Location: include/linux/pci.h:1882
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81c1a068)
Location: include/linux/pci.h:1882
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_bus_notifier
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_bus_notifier
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_match
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818b4fab)
Location: include/linux/pci.h:1882
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818dca4a)
Location: include/linux/pci.h:1882
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/edac/edac_pci.c (ffffffff8198f44f)
Location: include/linux/pci.h:1882
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81c28bd9)
Location: include/linux/pci.h:1882
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In arch/x86/pci/irq.c (ffffffff81c349e5)
Location: include/linux/pci.h:1882
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
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
In drivers/pci/probe.c (ffffffff81be8e45)
Location: include/linux/pci.h:1898
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff81634b0c)
Location: include/linux/pci.h:1898
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pcie_print_link_status
  - drivers/pci/pci.c:pci_ea_read
```
```
In drivers/pci/pci-driver.c (ffffffff8163575e)
Location: include/linux/pci.h:1898
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff81641c67)
Location: include/linux/pci.h:1898
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/rcec.c (ffffffff816428ea)
Location: include/linux/pci.h:1898
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:link_rcec_helper
```
```
In drivers/pci/quirks.c (ffffffff8164b409)
Location: include/linux/pci.h:1898
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8165215f)
Location: include/linux/pci.h:1898
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff81beee85)
Location: include/linux/pci.h:1898
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81bef6a8)
Location: include/linux/pci.h:1898
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/iov.c (ffffffff816594fa)
Location: include/linux/pci.h:1898
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/acpi/pci_irq.c (ffffffff81694808)
Location: include/linux/pci.h:1898
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
```
In drivers/pnp/quirks.c (ffffffff81bf5702)
Location: include/linux/pci.h:1898
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8170fbed)
Location: include/linux/pci.h:1898
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81bf9aef)
Location: include/linux/pci.h:1898
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:moan_device
```
```
In drivers/char/agp/isoch.c (ffffffff81779779)
Location: include/linux/pci.h:1898
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/iommu/intel/dmar.c (ffffffff81bfdb0b)
Location: include/linux/pci.h:1898
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_insert_dev_scope
  - drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff818652ea)
Location: include/linux/pci.h:1898
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81866dda)
Location: include/linux/pci.h:1898
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81c0bf30)
Location: include/linux/pci.h:1898
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_bus_notifier
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_bus_notifier
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_match
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff8189844c)
Location: include/linux/pci.h:1898
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818bfdba)
Location: include/linux/pci.h:1898
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/edac/edac_pci.c (ffffffff81973a5f)
Location: include/linux/pci.h:1898
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81c1adcc)
Location: include/linux/pci.h:1898
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In arch/x86/pci/irq.c (ffffffff81c26dcd)
Location: include/linux/pci.h:1898
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
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
In drivers/pci/probe.c (ffffffff81ce325b)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff816a4bfc)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pcie_print_link_status
  - drivers/pci/pci.c:pci_ea_read
```
```
In drivers/pci/pci-driver.c (ffffffff816a561e)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff816b2901)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/rcec.c (ffffffff816b35e8)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:link_rcec_helper
```
```
In drivers/pci/quirks.c (ffffffff816bcdd9)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff816c3eac)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff81ce9ed7)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81cea95f)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/iov.c (ffffffff816cb66c)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/acpi/pci_irq.c (ffffffff8170a512)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
```
In drivers/pnp/quirks.c (ffffffff81cf2c99)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8178c59d)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81cfa068)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:moan_device
```
```
In drivers/char/agp/isoch.c (ffffffff817ff6a9)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/iommu/intel/dmar.c (ffffffff81cff0a0)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_insert_dev_scope
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff818f431a)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff818f6222)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81928eb1)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_bus_notifier
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_bus_notifier
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_match
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff8192bccc)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81956426)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/edac/edac_pci.c (ffffffff81a1c75f)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d2acfc)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In arch/x86/pci/irq.c (ffffffff81d44d58)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
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
In drivers/pci/probe.c (ffffffff81ea9d71)
Location: include/linux/pci.h:1978
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff817c70b5)
Location: include/linux/pci.h:1978
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pcie_print_link_status
  - drivers/pci/pci.c:pci_ea_read
```
```
In drivers/pci/pci-driver.c (ffffffff817c7c12)
Location: include/linux/pci.h:1978
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff817d626b)
Location: include/linux/pci.h:1978
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/rcec.c (ffffffff817d6a20)
Location: include/linux/pci.h:1978
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:link_rcec_helper
```
```
In drivers/pci/pcie/edr.c (ffffffff81ead72e)
Location: include/linux/pci.h:1978
Inline: True
Inline callers:
  - drivers/pci/pcie/edr.c:edr_handle_event
```
```
In drivers/pci/quirks.c (ffffffff817e1e8e)
Location: include/linux/pci.h:1978
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff817e99ff)
Location: include/linux/pci.h:1978
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff81eb0f96)
Location: include/linux/pci.h:1978
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81eb19dc)
Location: include/linux/pci.h:1978
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/iov.c (ffffffff817f1cef)
Location: include/linux/pci.h:1978
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/vgaarb.c (ffffffff817f366a)
Location: include/linux/pci.h:1978
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_arb_read
```
```
In drivers/acpi/pci_irq.c (ffffffff8183899e)
Location: include/linux/pci.h:1978
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
```
In drivers/pnp/quirks.c (ffffffff81ebae2b)
Location: include/linux/pci.h:1978
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff818c41ed)
Location: include/linux/pci.h:1978
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
```
```
In drivers/char/agp/isoch.c (ffffffff8193ea17)
Location: include/linux/pci.h:1978
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/iommu/intel/dmar.c (ffffffff81ec7873)
Location: include/linux/pci.h:1978
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_insert_dev_scope
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81a47278)
Location: include/linux/pci.h:1978
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a7ee76)
Location: include/linux/pci.h:1978
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_bus_notifier
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_bus_notifier
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_match
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81a823c3)
Location: include/linux/pci.h:1978
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81aafffd)
Location: include/linux/pci.h:1978
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/edac/edac_pci.c (ffffffff81b85824)
Location: include/linux/pci.h:1978
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81ef6e9b)
Location: include/linux/pci.h:1978
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In arch/x86/pci/irq.c (ffffffff81f11ca7)
Location: include/linux/pci.h:1978
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_get_info
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
In drivers/pwm/pwm-lpss-pci.c (ffffffff818d1ec1)
Location: include/linux/pci.h:2017
Inline: True
```
```
In drivers/pci/probe.c (ffffffff818d4c26)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff818e4597)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pcie_print_link_status
  - drivers/pci/pci.c:pci_ea_read
```
```
In drivers/pci/pci-driver.c (ffffffff818e53d2)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend
```
```
In drivers/pci/pcie/portdrv.c (ffffffff818f7add)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
```
```
In drivers/pci/pcie/rcec.c (ffffffff818f7fd3)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:link_rcec_helper
```
```
In drivers/pci/pcie/edr.c (ffffffff818ffdc8)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - drivers/pci/pcie/edr.c:edr_handle_event
```
```
In drivers/pci/quirks.c (ffffffff8190587e)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8190f9df)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff8191410c)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81915a78)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/iov.c (ffffffff8191a25f)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/p2pdma.c (ffffffff8191ca07)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
```
```
In drivers/pci/vgaarb.c (ffffffff8191dc3a)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_arb_read
```
```
In drivers/pci/doe.c (ffffffff81920475)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - drivers/pci/doe.c:pcim_doe_create_mb
```
```
In drivers/acpi/pci_irq.c (ffffffff8196ddcd)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
```
In drivers/pnp/quirks.c (ffffffff819f0bec)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81a148cd)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
```
```
In drivers/char/agp/isoch.c (ffffffff81a9fbb8)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abdb3c)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_insert_dev_scope
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81bce2f8)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81c380fd)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/edac/edac_pci.c (ffffffff81d24ab4)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d24fe6)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In arch/x86/pci/irq.c (ffffffff8201b3f2)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_get_info
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
In drivers/pwm/pwm-lpss-pci.c (ffffffff81914ec1)
Location: include/linux/pci.h:2109
Inline: True
```
```
In drivers/pci/probe.c (ffffffff81917e76)
Location: include/linux/pci.h:2109
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff81927be7)
Location: include/linux/pci.h:2109
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pcie_print_link_status
  - drivers/pci/pci.c:pci_ea_read
```
```
In drivers/pci/pci-driver.c (ffffffff81928a12)
Location: include/linux/pci.h:2109
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend
```
```
In drivers/pci/pcie/portdrv.c (ffffffff8193af36)
Location: include/linux/pci.h:2109
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
```
```
In drivers/pci/pcie/rcec.c (ffffffff8193b433)
Location: include/linux/pci.h:2109
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:link_rcec_helper
```
```
In drivers/pci/pcie/edr.c (ffffffff8194333b)
Location: include/linux/pci.h:2109
Inline: True
Inline callers:
  - drivers/pci/pcie/edr.c:edr_handle_event
```
```
In drivers/pci/quirks.c (ffffffff81948ebe)
Location: include/linux/pci.h:2109
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81953103)
Location: include/linux/pci.h:2109
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff8195776c)
Location: include/linux/pci.h:2109
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81959085)
Location: include/linux/pci.h:2109
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/iov.c (ffffffff8195d88f)
Location: include/linux/pci.h:2109
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/p2pdma.c (ffffffff8195ffc5)
Location: include/linux/pci.h:2109
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
```
```
In drivers/pci/vgaarb.c (ffffffff819611ea)
Location: include/linux/pci.h:2109
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_arb_read
```
```
In drivers/pci/doe.c (ffffffff819636e6)
Location: include/linux/pci.h:2109
Inline: True
Inline callers:
  - drivers/pci/doe.c:pci_doe_create_mb
```
```
In drivers/acpi/pci_irq.c (ffffffff819b42fd)
Location: include/linux/pci.h:2109
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
```
In drivers/pnp/quirks.c (ffffffff81a393cc)
Location: include/linux/pci.h:2109
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81a5d92d)
Location: include/linux/pci.h:2109
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
```
```
In drivers/char/agp/isoch.c (ffffffff81aeb4d8)
Location: include/linux/pci.h:2109
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b0a4d3)
Location: include/linux/pci.h:2109
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_insert_dev_scope
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81c25ee8)
Location: include/linux/pci.h:2109
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81c9f4bd)
Location: include/linux/pci.h:2109
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/edac/edac_pci.c (ffffffff81d8dcd4)
Location: include/linux/pci.h:2109
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d8e206)
Location: include/linux/pci.h:2109
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In arch/x86/pci/irq.c (ffffffff8209ba72)
Location: include/linux/pci.h:2109
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_get_info
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
In drivers/pwm/pwm-lpss-pci.c (ffffffff8195ce31)
Location: include/linux/pci.h:2175
Inline: True
```
```
In drivers/pci/probe.c (ffffffff81960486)
Location: include/linux/pci.h:2175
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff81970387)
Location: include/linux/pci.h:2175
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pcie_print_link_status
  - drivers/pci/pci.c:pci_ea_read
```
```
In drivers/pci/pci-driver.c (ffffffff81971225)
Location: include/linux/pci.h:2175
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_pm_runtime_suspend
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_legacy_suspend
```
```
In drivers/pci/pcie/portdrv.c (ffffffff81983dc9)
Location: include/linux/pci.h:2175
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
```
```
In drivers/pci/pcie/rcec.c (ffffffff819842c3)
Location: include/linux/pci.h:2175
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:link_rcec_helper
```
```
In drivers/pci/pcie/edr.c (ffffffff8198c60b)
Location: include/linux/pci.h:2175
Inline: True
Inline callers:
  - drivers/pci/pcie/edr.c:edr_handle_event
```
```
In drivers/pci/quirks.c (ffffffff8199226e)
Location: include/linux/pci.h:2175
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8199c593)
Location: include/linux/pci.h:2175
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff819a0cdc)
Location: include/linux/pci.h:2175
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff819a25f5)
Location: include/linux/pci.h:2175
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/iov.c (ffffffff819a6eef)
Location: include/linux/pci.h:2175
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pci/p2pdma.c (ffffffff819a96aa)
Location: include/linux/pci.h:2175
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
```
```
In drivers/pci/vgaarb.c (ffffffff819aa969)
Location: include/linux/pci.h:2175
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_arb_read
```
```
In drivers/pci/doe.c (ffffffff819acd93)
Location: include/linux/pci.h:2175
Inline: True
Inline callers:
  - drivers/pci/doe.c:pci_doe_create_mb
```
```
In drivers/acpi/pci_irq.c (ffffffff819fe8fd)
Location: include/linux/pci.h:2175
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
```
In drivers/pnp/quirks.c (ffffffff81a84bec)
Location: include/linux/pci.h:2175
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81aaf8dd)
Location: include/linux/pci.h:2175
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
```
```
In drivers/char/agp/isoch.c (ffffffff81b3ea1d)
Location: include/linux/pci.h:2175
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5e523)
Location: include/linux/pci.h:2175
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_insert_dev_scope
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81cd8668)
Location: include/linux/pci.h:2175
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81d5410d)
Location: include/linux/pci.h:2175
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/edac/edac_pci.c (ffffffff81e455b4)
Location: include/linux/pci.h:2175
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81e45ae6)
Location: include/linux/pci.h:2175
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In arch/x86/pci/irq.c (ffffffff82173208)
Location: include/linux/pci.h:2175
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_get_info
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
In drivers/pci/probe.c (ffff8000106deeac)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffff8000106e9f0c)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pcie_print_link_status
  - drivers/pci/pci.c:pci_ea_init
```
```
In drivers/pci/pci-driver.c (ffff8000106eb4d4)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_uevent
```
```
In drivers/pci/quirks.c (ffff8000106fb940)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
```
In drivers/pci/pcie/portdrv_core.c (ffff8000107008cc)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/err.c (ffff8000107017a0)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffff80001070b630)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffff80001070f47c)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffff800010711194)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/iov.c (ffff800010716fb8)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pnp/quirks.c (ffff8000107b72c0)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/virtio/virtio_pci_common.c (ffff800010828dfc)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
```
```
In drivers/tty/serial/8250/8250_pci.c (ffff8000108904fc)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:moan_device
```
```
In drivers/gpu/vga/vgaarb.c (ffff8000109c0d78)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
```
```
In drivers/usb/core/hcd-pci.c (ffff800010a36ef0)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffff800010a90fb0)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/edac/edac_pci.c (ffff800010b13750)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/edac/edac_pci_sysfs.c (ffff800010b13dc0)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
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
In arch/arm/kernel/bios32.c (c0310ed8)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - arch/arm/kernel/bios32.c:pcibios_map_irq
  - arch/arm/kernel/bios32.c:pcibios_swizzle
  - arch/arm/kernel/bios32.c:pcibios_bus_report_status
```
```
In drivers/pci/probe.c (c087abb0)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (c0884e90)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pcie_print_link_status
  - drivers/pci/pci.c:pci_ea_init
```
```
In drivers/pci/pci-driver.c (c0886e90)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_uevent
```
```
In drivers/pci/quirks.c (c0893e8c)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
```
In drivers/pci/pcie/portdrv_core.c (c0898684)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/err.c (c0899368)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/iov.c (c08a1768)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/virtio/virtio_pci_common.c (c0946aac)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
```
```
In drivers/tty/serial/8250/8250_pci.c (c098ccd4)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:moan_device
```
```
In drivers/gpu/vga/vgaarb.c (c0a8d2dc)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
```
```
In drivers/usb/core/hcd-pci.c (c0b0a2f8)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (c0b6340c)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/edac/edac_pci.c (c0bf16f8)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/edac/edac_pci_sysfs.c (c0bf1b38)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
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
In arch/powerpc/kernel/eeh.c (c000000000045f20)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh.c:eeh_pe_reset
  - arch/powerpc/kernel/eeh.c:pcibios_set_pcie_reset_state
```
```
In arch/powerpc/kernel/eeh_cache.c (c000000000048128)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh_cache.c:eeh_addr_cache_show
  - arch/powerpc/kernel/eeh_cache.c:eeh_addr_cache_insert_dev
  - arch/powerpc/kernel/eeh_cache.c:eeh_addr_cache_insert_dev
```
```
In arch/powerpc/kernel/eeh_driver.c (c0000000000495a0)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh_driver.c:eeh_rmv_device
```
```
In arch/powerpc/kernel/pci_64.c (c000000000069e28)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci_64.c:pcibios_map_io_space
  - arch/powerpc/kernel/pci_64.c:pcibios_unmap_io_space
```
```
In arch/powerpc/kernel/pci-hotplug.c (c00000000006b260)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci-hotplug.c:pci_hp_remove_devices
```
```
In arch/powerpc/kernel/isa-bridge.c (c00000000006b888)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - arch/powerpc/kernel/isa-bridge.c:isa_bridge_notify
  - arch/powerpc/kernel/isa-bridge.c:isa_bridge_notify
```
```
In arch/powerpc/kernel/pci-common.c (c00000000006c640)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_claim_one_bus
  - arch/powerpc/kernel/pci-common.c:pcibios_allocate_resources
  - arch/powerpc/kernel/pci-common.c:pcibios_allocate_resources
  - arch/powerpc/kernel/pci-common.c:pcibios_allocate_resources
  - arch/powerpc/kernel/pci-common.c:pcibios_allocate_bus_resources
  - arch/powerpc/kernel/pci-common.c:pcibios_setup_bus_devices
  - arch/powerpc/kernel/pci-common.c:pcibios_setup_device
  - arch/powerpc/kernel/pci-common.c:pcibios_setup_bus_self
  - arch/powerpc/kernel/pci-common.c:pcibios_setup_bus_self
```
```
In arch/powerpc/kernel/pci_of_scan.c (c00000000006f738)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci_of_scan.c:of_create_pci_dev
```
```
In arch/powerpc/sysdev/mpic_u3msi.c (c0000000000b76ac)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - arch/powerpc/sysdev/mpic_u3msi.c:u3msi_setup_msi_irqs
```
```
In arch/powerpc/platforms/powernv/pci.c (c0000000000d0818)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci.c:pnv_setup_msi_irqs
  - arch/powerpc/platforms/powernv/pci.c:pnv_setup_msi_irqs
  - arch/powerpc/platforms/powernv/pci.c:pnv_setup_msi_irqs
  - arch/powerpc/platforms/powernv/pci.c:pnv_setup_msi_irqs
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000000d8904)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_msi_setup
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_msi_setup
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_msi_setup
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_setup_same_PE
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_setup_dev_PE
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_setup_dev_PE
```
```
In arch/powerpc/platforms/powernv/pci-cxl.c (c0000000000dc1a0)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-cxl.c:pnv_cxl_ioda_msi_setup
```
```
In arch/powerpc/platforms/pseries/setup.c (c0000000000ee858)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/setup.c:of_pci_parse_iov_addrs
  - arch/powerpc/platforms/pseries/setup.c:of_pci_set_vf_bar_size
```
```
In arch/powerpc/platforms/pseries/iommu.c (c0000000000f0cf0)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/iommu.c:pci_dma_dev_setup_pSeriesLP
  - arch/powerpc/platforms/pseries/iommu.c:pci_dma_dev_setup_pSeriesLP
  - arch/powerpc/platforms/pseries/iommu.c:pci_dma_dev_setup_pSeries
  - arch/powerpc/platforms/pseries/iommu.c:pci_dma_dev_setup_pSeries
```
```
In arch/powerpc/platforms/pseries/msi.c (c0000000000f7740)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/msi.c:msi_quota_for_device
  - arch/powerpc/platforms/pseries/msi.c:msi_quota_for_device
  - arch/powerpc/platforms/pseries/msi.c:msi_quota_for_device
```
```
In drivers/pci/probe.c (c000000000857d74)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (c0000000008650a0)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pcie_print_link_status
  - drivers/pci/pci.c:pci_ea_init
```
```
In drivers/pci/pci-driver.c (c000000000866cc8)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_uevent
```
```
In drivers/pci/quirks.c (c000000000879864)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
```
In drivers/pci/iov.c (c000000000887a68)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/virtio/virtio_pci_common.c (c0000000008d54fc)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
```
```
In drivers/tty/serial/8250/8250_pci.c (c00000000093a36c)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:moan_device
```
```
In drivers/char/agp/isoch.c (c00000000095783c)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/gpu/vga/vgaarb.c (c000000000a80d9c)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (c000000000ab7fe0)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
```
```
In drivers/usb/core/hcd-pci.c (c000000000af48c8)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (c000000000b6c710)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/edac/edac_pci.c (c000000000c082dc)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/edac/edac_pci_sysfs.c (c000000000c089c8)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
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
In drivers/pci/probe.c (ffffffe0004b6fda)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffe0004c0118)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pcie_print_link_status
  - drivers/pci/pci.c:pci_ea_init
```
```
In drivers/pci/pci-driver.c (ffffffe0004c0d9e)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_uevent
```
```
In drivers/pci/quirks.c (ffffffe0004cb66e)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffe0004cf806)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/err.c (ffffffe0004d034a)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffe0004d8262)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffe0004db788)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffe0004dd076)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/iov.c (ffffffe0004e0320)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/virtio/virtio_pci_common.c (ffffffe00051f16c)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffe0005596ce)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:moan_device
```
```
In drivers/gpu/vga/vgaarb.c (ffffffe000612c48)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
```
```
In drivers/usb/core/hcd-pci.c (ffffffe0006539e0)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffe0006a39ca)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/edac/edac_pci.c (ffffffe00070014c)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffe000700596)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
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
In drivers/pci/probe.c (ffffffff815728ce)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff8157a6a2)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pcie_print_link_status
  - drivers/pci/pci.c:pci_ea_init
```
```
In drivers/pci/pci-driver.c (ffffffff8157b7cb)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_uevent
```
```
In drivers/pci/quirks.c (ffffffff815884b9)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff8158d0c8)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/err.c (ffffffff8158dd55)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8159656f)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff8159a1d5)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8159b9ef)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/iov.c (ffffffff815a08d5)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pnp/quirks.c (ffffffff816104aa)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81625d4d)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8167999d)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:moan_device
```
```
In drivers/char/agp/isoch.c (ffffffff8168ec49)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/iommu/dmar.c (ffffffff816addc1)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff81772a3a)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff817742f9)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817baaf7)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff818061fc)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/edac/edac_pci.c (ffffffff81860f0f)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818617b6)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In arch/x86/pci/irq.c (ffffffff818a7d1f)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
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
In drivers/pci/probe.c (ffffffff8156102e)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff81568de2)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pcie_print_link_status
  - drivers/pci/pci.c:pci_ea_init
```
```
In drivers/pci/pci-driver.c (ffffffff8156a3fb)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_uevent
```
```
In drivers/pci/quirks.c (ffffffff81577269)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff8157bc08)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/err.c (ffffffff8157c895)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815856ff)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff81589365)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8158ab7f)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/iov.c (ffffffff8158fa65)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/pnp/quirks.c (ffffffff816049fa)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8161a3cd)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81658a8d)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:moan_device
```
```
In drivers/char/agp/isoch.c (ffffffff8166c639)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/iommu/dmar.c (ffffffff8168b721)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff817527ea)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff817540a9)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81782622)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817ac517)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817cd97c)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/edac/edac_pci.c (ffffffff818284df)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81828d66)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In arch/x86/pci/irq.c (ffffffff8186283f)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
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
In drivers/pci/probe.c (ffffffff815720fe)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff81579ed2)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pcie_print_link_status
  - drivers/pci/pci.c:pci_ea_init
```
```
In drivers/pci/pci-driver.c (ffffffff8157b4eb)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_uevent
```
```
In drivers/pci/quirks.c (ffffffff81588379)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff8158cf88)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/err.c (ffffffff8158dc15)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81596aaf)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff8159a715)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8159bf2f)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/iov.c (ffffffff815a0e55)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/acpi/pci_irq.c (ffffffff815dde6f)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
```
In drivers/pnp/quirks.c (ffffffff8163e28a)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81653d1d)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816a7d7d)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:moan_device
```
```
In drivers/char/agp/isoch.c (ffffffff816bceb9)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/iommu/dmar.c (ffffffff816dbfa1)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff817a2d9a)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff817a4649)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817cd3f2)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817f7597)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff818452ac)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-amd-mp2-pci.c (ffffffff81868262)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe
```
```
In drivers/edac/edac_pci.c (ffffffff818b053f)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818b0de6)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In arch/x86/pci/irq.c (ffffffff818f937f)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
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
In drivers/pci/probe.c (ffffffff8158c5de)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:__pci_read_base
```
```
In drivers/pci/pci.c (ffffffff81594382)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pcie_print_link_status
  - drivers/pci/pci.c:pci_ea_init
```
```
In drivers/pci/pci-driver.c (ffffffff81595afb)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_uevent
```
```
In drivers/pci/quirks.c (ffffffff815a2829)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff815a7438)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/pci/pcie/err.c (ffffffff815a80c5)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815b0f2f)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff815b4b55)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815b635f)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/iov.c (ffffffff815bb285)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
```
In drivers/acpi/pci_irq.c (ffffffff815f7d2f)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
```
In drivers/pnp/quirks.c (ffffffff816585da)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_intel_mch
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8166e3ad)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_bus_name
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816c21dd)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:moan_device
```
```
In drivers/char/agp/isoch.c (ffffffff816d7489)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/iommu/dmar.c (ffffffff816f6571)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_insert_dev_scope
  - drivers/iommu/dmar.c:dmar_alloc_pci_notify_info
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff817bcc1a)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff817be4c9)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_show
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817e7692)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818117d7)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff8185f82c)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/edac/edac_pci.c (ffffffff818cc7cf)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818cd076)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
  - drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test
```
```
In arch/x86/pci/irq.c (ffffffff8191a47f)
Location: include/linux/pci.h:1864
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
```
</details>
</li>
</ul>

## Differences
