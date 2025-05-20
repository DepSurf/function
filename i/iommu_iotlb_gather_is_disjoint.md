# Function: <code>iommu_iotlb_gather_is_disjoint</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8180d3a1)
Location: include/linux/iommu.h:538
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_unmap
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181a920)
Location: include/linux/iommu.h:538
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
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
In drivers/iommu/amd/iommu.c (ffffffff8194db40)
Location: include/linux/iommu.h:530
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_unmap
```
```
In drivers/iommu/intel/iommu.c (ffffffff8195b047)
Location: include/linux/iommu.h:530
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
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
In drivers/iommu/amd/iommu.c (ffffffff81ab235d)
Location: include/linux/iommu.h:568
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_unmap_pages
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac2c4e)
Location: include/linux/iommu.h:568
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
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
In drivers/iommu/amd/iommu.c (ffffffff81afe40d)
Location: include/linux/iommu.h:571
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_unmap_pages
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0faf0)
Location: include/linux/iommu.h:571
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
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
In drivers/iommu/amd/iommu.c (ffffffff81b51a7d)
Location: include/linux/iommu.h:772
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_unmap_pages
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b643e0)
Location: include/linux/iommu.h:772
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
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
