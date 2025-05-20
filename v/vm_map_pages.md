# Function: <code>vm_map_pages</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812561a0)
Location: mm/memory.c:1550
Inline: False
```
**Symbols:**

```
ffffffff812561a0-ffffffff812561b7: vm_map_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81264730)
Location: mm/memory.c:1555
Inline: False
```
**Symbols:**

```
ffffffff81264730-ffffffff81264747: vm_map_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81293200)
Location: mm/memory.c:1718
Inline: False
```
**Symbols:**

```
ffffffff81293200-ffffffff81293217: vm_map_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129dad0)
Location: mm/memory.c:1892
Inline: False
```
**Symbols:**

```
ffffffff8129dad0-ffffffff8129dae7: vm_map_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a30a0)
Location: mm/memory.c:1910
Inline: False
```
**Symbols:**

```
ffffffff812a30a0-ffffffff812a30b7: vm_map_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e63f0)
Location: mm/memory.c:2005
Inline: False
```
**Symbols:**

```
ffffffff812e63f0-ffffffff812e6407: vm_map_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813453b0)
Location: mm/memory.c:2098
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
**Symbols:**

```
ffffffff813453b0-ffffffff813453d3: vm_map_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bd630)
Location: mm/memory.c:2069
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
**Symbols:**

```
ffffffff813bd630-ffffffff813bd650: vm_map_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f2300)
Location: mm/memory.c:2089
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
**Symbols:**

```
ffffffff813f2300-ffffffff813f2323: vm_map_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141cf90)
Location: mm/memory.c:2112
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
**Symbols:**

```
ffffffff8141cf90-ffffffff8141cfb3: vm_map_pages (STB_GLOBAL)
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
int vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102fb478)
Location: mm/memory.c:1555
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
**Symbols:**

```
ffff8000102fb478-ffff8000102fb4c0: vm_map_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0519ce8)
Location: mm/memory.c:1555
Inline: False
```
**Symbols:**

```
c0519ce8-c0519d08: vm_map_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c6390)
Location: mm/memory.c:1555
Inline: False
```
**Symbols:**

```
c0000000003c6390-c0000000003c63a8: vm_map_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020abaa)
Location: mm/memory.c:1555
Inline: False
```
**Symbols:**

```
ffffffe00020abaa-ffffffe00020abe6: vm_map_pages (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125cd80)
Location: mm/memory.c:1555
Inline: False
```
**Symbols:**

```
ffffffff8125cd80-ffffffff8125cd97: vm_map_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124f240)
Location: mm/memory.c:1555
Inline: False
```
**Symbols:**

```
ffffffff8124f240-ffffffff8124f257: vm_map_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125ab20)
Location: mm/memory.c:1555
Inline: False
```
**Symbols:**

```
ffffffff8125ab20-ffffffff8125ab37: vm_map_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8126a4f0)
Location: mm/memory.c:1555
Inline: False
```
**Symbols:**

```
ffffffff8126a4f0-ffffffff8126a507: vm_map_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
