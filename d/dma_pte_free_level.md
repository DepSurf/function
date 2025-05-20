# Function: <code>dma_pte_free_level</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dma_pte_free_level(struct dmar_domain *domain, int level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81536760)
Location: drivers/iommu/intel-iommu.c:1113
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
```
**Symbols:**

```
ffffffff81536760-ffffffff81536887: dma_pte_free_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dma_pte_free_level(struct dmar_domain *domain, int level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158ab20)
Location: drivers/iommu/intel-iommu.c:1120
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
```
**Symbols:**

```
ffffffff8158ab20-ffffffff8158ac3d: dma_pte_free_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dma_pte_free_level(struct dmar_domain *domain, int level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815b8180)
Location: drivers/iommu/intel-iommu.c:1134
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
```
**Symbols:**

```
ffffffff815b8180-ffffffff815b829d: dma_pte_free_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dma_pte_free_level(struct dmar_domain *domain, int level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815cd9a0)
Location: drivers/iommu/intel-iommu.c:1139
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
```
**Symbols:**

```
ffffffff815cd9a0-ffffffff815cdaf8: dma_pte_free_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dma_pte_free_level(struct dmar_domain *domain, int level, int retain_level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816347d0)
Location: drivers/iommu/intel-iommu.c:1105
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
```
**Symbols:**

```
ffffffff816347d0-ffffffff81634931: dma_pte_free_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dma_pte_free_level(struct dmar_domain *domain, int level, int retain_level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8166fce0)
Location: drivers/iommu/intel-iommu.c:1107
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
```
**Symbols:**

```
ffffffff8166fce0-ffffffff8166fe53: dma_pte_free_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dma_pte_free_level(struct dmar_domain *domain, int level, int retain_level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168e2c0)
Location: drivers/iommu/intel-iommu.c:983
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
```
**Symbols:**

```
ffffffff8168e2c0-ffffffff8168e433: dma_pte_free_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dma_pte_free_level(struct dmar_domain *domain, int level, int retain_level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c5930)
Location: drivers/iommu/intel-iommu.c:988
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
```
**Symbols:**

```
ffffffff816c5930-ffffffff816c5aa3: dma_pte_free_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dma_pte_free_level(struct dmar_domain *domain, int level, int retain_level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e8960)
Location: drivers/iommu/intel-iommu.c:999
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
```
**Symbols:**

```
ffffffff816e8960-ffffffff816e8ad3: dma_pte_free_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dma_pte_free_level(struct dmar_domain *domain, int level, int retain_level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8179f8c0)
Location: drivers/iommu/intel/iommu.c:1015
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
```
**Symbols:**

```
ffffffff8179f8c0-ffffffff8179fa58: dma_pte_free_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dma_pte_free_level(struct dmar_domain *domain, int level, int retain_level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817ad460)
Location: drivers/iommu/intel/iommu.c:1105
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
```
**Symbols:**

```
ffffffff817ad460-ffffffff817ad5f8: dma_pte_free_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dma_pte_free_level(struct dmar_domain *domain, int level, int retain_level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8178fdf0)
Location: drivers/iommu/intel/iommu.c:1124
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
```
**Symbols:**

```
ffffffff8178fdf0-ffffffff8178ff83: dma_pte_free_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dma_pte_free_level(struct dmar_domain *domain, int level, int retain_level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1130
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
```
**Symbols:**

```
ffffffff81818c40-ffffffff81818dde: dma_pte_free_level (STB_LOCAL)
ffffffff81cff3a4-ffffffff81cff47e: dma_pte_free_level.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dma_pte_free_level(struct dmar_domain *domain, int level, int retain_level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1088
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
```
**Symbols:**

```
ffffffff81959e20-ffffffff81959ff5: dma_pte_free_level (STB_LOCAL)
ffffffff81ec7b81-ffffffff81ec7c63: dma_pte_free_level.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dma_pte_free_level(struct dmar_domain *domain, int level, int retain_level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1040
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
```
**Symbols:**

```
ffffffff81ac1380-ffffffff81ac1552: dma_pte_free_level (STB_LOCAL)
ffffffff820974cb-ffffffff820975ad: dma_pte_free_level.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dma_pte_free_level(struct dmar_domain *domain, int level, int retain_level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1039
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
```
**Symbols:**

```
ffffffff81b0dc10-ffffffff81b0dde2: dma_pte_free_level (STB_LOCAL)
ffffffff821184e6-ffffffff821185c8: dma_pte_free_level.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dma_pte_free_level(struct dmar_domain *domain, int level, int retain_level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:899
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
```
**Symbols:**

```
ffffffff81b625b0-ffffffff81b62782: dma_pte_free_level (STB_LOCAL)
ffffffff821f6232-ffffffff821f6314: dma_pte_free_level.cold (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void dma_pte_free_level(struct dmar_domain *domain, int level, int retain_level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ae440)
Location: drivers/iommu/intel-iommu.c:999
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
```
**Symbols:**

```
ffffffff816ae440-ffffffff816ae5b3: dma_pte_free_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dma_pte_free_level(struct dmar_domain *domain, int level, int retain_level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168bda0)
Location: drivers/iommu/intel-iommu.c:999
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
```
**Symbols:**

```
ffffffff8168bda0-ffffffff8168bf13: dma_pte_free_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dma_pte_free_level(struct dmar_domain *domain, int level, int retain_level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816dc620)
Location: drivers/iommu/intel-iommu.c:999
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
```
**Symbols:**

```
ffffffff816dc620-ffffffff816dc793: dma_pte_free_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dma_pte_free_level(struct dmar_domain *domain, int level, int retain_level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f6c60)
Location: drivers/iommu/intel-iommu.c:999
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
```
**Symbols:**

```
ffffffff816f6c60-ffffffff816f6dd3: dma_pte_free_level (STB_LOCAL)
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
<b>Param added. </b>
<code>int retain_level</code>
</li>
<li>
<b>Param reordered. </b>
<code>domain, level, pte, pfn, start_pfn, last_pfn</code> ➡️ <code>domain, level, retain_level, pte, pfn, start_pfn, last_pfn</code>
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
