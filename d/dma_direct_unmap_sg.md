# Function: <code>dma_direct_unmap_sg</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dma_direct_unmap_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81118700)
Location: kernel/dma/direct.c:298
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/ata/libata-core.c:__ata_qc_complete
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff81118700-ffffffff81118765: dma_direct_unmap_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dma_direct_unmap_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81122b40)
Location: kernel/dma/direct.c:312
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/ata/libata-core.c:__ata_qc_complete
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff81122b40-ffffffff81122ba5: dma_direct_unmap_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dma_direct_unmap_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8112ef80)
Location: kernel/dma/direct.c:312
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/ata/libata-core.c:__ata_qc_complete
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff8112ef80-ffffffff8112efe5: dma_direct_unmap_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dma_direct_unmap_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113dea4)
Location: kernel/dma/direct.c:399
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_unmap_memory
  - drivers/dma-buf/heaps/heap-helpers.c:dma_heap_unmap_dma_buf
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/ata/libata-core.c:__ata_qc_complete
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff8113df00-ffffffff8113dfcc: dma_direct_unmap_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dma_direct_unmap_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811391b0)
Location: kernel/dma/direct.c:384
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_unmap_sg_attrs
  - kernel/dma/direct.c:dma_direct_map_sg
```
**Symbols:**

```
ffffffff811391b0-ffffffff81139335: dma_direct_unmap_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dma_direct_unmap_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113a280)
Location: kernel/dma/direct.c:384
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_unmap_sg_attrs
  - kernel/dma/direct.c:dma_direct_map_sg
```
**Symbols:**

```
ffffffff8113a280-ffffffff8113a413: dma_direct_unmap_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dma_direct_unmap_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8115d310)
Location: kernel/dma/direct.c:424
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_unmap_sg_attrs
  - kernel/dma/direct.c:dma_direct_map_sg
```
**Symbols:**

```
ffffffff8115d310-ffffffff8115d4a2: dma_direct_unmap_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dma_direct_unmap_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811871b0)
Location: kernel/dma/direct.c:456
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_unmap_sg_attrs
  - kernel/dma/direct.c:dma_direct_map_sg
```
**Symbols:**

```
ffffffff811871b0-ffffffff8118737d: dma_direct_unmap_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dma_direct_unmap_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811c2cc0)
Location: kernel/dma/direct.c:460
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_unmap_sg_attrs
  - kernel/dma/direct.c:dma_direct_map_sg
```
**Symbols:**

```
ffffffff811c2cc0-ffffffff811c2e9e: dma_direct_unmap_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dma_direct_unmap_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811d5800)
Location: kernel/dma/direct.c:459
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_unmap_sg_attrs
  - kernel/dma/direct.c:dma_direct_map_sg
```
**Symbols:**

```
ffffffff811d5800-ffffffff811d59de: dma_direct_unmap_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dma_direct_unmap_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:448
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_unmap_sg_attrs
  - kernel/dma/direct.c:dma_direct_map_sg
```
**Symbols:**

```
ffffffff821b484b-ffffffff821b4899: dma_direct_unmap_sg.cold (STB_LOCAL)
ffffffff811ea730-ffffffff811ea952: dma_direct_unmap_sg (STB_GLOBAL)
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
void dma_direct_unmap_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffff800010194870)
Location: kernel/dma/direct.c:312
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_callback
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx_callback
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/ata/libata-core.c:__ata_qc_complete
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/mmc/host/mmci.c:_mmci_dmae_prep_data
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_unprep_data
```
**Symbols:**

```
ffff800010194870-ffff8000101948f4: dma_direct_unmap_sg (STB_GLOBAL)
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
In kernel/dma/direct.c (0)
Location: include/linux/dma-mapping.h:241
Inline: True
```
```
In drivers/tty/serial/amba-pl011.c (0)
Location: include/linux/dma-mapping.h:241
Inline: True
```
```
In drivers/tty/serial/imx.c (0)
Location: include/linux/dma-mapping.h:241
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/dma-mapping.h:241
Inline: True
```
```
In drivers/scsi/scsi_lib_dma.c (0)
Location: include/linux/dma-mapping.h:241
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/dma-mapping.h:241
Inline: True
```
```
In drivers/mtd/nand/raw/omap2.c (0)
Location: include/linux/dma-mapping.h:241
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/dma-mapping.h:241
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/dma-mapping.h:241
Inline: True
```
```
In drivers/usb/gadget/udc/core.c (0)
Location: include/linux/dma-mapping.h:241
Inline: True
```
```
In drivers/mmc/host/mmci.c (0)
Location: include/linux/dma-mapping.h:241
Inline: True
```
```
In drivers/mmc/host/mmci_stm32_sdmmc.c (0)
Location: include/linux/dma-mapping.h:241
Inline: True
```
```
In drivers/mmc/host/sdhci.c (0)
Location: include/linux/dma-mapping.h:241
Inline: True
```
```
In drivers/mmc/host/omap_hsmmc.c (0)
Location: include/linux/dma-mapping.h:241
Inline: True
```
```
In drivers/mmc/host/cqhci.c (0)
Location: include/linux/dma-mapping.h:241
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dma_direct_unmap_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c0000000001f4aa0)
Location: kernel/dma/direct.c:312
Inline: False
Direct callers:
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_unmap_sg
  - kernel/dma/direct.c:dma_direct_map_sg
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/ata/libata-core.c:__ata_qc_complete
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
**Symbols:**

```
c0000000001f4aa0-c0000000001f4b64: dma_direct_unmap_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dma_direct_unmap_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffe00012681c)
Location: kernel/dma/direct.c:312
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/ata/libata-core.c:__ata_qc_complete
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
**Symbols:**

```
ffffffe00012681c-ffffffe000126884: dma_direct_unmap_sg (STB_GLOBAL)
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
void dma_direct_unmap_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81127560)
Location: kernel/dma/direct.c:312
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/nvme/host/pci.c:nvme_unmap_data
  - drivers/ata/libata-core.c:__ata_qc_complete
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff81127560-ffffffff811275c5: dma_direct_unmap_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dma_direct_unmap_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81119fc0)
Location: kernel/dma/direct.c:312
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/nvme/host/pci.c:nvme_unmap_data
  - drivers/ata/libata-core.c:__ata_qc_complete
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff81119fc0-ffffffff8111a025: dma_direct_unmap_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dma_direct_unmap_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81125450)
Location: kernel/dma/direct.c:312
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/ata/libata-core.c:__ata_qc_complete
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff81125450-ffffffff811254b5: dma_direct_unmap_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dma_direct_unmap_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81131a90)
Location: kernel/dma/direct.c:312
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/ata/libata-core.c:__ata_qc_complete
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff81131a90-ffffffff81131af5: dma_direct_unmap_sg (STB_GLOBAL)
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
