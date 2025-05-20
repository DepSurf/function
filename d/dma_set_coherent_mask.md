# Function: <code>dma_set_coherent_mask</code>

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
In drivers/char/agp/intel-gtt.c (ffffffff81522df0)
Location: include/linux/dma-mapping.h:102
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffff815dd8cd)
Location: include/linux/dma-mapping.h:102
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/usb/dwc2/platform.c (ffffffff816264a6)
Location: include/linux/dma-mapping.h:102
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8162a3ab)
Location: include/linux/dma-mapping.h:102
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8163cf32)
Location: include/linux/dma-mapping.h:102
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8163d45c)
Location: include/linux/dma-mapping.h:102
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81644309)
Location: include/linux/dma-mapping.h:102
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/xhci.c (ffffffff8164e283)
Location: include/linux/dma-mapping.h:102
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
In drivers/virtio/virtio_pci_modern.c (ffffffff8151265c)
Location: include/linux/dma-mapping.h:523
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff81513a83)
Location: include/linux/dma-mapping.h:523
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81575dda)
Location: include/linux/dma-mapping.h:523
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/ata/libata-sff.c (ffffffff8163764f)
Location: include/linux/dma-mapping.h:523
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/usb/dwc2/platform.c (ffffffff816848fe)
Location: include/linux/dma-mapping.h:523
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8168a2b3)
Location: include/linux/dma-mapping.h:523
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8169db3e)
Location: include/linux/dma-mapping.h:523
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8169e074)
Location: include/linux/dma-mapping.h:523
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816a4dd2)
Location: include/linux/dma-mapping.h:523
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/xhci.c (ffffffff816aeba2)
Location: include/linux/dma-mapping.h:523
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
In drivers/virtio/virtio_mmio.c (ffffffff8153d825)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff8153ea04)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff8153ffb7)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815a246d)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/ata/libata-sff.c (ffffffff816686f2)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/usb/dwc2/platform.c (ffffffff816b0eaa)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816b8422)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-pci.c (ffffffff816cbc4f)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (ffffffff816cc1b6)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816d2ed5)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/xhci.c (ffffffff816dcd45)
Location: include/linux/dma-mapping.h:575
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
In drivers/pci/endpoint/pci-epc-core.c (ffffffff814d2458)
Location: include/linux/dma-mapping.h:606
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81551454)
Location: include/linux/dma-mapping.h:606
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff81552470)
Location: include/linux/dma-mapping.h:606
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff81553c1e)
Location: include/linux/dma-mapping.h:606
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815b541d)
Location: include/linux/dma-mapping.h:606
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/ata/libata-sff.c (ffffffff8167ceab)
Location: include/linux/dma-mapping.h:606
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/usb/dwc2/platform.c (ffffffff816c5ff7)
Location: include/linux/dma-mapping.h:606
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816cc6f2)
Location: include/linux/dma-mapping.h:606
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-pci.c (ffffffff816e0304)
Location: include/linux/dma-mapping.h:606
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (ffffffff816e08ca)
Location: include/linux/dma-mapping.h:606
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816e759d)
Location: include/linux/dma-mapping.h:606
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/xhci.c (ffffffff816f114c)
Location: include/linux/dma-mapping.h:606
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
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81512898)
Location: include/linux/dma-mapping.h:611
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815b4c84)
Location: include/linux/dma-mapping.h:611
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff815b5d67)
Location: include/linux/dma-mapping.h:611
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff815b75aa)
Location: include/linux/dma-mapping.h:611
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8161c415)
Location: include/linux/dma-mapping.h:611
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/ata/libata-sff.c (ffffffff816e65d8)
Location: include/linux/dma-mapping.h:611
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/usb/dwc2/platform.c (ffffffff817322f7)
Location: include/linux/dma-mapping.h:611
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81738c86)
Location: include/linux/dma-mapping.h:611
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8174cae4)
Location: include/linux/dma-mapping.h:611
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8174d159)
Location: include/linux/dma-mapping.h:611
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81753dc9)
Location: include/linux/dma-mapping.h:611
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/xhci.c (ffffffff8175d36f)
Location: include/linux/dma-mapping.h:611
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
In drivers/virtio/virtio_mmio.c (ffffffff815ecf51)
Location: include/linux/dma-mapping.h:615
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff815ee14f)
Location: include/linux/dma-mapping.h:615
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff815efada)
Location: include/linux/dma-mapping.h:615
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816560f8)
Location: include/linux/dma-mapping.h:615
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/ata/libata-sff.c (ffffffff81722ed1)
Location: include/linux/dma-mapping.h:615
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/usb/dwc2/platform.c (ffffffff81771c18)
Location: include/linux/dma-mapping.h:615
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81778cd6)
Location: include/linux/dma-mapping.h:615
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8178d3e9)
Location: include/linux/dma-mapping.h:615
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8178d98b)
Location: include/linux/dma-mapping.h:615
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8179441c)
Location: include/linux/dma-mapping.h:615
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/xhci.c (ffffffff8179ddb5)
Location: include/linux/dma-mapping.h:615
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
```
In drivers/i2c/busses/i2c-amd-pci-mp2.c (ffffffff817dce1f)
Location: include/linux/dma-mapping.h:615
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
int dma_set_coherent_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81118280)
Location: kernel/dma/mapping.c:335
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
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
**Symbols:**

```
ffffffff81118280-ffffffff811182dc: dma_set_coherent_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dma_set_coherent_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/mapping.c (0)
Location: kernel/dma/mapping.c:363
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
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
**Symbols:**

```
ffffffff811228e2-ffffffff811228f6: dma_set_coherent_mask.cold (STB_LOCAL)
ffffffff81122600-ffffffff81122650: dma_set_coherent_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dma_set_coherent_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8112ea10)
Location: kernel/dma/mapping.c:384
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
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff8112ea10-ffffffff8112ea40: dma_set_coherent_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dma_set_coherent_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8113d500)
Location: kernel/dma/mapping.c:355
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
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff8113d500-ffffffff8113d55e: dma_set_coherent_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dma_set_coherent_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811382b0)
Location: kernel/dma/mapping.c:598
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
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff811382b0-ffffffff81138311: dma_set_coherent_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dma_set_coherent_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811393d0)
Location: kernel/dma/mapping.c:688
Inline: False
Direct callers:
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
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff811393d0-ffffffff81139431: dma_set_coherent_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dma_set_coherent_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115c260)
Location: kernel/dma/mapping.c:753
Inline: False
Direct callers:
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
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff8115c260-ffffffff8115c2c1: dma_set_coherent_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dma_set_coherent_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81185f90)
Location: kernel/dma/mapping.c:746
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
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff81185f90-ffffffff81185ff9: dma_set_coherent_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dma_set_coherent_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c1920)
Location: kernel/dma/mapping.c:782
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
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
```
**Symbols:**

```
ffffffff811c1920-ffffffff811c1989: dma_set_coherent_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dma_set_coherent_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d43a0)
Location: kernel/dma/mapping.c:786
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
```
**Symbols:**

```
ffffffff811d43a0-ffffffff811d4409: dma_set_coherent_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dma_set_coherent_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e8c20)
Location: kernel/dma/mapping.c:780
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
```
**Symbols:**

```
ffffffff811e8c20-ffffffff811e8c89: dma_set_coherent_mask (STB_GLOBAL)
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
int dma_set_coherent_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffff800010193e60)
Location: kernel/dma/mapping.c:384
Inline: False
Direct callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_probe
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
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
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffff800010193e60-ffff800010193ea8: dma_set_coherent_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dma_set_coherent_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (c03e11d4)
Location: kernel/dma/mapping.c:384
Inline: False
Direct callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
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
  - drivers/ata/sata_highbank.c:ahci_highbank_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
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
c03e11d4-c03e1214: dma_set_coherent_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dma_set_coherent_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (c0000000001f4260)
Location: kernel/dma/mapping.c:384
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
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
c0000000001f4260-c0000000001f42c8: dma_set_coherent_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dma_set_coherent_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffe0001261c2)
Location: kernel/dma/mapping.c:384
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
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
**Symbols:**

```
ffffffe0001261c2-ffffffe000126200: dma_set_coherent_mask (STB_GLOBAL)
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
int dma_set_coherent_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81126ff0)
Location: kernel/dma/mapping.c:384
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
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff81126ff0-ffffffff81127020: dma_set_coherent_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dma_set_coherent_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81119a50)
Location: kernel/dma/mapping.c:384
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
ffffffff81119a50-ffffffff81119a80: dma_set_coherent_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dma_set_coherent_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81124ee0)
Location: kernel/dma/mapping.c:384
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
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
**Symbols:**

```
ffffffff81124ee0-ffffffff81124f10: dma_set_coherent_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dma_set_coherent_mask(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81131520)
Location: kernel/dma/mapping.c:384
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
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff81131520-ffffffff81131550: dma_set_coherent_mask (STB_GLOBAL)
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
