# Function: <code>intel_alloc_iova</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct iova *intel_alloc_iova(struct device *dev, struct dmar_domain *domain, long unsigned int nrpages, uint64_t dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815369b0)
Location: drivers/iommu/intel-iommu.c:3302
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff815369b0-ffffffff81536a8e: intel_alloc_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int intel_alloc_iova(struct device *dev, struct dmar_domain *domain, long unsigned int nrpages, uint64_t dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158aca0)
Location: drivers/iommu/intel-iommu.c:3363
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff8158aca0-ffffffff8158ad78: intel_alloc_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int intel_alloc_iova(struct device *dev, struct dmar_domain *domain, long unsigned int nrpages, uint64_t dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815b8300)
Location: drivers/iommu/intel-iommu.c:3441
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff815b8300-ffffffff815b83d8: intel_alloc_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int intel_alloc_iova(struct device *dev, struct dmar_domain *domain, long unsigned int nrpages, uint64_t dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815ce1a0)
Location: drivers/iommu/intel-iommu.c:3449
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff815ce1a0-ffffffff815ce27d: intel_alloc_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int intel_alloc_iova(struct device *dev, struct dmar_domain *domain, long unsigned int nrpages, uint64_t dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81634fe0)
Location: drivers/iommu/intel-iommu.c:3456
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff81634fe0-ffffffff816350c4: intel_alloc_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
long unsigned int intel_alloc_iova(struct device *dev, struct dmar_domain *domain, long unsigned int nrpages, uint64_t dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:3512
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff816705f0-ffffffff816706ab: intel_alloc_iova (STB_LOCAL)
ffffffff8167542c-ffffffff81675451: intel_alloc_iova.cold.85 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
long unsigned int intel_alloc_iova(struct device *dev, struct dmar_domain *domain, long unsigned int nrpages, uint64_t dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:3528
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__intel_map_page
```
**Symbols:**

```
ffffffff8168ed70-ffffffff8168ee2b: intel_alloc_iova (STB_LOCAL)
ffffffff816938a3-ffffffff816938c8: intel_alloc_iova.cold.88 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long unsigned int intel_alloc_iova(struct device *dev, struct dmar_domain *domain, long unsigned int nrpages, uint64_t dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:3368
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff816c62a0-ffffffff816c6356: intel_alloc_iova (STB_LOCAL)
ffffffff816cbd72-ffffffff816cbd91: intel_alloc_iova.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
long unsigned int intel_alloc_iova(struct device *dev, struct dmar_domain *domain, long unsigned int nrpages, uint64_t dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:3379
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff816e87f0-ffffffff816e88b0: intel_alloc_iova (STB_LOCAL)
ffffffff816ef5e5-ffffffff816ef60b: intel_alloc_iova.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
long unsigned int intel_alloc_iova(struct device *dev, struct dmar_domain *domain, long unsigned int nrpages, uint64_t dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:3340
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:bounce_map_single
  - drivers/iommu/intel/iommu.c:intel_map_sg
  - drivers/iommu/intel/iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff8179f6f0-ffffffff8179f7c2: intel_alloc_iova (STB_LOCAL)
ffffffff817a69cf-ffffffff817a69f5: intel_alloc_iova.cold (STB_LOCAL)
```
</details>
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
long unsigned int intel_alloc_iova(struct device *dev, struct dmar_domain *domain, long unsigned int nrpages, uint64_t dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:3379
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff816ae2d0-ffffffff816ae390: intel_alloc_iova (STB_LOCAL)
ffffffff816b4dd5-ffffffff816b4dfb: intel_alloc_iova.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
long unsigned int intel_alloc_iova(struct device *dev, struct dmar_domain *domain, long unsigned int nrpages, uint64_t dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:3379
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff8168bc30-ffffffff8168bcf0: intel_alloc_iova (STB_LOCAL)
ffffffff81692a15-ffffffff81692a3b: intel_alloc_iova.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
long unsigned int intel_alloc_iova(struct device *dev, struct dmar_domain *domain, long unsigned int nrpages, uint64_t dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:3379
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff816dc4b0-ffffffff816dc570: intel_alloc_iova (STB_LOCAL)
ffffffff816e32a5-ffffffff816e32cb: intel_alloc_iova.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
long unsigned int intel_alloc_iova(struct device *dev, struct dmar_domain *domain, long unsigned int nrpages, uint64_t dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:3379
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff816f6af0-ffffffff816f6bb0: intel_alloc_iova (STB_LOCAL)
ffffffff816fd935-ffffffff816fd95b: intel_alloc_iova.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct iova *</code> ➡️ <code>long unsigned int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
