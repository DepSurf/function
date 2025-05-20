# Function: <code>intel_iommu_map_pages</code>

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
int intel_iommu_map_pages(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t pgsize, size_t pgcount, int prot, gfp_t gfp, size_t *mapped);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:5066
Inline: False
```
**Symbols:**

```
ffffffff8181af30-ffffffff8181b04b: intel_iommu_map_pages (STB_LOCAL)
ffffffff81cffb1d-ffffffff81cffba6: intel_iommu_map_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int intel_iommu_map_pages(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t pgsize, size_t pgcount, int prot, gfp_t gfp, size_t *mapped);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4416
Inline: False
```
**Symbols:**

```
ffffffff8195b610-ffffffff8195b733: intel_iommu_map_pages (STB_LOCAL)
ffffffff81ec8184-ffffffff81ec820d: intel_iommu_map_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int intel_iommu_map_pages(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t pgsize, size_t pgcount, int prot, gfp_t gfp, size_t *mapped);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4320
Inline: False
```
**Symbols:**

```
ffffffff81ac33a0-ffffffff81ac34d2: intel_iommu_map_pages (STB_LOCAL)
ffffffff820979e2-ffffffff82097a48: intel_iommu_map_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int intel_iommu_map_pages(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t pgsize, size_t pgcount, int prot, gfp_t gfp, size_t *mapped);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4209
Inline: False
```
**Symbols:**

```
ffffffff81b10130-ffffffff81b10265: intel_iommu_map_pages (STB_LOCAL)
ffffffff8211894b-ffffffff8211899e: intel_iommu_map_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int intel_iommu_map_pages(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t pgsize, size_t pgcount, int prot, gfp_t gfp, size_t *mapped);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4101
Inline: False
```
**Symbols:**

```
ffffffff81b64bd0-ffffffff81b64d05: intel_iommu_map_pages (STB_LOCAL)
ffffffff821f667f-ffffffff821f66d2: intel_iommu_map_pages.cold (STB_LOCAL)
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
