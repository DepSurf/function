# Function: <code>dma_direct_map_sg</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int dma_direct_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8110d0e0)
Location: kernel/dma/direct.c:149
Inline: True
```
**Symbols:**

```
ffffffff8110d0e0-ffffffff8110d18e: dma_direct_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dma_direct_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811188d0)
Location: kernel/dma/direct.c:337
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/dma-buf/udmabuf.c:map_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff811188d0-ffffffff81118982: dma_direct_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dma_direct_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81122d00)
Location: kernel/dma/direct.c:351
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/dma-buf/udmabuf.c:map_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff81122d00-ffffffff81122dae: dma_direct_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dma_direct_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8112f140)
Location: kernel/dma/direct.c:351
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/dma-buf/udmabuf.c:map_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff8112f140-ffffffff8112f1ee: dma_direct_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dma_direct_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113de20)
Location: kernel/dma/direct.c:438
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_map_memory
  - drivers/dma-buf/heaps/heap-helpers.c:dma_heap_map_dma_buf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
  - drivers/ata/libata-core.c:ata_sg_setup
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff8113de20-ffffffff8113defc: dma_direct_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dma_direct_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81139340)
Location: kernel/dma/direct.c:396
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_map_sg_attrs
```
**Symbols:**

```
ffffffff81139340-ffffffff81139587: dma_direct_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dma_direct_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113a420)
Location: kernel/dma/direct.c:396
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_map_sg_attrs
```
**Symbols:**

```
ffffffff8113a420-ffffffff8113a65b: dma_direct_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dma_direct_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8115d4b0)
Location: kernel/dma/direct.c:436
Inline: False
Direct callers:
  - kernel/dma/mapping.c:__dma_map_sg_attrs
```
**Symbols:**

```
ffffffff8115d4b0-ffffffff8115d561: dma_direct_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dma_direct_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81187380)
Location: kernel/dma/direct.c:468
Inline: False
Direct callers:
  - kernel/dma/mapping.c:__dma_map_sg_attrs
```
**Symbols:**

```
ffffffff81187380-ffffffff8118745a: dma_direct_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dma_direct_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811c2eb0)
Location: kernel/dma/direct.c:476
Inline: False
Direct callers:
  - kernel/dma/mapping.c:__dma_map_sg_attrs
```
**Symbols:**

```
ffffffff811c2eb0-ffffffff811c2fef: dma_direct_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dma_direct_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811d59f0)
Location: kernel/dma/direct.c:475
Inline: False
Direct callers:
  - kernel/dma/mapping.c:__dma_map_sg_attrs
```
**Symbols:**

```
ffffffff811d59f0-ffffffff811d5b2f: dma_direct_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dma_direct_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811ea970)
Location: kernel/dma/direct.c:464
Inline: False
Direct callers:
  - kernel/dma/mapping.c:__dma_map_sg_attrs
```
**Symbols:**

```
ffffffff811ea970-ffffffff811eaaaf: dma_direct_map_sg (STB_GLOBAL)
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
int dma_direct_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffff800010194b00)
Location: kernel/dma/direct.c:351
Inline: False
Direct callers:
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/dma-buf/udmabuf.c:map_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/mmc/host/mmci.c:_mmci_dmae_prep_data
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_prep_data
```
**Symbols:**

```
ffff800010194b00-ffff800010194be4: dma_direct_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dma_direct_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c03e193c)
Location: kernel/dma/direct.c:351
Inline: False
Direct callers:
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/dma-buf/udmabuf.c:map_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_dma_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_dma_pref
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/gadget/udc/core.c:usb_gadget_map_request_by_dev
  - drivers/mmc/host/mmci.c:_mmci_dmae_prep_data
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_prep_data
  - drivers/mmc/host/sdhci.c:sdhci_pre_dma_transfer
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_pre_dma_transfer
  - drivers/mmc/host/cqhci.c:cqhci_request
```
**Symbols:**

```
c03e193c-c03e19dc: dma_direct_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dma_direct_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c0000000001f4dc0)
Location: kernel/dma/direct.c:351
Inline: False
Direct callers:
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_map_sg
  - drivers/dma-buf/udmabuf.c:map_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
c0000000001f4dc0-c0000000001f4f14: dma_direct_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dma_direct_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffe0001269ea)
Location: kernel/dma/direct.c:351
Inline: False
Direct callers:
  - drivers/dma-buf/udmabuf.c:map_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffe0001269ea-ffffffe000126a88: dma_direct_map_sg (STB_GLOBAL)
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
int dma_direct_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81127720)
Location: kernel/dma/direct.c:351
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/dma-buf/udmabuf.c:map_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff81127720-ffffffff811277ce: dma_direct_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dma_direct_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8111a180)
Location: kernel/dma/direct.c:351
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/dma-buf/udmabuf.c:map_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff8111a180-ffffffff8111a22e: dma_direct_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dma_direct_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81125610)
Location: kernel/dma/direct.c:351
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/dma-buf/udmabuf.c:map_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff81125610-ffffffff811256be: dma_direct_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dma_direct_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81131c50)
Location: kernel/dma/direct.c:351
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/dma-buf/udmabuf.c:map_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff81131c50-ffffffff81131cfe: dma_direct_map_sg (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
