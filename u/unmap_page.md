# Function: <code>unmap_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, struct dma_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8152f860)
Location: drivers/iommu/amd_iommu.c:2530
Inline: False
```
**Symbols:**

```
ffffffff8152f860-ffffffff8152f8e4: unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81584940)
Location: drivers/iommu/amd_iommu.c:2400
Inline: False
```
**Symbols:**

```
ffffffff81584940-ffffffff81584981: unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815b1a20)
Location: drivers/iommu/amd_iommu.c:2493
Inline: False
```
**Symbols:**

```
ffffffff815b1a20-ffffffff815b1a61: unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c76b0)
Location: drivers/iommu/amd_iommu.c:2654
Inline: False
```
**Symbols:**

```
ffffffff815c76b0-ffffffff815c76f1: unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162e380)
Location: drivers/iommu/amd_iommu.c:2435
Inline: False
```
**Symbols:**

```
ffffffff8162e380-ffffffff8162e3c1: unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void unmap_page(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816690f0)
Location: drivers/iommu/amd_iommu.c:2445
Inline: False
```
**Symbols:**

```
ffffffff816690f0-ffffffff81669131: unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
void unmap_page(struct page *page);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8128cd15)
Location: mm/huge_memory.c:2348
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In drivers/iommu/amd_iommu.c (ffffffff81687950)
Location: drivers/iommu/amd_iommu.c:2521
Inline: False
```
**Symbols:**

```
ffffffff81687950-ffffffff81687991: unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
void unmap_page(struct page *page);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a7a27)
Location: mm/huge_memory.c:2406
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In drivers/iommu/amd_iommu.c (ffffffff816bf0e0)
Location: drivers/iommu/amd_iommu.c:2499
Inline: False
```
**Symbols:**

```
ffffffff816bf0e0-ffffffff816bf123: unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void unmap_page(struct page *page);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b8ef2)
Location: mm/huge_memory.c:2411
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In drivers/iommu/amd_iommu.c (ffffffff816e2480)
Location: drivers/iommu/amd_iommu.c:2529
Inline: False
```
**Symbols:**

```
ffffffff816e2480-ffffffff816e24c3: unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812edb01)
Location: mm/huge_memory.c:2321
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f91c3)
Location: mm/huge_memory.c:2345
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
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
In mm/huge_memory.c (ffffffff812ff7c5)
Location: mm/huge_memory.c:2356
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
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
In mm/huge_memory.c (ffffffff813493e1)
Location: mm/huge_memory.c:2284
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
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
In mm/huge_memory.c (ffffffff813bf733)
Location: mm/huge_memory.c:2304
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff8000103595f0)
Location: mm/huge_memory.c:2411
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c000000000442b4c)
Location: mm/huge_memory.c:2411
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
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
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
void unmap_page(struct page *page);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b14d2)
Location: mm/huge_memory.c:2411
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a7ed0)
Location: drivers/iommu/amd_iommu.c:2529
Inline: False
```
**Symbols:**

```
ffffffff816a7ed0-ffffffff816a7f13: unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
void unmap_page(struct page *page);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a28a2)
Location: mm/huge_memory.c:2411
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In drivers/iommu/amd_iommu.c (ffffffff816858c0)
Location: drivers/iommu/amd_iommu.c:2529
Inline: False
```
**Symbols:**

```
ffffffff816858c0-ffffffff81685903: unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
void unmap_page(struct page *page);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812af2e2)
Location: mm/huge_memory.c:2411
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d6140)
Location: drivers/iommu/amd_iommu.c:2529
Inline: False
```
**Symbols:**

```
ffffffff816d6140-ffffffff816d6183: unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
void unmap_page(struct page *page);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812bf632)
Location: mm/huge_memory.c:2411
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In drivers/iommu/amd_iommu.c (ffffffff816f06f0)
Location: drivers/iommu/amd_iommu.c:2529
Inline: False
```
**Symbols:**

```
ffffffff816f06f0-ffffffff816f0733: unmap_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct dma_attrs *attrs</code> ➡️ <code>long unsigned int attrs</code>
</li>
</ul>
</details>
</li>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct page *page</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param removed. </b>
<code>dma_addr_t dma_addr</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t size</code>
</li>
<li>
<b>Param removed. </b>
<code>enum dma_data_direction dir</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int attrs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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
