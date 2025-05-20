# Function: <code>swiotlb_tbl_map_single</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device *hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81411ee0)
Location: lib/swiotlb.c:425
Inline: False
Direct callers:
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_map_page
  - lib/swiotlb.c:swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
**Symbols:**

```
ffffffff81411ee0-ffffffff814121b8: swiotlb_tbl_map_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device *hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81459c50)
Location: lib/swiotlb.c:425
Inline: False
Direct callers:
  - lib/swiotlb.c:swiotlb_map_sg_attrs
  - lib/swiotlb.c:swiotlb_map_page
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
**Symbols:**

```
ffffffff81459c50-ffffffff81459ee9: swiotlb_tbl_map_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device *hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81478620)
Location: lib/swiotlb.c:455
Inline: False
Direct callers:
  - lib/swiotlb.c:map_single
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
**Symbols:**

```
ffffffff81478620-ffffffff814788c7: swiotlb_tbl_map_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device *hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81481b80)
Location: lib/swiotlb.c:455
Inline: False
Direct callers:
  - lib/swiotlb.c:map_single
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
**Symbols:**

```
ffffffff81481b80-ffffffff81481e57: swiotlb_tbl_map_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device *hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814bd9e0)
Location: lib/swiotlb.c:493
Inline: False
Direct callers:
  - lib/swiotlb.c:map_single
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
**Symbols:**

```
ffffffff814bd9e0-ffffffff814bdd0c: swiotlb_tbl_map_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device *hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:479
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_alloc
  - kernel/dma/swiotlb.c:map_single
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
**Symbols:**

```
ffffffff8110e8b6-ffffffff8110e8c2: swiotlb_tbl_map_single.cold.20 (STB_LOCAL)
ffffffff8110db40-ffffffff8110de42: swiotlb_tbl_map_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device *hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:427
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
**Symbols:**

```
ffffffff81119e3b-ffffffff81119e47: swiotlb_tbl_map_single.cold.12 (STB_LOCAL)
ffffffff81119690-ffffffff81119992: swiotlb_tbl_map_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device *hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:445
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
**Symbols:**

```
ffffffff81124844-ffffffff81124878: swiotlb_tbl_map_single.cold (STB_LOCAL)
ffffffff811240f0-ffffffff811243e5: swiotlb_tbl_map_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device *hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:445
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/iommu/intel-iommu.c:bounce_map_single
```
**Symbols:**

```
ffffffff811307c4-ffffffff81130840: swiotlb_tbl_map_single.cold (STB_LOCAL)
ffffffff81130080-ffffffff81130363: swiotlb_tbl_map_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device *hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:446
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/iommu/intel/iommu.c:bounce_map_single
```
**Symbols:**

```
ffffffff8113f5cc-ffffffff8113f64e: swiotlb_tbl_map_single.cold (STB_LOCAL)
ffffffff8113ee50-ffffffff8113f145: swiotlb_tbl_map_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device *hwdev, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:464
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
**Symbols:**

```
ffffffff81be3705-ffffffff81be3777: swiotlb_tbl_map_single.cold (STB_LOCAL)
ffffffff8113a4e0-ffffffff8113a826: swiotlb_tbl_map_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device *dev, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:505
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
**Symbols:**

```
ffffffff81bd557d-ffffffff81bd55f9: swiotlb_tbl_map_single.cold (STB_LOCAL)
ffffffff8113ba00-ffffffff8113bb83: swiotlb_tbl_map_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device *dev, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:542
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
**Symbols:**

```
ffffffff81cb0603-ffffffff81cb06b6: swiotlb_tbl_map_single.cold (STB_LOCAL)
ffffffff8115eaf0-ffffffff8115ec4c: swiotlb_tbl_map_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device *dev, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, unsigned int alloc_align_mask, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:572
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
**Symbols:**

```
ffffffff81e61322-ffffffff81e613b6: swiotlb_tbl_map_single.cold (STB_LOCAL)
ffffffff81188c40-ffffffff81188dad: swiotlb_tbl_map_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device *dev, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, unsigned int alloc_align_mask, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:742
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
**Symbols:**

```
ffffffff8205aa02-ffffffff8205aa4b: swiotlb_tbl_map_single.cold (STB_LOCAL)
ffffffff811c4e80-ffffffff811c5111: swiotlb_tbl_map_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device *dev, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, unsigned int alloc_align_mask, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:765
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
**Symbols:**

```
ffffffff820d9269-ffffffff820d92b2: swiotlb_tbl_map_single.cold (STB_LOCAL)
ffffffff811d7be0-ffffffff811d7e4d: swiotlb_tbl_map_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device *dev, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, unsigned int alloc_align_mask, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:1289
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
**Symbols:**

```
ffffffff821b4af2-ffffffff821b4b28: swiotlb_tbl_map_single.cold (STB_LOCAL)
ffffffff811ed5d0-ffffffff811ed7fe: swiotlb_tbl_map_single (STB_GLOBAL)
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
phys_addr_t swiotlb_tbl_map_single(struct device *hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffff800010196868)
Location: kernel/dma/swiotlb.c:445
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
**Symbols:**

```
ffff800010196868-ffff800010196be8: swiotlb_tbl_map_single (STB_GLOBAL)
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
phys_addr_t swiotlb_tbl_map_single(struct device *hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (c0000000001f6bc0)
Location: kernel/dma/swiotlb.c:445
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_map
```
**Symbols:**

```
c0000000001f6bc0-c0000000001f7114: swiotlb_tbl_map_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device *hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffe0001281b6)
Location: kernel/dma/swiotlb.c:445
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
**Symbols:**

```
ffffffe0001281b6-ffffffe0001284d4: swiotlb_tbl_map_single (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device *hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:445
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/iommu/intel-iommu.c:bounce_map_single
```
**Symbols:**

```
ffffffff81128f74-ffffffff81128ff0: swiotlb_tbl_map_single.cold (STB_LOCAL)
ffffffff81128830-ffffffff81128b13: swiotlb_tbl_map_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device *hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:445
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/iommu/intel-iommu.c:bounce_map_single
```
**Symbols:**

```
ffffffff8111b804-ffffffff8111b880: swiotlb_tbl_map_single.cold (STB_LOCAL)
ffffffff8111b0c0-ffffffff8111b3a3: swiotlb_tbl_map_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device *hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:445
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/iommu/intel-iommu.c:bounce_map_single
```
**Symbols:**

```
ffffffff81126c94-ffffffff81126d10: swiotlb_tbl_map_single.cold (STB_LOCAL)
ffffffff81126550-ffffffff81126833: swiotlb_tbl_map_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
phys_addr_t swiotlb_tbl_map_single(struct device *hwdev, dma_addr_t tbl_dma_addr, phys_addr_t orig_addr, size_t mapping_size, size_t alloc_size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:445
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/iommu/intel-iommu.c:bounce_map_single
```
**Symbols:**

```
ffffffff811332e4-ffffffff81133360: swiotlb_tbl_map_single.cold (STB_LOCAL)
ffffffff81132b90-ffffffff81132e73: swiotlb_tbl_map_single (STB_GLOBAL)
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
<code>hwdev, tbl_dma_addr, orig_addr, size, dir, attrs</code> ➡️ <code>hwdev, tbl_dma_addr, orig_addr, mapping_size, alloc_size, dir, attrs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>dma_addr_t tbl_dma_addr</code>
</li>
<li>
<b>Param reordered. </b>
<code>hwdev, tbl_dma_addr, orig_addr, mapping_size, alloc_size, dir, attrs</code> ➡️ <code>hwdev, orig_addr, mapping_size, alloc_size, dir, attrs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int alloc_align_mask</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, orig_addr, mapping_size, alloc_size, dir, attrs</code> ➡️ <code>dev, orig_addr, mapping_size, alloc_size, alloc_align_mask, dir, attrs</code>
</li>
</ul>
</details>
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
