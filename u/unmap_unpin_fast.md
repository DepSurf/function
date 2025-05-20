# Function: <code>unmap_unpin_fast</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d3c71)
Location: drivers/vfio/vfio_iommu_type1.c:694
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t unmap_unpin_fast(struct vfio_domain *domain, struct vfio_dma *dma, dma_addr_t *iova, size_t len, phys_addr_t phys, long int *unlocked, struct list_head *unmapped_list, int *unmapped_cnt, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189e910)
Location: drivers/vfio/vfio_iommu_type1.c:803
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff8189e910-ffffffff8189ea07: unmap_unpin_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t unmap_unpin_fast(struct vfio_domain *domain, struct vfio_dma *dma, dma_addr_t *iova, size_t len, phys_addr_t phys, long int *unlocked, struct list_head *unmapped_list, int *unmapped_cnt, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ada50)
Location: drivers/vfio/vfio_iommu_type1.c:827
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff818ada50-ffffffff818adb47: unmap_unpin_fast (STB_LOCAL)
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
In drivers/vfio/vfio_iommu_type1.c (ffffffff81890bef)
Location: drivers/vfio/vfio_iommu_type1.c:1021
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
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
In drivers/vfio/vfio_iommu_type1.c (ffffffff819246e4)
Location: drivers/vfio/vfio_iommu_type1.c:1022
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
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
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7a018)
Location: drivers/vfio/vfio_iommu_type1.c:1020
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
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
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177dd21)
Location: drivers/vfio/vfio_iommu_type1.c:694
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c8af1)
Location: drivers/vfio/vfio_iommu_type1.c:694
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e2d8c)
Location: drivers/vfio/vfio_iommu_type1.c:694
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
