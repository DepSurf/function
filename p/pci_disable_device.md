# Function: <code>pci_disable_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81436ce0)
Location: drivers/pci/pci.c:1586
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_freeze
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/core/hcd-pci.c:suspend_common
```
**Symbols:**

```
ffffffff81436ce0-ffffffff81436da5: pci_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81482870)
Location: drivers/pci/pci.c:1607
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_freeze
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81482870-ffffffff8148293a: pci_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a3e00)
Location: drivers/pci/pci.c:1632
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/acpi/ioapic.c:acpi_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_freeze
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff814a3e00-ffffffff814a3eca: pci_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ade20)
Location: drivers/pci/pci.c:1630
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_freeze
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff814ade20-ffffffff814adedd: pci_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ed200)
Location: drivers/pci/pci.c:1633
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_freeze
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff814ed200-ffffffff814ed2bd: pci_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151ce20)
Location: drivers/pci/pci.c:1688
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_freeze
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_remove
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
```
**Symbols:**

```
ffffffff8151ce20-ffffffff8151cec9: pci_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81532520)
Location: drivers/pci/pci.c:1861
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_freeze
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81532520-ffffffff815325c9: pci_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81561bf0)
Location: drivers/pci/pci.c:1936
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_freeze
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81561bf0-ffffffff81561c99: pci_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81582d90)
Location: drivers/pci/pci.c:1932
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_freeze
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81582d90-ffffffff81582e39: pci_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816298a0)
Location: drivers/pci/pci.c:2002
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_freeze
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/ata/libata-core.c:ata_pci_device_suspend
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff816298a0-ffffffff816299c4: pci_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164fc70)
Location: drivers/pci/pci.c:2138
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_freeze
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/ata/libata-core.c:ata_pci_device_suspend
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff8164fc70-ffffffff8164fd94: pci_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81632830)
Location: drivers/pci/pci.c:2168
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_freeze
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/ata/libata-core.c:ata_pci_device_suspend
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81632830-ffffffff81632954: pci_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pci_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2199
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_freeze
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/ata/libata-core.c:ata_pci_device_suspend
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81ce4890-ffffffff81ce48a5: pci_disable_device.cold (STB_LOCAL)
ffffffff816a2990-ffffffff816a2ac3: pci_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2259
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_freeze
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/ata/libata-core.c:ata_pci_device_suspend
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81eab2f5-ffffffff81eab30a: pci_disable_device.cold (STB_LOCAL)
ffffffff817c4b40-ffffffff817c4c2d: pci_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void pci_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2233
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_remove
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_freeze
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/ata/libata-core.c:ata_pci_device_suspend
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff8208f1d5-ffffffff8208f1ea: pci_disable_device.cold (STB_LOCAL)
ffffffff818e1b20-ffffffff818e1c0d: pci_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void pci_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2271
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_remove
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_freeze
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/ata/libata-core.c:ata_pci_device_suspend
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_clean_structure
  - drivers/platform/x86/intel/pmc/core_ssram.c:pmc_core_ssram_init
```
**Symbols:**

```
ffffffff8210f53b-ffffffff8210f550: pci_disable_device.cold (STB_LOCAL)
ffffffff81924f60-ffffffff8192504d: pci_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void pci_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2368
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_remove
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_suspend
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/ata/libata-core.c:ata_pci_device_suspend
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff821ed1c2-ffffffff821ed1d7: pci_disable_device.cold (STB_LOCAL)
ffffffff8196d630-ffffffff8196d71d: pci_disable_device (STB_GLOBAL)
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
void pci_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e6ae8)
Location: drivers/pci/pci.c:1932
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_freeze
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffff8000106e6ae8-ffff8000106e6bcc: pci_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0881db0)
Location: drivers/pci/pci.c:1932
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_freeze
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/mfd/sm501.c:sm501_pci_remove
  - drivers/mfd/sm501.c:sm501_pci_probe
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
c0881db0-c0881e98: pci_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000860f60)
Location: drivers/pci/pci.c:1932
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_freeze
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
c000000000860f60-c0000000008610ac: pci_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bd43a)
Location: drivers/pci/pci.c:1932
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_suspend
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffe0004bd43a-ffffffe0004bd500: pci_disable_device (STB_GLOBAL)
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
void pci_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815772b0)
Location: drivers/pci/pci.c:1932
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_freeze
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_dev_disable
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff815772b0-ffffffff81577359: pci_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81565a10)
Location: drivers/pci/pci.c:1932
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_freeze
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_dev_disable
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81565a10-ffffffff81565ab9: pci_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81576ae0)
Location: drivers/pci/pci.c:1932
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_freeze
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_suspend
```
**Symbols:**

```
ffffffff81576ae0-ffffffff81576b89: pci_disable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_disable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81590fc0)
Location: drivers/pci/pci.c:1932
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/acpi/ioapic.c:pci_ioapic_remove
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_freeze
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/ata/libata-core.c:ata_pci_device_do_suspend
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81590fc0-ffffffff81591069: pci_disable_device (STB_GLOBAL)
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
