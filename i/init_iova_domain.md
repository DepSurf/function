# Function: <code>init_iova_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void init_iova_domain(struct iova_domain *iovad, long unsigned int granule, long unsigned int start_pfn, long unsigned int pfn_32bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8152d0b0)
Location: drivers/iommu/iova.c:25
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8152d0b0-ffffffff8152d0f0: init_iova_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void init_iova_domain(struct iova_domain *iovad, long unsigned int granule, long unsigned int start_pfn, long unsigned int pfn_32bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81580ba0)
Location: drivers/iommu/iova.c:36
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81580ba0-ffffffff81580cdc: init_iova_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void init_iova_domain(struct iova_domain *iovad, long unsigned int granule, long unsigned int start_pfn, long unsigned int pfn_32bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff815ad550)
Location: drivers/iommu/iova.c:36
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff815ad550-ffffffff815ad68e: init_iova_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void init_iova_domain(struct iova_domain *iovad, long unsigned int granule, long unsigned int start_pfn, long unsigned int pfn_32bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff815c3160)
Location: drivers/iommu/iova.c:37
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff815c3160-ffffffff815c32a3: init_iova_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void init_iova_domain(struct iova_domain *iovad, long unsigned int granule, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81629aa0)
Location: drivers/iommu/iova.c:42
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81629aa0-ffffffff81629c2d: init_iova_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void init_iova_domain(struct iova_domain *iovad, long unsigned int granule, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816647b0)
Location: drivers/iommu/iova.c:42
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816647b0-ffffffff8166493b: init_iova_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void init_iova_domain(struct iova_domain *iovad, long unsigned int granule, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81682db0)
Location: drivers/iommu/iova.c:42
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81682db0-ffffffff81682f2e: init_iova_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void init_iova_domain(struct iova_domain *iovad, long unsigned int granule, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816baa01)
Location: drivers/iommu/iova.c:30
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816bb11d-ffffffff816bb130: init_iova_domain.cold (STB_LOCAL)
ffffffff816ba9f0-ffffffff816bab7c: init_iova_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void init_iova_domain(struct iova_domain *iovad, long unsigned int granule, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816dd840)
Location: drivers/iommu/iova.c:30
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816dd840-ffffffff816dd9df: init_iova_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void init_iova_domain(struct iova_domain *iovad, long unsigned int granule, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81793e40)
Location: drivers/iommu/iova.c:30
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
  - drivers/iommu/intel/iommu.c:dmar_init_reserved_ranges
```
**Symbols:**

```
ffffffff81793e40-ffffffff81793efd: init_iova_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void init_iova_domain(struct iova_domain *iovad, long unsigned int granule, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817c0b90)
Location: drivers/iommu/iova.c:31
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
```
**Symbols:**

```
ffffffff817c0b90-ffffffff817c0c4d: init_iova_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void init_iova_domain(struct iova_domain *iovad, long unsigned int granule, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817a3ab0)
Location: drivers/iommu/iova.c:48
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
```
**Symbols:**

```
ffffffff817a3ab0-ffffffff817a3c3e: init_iova_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void init_iova_domain(struct iova_domain *iovad, long unsigned int granule, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:48
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
```
**Symbols:**

```
ffffffff81d020bd-ffffffff81d020de: init_iova_domain.cold (STB_LOCAL)
ffffffff8182cd00-ffffffff8182cee4: init_iova_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void init_iova_domain(struct iova_domain *iovad, long unsigned int granule, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:47
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
```
**Symbols:**

```
ffffffff81eca566-ffffffff81eca587: init_iova_domain.cold (STB_LOCAL)
ffffffff8196d640-ffffffff8196d6ff: init_iova_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void init_iova_domain(struct iova_domain *iovad, long unsigned int granule, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:52
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
```
**Symbols:**

```
ffffffff820980e0-ffffffff82098101: init_iova_domain.cold (STB_LOCAL)
ffffffff81ad7ee0-ffffffff81ad7f9f: init_iova_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void init_iova_domain(struct iova_domain *iovad, long unsigned int granule, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:52
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
```
**Symbols:**

```
ffffffff821190cf-ffffffff821190f0: init_iova_domain.cold (STB_LOCAL)
ffffffff81b25e20-ffffffff81b25edf: init_iova_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void init_iova_domain(struct iova_domain *iovad, long unsigned int granule, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:53
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
```
**Symbols:**

```
ffffffff821f70ab-ffffffff821f70cc: init_iova_domain.cold (STB_LOCAL)
ffffffff81b7cc50-ffffffff81b7cd0f: init_iova_domain (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void init_iova_domain(struct iova_domain *iovad, long unsigned int granule, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffff8000108ccf50)
Location: drivers/iommu/iova.c:30
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
```
**Symbols:**

```
ffff8000108ccf50-ffff8000108cd0c4: init_iova_domain (STB_GLOBAL)
```
</details>
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
void init_iova_domain(struct iova_domain *iovad, long unsigned int granule, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816a3290)
Location: drivers/iommu/iova.c:30
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816a3290-ffffffff816a342f: init_iova_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void init_iova_domain(struct iova_domain *iovad, long unsigned int granule, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81680c80)
Location: drivers/iommu/iova.c:30
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81680c80-ffffffff81680e1f: init_iova_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void init_iova_domain(struct iova_domain *iovad, long unsigned int granule, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816d1500)
Location: drivers/iommu/iova.c:30
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816d1500-ffffffff816d169f: init_iova_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void init_iova_domain(struct iova_domain *iovad, long unsigned int granule, long unsigned int start_pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816eb710)
Location: drivers/iommu/iova.c:30
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816eb710-ffffffff816eb8af: init_iova_domain (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int pfn_32bit</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
