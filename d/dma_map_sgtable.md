# Function: <code>dma_map_sgtable</code>

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
In drivers/dma-buf/heaps/system_heap.c (ffffffff8183af4d)
Location: include/linux/dma-mapping.h:319
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_map_dma_buf
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8183d900)
Location: include/linux/dma-mapping.h:319
Inline: True
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
In drivers/dma-buf/heaps/system_heap.c (ffffffff8181e18d)
Location: include/linux/dma-mapping.h:362
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_map_dma_buf
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81820a90)
Location: include/linux/dma-mapping.h:362
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dma_map_sgtable(struct device *dev, struct sg_table *sgt, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115b150)
Location: kernel/dma/mapping.c:259
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_map_dma_buf
```
**Symbols:**

```
ffffffff8115b150-ffffffff8115b180: dma_map_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dma_map_sgtable(struct device *dev, struct sg_table *sgt, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81184ae0)
Location: kernel/dma/mapping.c:259
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_map_dma_buf
```
**Symbols:**

```
ffffffff81184ae0-ffffffff81184b1b: dma_map_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dma_map_sgtable(struct device *dev, struct sg_table *sgt, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c0170)
Location: kernel/dma/mapping.c:266
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_map_dma_buf
  - drivers/spi/spi.c:spi_map_buf_attrs
```
**Symbols:**

```
ffffffff811c0170-ffffffff811c01ab: dma_map_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dma_map_sgtable(struct device *dev, struct sg_table *sgt, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d2c50)
Location: kernel/dma/mapping.c:270
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_map_dma_buf
  - drivers/spi/spi.c:spi_map_buf_attrs
```
**Symbols:**

```
ffffffff811d2c50-ffffffff811d2c8b: dma_map_sgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dma_map_sgtable(struct device *dev, struct sg_table *sgt, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e78d0)
Location: kernel/dma/mapping.c:270
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_map_dma_buf
  - drivers/gpu/drm/drm_prime.c:drm_gem_map_dma_buf
  - drivers/spi/spi.c:spi_map_buf_attrs
```
**Symbols:**

```
ffffffff811e78d0-ffffffff811e790b: dma_map_sgtable (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
