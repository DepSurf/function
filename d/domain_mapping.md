# Function: <code>domain_mapping</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, struct scatterlist *sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816720c0)
Location: drivers/iommu/intel-iommu.c:2370
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_map
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff816720c0-ffffffff816721ad: domain_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, struct scatterlist *sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81691ca0)
Location: drivers/iommu/intel-iommu.c:2339
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_map
  - drivers/iommu/intel-iommu.c:__intel_map_page
```
**Symbols:**

```
ffffffff81691ca0-ffffffff81691d8d: domain_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, struct scatterlist *sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c9ab0)
Location: drivers/iommu/intel-iommu.c:2327
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_map
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff816c9ab0-ffffffff816c9b43: domain_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, struct scatterlist *sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ec560)
Location: drivers/iommu/intel-iommu.c:2338
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_map
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff816ec560-ffffffff816ec5f3: domain_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, struct scatterlist *sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a4650)
Location: drivers/iommu/intel/iommu.c:2357
Inline: True
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_map
  - drivers/iommu/intel/iommu.c:bounce_map_single
  - drivers/iommu/intel/iommu.c:intel_map_sg
  - drivers/iommu/intel/iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff817a4650-ffffffff817a46ee: domain_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817b1b6a)
Location: drivers/iommu/intel/iommu.c:2400
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_map
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, struct scatterlist *sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b1e90)
Location: drivers/iommu/intel-iommu.c:2338
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_map
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff816b1e90-ffffffff816b1f23: domain_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, struct scatterlist *sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168f990)
Location: drivers/iommu/intel-iommu.c:2338
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_map
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff8168f990-ffffffff8168fa23: domain_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, struct scatterlist *sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e0220)
Location: drivers/iommu/intel-iommu.c:2338
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_map
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff816e0220-ffffffff816e02b3: domain_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int domain_mapping(struct dmar_domain *domain, long unsigned int iov_pfn, struct scatterlist *sg, long unsigned int phys_pfn, long unsigned int nr_pages, int prot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816fa830)
Location: drivers/iommu/intel-iommu.c:2338
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_map
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff816fa830-ffffffff816fa8c3: domain_mapping (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
