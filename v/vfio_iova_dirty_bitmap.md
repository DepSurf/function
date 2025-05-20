# Function: <code>vfio_iova_dirty_bitmap</code>

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
int vfio_iova_dirty_bitmap(u64 *bitmap, struct vfio_iommu *iommu, dma_addr_t iova, size_t size, size_t pgsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189f6d0)
Location: drivers/vfio/vfio_iommu_type1.c:1015
Inline: False
```
**Symbols:**

```
ffffffff8189f6d0-ffffffff8189f852: vfio_iova_dirty_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_iova_dirty_bitmap(u64 *bitmap, struct vfio_iommu *iommu, dma_addr_t iova, size_t size, size_t pgsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ae730)
Location: drivers/vfio/vfio_iommu_type1.c:1040
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
```
**Symbols:**

```
ffffffff818ae730-ffffffff818ae8b2: vfio_iova_dirty_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_iova_dirty_bitmap(u64 *bitmap, struct vfio_iommu *iommu, dma_addr_t iova, size_t size, size_t pgsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81892a50)
Location: drivers/vfio/vfio_iommu_type1.c:1238
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
```
**Symbols:**

```
ffffffff81892a50-ffffffff81892bd1: vfio_iova_dirty_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfio_iova_dirty_bitmap(u64 *bitmap, struct vfio_iommu *iommu, dma_addr_t iova, size_t size, size_t pgsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: drivers/vfio/vfio_iommu_type1.c:1239
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
```
**Symbols:**

```
ffffffff819254a0-ffffffff819255eb: vfio_iova_dirty_bitmap (STB_LOCAL)
ffffffff81d11a41-ffffffff81d11a61: vfio_iova_dirty_bitmap.cold (STB_LOCAL)
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
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7e141)
Location: drivers/vfio/vfio_iommu_type1.c:1237
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
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
</ul>
