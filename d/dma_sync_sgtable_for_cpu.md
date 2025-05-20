# Function: <code>dma_sync_sgtable_for_cpu</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8183aec2)
Location: include/linux/dma-mapping.h:360
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_begin_cpu_access
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
In drivers/dma-buf/heaps/system_heap.c (ffffffff8181e102)
Location: include/linux/dma-mapping.h:403
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_begin_cpu_access
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
In drivers/dma-buf/heaps/system_heap.c (ffffffff818a85d1)
Location: include/linux/dma-mapping.h:383
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_begin_cpu_access
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
In drivers/dma-buf/heaps/system_heap.c (ffffffff819f2371)
Location: include/linux/dma-mapping.h:383
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_begin_cpu_access
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
In drivers/dma-buf/heaps/system_heap.c (ffffffff81b7016e)
Location: include/linux/dma-mapping.h:388
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_begin_cpu_access
```
```
In drivers/spi/spi.c (ffffffff81bd117c)
Location: include/linux/dma-mapping.h:388
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_dma_sync_for_cpu
  - drivers/spi/spi.c:spi_dma_sync_for_cpu
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
In drivers/dma-buf/heaps/system_heap.c (ffffffff81bc3a9e)
Location: include/linux/dma-mapping.h:389
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_begin_cpu_access
```
```
In drivers/spi/spi.c (ffffffff81c28dec)
Location: include/linux/dma-mapping.h:389
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_dma_sync_for_cpu
  - drivers/spi/spi.c:spi_dma_sync_for_cpu
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
In drivers/dma-buf/heaps/system_heap.c (ffffffff81c1823e)
Location: include/linux/dma-mapping.h:394
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_begin_cpu_access
```
```
In drivers/spi/spi.c (ffffffff81cdb93c)
Location: include/linux/dma-mapping.h:394
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_dma_sync_for_cpu
  - drivers/spi/spi.c:spi_dma_sync_for_cpu
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
