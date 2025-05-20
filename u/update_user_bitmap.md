# Function: <code>update_user_bitmap</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int update_user_bitmap(u64 *bitmap, struct vfio_iommu *iommu, struct vfio_dma *dma, dma_addr_t base_iova, size_t pgsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189f570)
Location: drivers/vfio/vfio_iommu_type1.c:978
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
```
**Symbols:**

```
ffffffff8189f570-ffffffff8189f6cb: update_user_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int update_user_bitmap(u64 *bitmap, struct vfio_iommu *iommu, struct vfio_dma *dma, dma_addr_t base_iova, size_t pgsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ae5e0)
Location: drivers/vfio/vfio_iommu_type1.c:1003
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
```
**Symbols:**

```
ffffffff818ae5e0-ffffffff818ae727: update_user_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int update_user_bitmap(u64 *bitmap, struct vfio_iommu *iommu, struct vfio_dma *dma, dma_addr_t base_iova, size_t pgsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818928f0)
Location: drivers/vfio/vfio_iommu_type1.c:1201
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
```
**Symbols:**

```
ffffffff818928f0-ffffffff81892a45: update_user_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int update_user_bitmap(u64 *bitmap, struct vfio_iommu *iommu, struct vfio_dma *dma, dma_addr_t base_iova, size_t pgsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: drivers/vfio/vfio_iommu_type1.c:1202
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
```
**Symbols:**

```
ffffffff81923760-ffffffff819238ef: update_user_bitmap (STB_LOCAL)
ffffffff81d1183d-ffffffff81d118ab: update_user_bitmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int update_user_bitmap(u64 *bitmap, struct vfio_iommu *iommu, struct vfio_dma *dma, dma_addr_t base_iova, size_t pgsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: drivers/vfio/vfio_iommu_type1.c:1200
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
```
**Symbols:**

```
ffffffff81a79120-ffffffff81a792bc: update_user_bitmap (STB_LOCAL)
ffffffff81edc4bb-ffffffff81edc529: update_user_bitmap.cold (STB_LOCAL)
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
<b>Regular</b>
<ul>
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
</ul>
