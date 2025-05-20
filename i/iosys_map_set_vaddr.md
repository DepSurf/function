# Function: <code>iosys_map_set_vaddr</code>

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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (ffffffff819f2073)
Location: include/linux/iosys-map.h:169
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81b6fe10)
Location: include/linux/iosys-map.h:183
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
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
In drivers/dma-buf/heaps/system_heap.c (ffffffff81bc3740)
Location: include/linux/iosys-map.h:183
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81bc6766)
Location: include/linux/iosys-map.h:183
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:vmap_udmabuf
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
In drivers/dma-buf/heaps/system_heap.c (ffffffff81c17ee0)
Location: include/linux/iosys-map.h:183
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81c1b276)
Location: include/linux/iosys-map.h:183
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:vmap_udmabuf
```
```
In drivers/gpu/drm/drm_gem_shmem_helper.c (ffffffff81cbd9bf)
Location: include/linux/iosys-map.h:183
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_vmap
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_vmap
```
```
In drivers/gpu/drm/tiny/simpledrm.c (0)
Location: include/linux/iosys-map.h:183
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
