# Function: <code>swiotlb_tbl_unmap_single</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void swiotlb_tbl_unmap_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814121c0)
Location: lib/swiotlb.c:552
Inline: False
Direct callers:
  - lib/swiotlb.c:swiotlb_free_coherent
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
**Symbols:**

```
ffffffff814121c0-ffffffff814122d0: swiotlb_tbl_unmap_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void swiotlb_tbl_unmap_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81459ef0)
Location: lib/swiotlb.c:552
Inline: False
Direct callers:
  - lib/swiotlb.c:swiotlb_map_page
  - lib/swiotlb.c:swiotlb_free_coherent
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
**Symbols:**

```
ffffffff81459ef0-ffffffff8145a001: swiotlb_tbl_unmap_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void swiotlb_tbl_unmap_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814788d0)
Location: lib/swiotlb.c:592
Inline: False
Direct callers:
  - lib/swiotlb.c:swiotlb_map_page
  - lib/swiotlb.c:swiotlb_free_coherent
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
**Symbols:**

```
ffffffff814788d0-ffffffff814789ec: swiotlb_tbl_unmap_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void swiotlb_tbl_unmap_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814818f0)
Location: lib/swiotlb.c:592
Inline: False
Direct callers:
  - lib/swiotlb.c:swiotlb_unmap_page
  - lib/swiotlb.c:swiotlb_map_page
  - lib/swiotlb.c:swiotlb_free_coherent
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
**Symbols:**

```
ffffffff814818f0-ffffffff81481a03: swiotlb_tbl_unmap_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void swiotlb_tbl_unmap_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814bd740)
Location: lib/swiotlb.c:634
Inline: False
Direct callers:
  - lib/swiotlb.c:swiotlb_map_page
  - lib/swiotlb.c:swiotlb_free_coherent
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
**Symbols:**

```
ffffffff814bd740-ffffffff814bd853: swiotlb_tbl_unmap_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void swiotlb_tbl_unmap_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8110dee0)
Location: kernel/dma/swiotlb.c:618
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_free
  - kernel/dma/swiotlb.c:swiotlb_alloc
  - kernel/dma/swiotlb.c:swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
**Symbols:**

```
ffffffff8110dee0-ffffffff8110e011: swiotlb_tbl_unmap_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void swiotlb_tbl_unmap_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff811199a0)
Location: kernel/dma/swiotlb.c:546
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
**Symbols:**

```
ffffffff811199a0-ffffffff81119ad1: swiotlb_tbl_unmap_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void swiotlb_tbl_unmap_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff811243f0)
Location: kernel/dma/swiotlb.c:573
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
**Symbols:**

```
ffffffff811243f0-ffffffff8112450a: swiotlb_tbl_unmap_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void swiotlb_tbl_unmap_single(struct device *hwdev, phys_addr_t tlb_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81130370)
Location: kernel/dma/swiotlb.c:580
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/iommu/intel-iommu.c:bounce_unmap_single
  - drivers/iommu/intel-iommu.c:bounce_map_single
```
**Symbols:**

```
ffffffff81130370-ffffffff8113048b: swiotlb_tbl_unmap_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void swiotlb_tbl_unmap_single(struct device *hwdev, phys_addr_t tlb_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8113f150)
Location: kernel/dma/swiotlb.c:581
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/iommu/intel/iommu.c:bounce_unmap_single
  - drivers/iommu/intel/iommu.c:bounce_map_single
```
**Symbols:**

```
ffffffff8113f150-ffffffff8113f269: swiotlb_tbl_unmap_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void swiotlb_tbl_unmap_single(struct device *hwdev, phys_addr_t tlb_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8113a830)
Location: kernel/dma/swiotlb.c:596
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap_swiotlb
```
**Symbols:**

```
ffffffff8113a830-ffffffff8113a949: swiotlb_tbl_unmap_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void swiotlb_tbl_unmap_single(struct device *hwdev, phys_addr_t tlb_addr, size_t mapping_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8113bb90)
Location: kernel/dma/swiotlb.c:556
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap_swiotlb
```
**Symbols:**

```
ffffffff8113bb90-ffffffff8113bccf: swiotlb_tbl_unmap_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void swiotlb_tbl_unmap_single(struct device *dev, phys_addr_t tlb_addr, size_t mapping_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8115ec50)
Location: kernel/dma/swiotlb.c:638
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap_swiotlb
```
**Symbols:**

```
ffffffff8115ec50-ffffffff8115edc7: swiotlb_tbl_unmap_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void swiotlb_tbl_unmap_single(struct device *dev, phys_addr_t tlb_addr, size_t mapping_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81188db0)
Location: kernel/dma/swiotlb.c:670
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
**Symbols:**

```
ffffffff81188db0-ffffffff81188f37: swiotlb_tbl_unmap_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void swiotlb_tbl_unmap_single(struct device *dev, phys_addr_t tlb_addr, size_t mapping_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff811c5130)
Location: kernel/dma/swiotlb.c:847
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
**Symbols:**

```
ffffffff811c5130-ffffffff811c52f0: swiotlb_tbl_unmap_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_tbl_unmap_single(struct device *dev, phys_addr_t tlb_addr, size_t mapping_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff811d80c4)
Location: kernel/dma/swiotlb.c:872
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
Direct callers:
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
**Symbols:**

```
ffffffff811d7e60-ffffffff811d7ebc: swiotlb_tbl_unmap_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void swiotlb_tbl_unmap_single(struct device *dev, phys_addr_t tlb_addr, size_t mapping_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:1434
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
**Symbols:**

```
ffffffff821b4b28-ffffffff821b4b3d: swiotlb_tbl_unmap_single.cold (STB_LOCAL)
ffffffff811ed810-ffffffff811ed900: swiotlb_tbl_unmap_single (STB_GLOBAL)
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
void swiotlb_tbl_unmap_single(struct device *hwdev, phys_addr_t tlb_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffff800010196be8)
Location: kernel/dma/swiotlb.c:580
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
**Symbols:**

```
ffff800010196be8-ffff800010196d90: swiotlb_tbl_unmap_single (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void swiotlb_tbl_unmap_single(struct device *hwdev, phys_addr_t tlb_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (c0000000001f7120)
Location: kernel/dma/swiotlb.c:580
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/swiotlb.c:swiotlb_map
```
**Symbols:**

```
c0000000001f7120-c0000000001f72d8: swiotlb_tbl_unmap_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void swiotlb_tbl_unmap_single(struct device *hwdev, phys_addr_t tlb_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffe0001284d4)
Location: kernel/dma/swiotlb.c:580
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/swiotlb.c:swiotlb_map
```
**Symbols:**

```
ffffffe0001284d4-ffffffe000128644: swiotlb_tbl_unmap_single (STB_GLOBAL)
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
void swiotlb_tbl_unmap_single(struct device *hwdev, phys_addr_t tlb_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81128b20)
Location: kernel/dma/swiotlb.c:580
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/iommu/intel-iommu.c:bounce_unmap_single
  - drivers/iommu/intel-iommu.c:bounce_map_single
```
**Symbols:**

```
ffffffff81128b20-ffffffff81128c3b: swiotlb_tbl_unmap_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void swiotlb_tbl_unmap_single(struct device *hwdev, phys_addr_t tlb_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8111b3b0)
Location: kernel/dma/swiotlb.c:580
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/iommu/intel-iommu.c:bounce_unmap_single
  - drivers/iommu/intel-iommu.c:bounce_map_single
```
**Symbols:**

```
ffffffff8111b3b0-ffffffff8111b4cb: swiotlb_tbl_unmap_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void swiotlb_tbl_unmap_single(struct device *hwdev, phys_addr_t tlb_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81126840)
Location: kernel/dma/swiotlb.c:580
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/iommu/intel-iommu.c:bounce_unmap_single
  - drivers/iommu/intel-iommu.c:bounce_map_single
```
**Symbols:**

```
ffffffff81126840-ffffffff8112695b: swiotlb_tbl_unmap_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void swiotlb_tbl_unmap_single(struct device *hwdev, phys_addr_t tlb_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81132e80)
Location: kernel/dma/swiotlb.c:580
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/iommu/intel-iommu.c:bounce_unmap_single
  - drivers/iommu/intel-iommu.c:bounce_map_single
```
**Symbols:**

```
ffffffff81132e80-ffffffff81132f9b: swiotlb_tbl_unmap_single (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int attrs</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t mapping_size</code>
</li>
<li>
<b>Param added. </b>
<code>size_t alloc_size</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t size</code>
</li>
<li>
<b>Param reordered. </b>
<code>hwdev, tlb_addr, size, dir, attrs</code> ➡️ <code>hwdev, tlb_addr, mapping_size, alloc_size, dir, attrs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>size_t alloc_size</code>
</li>
<li>
<b>Param reordered. </b>
<code>hwdev, tlb_addr, mapping_size, alloc_size, dir, attrs</code> ➡️ <code>hwdev, tlb_addr, mapping_size, dir, attrs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *hwdev</code>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
