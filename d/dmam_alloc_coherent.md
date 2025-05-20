# Function: <code>dmam_alloc_coherent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *dmam_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dma-mapping.c (ffffffff8155dc60)
Location: drivers/base/dma-mapping.c:65
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start
```
**Symbols:**

```
ffffffff8155dc60-ffffffff8155dd5c: dmam_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *dmam_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dma-mapping.c (ffffffff815b1ea0)
Location: drivers/base/dma-mapping.c:64
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start
```
**Symbols:**

```
ffffffff815b1ea0-ffffffff815b1fa3: dmam_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *dmam_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dma-mapping.c (ffffffff815e0ef0)
Location: drivers/base/dma-mapping.c:64
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start
```
**Symbols:**

```
ffffffff815e0ef0-ffffffff815e0ff3: dmam_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *dmam_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dma-mapping.c (ffffffff815f5fe0)
Location: drivers/base/dma-mapping.c:61
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
```
**Symbols:**

```
ffffffff815f5fe0-ffffffff815f60e3: dmam_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *dmam_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dma-mapping.c (ffffffff8165df00)
Location: drivers/base/dma-mapping.c:61
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
```
**Symbols:**

```
ffffffff8165df00-ffffffff8165e006: dmam_alloc_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *dmam_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8110c970)
Location: kernel/dma/mapping.c:60
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
```
**Symbols:**

```
ffffffff8110c970-ffffffff8110cab5: dmam_alloc_coherent (STB_GLOBAL)
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
In drivers/ata/libata-sff.c (ffffffff817459b5)
Location: include/linux/dma-mapping.h:766
Inline: True
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
In drivers/ata/libata-sff.c (ffffffff81781685)
Location: include/linux/dma-mapping.h:772
Inline: True
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
In drivers/ata/libata-sff.c (ffffffff817a5045)
Location: include/linux/dma-mapping.h:771
Inline: True
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
In drivers/ata/libata-sff.c (ffffffff8186a4c0)
Location: include/linux/dma-mapping.h:857
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
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
In drivers/ata/libata-sff.c (ffffffff818792d0)
Location: include/linux/dma-mapping.h:511
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
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
In drivers/ata/libata-sff.c (ffffffff8185ba30)
Location: include/linux/dma-mapping.h:569
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
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
In drivers/ata/libata-sff.c (ffffffff818ea3c0)
Location: include/linux/dma-mapping.h:549
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff81a3beaf)
Location: include/linux/dma-mapping.h:549
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8192742e)
Location: include/linux/dma-mapping.h:554
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
```
```
In drivers/ata/libata-sff.c (ffffffff81bc130f)
Location: include/linux/dma-mapping.h:554
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81969d92)
Location: include/linux/dma-mapping.h:557
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_edma_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_edma_detect
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8196b5ef)
Location: include/linux/dma-mapping.h:557
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
```
```
In drivers/ata/libata-sff.c (ffffffff81c18def)
Location: include/linux/dma-mapping.h:557
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
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
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819b35b3)
Location: include/linux/dma-mapping.h:550
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_edma_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_edma_detect
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b50cf)
Location: include/linux/dma-mapping.h:550
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
```
```
In drivers/ata/libata-sff.c (ffffffff81c6ddff)
Location: include/linux/dma-mapping.h:550
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d74d8)
Location: include/linux/dma-mapping.h:771
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_init_one_queue
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_add_device
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_domain_finalise_s1
```
```
In drivers/ata/libata-sff.c (ffff8000109b01f8)
Location: include/linux/dma-mapping.h:771
Inline: True
```
```
In drivers/ata/libahci.c (ffff8000109bbcc0)
Location: include/linux/dma-mapping.h:771
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_port_start
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e922c)
Location: include/linux/dma-mapping.h:771
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
```
```
In drivers/mmc/host/mmci_stm32_sdmmc.c (ffff800010b482ac)
Location: include/linux/dma-mapping.h:771
Inline: True
Inline callers:
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (c0a802e8)
Location: include/linux/dma-mapping.h:771
Inline: True
```
```
In drivers/ata/libahci.c (c0a8634c)
Location: include/linux/dma-mapping.h:771
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_port_start
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0aca474)
Location: include/linux/dma-mapping.h:771
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
```
```
In drivers/mmc/host/mmci_stm32_sdmmc.c (c0c21810)
Location: include/linux/dma-mapping.h:771
Inline: True
Inline callers:
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_setup
```
```
In drivers/mmc/host/cqhci.c (c0c302e8)
Location: include/linux/dma-mapping.h:771
Inline: True
Inline callers:
  - drivers/mmc/host/cqhci.c:cqhci_enable
  - drivers/mmc/host/cqhci.c:cqhci_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (c000000000a79510)
Location: include/linux/dma-mapping.h:771
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffe00060decc)
Location: include/linux/dma-mapping.h:771
Inline: True
```
</details>
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
In drivers/ata/libata-sff.c (ffffffff8176a105)
Location: include/linux/dma-mapping.h:771
Inline: True
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
In drivers/ata/libata-sff.c (ffffffff81749f65)
Location: include/linux/dma-mapping.h:771
Inline: True
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
In drivers/ata/libata-sff.c (ffffffff81799ec5)
Location: include/linux/dma-mapping.h:771
Inline: True
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
In drivers/ata/libata-sff.c (ffffffff817b3d45)
Location: include/linux/dma-mapping.h:771
Inline: True
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
</ul>
