# Function: <code>sme_get_me_mask</code>

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
In arch/x86/kernel/head64.c (0)
Location: include/linux/mem_encrypt.h:36
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: include/linux/mem_encrypt.h:36
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (0)
Location: include/linux/mem_encrypt.h:36
Inline: True
```
```
In drivers/virtio/virtio_pci_modern.c (0)
Location: include/linux/mem_encrypt.h:36
Inline: True
```
```
In drivers/virtio/virtio_pci_legacy.c (0)
Location: include/linux/mem_encrypt.h:36
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/mem_encrypt.h:36
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/mem_encrypt.h:36
Inline: True
```
```
In drivers/usb/dwc2/platform.c (0)
Location: include/linux/mem_encrypt.h:36
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/mem_encrypt.h:36
Inline: True
```
```
In drivers/usb/host/ehci-pci.c (0)
Location: include/linux/mem_encrypt.h:36
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/mem_encrypt.h:36
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: include/linux/mem_encrypt.h:36
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/mem_encrypt.h:36
Inline: True
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
In arch/x86/kernel/head64.c (ffffffff81002000)
Location: include/linux/mem_encrypt.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_secondary_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815ed254)
Location: include/linux/mem_encrypt.h:36
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff815ee47d)
Location: include/linux/mem_encrypt.h:36
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff815efb15)
Location: include/linux/mem_encrypt.h:36
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816560d1)
Location: include/linux/mem_encrypt.h:36
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/ata/libata-sff.c (ffffffff81722ea8)
Location: include/linux/mem_encrypt.h:36
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
```
```
In drivers/usb/dwc2/platform.c (ffffffff81771f20)
Location: include/linux/mem_encrypt.h:36
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817790bc)
Location: include/linux/mem_encrypt.h:36
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8178d42d)
Location: include/linux/mem_encrypt.h:36
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8178db7f)
Location: include/linux/mem_encrypt.h:36
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81794601)
Location: include/linux/mem_encrypt.h:36
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/host/xhci.c (ffffffff8179dd7c)
Location: include/linux/mem_encrypt.h:36
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
```
In drivers/i2c/busses/i2c-amd-pci-mp2.c (ffffffff817dd08b)
Location: include/linux/mem_encrypt.h:36
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
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
In arch/x86/kernel/head64.c (ffffffff81002000)
Location: include/linux/mem_encrypt.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_secondary_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
```
```
In kernel/dma/mapping.c (ffffffff811182b3)
Location: include/linux/mem_encrypt.h:36
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
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
In arch/x86/kernel/head64.c (ffffffff81002000)
Location: include/linux/mem_encrypt.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_secondary_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
```
```
In kernel/dma/mapping.c (ffffffff81122633)
Location: include/linux/mem_encrypt.h:33
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81002000)
Location: arch/x86/include/asm/mem_encrypt.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_secondary_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81003000)
Location: arch/x86/include/asm/mem_encrypt.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_secondary_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81003060)
Location: arch/x86/include/asm/mem_encrypt.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_secondary_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81003060)
Location: arch/x86/include/asm/mem_encrypt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_secondary_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81003060)
Location: arch/x86/include/asm/mem_encrypt.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_secondary_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
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
In arch/x86/kernel/head64.c (ffffffff8100042d)
Location: arch/x86/include/asm/mem_encrypt.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff8347767c)
Location: arch/x86/include/asm/mem_encrypt.h:103
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
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
In arch/x86/kernel/head64.c (ffffffff8100045c)
Location: arch/x86/include/asm/mem_encrypt.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea0d3d)
Location: arch/x86/include/asm/mem_encrypt.h:105
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
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
In arch/x86/kernel/head64.c (ffffffff81000574)
Location: arch/x86/include/asm/mem_encrypt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4e4d)
Location: arch/x86/include/asm/mem_encrypt.h:109
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
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
In arch/x86/kernel/head64.c (ffffffff81000584)
Location: arch/x86/include/asm/mem_encrypt.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f5a4d)
Location: arch/x86/include/asm/mem_encrypt.h:109
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81002000)
Location: arch/x86/include/asm/mem_encrypt.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_secondary_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff810004f0)
Location: arch/x86/include/asm/mem_encrypt.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_secondary_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81002000)
Location: arch/x86/include/asm/mem_encrypt.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_secondary_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81002000)
Location: arch/x86/include/asm/mem_encrypt.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_secondary_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
```
</details>
</li>
</ul>

## Differences
