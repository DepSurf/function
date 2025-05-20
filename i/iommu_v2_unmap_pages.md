# Function: <code>iommu_v2_unmap_pages</code>

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
long unsigned int iommu_v2_unmap_pages(struct io_pgtable_ops *ops, long unsigned int iova, size_t pgsize, size_t pgcount, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable_v2.c (0)
Location: drivers/iommu/amd/io_pgtable_v2.c:293
Inline: False
```
**Symbols:**

```
ffffffff81abb6a0-ffffffff81abb773: iommu_v2_unmap_pages (STB_LOCAL)
ffffffff82097301-ffffffff82097320: iommu_v2_unmap_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long unsigned int iommu_v2_unmap_pages(struct io_pgtable_ops *ops, long unsigned int iova, size_t pgsize, size_t pgcount, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable_v2.c (0)
Location: drivers/iommu/amd/io_pgtable_v2.c:288
Inline: False
```
**Symbols:**

```
ffffffff81b079d0-ffffffff81b07aa2: iommu_v2_unmap_pages (STB_LOCAL)
ffffffff8211829c-ffffffff821182bb: iommu_v2_unmap_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long unsigned int iommu_v2_unmap_pages(struct io_pgtable_ops *ops, long unsigned int iova, size_t pgsize, size_t pgcount, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/io_pgtable_v2.c (0)
Location: drivers/iommu/amd/io_pgtable_v2.c:282
Inline: False
```
**Symbols:**

```
ffffffff81b5ba00-ffffffff81b5bad2: iommu_v2_unmap_pages (STB_LOCAL)
ffffffff821f5fa9-ffffffff821f5fc8: iommu_v2_unmap_pages.cold (STB_LOCAL)
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
