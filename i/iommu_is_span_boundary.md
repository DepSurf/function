# Function: <code>iommu_is_span_boundary</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int iommu_is_span_boundary(unsigned int index, unsigned int nr, long unsigned int shift, long unsigned int boundary_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff81413140)
Location: lib/iommu-helper.c:9
Inline: True
Direct callers:
  - lib/swiotlb.c:swiotlb_tbl_map_single
  - lib/iommu-helper.c:iommu_area_alloc
```
**Symbols:**

```
ffffffff81413140-ffffffff8141316b: iommu_is_span_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int iommu_is_span_boundary(unsigned int index, unsigned int nr, long unsigned int shift, long unsigned int boundary_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff8145ae40)
Location: lib/iommu-helper.c:9
Inline: True
Direct callers:
  - lib/swiotlb.c:swiotlb_tbl_map_single
  - lib/iommu-helper.c:iommu_area_alloc
```
**Symbols:**

```
ffffffff8145ae40-ffffffff8145ae6b: iommu_is_span_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int iommu_is_span_boundary(unsigned int index, unsigned int nr, long unsigned int shift, long unsigned int boundary_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff81479930)
Location: lib/iommu-helper.c:9
Inline: True
Direct callers:
  - lib/swiotlb.c:swiotlb_tbl_map_single
  - lib/iommu-helper.c:iommu_area_alloc
```
**Symbols:**

```
ffffffff81479930-ffffffff8147995b: iommu_is_span_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int iommu_is_span_boundary(unsigned int index, unsigned int nr, long unsigned int shift, long unsigned int boundary_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff81482c90)
Location: lib/iommu-helper.c:9
Inline: True
Direct callers:
  - lib/swiotlb.c:swiotlb_tbl_map_single
  - lib/iommu-helper.c:iommu_area_alloc
```
**Symbols:**

```
ffffffff81482c90-ffffffff81482cbb: iommu_is_span_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int iommu_is_span_boundary(unsigned int index, unsigned int nr, long unsigned int shift, long unsigned int boundary_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff814becd0)
Location: lib/iommu-helper.c:10
Inline: True
Direct callers:
  - lib/swiotlb.c:swiotlb_tbl_map_single
  - lib/iommu-helper.c:iommu_area_alloc
```
**Symbols:**

```
ffffffff814becd0-ffffffff814becfa: iommu_is_span_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8110dc20)
Location: include/linux/iommu-helper.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In lib/iommu-helper.c (ffffffff814eff41)
Location: include/linux/iommu-helper.h:18
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81119770)
Location: include/linux/iommu-helper.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In lib/iommu-helper.c (ffffffff81503e61)
Location: include/linux/iommu-helper.h:18
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff811241fd)
Location: include/linux/iommu-helper.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In lib/iommu-helper.c (ffffffff81531fd3)
Location: include/linux/iommu-helper.h:18
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81130197)
Location: include/linux/iommu-helper.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In lib/iommu-helper.c (ffffffff81552e13)
Location: include/linux/iommu-helper.h:18
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8113ef61)
Location: include/linux/iommu-helper.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In lib/iommu-helper.c (ffffffff815dc1f6)
Location: include/linux/iommu-helper.h:18
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8113a60f)
Location: include/linux/iommu-helper.h:20
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In lib/iommu-helper.c (ffffffff815f9e96)
Location: include/linux/iommu-helper.h:20
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
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
In kernel/dma/swiotlb.c (ffffffff8113b362)
Location: include/linux/iommu-helper.h:20
Inline: True
```
```
In lib/iommu-helper.c (ffffffff815dca76)
Location: include/linux/iommu-helper.h:20
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
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
In kernel/dma/swiotlb.c (ffffffff8115e473)
Location: include/linux/iommu-helper.h:20
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_find_slots
```
```
In lib/iommu-helper.c (ffffffff816483d6)
Location: include/linux/iommu-helper.h:20
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
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
In kernel/dma/swiotlb.c (ffffffff811885a7)
Location: include/linux/iommu-helper.h:20
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_find_slots
```
```
In lib/iommu-helper.c (ffffffff8175e7b4)
Location: include/linux/iommu-helper.h:20
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
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
In kernel/dma/swiotlb.c (ffffffff811c462c)
Location: include/linux/iommu-helper.h:20
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_do_find_slots
```
```
In lib/iommu-helper.c (ffffffff8188bfd4)
Location: include/linux/iommu-helper.h:20
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
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
In kernel/dma/swiotlb.c (ffffffff811d7058)
Location: include/linux/iommu-helper.h:20
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_do_find_slots
```
```
In lib/iommu-helper.c (ffffffff818ce444)
Location: include/linux/iommu-helper.h:20
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
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
In kernel/dma/swiotlb.c (ffffffff811ec054)
Location: include/linux/iommu-helper.h:20
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_search_pool_area
```
```
In lib/iommu-helper.c (ffffffff819201f4)
Location: include/linux/iommu-helper.h:20
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
</details>
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
In kernel/dma/swiotlb.c (ffff800010196964)
Location: include/linux/iommu-helper.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (c0000000001f6d40)
Location: include/linux/iommu-helper.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In lib/iommu-helper.c (c0000000008119e0)
Location: include/linux/iommu-helper.h:18
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffe0001282a0)
Location: include/linux/iommu-helper.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81128947)
Location: include/linux/iommu-helper.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In lib/iommu-helper.c (ffffffff8154b3f3)
Location: include/linux/iommu-helper.h:18
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8111b1d7)
Location: include/linux/iommu-helper.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In lib/iommu-helper.c (ffffffff8153b6d3)
Location: include/linux/iommu-helper.h:18
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81126667)
Location: include/linux/iommu-helper.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In lib/iommu-helper.c (ffffffff81547133)
Location: include/linux/iommu-helper.h:18
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81132ca7)
Location: include/linux/iommu-helper.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In lib/iommu-helper.c (ffffffff81560f83)
Location: include/linux/iommu-helper.h:18
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
</ul>
