# Function: <code>dma_get_seg_boundary</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066583)
Location: include/linux/dma-mapping.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff810674fd)
Location: include/linux/dma-mapping.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
```
```
In lib/swiotlb.c (ffffffff81411f19)
Location: include/linux/dma-mapping.h:164
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_tbl_map_single
```
```
In lib/iommu-common.c (ffffffff8141351c)
Location: include/linux/dma-mapping.h:164
Inline: True
Inline callers:
  - lib/iommu-common.c:iommu_tbl_range_alloc
```
```
In drivers/iommu/amd_iommu.c (ffffffff8152e0a1)
Location: include/linux/dma-mapping.h:164
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:dma_ops_area_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066313)
Location: include/linux/dma-mapping.h:585
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106727d)
Location: include/linux/dma-mapping.h:585
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
```
```
In lib/swiotlb.c (ffffffff81459c89)
Location: include/linux/dma-mapping.h:585
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_tbl_map_single
```
```
In lib/iommu-common.c (ffffffff8145b244)
Location: include/linux/dma-mapping.h:585
Inline: True
Inline callers:
  - lib/iommu-common.c:iommu_tbl_range_alloc
```
```
In drivers/iommu/amd_iommu.c (ffffffff81581bf0)
Location: include/linux/dma-mapping.h:585
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:sg_num_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81069fa3)
Location: include/linux/dma-mapping.h:637
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106aecd)
Location: include/linux/dma-mapping.h:637
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
```
```
In lib/swiotlb.c (ffffffff8147865d)
Location: include/linux/dma-mapping.h:637
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_tbl_map_single
```
```
In lib/iommu-common.c (ffffffff81479d34)
Location: include/linux/dma-mapping.h:637
Inline: True
Inline callers:
  - lib/iommu-common.c:iommu_tbl_range_alloc
```
```
In drivers/iommu/amd_iommu.c (ffffffff815ae560)
Location: include/linux/dma-mapping.h:637
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:sg_num_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106930a)
Location: include/linux/dma-mapping.h:668
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106a331)
Location: include/linux/dma-mapping.h:668
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
```
```
In lib/swiotlb.c (ffffffff81481bbd)
Location: include/linux/dma-mapping.h:668
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_tbl_map_single
```
```
In lib/iommu-common.c (ffffffff8148306e)
Location: include/linux/dma-mapping.h:668
Inline: True
Inline callers:
  - lib/iommu-common.c:iommu_tbl_range_alloc
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c4170)
Location: include/linux/dma-mapping.h:668
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:sg_num_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106dbba)
Location: include/linux/dma-mapping.h:676
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106ec41)
Location: include/linux/dma-mapping.h:676
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
```
```
In lib/swiotlb.c (ffffffff814bda37)
Location: include/linux/dma-mapping.h:676
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_tbl_map_single
```
```
In lib/iommu-common.c (ffffffff814bf0ae)
Location: include/linux/dma-mapping.h:676
Inline: True
Inline callers:
  - lib/iommu-common.c:iommu_tbl_range_alloc
```
```
In drivers/iommu/amd_iommu.c (ffffffff8162aec0)
Location: include/linux/dma-mapping.h:676
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:sg_num_pages
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
In arch/x86/kernel/amd_gart_64.c (ffffffff81070ab3)
Location: include/linux/dma-mapping.h:680
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81071b1d)
Location: include/linux/dma-mapping.h:680
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
```
```
In kernel/dma/swiotlb.c (ffffffff8110db93)
Location: include/linux/dma-mapping.h:680
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In drivers/iommu/amd_iommu.c (ffffffff81665ac0)
Location: include/linux/dma-mapping.h:680
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:sg_num_pages
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
In arch/x86/kernel/amd_gart_64.c (ffffffff81076aa3)
Location: include/linux/dma-mapping.h:705
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81077b3d)
Location: include/linux/dma-mapping.h:705
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
```
```
In kernel/dma/swiotlb.c (ffffffff811196e3)
Location: include/linux/dma-mapping.h:705
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In drivers/iommu/amd_iommu.c (ffffffff81684530)
Location: include/linux/dma-mapping.h:705
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:sg_num_pages
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8107a643)
Location: include/linux/dma-mapping.h:730
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107b6b2)
Location: include/linux/dma-mapping.h:730
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
```
```
In kernel/dma/swiotlb.c (ffffffff8112414c)
Location: include/linux/dma-mapping.h:730
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In drivers/iommu/amd_iommu.c (ffffffff816bba8d)
Location: include/linux/dma-mapping.h:730
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:sg_num_pages
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8107b733)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107c7a2)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
```
```
In kernel/dma/swiotlb.c (ffffffff811300e7)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In drivers/iommu/amd_iommu.c (ffffffff816de91d)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:sg_num_pages
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
In arch/x86/kernel/amd_gart_64.c (ffffffff81082de5)
Location: include/linux/dma-mapping.h:821
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff8113eea7)
Location: include/linux/dma-mapping.h:821
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In drivers/iommu/dma-iommu.c (ffffffff81792402)
Location: include/linux/dma-mapping.h:821
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
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
In arch/x86/kernel/amd_gart_64.c (ffffffff81084325)
Location: include/linux/dma-mapping.h:468
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
```
In kernel/dma/swiotlb.c (ffffffff8113a556)
Location: include/linux/dma-mapping.h:468
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In drivers/iommu/dma-iommu.c (ffffffff817bf2b4)
Location: include/linux/dma-mapping.h:468
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
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
In arch/x86/kernel/amd_gart_64.c (ffffffff81085085)
Location: include/linux/dma-mapping.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
```
In kernel/dma/swiotlb.c (ffffffff8113b246)
Location: include/linux/dma-mapping.h:510
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff817a20ad)
Location: include/linux/dma-mapping.h:510
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
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
In arch/x86/kernel/amd_gart_64.c (ffffffff81094535)
Location: include/linux/dma-mapping.h:490
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
```
In kernel/dma/swiotlb.c (ffffffff8115e330)
Location: include/linux/dma-mapping.h:490
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_find_slots
```
```
In drivers/iommu/dma-iommu.c (ffffffff8182b1a0)
Location: include/linux/dma-mapping.h:490
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
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
In arch/x86/kernel/amd_gart_64.c (ffffffff810a6795)
Location: include/linux/dma-mapping.h:490
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
```
In kernel/dma/swiotlb.c (ffffffff811884a3)
Location: include/linux/dma-mapping.h:490
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_find_slots
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196b875)
Location: include/linux/dma-mapping.h:490
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
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
In arch/x86/kernel/amd_gart_64.c (ffffffff810bf8a5)
Location: include/linux/dma-mapping.h:495
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
```
In kernel/dma/swiotlb.c (ffffffff811c4520)
Location: include/linux/dma-mapping.h:495
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_do_find_slots
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad5e73)
Location: include/linux/dma-mapping.h:495
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
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
In arch/x86/kernel/amd_gart_64.c (ffffffff810c2f85)
Location: include/linux/dma-mapping.h:496
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
```
In kernel/dma/swiotlb.c (ffffffff811d6f3a)
Location: include/linux/dma-mapping.h:496
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_do_find_slots
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b245f3)
Location: include/linux/dma-mapping.h:496
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
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
In arch/x86/kernel/amd_gart_64.c (ffffffff810cb3c5)
Location: include/linux/dma-mapping.h:489
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
```
In kernel/dma/swiotlb.c (ffffffff811ebf2c)
Location: include/linux/dma-mapping.h:489
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_search_pool_area
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7b263)
Location: include/linux/dma-mapping.h:489
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffff8000101968c4)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In drivers/iommu/dma-iommu.c (ffff8000108c9aec)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
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
In arch/powerpc/kernel/iommu.c (c00000000005146c)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - arch/powerpc/kernel/iommu.c:iommu_range_alloc
```
```
In kernel/dma/swiotlb.c (c0000000001f6c5c)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
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
In kernel/dma/swiotlb.c (ffffffe0001281fe)
Location: include/linux/dma-mapping.h:735
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8107a733)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107b7a2)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
```
```
In kernel/dma/swiotlb.c (ffffffff81128897)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a436d)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:sg_num_pages
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
In arch/x86/kernel/amd_gart_64.c (ffffffff81069e63)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106aed2)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
```
```
In kernel/dma/swiotlb.c (ffffffff8111b127)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In drivers/iommu/amd_iommu.c (ffffffff81681d5d)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:sg_num_pages
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8107a6e3)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107b752)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
```
```
In kernel/dma/swiotlb.c (ffffffff811265b7)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d25dd)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:sg_num_pages
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8107c7e3)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107d852)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
```
```
In kernel/dma/swiotlb.c (ffffffff81132bf7)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In drivers/iommu/amd_iommu.c (ffffffff816ecc1d)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:sg_num_pages
```
</details>
</li>
</ul>

## Differences
