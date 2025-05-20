# Function: <code>qcom_iommu_tlb_inv_range_nosync</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
void qcom_iommu_tlb_inv_range_nosync(long unsigned int iova, size_t size, size_t granule, bool leaf, void *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/qcom_iommu.c (ffff8000108d9d80)
Location: drivers/iommu/qcom_iommu.c:147
Inline: False
Direct callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_add_page
  - drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_flush_leaf
  - drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_flush_walk
```
**Symbols:**

```
ffff8000108d9d80-ffff8000108d9e60: qcom_iommu_tlb_inv_range_nosync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void qcom_iommu_tlb_inv_range_nosync(long unsigned int iova, size_t size, size_t granule, bool leaf, void *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/qcom_iommu.c (c09cb1e4)
Location: drivers/iommu/qcom_iommu.c:147
Inline: False
Direct callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_add_page
  - drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_flush_leaf
  - drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_flush_walk
```
**Symbols:**

```
c09cb1e4-c09cb28c: qcom_iommu_tlb_inv_range_nosync (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
