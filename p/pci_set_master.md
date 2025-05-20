# Function: <code>pci_set_master</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void pci_set_master(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81437e40)
Location: drivers/pci/pci.c:3119
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_reenable_device
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/dwc2/pci.c:dwc2_pci_probe
```
**Symbols:**

```
ffffffff81437e40-ffffffff81437e62: pci_set_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void pci_set_master(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81483b70)
Location: drivers/pci/pci.c:3429
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_reenable_device
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81483ad0-ffffffff81483af2: pci_set_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void pci_set_master(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a52d0)
Location: drivers/pci/pci.c:3467
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_reenable_device
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff814a5230-ffffffff814a5252: pci_set_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pci_set_master(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814af2db)
Location: drivers/pci/pci.c:3605
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_reenable_device
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff814af240-ffffffff814af262: pci_set_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pci_set_master(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ee7fb)
Location: drivers/pci/pci.c:3620
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_reenable_device
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff814ee760-ffffffff814ee782: pci_set_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pci_set_master(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151e480)
Location: drivers/pci/pci.c:3804
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_reenable_device
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
```
**Symbols:**

```
ffffffff8151e3e0-ffffffff8151e402: pci_set_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pci_set_master(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81534210)
Location: drivers/pci/pci.c:4069
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_reenable_device
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81534170-ffffffff81534192: pci_set_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pci_set_master(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815636e5)
Location: drivers/pci/pci.c:4167
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_reenable_device
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81563650-ffffffff81563674: pci_set_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pci_set_master(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815848a5)
Location: drivers/pci/pci.c:4163
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_reenable_device
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81584810-ffffffff81584834: pci_set_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pci_set_master(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162b47c)
Location: drivers/pci/pci.c:4234
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/ata/libata-core.c:ata_pci_device_resume
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff8162b3e0-ffffffff8162b406: pci_set_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pci_set_master(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8165117c)
Location: drivers/pci/pci.c:4309
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/ata/libata-core.c:ata_pci_device_resume
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff816510e0-ffffffff81651106: pci_set_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pci_set_master(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81633bbc)
Location: drivers/pci/pci.c:4341
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/ata/libata-core.c:ata_pci_device_resume
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81633b20-ffffffff81633b46: pci_set_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pci_set_master(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a3d6c)
Location: drivers/pci/pci.c:4391
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/ata/libata-core.c:ata_pci_device_resume
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff816a3cd0-ffffffff816a3cf6: pci_set_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pci_set_master(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c6113)
Location: drivers/pci/pci.c:4487
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/ata/libata-core.c:ata_pci_device_resume
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff817c6070-ffffffff817c609d: pci_set_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_set_master(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e344f)
Location: drivers/pci/pci.c:4430
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_mid.c:dnv_setup
  - drivers/ata/libata-core.c:ata_pci_device_resume
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff818e33a0-ffffffff818e33cd: pci_set_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_set_master(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8192689f)
Location: drivers/pci/pci.c:4468
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_mid.c:dnv_setup
  - drivers/ata/libata-core.c:ata_pci_device_resume
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff819267f0-ffffffff8192681d: pci_set_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_set_master(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196f03f)
Location: drivers/pci/pci.c:4578
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_thaw
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_legacy_resume
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_resume
  - drivers/tty/serial/8250/8250_mid.c:dnv_setup
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/ata/libata-core.c:ata_pci_device_resume
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff8196ef90-ffffffff8196efbd: pci_set_master (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void pci_set_master(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e8e1c)
Location: drivers/pci/pci.c:4163
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_reenable_device
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffff8000106e8d78-ffff8000106e8db0: pci_set_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pci_set_master(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0883e40)
Location: drivers/pci/pci.c:4163
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_reenable_device
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/dwc2/pci.c:dwc2_pci_probe
```
**Symbols:**

```
c0883db4-c0883de0: pci_set_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pci_set_master(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000863bb0)
Location: drivers/pci/pci.c:4163
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_enable_bridge
  - drivers/pci/pci-driver.c:pci_pm_reenable_device
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
c000000000863ad0-c000000000863b1c: pci_set_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pci_set_master(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bf2c4)
Location: drivers/pci/pci.c:4163
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffe0004bf226-ffffffe0004bf25c: pci_set_master (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void pci_set_master(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81578dc5)
Location: drivers/pci/pci.c:4163
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_reenable_device
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81578d30-ffffffff81578d54: pci_set_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pci_set_master(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81567505)
Location: drivers/pci/pci.c:4163
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_reenable_device
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81567470-ffffffff81567494: pci_set_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pci_set_master(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815785f5)
Location: drivers/pci/pci.c:4163
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_reenable_device
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe
```
**Symbols:**

```
ffffffff81578560-ffffffff81578584: pci_set_master (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pci_set_master(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81592ab5)
Location: drivers/pci/pci.c:4163
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_reenable_device
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/ata/libata-core.c:ata_pci_device_do_resume
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81592a20-ffffffff81592a44: pci_set_master (STB_GLOBAL)
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
