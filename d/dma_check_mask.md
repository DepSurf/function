# Function: <code>dma_check_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815128cb)
Location: include/linux/dma-mapping.h:571
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815b4c70)
Location: include/linux/dma-mapping.h:571
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff815b5d54)
Location: include/linux/dma-mapping.h:571
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff815b7597)
Location: include/linux/dma-mapping.h:571
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8161c3f7)
Location: include/linux/dma-mapping.h:571
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/ata/libata-sff.c (ffffffff816e65bf)
Location: include/linux/dma-mapping.h:571
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/usb/dwc2/platform.c (ffffffff81732332)
Location: include/linux/dma-mapping.h:571
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81738c66)
Location: include/linux/dma-mapping.h:571
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8174cb1f)
Location: include/linux/dma-mapping.h:571
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8174d145)
Location: include/linux/dma-mapping.h:571
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81753db0)
Location: include/linux/dma-mapping.h:571
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/xhci.c (ffffffff8175d357)
Location: include/linux/dma-mapping.h:571
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
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
In drivers/virtio/virtio_mmio.c (ffffffff815ecf3d)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff815ee13c)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff815efac7)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816560c8)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/ata/libata-sff.c (ffffffff81722e9f)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/usb/dwc2/platform.c (ffffffff81771c52)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81778cb6)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8178d424)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8178d974)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81794400)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/xhci.c (ffffffff8179dd73)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
```
In drivers/i2c/busses/i2c-amd-pci-mp2.c (ffffffff817dce0c)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8111829b)
Location: kernel/dma/mapping.c:303
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
  - kernel/dma/mapping.c:dma_set_mask
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8112261b)
Location: kernel/dma/mapping.c:320
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
  - kernel/dma/mapping.c:dma_set_mask
```
</details>
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
