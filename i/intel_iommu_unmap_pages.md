# Function: <code>intel_iommu_unmap_pages</code>

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
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
size_t intel_iommu_unmap_pages(struct iommu_domain *domain, long unsigned int iova, size_t pgsize, size_t pgcount, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:5117
Inline: False
```
**Symbols:**

```
ffffffff8181a9d0-ffffffff8181aa19: intel_iommu_unmap_pages (STB_LOCAL)
ffffffff81cff95a-ffffffff81cff981: intel_iommu_unmap_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t intel_iommu_unmap_pages(struct iommu_domain *domain, long unsigned int iova, size_t pgsize, size_t pgcount, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4466
Inline: False
```
**Symbols:**

```
ffffffff8195b110-ffffffff8195b168: intel_iommu_unmap_pages (STB_LOCAL)
ffffffff81ec8098-ffffffff81ec80bf: intel_iommu_unmap_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t intel_iommu_unmap_pages(struct iommu_domain *domain, long unsigned int iova, size_t pgsize, size_t pgcount, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4375
Inline: False
```
**Symbols:**

```
ffffffff81ac2cf0-ffffffff81ac2d48: intel_iommu_unmap_pages (STB_LOCAL)
ffffffff8209792e-ffffffff82097955: intel_iommu_unmap_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t intel_iommu_unmap_pages(struct iommu_domain *domain, long unsigned int iova, size_t pgsize, size_t pgcount, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4266
Inline: False
```
**Symbols:**

```
ffffffff81b0fb90-ffffffff81b0fbe8: intel_iommu_unmap_pages (STB_LOCAL)
ffffffff82118889-ffffffff821188b0: intel_iommu_unmap_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t intel_iommu_unmap_pages(struct iommu_domain *domain, long unsigned int iova, size_t pgsize, size_t pgcount, struct iommu_iotlb_gather *gather);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4158
Inline: False
```
**Symbols:**

```
ffffffff81b64480-ffffffff81b644d8: intel_iommu_unmap_pages (STB_LOCAL)
ffffffff821f6597-ffffffff821f65be: intel_iommu_unmap_pages.cold (STB_LOCAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
