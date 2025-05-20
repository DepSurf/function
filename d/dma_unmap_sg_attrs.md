# Function: <code>dma_unmap_sg_attrs</code>

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
In drivers/char/agp/intel-gtt.c (ffffffff81521ff7)
Location: include/asm-generic/dma-mapping-common.h:65
Inline: True
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff815b18b4)
Location: include/asm-generic/dma-mapping-common.h:65
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
```
```
In drivers/ata/libata-core.c (ffffffff815cabc0)
Location: include/asm-generic/dma-mapping-common.h:65
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_sg_clean
```
```
In drivers/spi/spi.c (ffffffff815e711e)
Location: include/asm-generic/dma-mapping-common.h:65
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8160ccfa)
Location: include/asm-generic/dma-mapping-common.h:65
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
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
In drivers/char/agp/intel-gtt.c (ffffffff81574e2f)
Location: include/linux/dma-mapping.h:223
Inline: True
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81609c44)
Location: include/linux/dma-mapping.h:223
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
```
```
In drivers/ata/libata-core.c (ffffffff81623400)
Location: include/linux/dma-mapping.h:223
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_sg_clean
```
```
In drivers/spi/spi.c (ffffffff81645a4e)
Location: include/linux/dma-mapping.h:223
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8166c875)
Location: include/linux/dma-mapping.h:223
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
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
In drivers/char/agp/intel-gtt.c (ffffffff815a149f)
Location: include/linux/dma-mapping.h:234
Inline: True
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81639524)
Location: include/linux/dma-mapping.h:234
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
```
```
In drivers/ata/libata-core.c (ffffffff81653f80)
Location: include/linux/dma-mapping.h:234
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_sg_clean
```
```
In drivers/spi/spi.c (ffffffff8167684e)
Location: include/linux/dma-mapping.h:234
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8169a575)
Location: include/linux/dma-mapping.h:234
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
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
In drivers/char/agp/intel-gtt.c (ffffffff815b50bf)
Location: include/linux/dma-mapping.h:277
Inline: True
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff8164e08c)
Location: include/linux/dma-mapping.h:277
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
```
```
In drivers/ata/libata-core.c (ffffffff816688c1)
Location: include/linux/dma-mapping.h:277
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffff8168af4f)
Location: include/linux/dma-mapping.h:277
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff816af7e7)
Location: include/linux/dma-mapping.h:277
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
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
In drivers/char/agp/intel-gtt.c (ffffffff8161bd64)
Location: include/linux/dma-mapping.h:276
Inline: True
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff816b7380)
Location: include/linux/dma-mapping.h:276
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
```
```
In drivers/ata/libata-core.c (ffffffff816d1f47)
Location: include/linux/dma-mapping.h:276
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffff816f48bf)
Location: include/linux/dma-mapping.h:276
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8171ae49)
Location: include/linux/dma-mapping.h:276
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
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
In drivers/char/agp/intel-gtt.c (ffffffff81655a08)
Location: include/linux/dma-mapping.h:276
Inline: True
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff816f3678)
Location: include/linux/dma-mapping.h:276
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
```
```
In drivers/ata/libata-core.c (ffffffff8170e678)
Location: include/linux/dma-mapping.h:276
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffff8173297d)
Location: include/linux/dma-mapping.h:276
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
```
```
In drivers/usb/core/hcd.c (ffffffff81759b2e)
Location: include/linux/dma-mapping.h:276
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
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
In drivers/char/agp/intel-gtt.c (ffffffff81673c0c)
Location: include/linux/dma-mapping.h:331
Inline: True
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81716062)
Location: include/linux/dma-mapping.h:331
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
```
```
In drivers/ata/libata-core.c (ffffffff81730af8)
Location: include/linux/dma-mapping.h:331
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffff8175539b)
Location: include/linux/dma-mapping.h:331
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
```
```
In drivers/usb/core/hcd.c (ffffffff8177e1ab)
Location: include/linux/dma-mapping.h:331
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
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
In drivers/char/agp/intel-gtt.c (ffffffff816a96cc)
Location: include/linux/dma-mapping.h:333
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81746ac1)
Location: include/linux/dma-mapping.h:333
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff8175183f)
Location: include/linux/dma-mapping.h:333
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
```
```
In drivers/ata/libata-core.c (ffffffff8176c265)
Location: include/linux/dma-mapping.h:333
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffff817914a0)
Location: include/linux/dma-mapping.h:333
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817bc714)
Location: include/linux/dma-mapping.h:333
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
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
In drivers/char/agp/intel-gtt.c (ffffffff816cc40c)
Location: include/linux/dma-mapping.h:326
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8176ac11)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81775abf)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
```
```
In drivers/ata/libata-core.c (ffffffff817902d5)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffff817b50a0)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817ecf34)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
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
In drivers/char/agp/intel-gtt.c (ffffffff81780eb0)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_unmap_memory
```
```
In drivers/dma-buf/heaps/heap-helpers.c (ffffffff8182a4fa)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/heap-helpers.c:dma_heap_unmap_dma_buf
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8182d010)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff818389df)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
```
```
In drivers/ata/libata-core.c (ffffffff81854f65)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffff8187bc92)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
```
```
In drivers/usb/core/hcd.c (ffffffff818bc254)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dma_unmap_sg_attrs(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81137590)
Location: kernel/dma/mapping.c:205
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_unmap_dma_buf
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/ata/libata-core.c:__ata_qc_complete
  - drivers/spi/spi.c:spi_map_msg
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff81137590-ffffffff811375d4: dma_unmap_sg_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dma_unmap_sg_attrs(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81138330)
Location: kernel/dma/mapping.c:207
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_unmap_dma_buf
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/ata/libata-core.c:__ata_qc_complete
  - drivers/spi/spi.c:spi_map_msg
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff81138330-ffffffff81138374: dma_unmap_sg_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dma_unmap_sg_attrs(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115b180)
Location: kernel/dma/mapping.c:272
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_unmap_dma_buf
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/ata/libata-core.c:__ata_qc_complete
  - drivers/spi/spi.c:spi_map_msg
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff8115b180-ffffffff8115b1c4: dma_unmap_sg_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dma_unmap_sg_attrs(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81184b20)
Location: kernel/dma/mapping.c:272
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_unmap_dma_buf
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/ata/libata-core.c:__ata_qc_complete
  - drivers/spi/spi.c:spi_map_msg
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff81184b20-ffffffff81184b86: dma_unmap_sg_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dma_unmap_sg_attrs(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c01c0)
Location: kernel/dma/mapping.c:279
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_unmap_dma_buf
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/ata/libata-core.c:__ata_qc_complete
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff811c01c0-ffffffff811c0226: dma_unmap_sg_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dma_unmap_sg_attrs(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d2ca0)
Location: kernel/dma/mapping.c:283
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_unmap_dma_buf
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/ata/libata-core.c:__ata_qc_complete
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff811d2ca0-ffffffff811d2d06: dma_unmap_sg_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dma_unmap_sg_attrs(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e7920)
Location: kernel/dma/mapping.c:283
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_unmap_dma_buf
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/ata/libata-core.c:__ata_qc_complete
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_purge
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_free
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi.c:spi_unmap_buf
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff811e7920-ffffffff811e7986: dma_unmap_sg_attrs (STB_GLOBAL)
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
In drivers/tty/serial/amba-pl011.c (ffff8000108962b4)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_callback
```
```
In drivers/tty/serial/imx.c (ffff80001089c86c)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx_callback
```
```
In drivers/dma-buf/udmabuf.c (ffff80001096c740)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffff80001097a25c)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
```
```
In drivers/ata/libata-core.c (ffff800010999f30)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffff8000109c87b8)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
```
```
In drivers/usb/core/hcd.c (ffff800010a1bf9c)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
```
In drivers/mmc/host/mmci.c (ffff800010b459ec)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:_mmci_dmae_prep_data
```
```
In drivers/mmc/host/mmci_stm32_sdmmc.c (ffff800010b483e0)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_unprep_data
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
In drivers/tty/serial/amba-pl011.c (c099246c)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_callback
```
```
In drivers/tty/serial/imx.c (c09975dc)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_dma_tx
  - drivers/tty/serial/imx.c:imx_uart_dma_tx_callback
```
```
In drivers/dma-buf/udmabuf.c (c0a422a8)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (c0a4da88)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
```
```
In drivers/ata/libata-core.c (c0a69f68)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/mtd/nand/raw/omap2.c (c0aac6f8)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_dma_pref
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_dma_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_dma_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_dma_pref
```
```
In drivers/spi/spi.c (c0ab23ec)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
```
```
In drivers/usb/core/hcd.c (c0af3ce4)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
```
In drivers/usb/gadget/udc/core.c (c0b73c64)
Location: include/linux/dma-mapping.h:326
Inline: True
```
```
In drivers/mmc/host/mmci.c (c0c1f8f8)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:_mmci_dmae_prep_data
  - drivers/mmc/host/mmci.c:mmci_dma_unmap
```
```
In drivers/mmc/host/mmci_stm32_sdmmc.c (c0c21938)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_unprep_data
```
```
In drivers/mmc/host/sdhci.c (c0c22d20)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_request_done
  - drivers/mmc/host/sdhci.c:sdhci_post_req
```
```
In drivers/mmc/host/omap_hsmmc.c (c0c2c300)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_post_req
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_dma_callback
```
```
In drivers/mmc/host/cqhci.c (c0c30ec0)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/mmc/host/cqhci.c:cqhci_post_req
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
In drivers/dma-buf/udmabuf.c (c000000000a2580c)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (c000000000a348e0)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
```
```
In drivers/ata/libata-core.c (c000000000a5d254)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (c000000000a8a1b4)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
```
```
In drivers/usb/core/hcd.c (c000000000ad5c68)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
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
In drivers/dma-buf/udmabuf.c (ffffffe0005d7682)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffe0005e1396)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
```
```
In drivers/ata/libata-core.c (ffffffe0005fa93a)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffe000618c06)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
```
```
In drivers/usb/core/hcd.c (ffffffe000640190)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
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
In drivers/char/agp/intel-gtt.c (ffffffff81691e5c)
Location: include/linux/dma-mapping.h:326
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8171f301)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff8172a1af)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
```
```
In drivers/nvme/host/pci.c (ffffffff8174d657)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_unmap_data
```
```
In drivers/ata/libata-core.c (ffffffff81755445)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffff81779b80)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817a5314)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
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
In drivers/char/agp/intel-gtt.c (ffffffff8166f84c)
Location: include/linux/dma-mapping.h:326
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff816f8731)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff817035cf)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
```
```
In drivers/nvme/host/pci.c (ffffffff8172d4f7)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_unmap_data
```
```
In drivers/ata/libata-core.c (ffffffff817352e5)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffff81759930)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
```
```
In drivers/usb/core/hcd.c (ffffffff81796e24)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
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
In drivers/char/agp/intel-gtt.c (ffffffff816c00cc)
Location: include/linux/dma-mapping.h:326
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8175e0d1)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81768f7f)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
```
```
In drivers/ata/libata-core.c (ffffffff81785155)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffff817a9f20)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817e1db4)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
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
In drivers/char/agp/intel-gtt.c (ffffffff816da69c)
Location: include/linux/dma-mapping.h:326
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81779731)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff817846ef)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
```
```
In drivers/ata/libata-core.c (ffffffff8179ef45)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
```
```
In drivers/spi/spi.c (ffffffff817c3db0)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unmap_buf
```
```
In drivers/usb/core/hcd.c (ffffffff817fc0a4)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
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
