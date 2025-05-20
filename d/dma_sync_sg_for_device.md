# Function: <code>dma_sync_sg_for_device</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/heaps/heap-helpers.c (ffffffff8182a22b)
Location: include/linux/dma-mapping.h:419
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/heap-helpers.c:dma_heap_dma_buf_end_cpu_access
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8182c85d)
Location: include/linux/dma-mapping.h:419
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:end_cpu_udmabuf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dma_sync_sg_for_device(struct device *dev, struct scatterlist *sg, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81137720)
Location: kernel/dma/mapping.c:300
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_end_cpu_access
  - drivers/dma-buf/udmabuf.c:end_cpu_udmabuf
```
**Symbols:**

```
ffffffff81137720-ffffffff81137767: dma_sync_sg_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dma_sync_sg_for_device(struct device *dev, struct scatterlist *sg, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81138510)
Location: kernel/dma/mapping.c:302
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_end_cpu_access
  - drivers/dma-buf/udmabuf.c:end_cpu_udmabuf
```
**Symbols:**

```
ffffffff81138510-ffffffff81138557: dma_sync_sg_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dma_sync_sg_for_device(struct device *dev, struct scatterlist *sg, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115b360)
Location: kernel/dma/mapping.c:367
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_end_cpu_access
  - drivers/dma-buf/udmabuf.c:end_cpu_udmabuf
```
**Symbols:**

```
ffffffff8115b360-ffffffff8115b3a7: dma_sync_sg_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dma_sync_sg_for_device(struct device *dev, struct scatterlist *sg, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81184cb0)
Location: kernel/dma/mapping.c:363
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_end_cpu_access
  - drivers/dma-buf/udmabuf.c:end_cpu_udmabuf
```
**Symbols:**

```
ffffffff81184cb0-ffffffff81184d13: dma_sync_sg_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dma_sync_sg_for_device(struct device *dev, struct scatterlist *sg, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c0380)
Location: kernel/dma/mapping.c:370
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_end_cpu_access
  - drivers/dma-buf/udmabuf.c:end_cpu_udmabuf
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff811c0380-ffffffff811c03e3: dma_sync_sg_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dma_sync_sg_for_device(struct device *dev, struct scatterlist *sg, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d2e60)
Location: kernel/dma/mapping.c:374
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_end_cpu_access
  - drivers/dma-buf/udmabuf.c:end_cpu_udmabuf
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff811d2e60-ffffffff811d2ec3: dma_sync_sg_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dma_sync_sg_for_device(struct device *dev, struct scatterlist *sg, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e7ae0)
Location: kernel/dma/mapping.c:374
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_end_cpu_access
  - drivers/dma-buf/udmabuf.c:end_cpu_udmabuf
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff811e7ae0-ffffffff811e7b43: dma_sync_sg_for_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/imx.c (ffff80001089db00)
Location: include/linux/dma-mapping.h:419
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/imx.c (c0995e30)
Location: include/linux/dma-mapping.h:419
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
```
</details>
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
