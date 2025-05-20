# Function: <code>dma_pte_clear_level</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *dma_pte_clear_level(struct dmar_domain *domain, int level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81535840)
Location: drivers/iommu/intel-iommu.c:1198
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:domain_unmap
```
**Symbols:**

```
ffffffff81535840-ffffffff815359ca: dma_pte_clear_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *dma_pte_clear_level(struct dmar_domain *domain, int level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158a0a0)
Location: drivers/iommu/intel-iommu.c:1205
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_unmap
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff8158a0a0-ffffffff8158a224: dma_pte_clear_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *dma_pte_clear_level(struct dmar_domain *domain, int level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815b7720)
Location: drivers/iommu/intel-iommu.c:1219
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_unmap
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff815b7720-ffffffff815b78a4: dma_pte_clear_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *dma_pte_clear_level(struct dmar_domain *domain, int level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815cd700)
Location: drivers/iommu/intel-iommu.c:1224
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_unmap
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff815cd700-ffffffff815cd89e: dma_pte_clear_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *dma_pte_clear_level(struct dmar_domain *domain, int level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81634530)
Location: drivers/iommu/intel-iommu.c:1200
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_unmap
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff81634530-ffffffff816346ce: dma_pte_clear_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *dma_pte_clear_level(struct dmar_domain *domain, int level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8166fa50)
Location: drivers/iommu/intel-iommu.c:1202
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_unmap
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff8166fa50-ffffffff8166fbd5: dma_pte_clear_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *dma_pte_clear_level(struct dmar_domain *domain, int level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168df60)
Location: drivers/iommu/intel-iommu.c:1078
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_unmap
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff8168df60-ffffffff8168e0e5: dma_pte_clear_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *dma_pte_clear_level(struct dmar_domain *domain, int level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c5580)
Location: drivers/iommu/intel-iommu.c:1083
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_unmap
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff816c5580-ffffffff816c570b: dma_pte_clear_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *dma_pte_clear_level(struct dmar_domain *domain, int level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e84f0)
Location: drivers/iommu/intel-iommu.c:1094
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_unmap
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff816e84f0-ffffffff816e867b: dma_pte_clear_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *dma_pte_clear_level(struct dmar_domain *domain, int level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a1060)
Location: drivers/iommu/intel/iommu.c:1110
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_unmap
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff817a1060-ffffffff817a11f0: dma_pte_clear_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *dma_pte_clear_level(struct dmar_domain *domain, int level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817ae5f0)
Location: drivers/iommu/intel/iommu.c:1200
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_unmap
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff817ae5f0-ffffffff817ae780: dma_pte_clear_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *dma_pte_clear_level(struct dmar_domain *domain, int level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81790e70)
Location: drivers/iommu/intel/iommu.c:1219
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_unmap
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff81790e70-ffffffff81790ffa: dma_pte_clear_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *dma_pte_clear_level(struct dmar_domain *domain, int level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1225
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_unmap
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff81818ed0-ffffffff818190b1: dma_pte_clear_level (STB_LOCAL)
ffffffff81cff4ac-ffffffff81cff5b0: dma_pte_clear_level.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dma_pte_clear_level(struct dmar_domain *domain, int level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn, struct list_head *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1175
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_unmap
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff8195a130-ffffffff8195a31f: dma_pte_clear_level (STB_LOCAL)
ffffffff81ec7ca5-ffffffff81ec7da7: dma_pte_clear_level.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dma_pte_clear_level(struct dmar_domain *domain, int level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn, struct list_head *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1127
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_unmap
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff81ac1690-ffffffff81ac187c: dma_pte_clear_level (STB_LOCAL)
ffffffff820975ad-ffffffff820976af: dma_pte_clear_level.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dma_pte_clear_level(struct dmar_domain *domain, int level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn, struct list_head *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1126
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_unmap
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff81b0e0a0-ffffffff81b0e28d: dma_pte_clear_level (STB_LOCAL)
ffffffff8211865c-ffffffff82118766: dma_pte_clear_level.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dma_pte_clear_level(struct dmar_domain *domain, int level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn, struct list_head *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:986
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_unmap
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff81b62b00-ffffffff81b62ced: dma_pte_clear_level (STB_LOCAL)
ffffffff821f63a8-ffffffff821f64b2: dma_pte_clear_level.cold (STB_LOCAL)
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
struct page *dma_pte_clear_level(struct dmar_domain *domain, int level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816adfd0)
Location: drivers/iommu/intel-iommu.c:1094
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_unmap
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff816adfd0-ffffffff816ae15b: dma_pte_clear_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *dma_pte_clear_level(struct dmar_domain *domain, int level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168b930)
Location: drivers/iommu/intel-iommu.c:1094
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_unmap
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff8168b930-ffffffff8168babb: dma_pte_clear_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *dma_pte_clear_level(struct dmar_domain *domain, int level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816dc1b0)
Location: drivers/iommu/intel-iommu.c:1094
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_unmap
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff816dc1b0-ffffffff816dc33b: dma_pte_clear_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *dma_pte_clear_level(struct dmar_domain *domain, int level, struct dma_pte *pte, long unsigned int pfn, long unsigned int start_pfn, long unsigned int last_pfn, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f67f0)
Location: drivers/iommu/intel-iommu.c:1094
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_unmap
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff816f67f0-ffffffff816f697b: dma_pte_clear_level (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct page *freelist</code> ➡️ <code>struct list_head *freelist</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct page *</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
