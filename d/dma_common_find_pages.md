# Function: <code>dma_common_find_pages</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page **dma_common_find_pages(void *cpu_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/remap.c (ffffffff811897b0)
Location: kernel/dma/remap.c:9
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
**Symbols:**

```
ffffffff811897b0-ffffffff811897e0: dma_common_find_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page **dma_common_find_pages(void *cpu_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/remap.c (ffffffff811c5bf0)
Location: kernel/dma/remap.c:9
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
**Symbols:**

```
ffffffff811c5bf0-ffffffff811c5c20: dma_common_find_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page **dma_common_find_pages(void *cpu_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/remap.c (ffffffff811d87c0)
Location: kernel/dma/remap.c:9
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
**Symbols:**

```
ffffffff811d87c0-ffffffff811d87f0: dma_common_find_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page **dma_common_find_pages(void *cpu_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/remap.c (ffffffff811ee2d0)
Location: kernel/dma/remap.c:9
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
**Symbols:**

```
ffffffff811ee2d0-ffffffff811ee300: dma_common_find_pages (STB_GLOBAL)
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
struct page **dma_common_find_pages(void *cpu_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/remap.c (ffff800010197240)
Location: kernel/dma/remap.c:14
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
  - drivers/iommu/dma-iommu.c:__iommu_dma_free
```
**Symbols:**

```
ffff800010197240-ffff800010197290: dma_common_find_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page **dma_common_find_pages(void *cpu_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/remap.c (c03e2934)
Location: kernel/dma/remap.c:14
Inline: False
Direct callers:
  - arch/arm/mm/dma-mapping.c:__iommu_get_pages
```
**Symbols:**

```
c03e2934-c03e2968: dma_common_find_pages (STB_GLOBAL)
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
</ul>
