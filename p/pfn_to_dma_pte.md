# Function: <code>pfn_to_dma_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dma_pte *pfn_to_dma_pte(struct dmar_domain *domain, long unsigned int pfn, int *target_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815376a0)
Location: drivers/iommu/intel-iommu.c:994
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
```
**Symbols:**

```
ffffffff815376a0-ffffffff815378e8: pfn_to_dma_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dma_pte *pfn_to_dma_pte(struct dmar_domain *domain, long unsigned int pfn, int *target_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158c1a0)
Location: drivers/iommu/intel-iommu.c:1001
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff8158c1a0-ffffffff8158c3a9: pfn_to_dma_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dma_pte *pfn_to_dma_pte(struct dmar_domain *domain, long unsigned int pfn, int *target_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815b98e0)
Location: drivers/iommu/intel-iommu.c:1015
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff815b98e0-ffffffff815b9ae9: pfn_to_dma_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dma_pte *pfn_to_dma_pte(struct dmar_domain *domain, long unsigned int pfn, int *target_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815cf6a0)
Location: drivers/iommu/intel-iommu.c:1020
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff815cf6a0-ffffffff815cf892: pfn_to_dma_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dma_pte *pfn_to_dma_pte(struct dmar_domain *domain, long unsigned int pfn, int *target_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81636430)
Location: drivers/iommu/intel-iommu.c:986
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff81636430-ffffffff81636622: pfn_to_dma_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dma_pte *pfn_to_dma_pte(struct dmar_domain *domain, long unsigned int pfn, int *target_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816719c0)
Location: drivers/iommu/intel-iommu.c:988
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff816719c0-ffffffff81671b9d: pfn_to_dma_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dma_pte *pfn_to_dma_pte(struct dmar_domain *domain, long unsigned int pfn, int *target_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81690320)
Location: drivers/iommu/intel-iommu.c:864
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff81690320-ffffffff816904cf: pfn_to_dma_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dma_pte *pfn_to_dma_pte(struct dmar_domain *domain, long unsigned int pfn, int *target_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c84c0)
Location: drivers/iommu/intel-iommu.c:870
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff816c84c0-ffffffff816c8656: pfn_to_dma_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dma_pte *pfn_to_dma_pte(struct dmar_domain *domain, long unsigned int pfn, int *target_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816eb470)
Location: drivers/iommu/intel-iommu.c:881
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff816eb470-ffffffff816eb606: pfn_to_dma_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dma_pte *pfn_to_dma_pte(struct dmar_domain *domain, long unsigned int pfn, int *target_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a2540)
Location: drivers/iommu/intel/iommu.c:895
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
  - drivers/iommu/intel/iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff817a2540-ffffffff817a2742: pfn_to_dma_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dma_pte *pfn_to_dma_pte(struct dmar_domain *domain, long unsigned int pfn, int *target_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817af7a0)
Location: drivers/iommu/intel/iommu.c:985
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
  - drivers/iommu/intel/iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff817af7a0-ffffffff817af9a2: pfn_to_dma_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dma_pte *pfn_to_dma_pte(struct dmar_domain *domain, long unsigned int pfn, int *target_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81792770)
Location: drivers/iommu/intel/iommu.c:1001
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map
  - drivers/iommu/intel/iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/iommu.c:switch_to_super_page
```
**Symbols:**

```
ffffffff81792770-ffffffff81792995: pfn_to_dma_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dma_pte *pfn_to_dma_pte(struct dmar_domain *domain, long unsigned int pfn, int *target_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1007
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/iommu.c:switch_to_super_page
```
**Symbols:**

```
ffffffff8181a580-ffffffff8181a7a8: pfn_to_dma_pte (STB_LOCAL)
ffffffff81cff8bf-ffffffff81cff904: pfn_to_dma_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dma_pte *pfn_to_dma_pte(struct dmar_domain *domain, long unsigned int pfn, int *target_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:965
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/iommu.c:switch_to_super_page
```
**Symbols:**

```
ffffffff8195ac80-ffffffff8195aece: pfn_to_dma_pte (STB_LOCAL)
ffffffff81ec7ffd-ffffffff81ec8042: pfn_to_dma_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct dma_pte *pfn_to_dma_pte(struct dmar_domain *domain, long unsigned int pfn, int *target_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:919
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/iommu.c:switch_to_super_page
```
**Symbols:**

```
ffffffff81ac2840-ffffffff81ac2a67: pfn_to_dma_pte (STB_LOCAL)
ffffffff82097870-ffffffff820978b5: pfn_to_dma_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct dma_pte *pfn_to_dma_pte(struct dmar_domain *domain, long unsigned int pfn, int *target_level, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:919
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/iommu.c:switch_to_super_page
```
**Symbols:**

```
ffffffff81b0f700-ffffffff81b0f8fc: pfn_to_dma_pte (STB_LOCAL)
ffffffff821187f9-ffffffff8211883b: pfn_to_dma_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct dma_pte *pfn_to_dma_pte(struct dmar_domain *domain, long unsigned int pfn, int *target_level, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:779
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_read_and_clear_dirty
  - drivers/iommu/intel/iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/iommu.c:switch_to_super_page
```
**Symbols:**

```
ffffffff81b63ff0-ffffffff81b641ec: pfn_to_dma_pte (STB_LOCAL)
ffffffff821f6507-ffffffff821f6549: pfn_to_dma_pte.cold (STB_LOCAL)
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
struct dma_pte *pfn_to_dma_pte(struct dmar_domain *domain, long unsigned int pfn, int *target_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b0da0)
Location: drivers/iommu/intel-iommu.c:881
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff816b0da0-ffffffff816b0f36: pfn_to_dma_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dma_pte *pfn_to_dma_pte(struct dmar_domain *domain, long unsigned int pfn, int *target_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168e8a0)
Location: drivers/iommu/intel-iommu.c:881
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff8168e8a0-ffffffff8168ea36: pfn_to_dma_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dma_pte *pfn_to_dma_pte(struct dmar_domain *domain, long unsigned int pfn, int *target_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816df130)
Location: drivers/iommu/intel-iommu.c:881
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff816df130-ffffffff816df2c6: pfn_to_dma_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dma_pte *pfn_to_dma_pte(struct dmar_domain *domain, long unsigned int pfn, int *target_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f9740)
Location: drivers/iommu/intel-iommu.c:881
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_iova_to_phys
  - drivers/iommu/intel-iommu.c:intel_iommu_unmap
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff816f9740-ffffffff816f98d6: pfn_to_dma_pte (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
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
