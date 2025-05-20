# Function: <code>pci_enable_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81438070)
Location: drivers/pci/pci.c:1398
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:resume_common
```
**Symbols:**

```
ffffffff81438070-ffffffff81438085: pci_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81483d71)
Location: drivers/pci/pci.c:1419
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81483d10-ffffffff81483d25: pci_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a54d1)
Location: drivers/pci/pci.c:1444
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff814a5470-ffffffff814a5485: pci_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814af4d1)
Location: drivers/pci/pci.c:1442
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
Direct callers:
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff814af470-ffffffff814af485: pci_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ee9f1)
Location: drivers/pci/pci.c:1445
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
Direct callers:
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff814ee990-ffffffff814ee9a5: pci_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151e671)
Location: drivers/pci/pci.c:1496
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
```
**Symbols:**

```
ffffffff8151e610-ffffffff8151e625: pci_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81534401)
Location: drivers/pci/pci.c:1669
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff815343a0-ffffffff815343b5: pci_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815638d1)
Location: drivers/pci/pci.c:1743
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff81563870-ffffffff81563885: pci_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81584a91)
Location: drivers/pci/pci.c:1739
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff81584a30-ffffffff81584a45: pci_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162b6b1)
Location: drivers/pci/pci.c:1809
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/eisa/pci_eisa.c:pci_eisa_init
```
**Symbols:**

```
ffffffff8162b650-ffffffff8162b665: pci_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816513b1)
Location: drivers/pci/pci.c:1945
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/eisa/pci_eisa.c:pci_eisa_init
```
**Symbols:**

```
ffffffff81651350-ffffffff81651365: pci_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81633dc1)
Location: drivers/pci/pci.c:1975
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff81633d60-ffffffff81633d75: pci_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a3fa1)
Location: drivers/pci/pci.c:2006
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff816a3f40-ffffffff816a3f55: pci_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c6370)
Location: drivers/pci/pci.c:2071
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff817c6300-ffffffff817c631d: pci_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e3710)
Location: drivers/pci/pci.c:2045
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff818e3690-ffffffff818e36ad: pci_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81926b60)
Location: drivers/pci/pci.c:2083
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff81926ae0-ffffffff81926afd: pci_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196f300)
Location: drivers/pci/pci.c:2180
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/pci/pci.c:pci_enable_bridge
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff8196f280-ffffffff8196f29d: pci_enable_device (STB_GLOBAL)
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
int pci_enable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e90c0)
Location: drivers/pci/pci.c:1739
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
Direct callers:
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffff8000106e9030-ffff8000106e9060: pci_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0884084)
Location: drivers/pci/pci.c:1739
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
Direct callers:
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one
  - drivers/mfd/sm501.c:sm501_pci_probe
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
c0884014-c0884034: pci_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000863ed0)
Location: drivers/pci/pci.c:1739
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
Direct callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_enable_bridge
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/video/fbdev/gxt4500.c:gxt4500_probe
  - drivers/video/fbdev/offb.c:offb_init_nodriver
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
c000000000863e20-c000000000863e38: pci_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bf4ce)
Location: drivers/pci/pci.c:1739
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
Direct callers:
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_resume
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffe0004bf450-ffffffe0004bf47e: pci_enable_device (STB_GLOBAL)
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
int pci_enable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81578fb1)
Location: drivers/pci/pci.c:1739
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff81578f50-ffffffff81578f65: pci_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815676f1)
Location: drivers/pci/pci.c:1739
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff81567690-ffffffff815676a5: pci_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815787e1)
Location: drivers/pci/pci.c:1739
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_resume
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff81578780-ffffffff81578795: pci_enable_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pci_enable_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81592ca1)
Location: drivers/pci/pci.c:1739
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_enable_device
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_probe
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci-sysfs.c:enable_store
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:virtio_pci_restore
  - drivers/tty/serial/8250/8250_pci.c:pciserial_resume_one
  - drivers/char/agp/intel-agp.c:agp_intel_probe
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/usb/core/hcd-pci.c:resume_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff81592c40-ffffffff81592c55: pci_enable_device (STB_GLOBAL)
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
