# Function: <code>dma_map_sg_attrs</code>

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
In drivers/char/agp/intel-gtt.c (ffffffff815222ad)
Location: include/asm-generic/dma-mapping-common.h:47
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff815b194c)
Location: include/asm-generic/dma-mapping-common.h:47
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff815cb52b)
Location: include/asm-generic/dma-mapping-common.h:47
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff815e7927)
Location: include/asm-generic/dma-mapping-common.h:47
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8160d324)
Location: include/asm-generic/dma-mapping-common.h:47
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
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
In drivers/char/agp/intel-gtt.c (ffffffff81575116)
Location: include/linux/dma-mapping.h:205
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81609cdc)
Location: include/linux/dma-mapping.h:205
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff81623cc4)
Location: include/linux/dma-mapping.h:205
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff81645982)
Location: include/linux/dma-mapping.h:205
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8166ceb1)
Location: include/linux/dma-mapping.h:205
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
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
In drivers/char/agp/intel-gtt.c (ffffffff815a17a2)
Location: include/linux/dma-mapping.h:216
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff816395bc)
Location: include/linux/dma-mapping.h:216
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff81654844)
Location: include/linux/dma-mapping.h:216
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff816770f5)
Location: include/linux/dma-mapping.h:216
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8169abb1)
Location: include/linux/dma-mapping.h:216
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
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
In drivers/char/agp/intel-gtt.c (ffffffff815b5f9c)
Location: include/linux/dma-mapping.h:259
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff8164e11f)
Location: include/linux/dma-mapping.h:259
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff81668e52)
Location: include/linux/dma-mapping.h:259
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff8168b7f0)
Location: include/linux/dma-mapping.h:259
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff816affa3)
Location: include/linux/dma-mapping.h:259
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
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
In drivers/char/agp/intel-gtt.c (ffffffff8161c1a5)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff816b73f1)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff816d24ed)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff816f517c)
Location: include/linux/dma-mapping.h:261
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8171b519)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
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
In drivers/char/agp/intel-gtt.c (ffffffff81655d39)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff816f36f1)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff8170ebde)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff817328ce)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff8175a2c8)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
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
In drivers/char/agp/intel-gtt.c (ffffffff81674939)
Location: include/linux/dma-mapping.h:313
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8170af07)
Location: include/linux/dma-mapping.h:313
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff817160e4)
Location: include/linux/dma-mapping.h:313
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff81731072)
Location: include/linux/dma-mapping.h:313
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff817552c2)
Location: include/linux/dma-mapping.h:313
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff8177e848)
Location: include/linux/dma-mapping.h:313
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
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
In drivers/char/agp/intel-gtt.c (ffffffff816a99ad)
Location: include/linux/dma-mapping.h:315
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81746b88)
Location: include/linux/dma-mapping.h:315
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff817518c1)
Location: include/linux/dma-mapping.h:315
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff8176c82b)
Location: include/linux/dma-mapping.h:315
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff817913c8)
Location: include/linux/dma-mapping.h:315
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817bcde4)
Location: include/linux/dma-mapping.h:315
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/intel-gtt.c (ffffffff816cc6ed)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8176acd8)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81775b41)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff8179089b)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff817b500c)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817ed7c1)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/intel-gtt.c (ffffffff81780fc2)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_map_memory
```
```
In drivers/dma-buf/heaps/heap-helpers.c (ffffffff8182a564)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/heap-helpers.c:dma_heap_map_dma_buf
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8182ce30)
Location: include/linux/dma-mapping.h:308
Inline: True
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81838a61)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff81852d34)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_sg_setup
```
```
In drivers/spi/spi.c (ffffffff8187bbd4)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff818bce95)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dma_map_sg_attrs(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81137540)
Location: kernel/dma/mapping.c:182
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_map_memory
  - drivers/dma-buf/heaps/system_heap.c:system_heap_map_dma_buf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff81137540-ffffffff8113758e: dma_map_sg_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dma_map_sg_attrs(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811382e0)
Location: kernel/dma/mapping.c:184
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/dma-buf/heaps/system_heap.c:system_heap_map_dma_buf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff811382e0-ffffffff8113832e: dma_map_sg_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int dma_map_sg_attrs(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115b130)
Location: kernel/dma/mapping.c:223
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff8115b130-ffffffff8115b147: dma_map_sg_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int dma_map_sg_attrs(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81184ab0)
Location: kernel/dma/mapping.c:223
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/spi/spi.c:spi_map_buf
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff81184ab0-ffffffff81184ad6: dma_map_sg_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int dma_map_sg_attrs(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c0130)
Location: kernel/dma/mapping.c:227
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff811c0130-ffffffff811c0156: dma_map_sg_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int dma_map_sg_attrs(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d2c10)
Location: kernel/dma/mapping.c:231
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff811d2c10-ffffffff811d2c36: dma_map_sg_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int dma_map_sg_attrs(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e7890)
Location: kernel/dma/mapping.c:231
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
**Symbols:**

```
ffffffff811e7890-ffffffff811e78b6: dma_map_sg_attrs (STB_GLOBAL)
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
In drivers/tty/serial/amba-pl011.c (ffff800010894bcc)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill
```
```
In drivers/tty/serial/imx.c (ffff80001089aa74)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
```
```
In drivers/dma-buf/udmabuf.c (ffff80001096c824)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffff80001097a2e0)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffff80001099a4dc)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
```
```
In drivers/spi/spi.c (ffff8000109c8648)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffff800010a1c8f4)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/mmc/host/mmci.c (ffff800010b458dc)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:_mmci_dmae_prep_data
```
```
In drivers/mmc/host/mmci_stm32_sdmmc.c (ffff800010b48474)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_prep_data
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
In drivers/tty/serial/amba-pl011.c (c0990b74)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill
```
```
In drivers/tty/serial/imx.c (c09979cc)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
```
```
In drivers/dma-buf/udmabuf.c (c0a42398)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (c0a4db20)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (c0a6a754)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
```
```
In drivers/mtd/nand/raw/omap2.c (c0aac554)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_dma_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_dma_pref
```
```
In drivers/spi/spi.c (c0ab2344)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (c0af58b8)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/gadget/udc/core.c (c0b73e48)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/usb/gadget/udc/core.c:usb_gadget_map_request_by_dev
```
```
In drivers/mmc/host/mmci.c (c0c1f7f0)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:_mmci_dmae_prep_data
```
```
In drivers/mmc/host/mmci_stm32_sdmmc.c (c0c219d4)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_prep_data
```
```
In drivers/mmc/host/sdhci.c (c0c22994)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_pre_dma_transfer
```
```
In drivers/mmc/host/omap_hsmmc.c (c0c2b950)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_pre_dma_transfer
```
```
In drivers/mmc/host/cqhci.c (c0c3105c)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/mmc/host/cqhci.c:cqhci_request
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/udmabuf.c (c000000000a25a38)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (c000000000a349bc)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (c000000000a5da88)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
```
```
In drivers/spi/spi.c (c000000000a89e38)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (c000000000ad7d40)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/udmabuf.c (ffffffe0005d773c)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffe0005e1400)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffe0005faeb8)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffe000618a7c)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffe000641624)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/intel-gtt.c (ffffffff8169213d)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8171f3c8)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff8172a231)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/nvme/host/pci.c (ffffffff8174ec1e)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_map_data
```
```
In drivers/ata/libata-core.c (ffffffff817559db)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff81779aec)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817a5ba1)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/intel-gtt.c (ffffffff8166fb2d)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/dma-buf/udmabuf.c (ffffffff816f87f8)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81703651)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/nvme/host/pci.c (ffffffff8172eabe)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_map_data
```
```
In drivers/ata/libata-core.c (ffffffff8173587b)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff8175989c)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817980d1)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/intel-gtt.c (ffffffff816c03ad)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8175e198)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81769001)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff8178571b)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff817a9e8c)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817e2641)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/intel-gtt.c (ffffffff816da97d)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries
```
```
In drivers/dma-buf/udmabuf.c (ffffffff817797f8)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:map_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81784771)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/ata/libata-core.c (ffffffff8179f54b)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
```
```
In drivers/spi/spi.c (ffffffff817c3d1c)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817fd391)
Location: include/linux/dma-mapping.h:308
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
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
