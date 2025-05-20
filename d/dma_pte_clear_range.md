# Function: <code>dma_pte_clear_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dma_pte_clear_range(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81535ad0)
Location: drivers/iommu/intel-iommu.c:1082
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
```
**Symbols:**

```
ffffffff81535ad0-ffffffff81535c73: dma_pte_clear_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dma_pte_clear_range(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158bd30)
Location: drivers/iommu/intel-iommu.c:1089
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
```
**Symbols:**

```
ffffffff8158bd30-ffffffff8158bed2: dma_pte_clear_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dma_pte_clear_range(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815b9470)
Location: drivers/iommu/intel-iommu.c:1103
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
```
**Symbols:**

```
ffffffff815b9470-ffffffff815b9612: dma_pte_clear_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dma_pte_clear_range(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815cf190)
Location: drivers/iommu/intel-iommu.c:1108
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
```
**Symbols:**

```
ffffffff815cf190-ffffffff815cf338: dma_pte_clear_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dma_pte_clear_range(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81635f10)
Location: drivers/iommu/intel-iommu.c:1074
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
```
**Symbols:**

```
ffffffff81635f10-ffffffff816360b8: dma_pte_clear_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dma_pte_clear_range(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816713e0)
Location: drivers/iommu/intel-iommu.c:1076
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
```
**Symbols:**

```
ffffffff816713e0-ffffffff81671598: dma_pte_clear_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dma_pte_clear_range(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168f6b0)
Location: drivers/iommu/intel-iommu.c:952
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
```
**Symbols:**

```
ffffffff8168f6b0-ffffffff8168f868: dma_pte_clear_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dma_pte_clear_range(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c71f0)
Location: drivers/iommu/intel-iommu.c:957
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
```
**Symbols:**

```
ffffffff816c71f0-ffffffff816c7395: dma_pte_clear_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dma_pte_clear_range(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ea150)
Location: drivers/iommu/intel-iommu.c:968
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
```
**Symbols:**

```
ffffffff816ea150-ffffffff816ea2f5: dma_pte_clear_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dma_pte_clear_range(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a0d40)
Location: drivers/iommu/intel/iommu.c:984
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:dma_pte_free_pagetable
```
**Symbols:**

```
ffffffff817a0d40-ffffffff817a0ef4: dma_pte_clear_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dma_pte_clear_range(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817ae2d0)
Location: drivers/iommu/intel/iommu.c:1074
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:dma_pte_free_pagetable
```
**Symbols:**

```
ffffffff817ae2d0-ffffffff817ae489: dma_pte_clear_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dma_pte_clear_range(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81790c40)
Location: drivers/iommu/intel/iommu.c:1093
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:switch_to_super_page
```
**Symbols:**

```
ffffffff81790c40-ffffffff81790dec: dma_pte_clear_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dma_pte_clear_range(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1099
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:switch_to_super_page
```
**Symbols:**

```
ffffffff8181a0c0-ffffffff8181a25a: dma_pte_clear_range (STB_LOCAL)
ffffffff81cff719-ffffffff81cff80e: dma_pte_clear_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dma_pte_clear_range(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1057
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:switch_to_super_page
```
**Symbols:**

```
ffffffff8195aa20-ffffffff8195abcb: dma_pte_clear_range (STB_LOCAL)
ffffffff81ec7ef2-ffffffff81ec7fe2: dma_pte_clear_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dma_pte_clear_range(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1009
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:switch_to_super_page
```
**Symbols:**

```
ffffffff81ac2270-ffffffff81ac240c: dma_pte_clear_range (STB_LOCAL)
ffffffff82097783-ffffffff82097870: dma_pte_clear_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8371ae4e)
Location: drivers/iommu/intel/iommu.c:1008
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:switch_to_super_page
Direct callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:switch_to_super_page
```
**Symbols:**

```
ffffffff81b0de00-ffffffff81b0df4b: dma_pte_clear_range.part.0 (STB_LOCAL)
ffffffff821185c8-ffffffff8211865c: dma_pte_clear_range.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8394e92e)
Location: drivers/iommu/intel/iommu.c:868
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:switch_to_super_page
Direct callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:switch_to_super_page
```
**Symbols:**

```
ffffffff81b62860-ffffffff81b629ab: dma_pte_clear_range.part.0 (STB_LOCAL)
ffffffff821f6314-ffffffff821f63a8: dma_pte_clear_range.part.0.cold (STB_LOCAL)
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
void dma_pte_clear_range(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816afc30)
Location: drivers/iommu/intel-iommu.c:968
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
```
**Symbols:**

```
ffffffff816afc30-ffffffff816afdd5: dma_pte_clear_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dma_pte_clear_range(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168d580)
Location: drivers/iommu/intel-iommu.c:968
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
```
**Symbols:**

```
ffffffff8168d580-ffffffff8168d725: dma_pte_clear_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dma_pte_clear_range(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816dde10)
Location: drivers/iommu/intel-iommu.c:968
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
```
**Symbols:**

```
ffffffff816dde10-ffffffff816ddfb5: dma_pte_clear_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dma_pte_clear_range(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f8410)
Location: drivers/iommu/intel-iommu.c:968
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_domain_identity_map
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
```
**Symbols:**

```
ffffffff816f8410-ffffffff816f85b5: dma_pte_clear_range (STB_LOCAL)
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
