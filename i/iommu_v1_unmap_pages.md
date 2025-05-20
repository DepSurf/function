# Function: <code>iommu_v1_unmap_pages</code>

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
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long unsigned int iommu_v1_unmap_pages(struct io_pgtable_ops *ops, long unsigned int iova, size_t pgsize, size_t pgcount, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (0)
Location: drivers/iommu/amd/io_pgtable.c:438
Inline: False
```
**Symbols:**

```
ffffffff81aba390-ffffffff81aba4d3: iommu_v1_unmap_pages (STB_LOCAL)
ffffffff820971e5-ffffffff82097204: iommu_v1_unmap_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long unsigned int iommu_v1_unmap_pages(struct io_pgtable_ops *ops, long unsigned int iova, size_t pgsize, size_t pgcount, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (0)
Location: drivers/iommu/amd/io_pgtable.c:438
Inline: False
```
**Symbols:**

```
ffffffff81b06950-ffffffff81b06a84: iommu_v1_unmap_pages (STB_LOCAL)
ffffffff82118180-ffffffff8211819f: iommu_v1_unmap_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long unsigned int iommu_v1_unmap_pages(struct io_pgtable_ops *ops, long unsigned int iova, size_t pgsize, size_t pgcount, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable.c (0)
Location: drivers/iommu/amd/io_pgtable.c:439
Inline: False
```
**Symbols:**

```
ffffffff81b5a770-ffffffff81b5a8a4: iommu_v1_unmap_pages (STB_LOCAL)
ffffffff821f5e4d-ffffffff821f5e6c: iommu_v1_unmap_pages.cold (STB_LOCAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
