# Function: <code>iommu_tlb_sync</code>

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
In drivers/iommu/iommu.c (ffffffff816d9a37)
Location: include/linux/iommu.h:505
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d3a65)
Location: include/linux/iommu.h:505
Inline: True
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
In drivers/iommu/iommu.c (ffffffff8178e9c7)
Location: include/linux/iommu.h:545
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/iommu/dma-iommu.c (ffffffff81791a68)
Location: include/linux/iommu.h:545
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189e845)
Location: include/linux/iommu.h:545
Inline: True
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
In drivers/iommu/iommu.c (ffff8000108c5918)
Location: include/linux/iommu.h:505
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/iommu/dma-iommu.c (ffff8000108c8e48)
Location: include/linux/iommu.h:505
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d34c8)
Location: include/linux/iommu.h:505
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
In drivers/iommu/iommu.c (c09bc6e8)
Location: include/linux/iommu.h:505
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
In drivers/iommu/iommu.c (c00000000096b490)
Location: include/linux/iommu.h:505
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
In drivers/iommu/iommu.c (ffffffff8169f487)
Location: include/linux/iommu.h:505
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
In drivers/iommu/iommu.c (ffffffff8167ce77)
Location: include/linux/iommu.h:505
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177db15)
Location: include/linux/iommu.h:505
Inline: True
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
In drivers/iommu/iommu.c (ffffffff816cd6f7)
Location: include/linux/iommu.h:505
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c88e5)
Location: include/linux/iommu.h:505
Inline: True
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
In drivers/iommu/iommu.c (ffffffff816e7c27)
Location: include/linux/iommu.h:505
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e2b85)
Location: include/linux/iommu.h:505
Inline: True
```
</details>
</li>
</ul>

## Differences
