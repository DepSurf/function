# Function: <code>iommu_map_page</code>

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
In drivers/iommu/amd_iommu.c (ffffffff8152fcd9)
Location: drivers/iommu/amd_iommu.c:1257
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int iommu_map_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815835d0)
Location: drivers/iommu/amd_iommu.c:1363
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff815835d0-ffffffff81583980: iommu_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int iommu_map_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815b08e0)
Location: drivers/iommu/amd_iommu.c:1453
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff815b08e0-ffffffff815b0c87: iommu_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int iommu_map_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c6810)
Location: drivers/iommu/amd_iommu.c:1512
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff815c6810-ffffffff815c6bae: iommu_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iommu_map_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162d5b0)
Location: drivers/iommu/amd_iommu.c:1453
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff8162d5b0-ffffffff8162d97d: iommu_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int iommu_map_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81668070)
Location: drivers/iommu/amd_iommu.c:1459
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff81668070-ffffffff81668425: iommu_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int iommu_map_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:1595
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff816863b0-ffffffff816867f5: iommu_map_page (STB_LOCAL)
ffffffff81689c21-ffffffff81689c52: iommu_map_page.cold.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int iommu_map_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:1610
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff816bdc70-ffffffff816be0d5: iommu_map_page (STB_LOCAL)
ffffffff816c1227-ffffffff816c1258: iommu_map_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int iommu_map_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:1658
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff816e0e60-ffffffff816e13ab: iommu_map_page (STB_LOCAL)
ffffffff816e4261-ffffffff816e428e: iommu_map_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int iommu_map_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1631
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_map
```
**Symbols:**

```
ffffffff81799930-ffffffff81799ba0: iommu_map_page (STB_LOCAL)
ffffffff8179a867-ffffffff8179a8a7: iommu_map_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int iommu_map_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1722
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_map
```
**Symbols:**

```
ffffffff817a8060-ffffffff817a82d0: iommu_map_page (STB_LOCAL)
ffffffff81c0b731-ffffffff81c0b771: iommu_map_page.cold (STB_LOCAL)
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
dma_addr_t iommu_map_page(struct device *dev, struct iommu_table *tbl, struct page *page, long unsigned int offset, size_t size, long unsigned int mask, enum dma_data_direction direction, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/iommu.c (c000000000052c10)
Location: arch/powerpc/kernel/iommu.c:794
Inline: False
Direct callers:
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_map_page
  - arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_map_page
```
**Symbols:**

```
c000000000052c10-c000000000052e14: iommu_map_page (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int iommu_map_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:1658
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff816a68b0-ffffffff816a6dfb: iommu_map_page (STB_LOCAL)
ffffffff816a9d41-ffffffff816a9d6e: iommu_map_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int iommu_map_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:1658
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff816842a0-ffffffff816847eb: iommu_map_page (STB_LOCAL)
ffffffff816876a1-ffffffff816876ce: iommu_map_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int iommu_map_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:1658
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff816d4b20-ffffffff816d506b: iommu_map_page (STB_LOCAL)
ffffffff816d7f21-ffffffff816d7f4e: iommu_map_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int iommu_map_page(struct protection_domain *dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:1658
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_map
  - drivers/iommu/amd_iommu.c:map_sg
```
**Symbols:**

```
ffffffff816ef220-ffffffff816ef76b: iommu_map_page (STB_LOCAL)
ffffffff816f24d1-ffffffff816f24fe: iommu_map_page.cold (STB_LOCAL)
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
<code>struct device *dev</code>
</li>
<li>
<b>Param added. </b>
<code>struct iommu_table *tbl</code>
</li>
<li>
<b>Param added. </b>
<code>struct page *page</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int offset</code>
</li>
<li>
<b>Param added. </b>
<code>size_t size</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int mask</code>
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
<code>long unsigned int phys_addr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int page_size</code>
</li>
<li>
<b>Param removed. </b>
<code>int prot</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>dma_addr_t</code>
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
