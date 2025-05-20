# Function: <code>dma_set_mask</code>

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
In drivers/char/agp/intel-gtt.c (ffffffff81522d94)
Location: include/asm-generic/dma-mapping-common.h:344
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffff815dd895)
Location: include/asm-generic/dma-mapping-common.h:344
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8162a370)
Location: include/asm-generic/dma-mapping-common.h:344
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8163d3d5)
Location: include/asm-generic/dma-mapping-common.h:344
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8164428e)
Location: include/asm-generic/dma-mapping-common.h:344
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/xhci.c (ffffffff8164e23c)
Location: include/asm-generic/dma-mapping-common.h:344
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
In drivers/virtio/virtio_pci_modern.c (ffffffff81512348)
Location: include/linux/dma-mapping.h:499
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff815139d6)
Location: include/linux/dma-mapping.h:499
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81575d31)
Location: include/linux/dma-mapping.h:499
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/ata/libata-sff.c (ffffffff81637617)
Location: include/linux/dma-mapping.h:499
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8168a278)
Location: include/linux/dma-mapping.h:499
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8169dff1)
Location: include/linux/dma-mapping.h:499
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816a4d51)
Location: include/linux/dma-mapping.h:499
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/xhci.c (ffffffff816aeb63)
Location: include/linux/dma-mapping.h:499
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
In drivers/virtio/virtio_mmio.c (ffffffff8153d75f)
Location: include/linux/dma-mapping.h:551
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff8153e6e7)
Location: include/linux/dma-mapping.h:551
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff8153fdf6)
Location: include/linux/dma-mapping.h:551
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815a23c1)
Location: include/linux/dma-mapping.h:551
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/ata/libata-sff.c (ffffffff816686b7)
Location: include/linux/dma-mapping.h:551
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816b83e4)
Location: include/linux/dma-mapping.h:551
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-platform.c (ffffffff816cc130)
Location: include/linux/dma-mapping.h:551
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816d2e51)
Location: include/linux/dma-mapping.h:551
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/xhci.c (ffffffff816dcd03)
Location: include/linux/dma-mapping.h:551
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
In drivers/virtio/virtio_mmio.c (ffffffff81551400)
Location: include/linux/dma-mapping.h:587
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff81552417)
Location: include/linux/dma-mapping.h:587
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff81553bc6)
Location: include/linux/dma-mapping.h:587
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815b53c6)
Location: include/linux/dma-mapping.h:587
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/ata/libata-sff.c (ffffffff8167ce57)
Location: include/linux/dma-mapping.h:587
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816cc6aa)
Location: include/linux/dma-mapping.h:587
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-platform.c (ffffffff816e087d)
Location: include/linux/dma-mapping.h:587
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816e7549)
Location: include/linux/dma-mapping.h:587
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/xhci.c (ffffffff816f10f7)
Location: include/linux/dma-mapping.h:587
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
In drivers/virtio/virtio_mmio.c (ffffffff815b4c24)
Location: include/linux/dma-mapping.h:589
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff815b5d0a)
Location: include/linux/dma-mapping.h:589
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff815b7546)
Location: include/linux/dma-mapping.h:589
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8161c3aa)
Location: include/linux/dma-mapping.h:589
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/ata/libata-sff.c (ffffffff816e6577)
Location: include/linux/dma-mapping.h:589
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81738c2b)
Location: include/linux/dma-mapping.h:589
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8174d0fd)
Location: include/linux/dma-mapping.h:589
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81753d66)
Location: include/linux/dma-mapping.h:589
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/xhci.c (ffffffff8175d30f)
Location: include/linux/dma-mapping.h:589
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
In drivers/virtio/virtio_mmio.c (ffffffff815ecef1)
Location: include/linux/dma-mapping.h:593
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff815ee0f2)
Location: include/linux/dma-mapping.h:593
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff815efa85)
Location: include/linux/dma-mapping.h:593
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81656089)
Location: include/linux/dma-mapping.h:593
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/ata/libata-sff.c (ffffffff81722e57)
Location: include/linux/dma-mapping.h:593
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81778c7b)
Location: include/linux/dma-mapping.h:593
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8178d933)
Location: include/linux/dma-mapping.h:593
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817943bd)
Location: include/linux/dma-mapping.h:593
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/xhci.c (ffffffff8179dd2b)
Location: include/linux/dma-mapping.h:593
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
```
In drivers/i2c/busses/i2c-amd-pci-mp2.c (ffffffff817dcdbf)
Location: include/linux/dma-mapping.h:593
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dma_set_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81118210)
Location: kernel/dma/mapping.c:322
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
**Symbols:**

```
ffffffff81118210-ffffffff8111827e: dma_set_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dma_set_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/mapping.c (0)
Location: kernel/dma/mapping.c:344
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
**Symbols:**

```
ffffffff811228ce-ffffffff811228e2: dma_set_mask.cold (STB_LOCAL)
ffffffff81122590-ffffffff811225f2: dma_set_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dma_set_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8112e9c0)
Location: kernel/dma/mapping.c:366
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff8112e9c0-ffffffff8112ea03: dma_set_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dma_set_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8113d560)
Location: kernel/dma/mapping.c:337
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff8113d560-ffffffff8113d5d3: dma_set_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dma_set_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81138320)
Location: kernel/dma/mapping.c:580
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff81138320-ffffffff81138396: dma_set_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dma_set_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81139440)
Location: kernel/dma/mapping.c:670
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff81139440-ffffffff811394b6: dma_set_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dma_set_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115c2d0)
Location: kernel/dma/mapping.c:735
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff8115c2d0-ffffffff8115c346: dma_set_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dma_set_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81186000)
Location: kernel/dma/mapping.c:729
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff81186000-ffffffff8118608a: dma_set_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dma_set_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c0ed0)
Location: kernel/dma/mapping.c:765
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
```
**Symbols:**

```
ffffffff811c0ed0-ffffffff811c0f5a: dma_set_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dma_set_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d39c0)
Location: kernel/dma/mapping.c:769
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
```
**Symbols:**

```
ffffffff811d39c0-ffffffff811d3a4a: dma_set_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dma_set_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e8660)
Location: kernel/dma/mapping.c:763
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
```
**Symbols:**

```
ffffffff811e8660-ffffffff811e86ea: dma_set_mask (STB_GLOBAL)
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
int dma_set_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffff800010193e08)
Location: kernel/dma/mapping.c:366
Inline: False
Direct callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_probe
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_hw_probe
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libahci_platform.c:ahci_platform_init_host
  - drivers/ata/libahci_platform.c:ahci_platform_init_host
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffff800010193e08-ffff800010193e5c: dma_set_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dma_set_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (c03e1180)
Location: kernel/dma/mapping.c:366
Inline: False
Direct callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_probe
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_probe
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libahci_platform.c:ahci_platform_init_host
  - drivers/ata/libahci_platform.c:ahci_platform_init_host
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_probe
  - drivers/usb/host/ohci-exynos.c:exynos_ohci_probe
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
c03e1180-c03e11d4: dma_set_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dma_set_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (c0000000001f41e0)
Location: kernel/dma/mapping.c:366
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
c0000000001f41e0-c0000000001f4260: dma_set_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dma_set_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffe00012617a)
Location: kernel/dma/mapping.c:366
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
**Symbols:**

```
ffffffe00012617a-ffffffe0001261c2: dma_set_mask (STB_GLOBAL)
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
int dma_set_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81126fa0)
Location: kernel/dma/mapping.c:366
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff81126fa0-ffffffff81126fe3: dma_set_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dma_set_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81119a00)
Location: kernel/dma/mapping.c:366
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
**Symbols:**

```
ffffffff81119a00-ffffffff81119a43: dma_set_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dma_set_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81124e90)
Location: kernel/dma/mapping.c:366
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe
```
**Symbols:**

```
ffffffff81124e90-ffffffff81124ed3: dma_set_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dma_set_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811314d0)
Location: kernel/dma/mapping.c:366
Inline: False
Direct callers:
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff811314d0-ffffffff81131513: dma_set_mask (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
