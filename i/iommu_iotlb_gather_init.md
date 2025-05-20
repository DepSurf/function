# Function: <code>iommu_iotlb_gather_init</code>

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
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816d9a17)
Location: include/linux/iommu.h:396
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d3be4)
Location: include/linux/iommu.h:396
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
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
In drivers/iommu/iommu.c (ffffffff8178e9a7)
Location: include/linux/iommu.h:408
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/iommu/dma-iommu.c (ffffffff81791a22)
Location: include/linux/iommu.h:408
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189eae0)
Location: include/linux/iommu.h:408
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
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
In drivers/iommu/intel/iommu.c (ffffffff817afb72)
Location: include/linux/iommu.h:404
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
```
```
In drivers/iommu/iommu.c (ffffffff817babd7)
Location: include/linux/iommu.h:404
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/iommu/dma-iommu.c (ffffffff817bdc1a)
Location: include/linux/iommu.h:404
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818adc29)
Location: include/linux/iommu.h:404
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
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
In drivers/iommu/intel/iommu.c (ffffffff81792b66)
Location: include/linux/iommu.h:371
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
```
```
In drivers/iommu/iommu.c (ffffffff8179d4e7)
Location: include/linux/iommu.h:371
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/iommu/dma-iommu.c (ffffffff817a0e59)
Location: include/linux/iommu.h:371
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81890b5a)
Location: include/linux/iommu.h:371
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
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
In drivers/iommu/amd/iommu.c (ffffffff8180d3d4)
Location: include/linux/iommu.h:398
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_unmap
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181a94d)
Location: include/linux/iommu.h:398
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
```
```
In drivers/iommu/iommu.c (ffffffff81826227)
Location: include/linux/iommu.h:398
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/iommu/dma-iommu.c (ffffffff8182a9b2)
Location: include/linux/iommu.h:398
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8192464a)
Location: include/linux/iommu.h:398
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
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
In drivers/iommu/amd/iommu.c (ffffffff8194db6a)
Location: include/linux/iommu.h:396
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_unmap
```
```
In drivers/iommu/intel/iommu.c (ffffffff8195b07c)
Location: include/linux/iommu.h:396
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
```
```
In drivers/iommu/iommu.c (ffffffff81966506)
Location: include/linux/iommu.h:396
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196b0e5)
Location: include/linux/iommu.h:396
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a79f5d)
Location: include/linux/iommu.h:396
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
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
In drivers/iommu/amd/iommu.c (ffffffff81ab2388)
Location: include/linux/iommu.h:438
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_unmap_pages
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac2c79)
Location: include/linux/iommu.h:438
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
```
```
In drivers/iommu/iommu.c (ffffffff81acfec6)
Location: include/linux/iommu.h:438
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad55d5)
Location: include/linux/iommu.h:438
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
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
In drivers/iommu/amd/iommu.c (ffffffff81afe438)
Location: include/linux/iommu.h:445
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_unmap_pages
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0fb19)
Location: include/linux/iommu.h:445
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
```
```
In drivers/iommu/iommu.c (ffffffff81b1f176)
Location: include/linux/iommu.h:445
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b23d85)
Location: include/linux/iommu.h:445
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
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
In drivers/iommu/amd/iommu.c (ffffffff81b51aa8)
Location: include/linux/iommu.h:657
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_unmap_pages
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b64409)
Location: include/linux/iommu.h:657
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
```
```
In drivers/iommu/iommu.c (ffffffff81b755b6)
Location: include/linux/iommu.h:657
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7a945)
Location: include/linux/iommu.h:657
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
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
In drivers/iommu/iommu.c (ffff8000108c58f8)
Location: include/linux/iommu.h:396
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/iommu/dma-iommu.c (ffff8000108c8df8)
Location: include/linux/iommu.h:396
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d34e0)
Location: include/linux/iommu.h:396
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_tlb_inv_page_nosync
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
In drivers/iommu/iommu.c (c09bc6c0)
Location: include/linux/iommu.h:396
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096b478)
Location: include/linux/iommu.h:396
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8169f467)
Location: include/linux/iommu.h:396
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
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
In drivers/iommu/iommu.c (ffffffff8167ce57)
Location: include/linux/iommu.h:396
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177dc94)
Location: include/linux/iommu.h:396
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
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
In drivers/iommu/iommu.c (ffffffff816cd6d7)
Location: include/linux/iommu.h:396
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c8a64)
Location: include/linux/iommu.h:396
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
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
In drivers/iommu/iommu.c (ffffffff816e7c07)
Location: include/linux/iommu.h:396
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e2cff)
Location: include/linux/iommu.h:396
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
</details>
</li>
</ul>

## Differences
