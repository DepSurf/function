# Function: <code>__phys_to_dma</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8110d045)
Location: include/linux/dma-direct.h:11
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
```
```
In kernel/dma/swiotlb.c (ffffffff8110e441)
Location: include/linux/dma-direct.h:11
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_alloc
  - kernel/dma/swiotlb.c:swiotlb_alloc
  - kernel/dma/swiotlb.c:swiotlb_dma_supported
  - kernel/dma/swiotlb.c:swiotlb_dma_mapping_error
  - kernel/dma/swiotlb.c:swiotlb_map_page
  - kernel/dma/swiotlb.c:swiotlb_map_page
  - kernel/dma/swiotlb.c:swiotlb_map_page
  - kernel/dma/swiotlb.c:swiotlb_map_page
  - kernel/dma/swiotlb.c:map_single
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
In kernel/dma/direct.c (ffffffff81118da5)
Location: include/linux/dma-direct.h:11
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_supported
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
```
In kernel/dma/swiotlb.c (ffffffff81119d25)
Location: include/linux/dma-direct.h:11
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_dma_supported
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_map
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
In kernel/dma/direct.c (ffffffff81123295)
Location: include/linux/dma-direct.h:11
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_supported
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
```
In kernel/dma/swiotlb.c (ffffffff811245cf)
Location: include/linux/dma-direct.h:11
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_map
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
In kernel/dma/direct.c (ffffffff8112f6d5)
Location: include/linux/dma-direct.h:14
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_supported
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
```
In kernel/dma/swiotlb.c (ffffffff8113054f)
Location: include/linux/dma-direct.h:14
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/iommu/intel-iommu.c (ffffffff816edf5b)
Location: include/linux/dma-direct.h:14
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_map_single
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
In kernel/dma/direct.c (ffffffff8113e485)
Location: include/linux/dma-direct.h:14
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_supported
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_coherent_ok
  - kernel/dma/direct.c:dma_coherent_ok
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
```
In kernel/dma/swiotlb.c (ffffffff8113f331)
Location: include/linux/dma-direct.h:14
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a5bec)
Location: include/linux/dma-direct.h:14
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:bounce_map_single
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffff800010195224)
Location: include/linux/dma-direct.h:14
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_supported
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
```
In kernel/dma/swiotlb.c (ffff800010196eac)
Location: include/linux/dma-direct.h:14
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In kernel/dma/remap.c (ffff800010197620)
Location: include/linux/dma-direct.h:14
Inline: True
Inline callers:
  - kernel/dma/remap.c:arch_dma_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c03e1eb8)
Location: arch/arm/include/asm/dma-direct.h:5
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_supported
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c0000000001f553c)
Location: arch/powerpc/include/asm/dma-direct.h:14
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_supported
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
```
In kernel/dma/swiotlb.c (c0000000001f7418)
Location: arch/powerpc/include/asm/dma-direct.h:14
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_map
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffe000126f38)
Location: include/linux/dma-direct.h:14
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_supported
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
```
In kernel/dma/swiotlb.c (ffffffe000128758)
Location: include/linux/dma-direct.h:14
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_map
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
In kernel/dma/direct.c (ffffffff81127d15)
Location: include/linux/dma-direct.h:14
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_supported
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_coherent_ok
  - kernel/dma/direct.c:dma_coherent_ok
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
```
In kernel/dma/swiotlb.c (ffffffff81128cff)
Location: include/linux/dma-direct.h:14
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/iommu/intel-iommu.c (ffffffff816b36cb)
Location: include/linux/dma-direct.h:14
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_map_single
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
In kernel/dma/direct.c (ffffffff8111a715)
Location: include/linux/dma-direct.h:14
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_supported
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
```
In kernel/dma/swiotlb.c (ffffffff8111b58f)
Location: include/linux/dma-direct.h:14
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/iommu/intel-iommu.c (ffffffff8169138b)
Location: include/linux/dma-direct.h:14
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_map_single
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
In kernel/dma/direct.c (ffffffff81125ba5)
Location: include/linux/dma-direct.h:14
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_supported
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
```
In kernel/dma/swiotlb.c (ffffffff81126a1f)
Location: include/linux/dma-direct.h:14
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e1c1b)
Location: include/linux/dma-direct.h:14
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_map_single
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
In kernel/dma/direct.c (ffffffff811321e5)
Location: include/linux/dma-direct.h:14
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_supported
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
```
In kernel/dma/swiotlb.c (ffffffff8113305f)
Location: include/linux/dma-direct.h:14
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/iommu/intel-iommu.c (ffffffff816fc235)
Location: include/linux/dma-direct.h:14
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_map_single
```
</details>
</li>
</ul>

## Differences
