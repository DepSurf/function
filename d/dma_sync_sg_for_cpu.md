# Function: <code>dma_sync_sg_for_cpu</code>

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
In drivers/dma-buf/heaps/heap-helpers.c (ffffffff8182a2db)
Location: include/linux/dma-mapping.h:405
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/heap-helpers.c:dma_heap_dma_buf_begin_cpu_access
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8182ceea)
Location: include/linux/dma-mapping.h:405
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:begin_cpu_udmabuf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dma_sync_sg_for_cpu(struct device *dev, struct scatterlist *sg, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811376d0)
Location: kernel/dma/mapping.c:286
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_begin_cpu_access
  - drivers/dma-buf/udmabuf.c:begin_cpu_udmabuf
```
**Symbols:**

```
ffffffff811376d0-ffffffff81137717: dma_sync_sg_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dma_sync_sg_for_cpu(struct device *dev, struct scatterlist *sg, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811384c0)
Location: kernel/dma/mapping.c:288
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_begin_cpu_access
  - drivers/dma-buf/udmabuf.c:begin_cpu_udmabuf
```
**Symbols:**

```
ffffffff811384c0-ffffffff81138507: dma_sync_sg_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dma_sync_sg_for_cpu(struct device *dev, struct scatterlist *sg, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115b310)
Location: kernel/dma/mapping.c:353
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_begin_cpu_access
  - drivers/dma-buf/udmabuf.c:begin_cpu_udmabuf
```
**Symbols:**

```
ffffffff8115b310-ffffffff8115b357: dma_sync_sg_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dma_sync_sg_for_cpu(struct device *dev, struct scatterlist *sg, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81184c40)
Location: kernel/dma/mapping.c:349
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_begin_cpu_access
  - drivers/dma-buf/udmabuf.c:begin_cpu_udmabuf
```
**Symbols:**

```
ffffffff81184c40-ffffffff81184ca3: dma_sync_sg_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dma_sync_sg_for_cpu(struct device *dev, struct scatterlist *sg, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c0300)
Location: kernel/dma/mapping.c:356
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_begin_cpu_access
  - drivers/dma-buf/udmabuf.c:begin_cpu_udmabuf
  - drivers/spi/spi.c:spi_dma_sync_for_cpu
  - drivers/spi/spi.c:spi_dma_sync_for_cpu
```
**Symbols:**

```
ffffffff811c0300-ffffffff811c0363: dma_sync_sg_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dma_sync_sg_for_cpu(struct device *dev, struct scatterlist *sg, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d2de0)
Location: kernel/dma/mapping.c:360
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_begin_cpu_access
  - drivers/dma-buf/udmabuf.c:begin_cpu_udmabuf
  - drivers/spi/spi.c:spi_dma_sync_for_cpu
  - drivers/spi/spi.c:spi_dma_sync_for_cpu
```
**Symbols:**

```
ffffffff811d2de0-ffffffff811d2e43: dma_sync_sg_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dma_sync_sg_for_cpu(struct device *dev, struct scatterlist *sg, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e7a60)
Location: kernel/dma/mapping.c:360
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_begin_cpu_access
  - drivers/dma-buf/udmabuf.c:begin_cpu_udmabuf
  - drivers/spi/spi.c:spi_dma_sync_for_cpu
  - drivers/spi/spi.c:spi_dma_sync_for_cpu
```
**Symbols:**

```
ffffffff811e7a60-ffffffff811e7ac3: dma_sync_sg_for_cpu (STB_GLOBAL)
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
In drivers/tty/serial/imx.c (ffff80001089dabc)
Location: include/linux/dma-mapping.h:405
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
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
In drivers/tty/serial/imx.c (c0995dc8)
Location: include/linux/dma-mapping.h:405
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
```
```
In drivers/mmc/host/sdhci.c (c0c280e0)
Location: include/linux/dma-mapping.h:405
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_finish_data
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
