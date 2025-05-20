# Function: <code>dma_unmap_sgtable</code>

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
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8183af13)
Location: include/linux/dma-mapping.h:342
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_unmap_dma_buf
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8183df3f)
Location: include/linux/dma-mapping.h:342
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8181e153)
Location: include/linux/dma-mapping.h:385
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_unmap_dma_buf
```
```
In drivers/dma-buf/udmabuf.c (ffffffff818210df)
Location: include/linux/dma-mapping.h:385
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (ffffffff818a8413)
Location: include/linux/dma-mapping.h:365
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_unmap_dma_buf
```
```
In drivers/dma-buf/udmabuf.c (ffffffff818ab29f)
Location: include/linux/dma-mapping.h:365
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (ffffffff819f2183)
Location: include/linux/dma-mapping.h:365
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_unmap_dma_buf
```
```
In drivers/dma-buf/udmabuf.c (ffffffff819f5941)
Location: include/linux/dma-mapping.h:365
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
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
In drivers/dma-buf/heaps/system_heap.c (ffffffff81b6ff43)
Location: include/linux/dma-mapping.h:370
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_unmap_dma_buf
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81b72eee)
Location: include/linux/dma-mapping.h:370
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
```
```
In drivers/spi/spi.c (ffffffff81bd1c49)
Location: include/linux/dma-mapping.h:370
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi.c:spi_unmap_buf
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
In drivers/dma-buf/heaps/system_heap.c (ffffffff81bc3873)
Location: include/linux/dma-mapping.h:371
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_unmap_dma_buf
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81bc6a1b)
Location: include/linux/dma-mapping.h:371
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
```
```
In drivers/spi/spi.c (ffffffff81c2adb9)
Location: include/linux/dma-mapping.h:371
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi.c:spi_unmap_buf
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
In drivers/dma-buf/heaps/system_heap.c (ffffffff81c18013)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_unmap_dma_buf
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81c1b55b)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/dma-buf/udmabuf.c:unmap_udmabuf
```
```
In drivers/gpu/drm/drm_prime.c (ffffffff81cac58d)
Location: include/linux/dma-mapping.h:376
Inline: True
```
```
In drivers/gpu/drm/drm_gem_shmem_helper.c (ffffffff81cbd74c)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_purge
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_free
```
```
In drivers/spi/spi.c (ffffffff81cdd609)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_msg
  - drivers/spi/spi.c:spi_unmap_buf
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
