# Function: <code>iommu_dma_free_iova</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void iommu_dma_free_iova(struct iommu_dma_cookie *cookie, dma_addr_t iova, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81791960)
Location: drivers/iommu/dma-iommu.c:440
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_msi_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
**Symbols:**

```
ffffffff81791960-ffffffff817919a6: iommu_dma_free_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iommu_dma_free_iova(struct iommu_dma_cookie *cookie, dma_addr_t iova, size_t size, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817bdb50)
Location: drivers/iommu/dma-iommu.c:471
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_msi_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
**Symbols:**

```
ffffffff817bdb50-ffffffff817bdb9a: iommu_dma_free_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iommu_dma_free_iova(struct iommu_dma_cookie *cookie, dma_addr_t iova, size_t size, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817a0d90)
Location: drivers/iommu/dma-iommu.c:457
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
**Symbols:**

```
ffffffff817a0d90-ffffffff817a0dda: iommu_dma_free_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void iommu_dma_free_iova(struct iommu_dma_cookie *cookie, dma_addr_t iova, size_t size, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:473
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
**Symbols:**

```
ffffffff8182a840-ffffffff8182a92d: iommu_dma_free_iova (STB_LOCAL)
ffffffff81d01daa-ffffffff81d01e4b: iommu_dma_free_iova.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void iommu_dma_free_iova(struct iommu_dma_cookie *cookie, dma_addr_t iova, size_t size, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:646
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
**Symbols:**

```
ffffffff8196ad50-ffffffff8196b049: iommu_dma_free_iova (STB_LOCAL)
ffffffff81eca258-ffffffff81eca2f1: iommu_dma_free_iova.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void iommu_dma_free_iova(struct iommu_dma_cookie *cookie, dma_addr_t iova, size_t size, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:657
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
**Symbols:**

```
ffffffff81ad5230-ffffffff81ad5529: iommu_dma_free_iova (STB_LOCAL)
ffffffff82097f2a-ffffffff82097fc3: iommu_dma_free_iova.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void iommu_dma_free_iova(struct iommu_dma_cookie *cookie, dma_addr_t iova, size_t size, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:690
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
**Symbols:**

```
ffffffff81b239e0-ffffffff81b23cd9: iommu_dma_free_iova (STB_LOCAL)
ffffffff82118f3a-ffffffff82118fd3: iommu_dma_free_iova.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void iommu_dma_free_iova(struct iommu_dma_cookie *cookie, dma_addr_t iova, size_t size, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:809
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
**Symbols:**

```
ffffffff81b7a790-ffffffff81b7a89c: iommu_dma_free_iova (STB_LOCAL)
ffffffff821f6ede-ffffffff821f6f7f: iommu_dma_free_iova.cold (STB_LOCAL)
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
void iommu_dma_free_iova(struct iommu_dma_cookie *cookie, dma_addr_t iova, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffff8000108c8ce0)
Location: drivers/iommu/dma-iommu.c:425
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
**Symbols:**

```
ffff8000108c8ce0-ffff8000108c8d78: iommu_dma_free_iova (STB_LOCAL)
```
</details>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct page *freelist</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iommu_iotlb_gather *gather</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *freelist</code>
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
<b>Arch</b>
<ul>
</ul>
