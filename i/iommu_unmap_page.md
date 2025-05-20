# Function: <code>iommu_unmap_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8152fa5e)
Location: drivers/iommu/amd_iommu.c:1301
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int page_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81582a40)
Location: drivers/iommu/amd_iommu.c:1408
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff81582a40-ffffffff81582b38: iommu_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int page_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815aed20)
Location: drivers/iommu/amd_iommu.c:1498
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff815aed20-ffffffff815aee18: iommu_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int page_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c4920)
Location: drivers/iommu/amd_iommu.c:1557
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff815c4920-ffffffff815c4a18: iommu_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int page_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162b780)
Location: drivers/iommu/amd_iommu.c:1498
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff8162b780-ffffffff8162b878: iommu_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int page_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816663d0)
Location: drivers/iommu/amd_iommu.c:1504
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff816663d0-ffffffff816664c4: iommu_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int page_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81684d00)
Location: drivers/iommu/amd_iommu.c:1646
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff81684d00-ffffffff81684df5: iommu_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int page_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bc210)
Location: drivers/iommu/amd_iommu.c:1661
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff816bc210-ffffffff816bc30a: iommu_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int page_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816df0a0)
Location: drivers/iommu/amd_iommu.c:1721
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff816df0a0-ffffffff816df19a: iommu_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int page_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81795f00)
Location: drivers/iommu/amd/iommu.c:1700
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_unmap
```
**Symbols:**

```
ffffffff81795f00-ffffffff8179600e: iommu_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int page_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a4620)
Location: drivers/iommu/amd/iommu.c:1791
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_unmap
```
**Symbols:**

```
ffffffff817a4620-ffffffff817a472e: iommu_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void iommu_unmap_page(struct iommu_table *tbl, dma_addr_t dma_handle, size_t size, enum dma_data_direction direction, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/iommu.c (c000000000052e20)
Location: arch/powerpc/kernel/iommu.c:833
Inline: False
Direct callers:
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_unmap_page
  - arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_unmap_page
```
**Symbols:**

```
c000000000052e20-c000000000052e74: iommu_unmap_page (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int page_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a4af0)
Location: drivers/iommu/amd_iommu.c:1721
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff816a4af0-ffffffff816a4bea: iommu_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int page_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816824e0)
Location: drivers/iommu/amd_iommu.c:1721
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff816824e0-ffffffff816825da: iommu_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int page_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d2d60)
Location: drivers/iommu/amd_iommu.c:1721
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff816d2d60-ffffffff816d2e5a: iommu_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int page_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ed400)
Location: drivers/iommu/amd_iommu.c:1721
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff816ed400-ffffffff816ed4fa: iommu_unmap_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iommu_table *tbl</code>
</li>
<li>
<b>Param added. </b>
<code>dma_addr_t dma_handle</code>
</li>
<li>
<b>Param added. </b>
<code>size_t size</code>
</li>
<li>
<b>Param added. </b>
<code>enum dma_data_direction direction</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int attrs</code>
</li>
<li>
<b>Param removed. </b>
<code>struct protection_domain *dom</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int bus_addr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int page_size</code>
</li>
<li>
<b>Return type changed. </b>
<code>long unsigned int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
