# Function: <code>sme_active</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool sme_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff826c6190)
Location: arch/x86/mm/mem_encrypt.c:404
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt.c:sme_encrypt_kernel
  - lib/swiotlb.c:swiotlb_tbl_map_single
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
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
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
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
ffffffff81080290-ffffffff810802ac: sme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool sme_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff826eff64)
Location: arch/x86/mm/mem_encrypt.c:338
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
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
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/iommu/amd_iommu_init.c:amd_iommu_detect
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
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
```
**Symbols:**

```
ffffffff81083760-ffffffff81083777: sme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool sme_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6c21)
Location: arch/x86/mm/mem_encrypt.c:338
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
  - drivers/iommu/amd_iommu_init.c:amd_iommu_detect
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff8108a430-ffffffff8108a447: sme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool sme_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828bf2d3)
Location: arch/x86/mm/mem_encrypt.c:343
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - drivers/iommu/amd_iommu_init.c:amd_iommu_detect
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff8108e1c0-ffffffff8108e1d7: sme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool sme_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828c574e)
Location: arch/x86/mm/mem_encrypt.c:343
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - drivers/iommu/amd_iommu_init.c:amd_iommu_detect
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff8108ee20-ffffffff8108ee37: sme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool sme_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff82ce8943)
Location: arch/x86/mm/mem_encrypt.c:343
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
Direct callers:
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - drivers/iommu/amd/init.c:amd_iommu_detect
  - drivers/iommu/amd/init.c:copy_device_table
```
**Symbols:**

```
ffffffff810951d0-ffffffff810951e7: sme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool sme_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff810944cc)
Location: arch/x86/mm/mem_encrypt.c:376
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
Direct callers:
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - drivers/iommu/amd/init.c:amd_iommu_detect
  - drivers/iommu/amd/init.c:copy_device_table
```
**Symbols:**

```
ffffffff810944a0-ffffffff810944b7: sme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool sme_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff81094e3c)
Location: arch/x86/mm/mem_encrypt.c:380
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
Direct callers:
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - drivers/iommu/amd/init.c:amd_iommu_detect
  - drivers/iommu/amd/init.c:copy_device_table
```
**Symbols:**

```
ffffffff81094e10-ffffffff81094e2a: sme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool sme_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff810a4dbc)
Location: arch/x86/mm/mem_encrypt.c:381
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
Direct callers:
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - drivers/iommu/amd/init.c:amd_iommu_detect
  - drivers/iommu/amd/init.c:copy_device_table
```
**Symbols:**

```
ffffffff810a4d90-ffffffff810a4daa: sme_active (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool sme_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828b06e6)
Location: arch/x86/mm/mem_encrypt.c:343
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - drivers/iommu/amd_iommu_init.c:amd_iommu_detect
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff8108dde0-ffffffff8108ddf7: sme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool sme_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828a886b)
Location: arch/x86/mm/mem_encrypt.c:343
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - drivers/iommu/amd_iommu_init.c:amd_iommu_detect
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff8107c8f0-ffffffff8107c907: sme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool sme_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828c35e5)
Location: arch/x86/mm/mem_encrypt.c:343
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - drivers/iommu/amd_iommu_init.c:amd_iommu_detect
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff8108dd90-ffffffff8108dda7: sme_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool sme_active();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828c678b)
Location: arch/x86/mm/mem_encrypt.c:343
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt.c:sme_map_bootdata
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/pci-swiotlb.c:pci_swiotlb_detect_4gb
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - drivers/iommu/amd_iommu_init.c:amd_iommu_detect
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff81090170-ffffffff81090187: sme_active (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
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
