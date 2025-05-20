# Function: <code>iommu_iotlb_sync</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817afb5a)
Location: include/linux/iommu.h:528
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
```
```
In drivers/iommu/iommu.c (ffffffff817babff)
Location: include/linux/iommu.h:528
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/iommu/dma-iommu.c (ffffffff817bdc66)
Location: include/linux/iommu.h:528
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ad992)
Location: include/linux/iommu.h:528
Inline: True
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
In drivers/iommu/intel/iommu.c (ffffffff81792b4e)
Location: include/linux/iommu.h:491
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
```
```
In drivers/iommu/iommu.c (ffffffff8179d50f)
Location: include/linux/iommu.h:491
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/iommu/dma-iommu.c (ffffffff817a0ea4)
Location: include/linux/iommu.h:491
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818909e2)
Location: include/linux/iommu.h:491
Inline: True
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
In drivers/iommu/amd/iommu.c (ffffffff8180d3b4)
Location: include/linux/iommu.h:517
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_unmap
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181a935)
Location: include/linux/iommu.h:517
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
```
```
In drivers/iommu/iommu.c (ffffffff81826257)
Location: include/linux/iommu.h:517
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/iommu/dma-iommu.c (ffffffff8182aa16)
Location: include/linux/iommu.h:517
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff819244c2)
Location: include/linux/iommu.h:517
Inline: True
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
In drivers/iommu/amd/iommu.c (ffffffff8194db52)
Location: include/linux/iommu.h:509
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_unmap
```
```
In drivers/iommu/intel/iommu.c (ffffffff8195b05c)
Location: include/linux/iommu.h:509
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
```
```
In drivers/iommu/iommu.c (ffffffff8196653a)
Location: include/linux/iommu.h:509
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196b160)
Location: include/linux/iommu.h:509
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a79dd4)
Location: include/linux/iommu.h:509
Inline: True
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
In drivers/iommu/amd/iommu.c (ffffffff81ab2370)
Location: include/linux/iommu.h:547
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_unmap_pages
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac2c61)
Location: include/linux/iommu.h:547
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
```
```
In drivers/iommu/iommu.c (ffffffff81acfefa)
Location: include/linux/iommu.h:547
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad5650)
Location: include/linux/iommu.h:547
Inline: True
Inline callers:
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
In drivers/iommu/amd/iommu.c (ffffffff81afe420)
Location: include/linux/iommu.h:550
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_unmap_pages
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0fb01)
Location: include/linux/iommu.h:550
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
```
```
In drivers/iommu/iommu.c (ffffffff81b1f1aa)
Location: include/linux/iommu.h:550
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b23e00)
Location: include/linux/iommu.h:550
Inline: True
Inline callers:
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
In drivers/iommu/amd/iommu.c (ffffffff81b51a90)
Location: include/linux/iommu.h:751
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_unmap_pages
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b643f1)
Location: include/linux/iommu.h:751
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
```
```
In drivers/iommu/iommu.c (ffffffff81b755ea)
Location: include/linux/iommu.h:751
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7a9c0)
Location: include/linux/iommu.h:751
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
</details>
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
