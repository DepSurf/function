# Function: <code>dma_pte_free_pagetable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dma_pte_free_pagetable(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81536890)
Location: drivers/iommu/intel-iommu.c:1147
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
  - drivers/iommu/intel-iommu.c:intel_map_sg
```
**Symbols:**

```
ffffffff81536890-ffffffff8153694b: dma_pte_free_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dma_pte_free_pagetable(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158bee0)
Location: drivers/iommu/intel-iommu.c:1154
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff8158bee0-ffffffff8158bf9b: dma_pte_free_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dma_pte_free_pagetable(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815b9620)
Location: drivers/iommu/intel-iommu.c:1168
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff815b9620-ffffffff815b96db: dma_pte_free_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dma_pte_free_pagetable(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815cf340)
Location: drivers/iommu/intel-iommu.c:1173
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff815cf340-ffffffff815cf3fb: dma_pte_free_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dma_pte_free_pagetable(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn, int retain_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816360c0)
Location: drivers/iommu/intel-iommu.c:1148
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff816360c0-ffffffff8163618a: dma_pte_free_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dma_pte_free_pagetable(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn, int retain_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816715a0)
Location: drivers/iommu/intel-iommu.c:1150
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff816715a0-ffffffff8167166a: dma_pte_free_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dma_pte_free_pagetable(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn, int retain_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168f870)
Location: drivers/iommu/intel-iommu.c:1026
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff8168f870-ffffffff8168f93a: dma_pte_free_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dma_pte_free_pagetable(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn, int retain_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c73a0)
Location: drivers/iommu/intel-iommu.c:1031
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff816c73a0-ffffffff816c7473: dma_pte_free_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dma_pte_free_pagetable(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn, int retain_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ea300)
Location: drivers/iommu/intel-iommu.c:1042
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff816ea300-ffffffff816ea3d3: dma_pte_free_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dma_pte_free_pagetable(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn, int retain_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a0f00)
Location: drivers/iommu/intel/iommu.c:1058
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_map_sg
  - drivers/iommu/intel/iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff817a0f00-ffffffff817a0fd3: dma_pte_free_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dma_pte_free_pagetable(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn, int retain_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817ae490)
Location: drivers/iommu/intel/iommu.c:1148
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff817ae490-ffffffff817ae563: dma_pte_free_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81792c55)
Location: drivers/iommu/intel/iommu.c:1167
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:switch_to_super_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8181aada)
Location: drivers/iommu/intel/iommu.c:1173
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:switch_to_super_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8195b22b)
Location: drivers/iommu/intel/iommu.c:1131
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:switch_to_super_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac2e3f)
Location: drivers/iommu/intel/iommu.c:1083
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:switch_to_super_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b0fceb)
Location: drivers/iommu/intel/iommu.c:1082
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:switch_to_super_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b6473b)
Location: drivers/iommu/intel/iommu.c:942
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:switch_to_super_page
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
void dma_pte_free_pagetable(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn, int retain_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816afde0)
Location: drivers/iommu/intel-iommu.c:1042
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff816afde0-ffffffff816afeb3: dma_pte_free_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dma_pte_free_pagetable(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn, int retain_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168d730)
Location: drivers/iommu/intel-iommu.c:1042
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff8168d730-ffffffff8168d803: dma_pte_free_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dma_pte_free_pagetable(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn, int retain_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ddfc0)
Location: drivers/iommu/intel-iommu.c:1042
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff816ddfc0-ffffffff816de093: dma_pte_free_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dma_pte_free_pagetable(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int last_pfn, int retain_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f85c0)
Location: drivers/iommu/intel-iommu.c:1042
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff816f85c0-ffffffff816f8693: dma_pte_free_pagetable (STB_LOCAL)
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
