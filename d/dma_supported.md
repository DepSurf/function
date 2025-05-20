# Function: <code>dma_supported</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-dma.c (ffffffff81034d20)
Location: arch/x86/kernel/pci-dma.c:215
Inline: True
Direct callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
**Symbols:**

```
ffffffff81034d20-ffffffff81034dba: dma_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-dma.c (ffffffff81033f00)
Location: arch/x86/kernel/pci-dma.c:215
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
**Symbols:**

```
ffffffff81033f00-ffffffff81033f9a: dma_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-dma.c (ffffffff81033b30)
Location: arch/x86/kernel/pci-dma.c:215
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
**Symbols:**

```
ffffffff81033b30-ffffffff81033bca: dma_supported (STB_GLOBAL)
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
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81551411)
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
In drivers/virtio/virtio_pci_modern.c (ffffffff81552427)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff81553bdd)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815b53dd)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/ata/libata-sff.c (ffffffff8167ce67)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/usb/dwc2/platform.c (ffffffff816c5ff7)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816cc6aa)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-pci.c (ffffffff816e0304)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (ffffffff816e088d)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816e7559)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/xhci.c (ffffffff816f1100)
Location: include/linux/dma-mapping.h:575
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
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81512898)
Location: include/linux/dma-mapping.h:577
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815b4c33)
Location: include/linux/dma-mapping.h:577
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
In drivers/virtio/virtio_pci_modern.c (ffffffff815b5d18)
Location: include/linux/dma-mapping.h:577
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff815b755b)
Location: include/linux/dma-mapping.h:577
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8161c3bf)
Location: include/linux/dma-mapping.h:577
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/ata/libata-sff.c (ffffffff816e6585)
Location: include/linux/dma-mapping.h:577
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/usb/dwc2/platform.c (ffffffff817322f7)
Location: include/linux/dma-mapping.h:577
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81738c2b)
Location: include/linux/dma-mapping.h:577
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8174cae4)
Location: include/linux/dma-mapping.h:577
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8174d10d)
Location: include/linux/dma-mapping.h:577
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81753d76)
Location: include/linux/dma-mapping.h:577
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/xhci.c (ffffffff8175d318)
Location: include/linux/dma-mapping.h:577
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
In drivers/virtio/virtio_mmio.c (ffffffff815ecf00)
Location: include/linux/dma-mapping.h:581
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
In drivers/virtio/virtio_pci_modern.c (ffffffff815ee100)
Location: include/linux/dma-mapping.h:581
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff815efa8b)
Location: include/linux/dma-mapping.h:581
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8165608f)
Location: include/linux/dma-mapping.h:581
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/ata/libata-sff.c (ffffffff81722e65)
Location: include/linux/dma-mapping.h:581
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/usb/dwc2/platform.c (ffffffff81771c18)
Location: include/linux/dma-mapping.h:581
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81778c7b)
Location: include/linux/dma-mapping.h:581
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8178d3e9)
Location: include/linux/dma-mapping.h:581
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8178d93c)
Location: include/linux/dma-mapping.h:581
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817943c6)
Location: include/linux/dma-mapping.h:581
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/xhci.c (ffffffff8179dd39)
Location: include/linux/dma-mapping.h:581
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
```
In drivers/i2c/busses/i2c-amd-pci-mp2.c (ffffffff817dcdcd)
Location: include/linux/dma-mapping.h:581
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
<summary>In <code>5.0</code>: ✅</summary>

```c
int dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81117fd0)
Location: kernel/dma/mapping.c:309
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
**Symbols:**

```
ffffffff81117fd0-ffffffff81118014: dma_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81122370)
Location: kernel/dma/mapping.c:326
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
**Symbols:**

```
ffffffff81122370-ffffffff811223af: dma_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8112e980)
Location: kernel/dma/mapping.c:348
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
**Symbols:**

```
ffffffff8112e980-ffffffff8112e9bf: dma_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8113d505)
Location: kernel/dma/mapping.c:319
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
**Symbols:**

```
ffffffff8113d320-ffffffff8113d35f: dma_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811382b5)
Location: kernel/dma/mapping.c:558
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
**Symbols:**

```
ffffffff81137ba0-ffffffff81137be2: dma_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811393d5)
Location: kernel/dma/mapping.c:648
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
**Symbols:**

```
ffffffff81138be0-ffffffff81138c22: dma_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115c265)
Location: kernel/dma/mapping.c:713
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
**Symbols:**

```
ffffffff8115baf0-ffffffff8115bb32: dma_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81185f95)
Location: kernel/dma/mapping.c:707
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
**Symbols:**

```
ffffffff81185650-ffffffff811856aa: dma_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c1925)
Location: kernel/dma/mapping.c:726
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d43a5)
Location: kernel/dma/mapping.c:730
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e8c25)
Location: kernel/dma/mapping.c:730
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
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
int dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffff800010193d98)
Location: kernel/dma/mapping.c:348
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
**Symbols:**

```
ffff800010193d98-ffff800010193e04: dma_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (c03e1114)
Location: kernel/dma/mapping.c:348
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
**Symbols:**

```
c03e1114-c03e1180: dma_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (c0000000001f4150)
Location: kernel/dma/mapping.c:348
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
**Symbols:**

```
c0000000001f4150-c0000000001f41dc: dma_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffe00012611e)
Location: kernel/dma/mapping.c:348
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
**Symbols:**

```
ffffffe00012611e-ffffffe00012617a: dma_supported (STB_GLOBAL)
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
int dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81126f60)
Location: kernel/dma/mapping.c:348
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
**Symbols:**

```
ffffffff81126f60-ffffffff81126f9f: dma_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811199c0)
Location: kernel/dma/mapping.c:348
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
**Symbols:**

```
ffffffff811199c0-ffffffff811199ff: dma_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81124e50)
Location: kernel/dma/mapping.c:348
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
**Symbols:**

```
ffffffff81124e50-ffffffff81124e8f: dma_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81131490)
Location: kernel/dma/mapping.c:348
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
**Symbols:**

```
ffffffff81131490-ffffffff811314cf: dma_supported (STB_GLOBAL)
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
