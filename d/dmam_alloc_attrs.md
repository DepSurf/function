# Function: <code>dmam_alloc_attrs</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *dmam_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dma-mapping.c (ffffffff815f5d50)
Location: drivers/base/dma-mapping.c:120
Inline: False
```
**Symbols:**

```
ffffffff815f5d50-ffffffff815f5e71: dmam_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *dmam_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dma-mapping.c (ffffffff8165dd10)
Location: drivers/base/dma-mapping.c:120
Inline: False
```
**Symbols:**

```
ffffffff8165dd10-ffffffff8165de34: dmam_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *dmam_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8110c750)
Location: kernel/dma/mapping.c:119
Inline: False
```
**Symbols:**

```
ffffffff8110c750-ffffffff8110c8a1: dmam_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *dmam_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81117e90)
Location: kernel/dma/mapping.c:81
Inline: False
```
**Symbols:**

```
ffffffff81117e90-ffffffff81117f4e: dmam_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *dmam_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811221f0)
Location: kernel/dma/mapping.c:81
Inline: False
```
**Symbols:**

```
ffffffff811221f0-ffffffff8112229a: dmam_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *dmam_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8112e860)
Location: kernel/dma/mapping.c:81
Inline: False
```
**Symbols:**

```
ffffffff8112e860-ffffffff8112e90a: dmam_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *dmam_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8113d1f0)
Location: kernel/dma/mapping.c:81
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
```
**Symbols:**

```
ffffffff8113d1f0-ffffffff8113d29a: dmam_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *dmam_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811378d0)
Location: kernel/dma/mapping.c:82
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
```
**Symbols:**

```
ffffffff811378d0-ffffffff8113797a: dmam_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *dmam_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811386c0)
Location: kernel/dma/mapping.c:84
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
```
**Symbols:**

```
ffffffff811386c0-ffffffff8113876a: dmam_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *dmam_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115b510)
Location: kernel/dma/mapping.c:84
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
```
**Symbols:**

```
ffffffff8115b510-ffffffff8115b5c1: dmam_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *dmam_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81184f40)
Location: kernel/dma/mapping.c:84
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
```
**Symbols:**

```
ffffffff81184f40-ffffffff81184ff4: dmam_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *dmam_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c06b0)
Location: kernel/dma/mapping.c:85
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff811c06b0-ffffffff811c0764: dmam_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *dmam_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d31a0)
Location: kernel/dma/mapping.c:89
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_edma_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_edma_detect
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff811d31a0-ffffffff811d3254: dmam_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *dmam_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e7e20)
Location: kernel/dma/mapping.c:89
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_edma_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_edma_detect
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
**Symbols:**

```
ffffffff811e7e20-ffffffff811e7ed4: dmam_alloc_attrs (STB_GLOBAL)
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
void *dmam_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffff800010193bc8)
Location: kernel/dma/mapping.c:81
Inline: False
Direct callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_init_one_queue
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_add_device
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_domain_finalise_s1
  - drivers/ata/libahci.c:ahci_port_start
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_setup
```
**Symbols:**

```
ffff800010193bc8-ffff800010193c7c: dmam_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *dmam_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (c03e0f58)
Location: kernel/dma/mapping.c:81
Inline: False
Direct callers:
  - drivers/ata/libahci.c:ahci_port_start
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_setup
  - drivers/mmc/host/cqhci.c:cqhci_enable
  - drivers/mmc/host/cqhci.c:cqhci_enable
```
**Symbols:**

```
c03e0f58-c03e1004: dmam_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *dmam_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (c0000000001f3e60)
Location: kernel/dma/mapping.c:81
Inline: False
```
**Symbols:**

```
c0000000001f3e60-c0000000001f3f58: dmam_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *dmam_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffe000125f66)
Location: kernel/dma/mapping.c:81
Inline: False
```
**Symbols:**

```
ffffffe000125f66-ffffffe000126004: dmam_alloc_attrs (STB_GLOBAL)
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
void *dmam_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81126e40)
Location: kernel/dma/mapping.c:81
Inline: False
```
**Symbols:**

```
ffffffff81126e40-ffffffff81126eea: dmam_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *dmam_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811198a0)
Location: kernel/dma/mapping.c:81
Inline: False
```
**Symbols:**

```
ffffffff811198a0-ffffffff8111994a: dmam_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *dmam_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81124d30)
Location: kernel/dma/mapping.c:81
Inline: False
```
**Symbols:**

```
ffffffff81124d30-ffffffff81124dda: dmam_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *dmam_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81131370)
Location: kernel/dma/mapping.c:81
Inline: False
```
**Symbols:**

```
ffffffff81131370-ffffffff8113141a: dmam_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
