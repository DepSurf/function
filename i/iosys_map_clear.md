# Function: <code>iosys_map_clear</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff819ed5bd)
Location: include/linux/iosys-map.h:251
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_vunmap
  - drivers/dma-buf/dma-buf.c:dma_buf_vmap
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff819f2245)
Location: include/linux/iosys-map.h:251
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vunmap
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
In drivers/dma-buf/dma-buf.c (ffffffff81b6a871)
Location: include/linux/iosys-map.h:265
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_vunmap
  - drivers/dma-buf/dma-buf.c:dma_buf_vmap_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_vmap
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81b70022)
Location: include/linux/iosys-map.h:265
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vunmap
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
In drivers/dma-buf/dma-buf.c (ffffffff81bbdcc1)
Location: include/linux/iosys-map.h:265
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_vunmap
  - drivers/dma-buf/dma-buf.c:dma_buf_vmap_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_vmap
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81bc3952)
Location: include/linux/iosys-map.h:265
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vunmap
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
In drivers/dma-buf/dma-buf.c (ffffffff81c12411)
Location: include/linux/iosys-map.h:265
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_vunmap
  - drivers/dma-buf/dma-buf.c:dma_buf_vmap_unlocked
  - drivers/dma-buf/dma-buf.c:dma_buf_vmap
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81c180f2)
Location: include/linux/iosys-map.h:265
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vunmap
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9ba40)
Location: include/linux/iosys-map.h:265
Inline: True
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
