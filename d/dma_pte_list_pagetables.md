# Function: <code>dma_pte_list_pagetables</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *dma_pte_list_pagetables(struct dmar_domain *domain, int level, struct dma_pte *pte, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81535640)
Location: drivers/iommu/intel-iommu.c:1174
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff81535640-ffffffff815356c9: dma_pte_list_pagetables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *dma_pte_list_pagetables(struct dmar_domain *domain, int level, struct dma_pte *pte, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81589d40)
Location: drivers/iommu/intel-iommu.c:1181
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
```
**Symbols:**

```
ffffffff81589d40-ffffffff81589dc3: dma_pte_list_pagetables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *dma_pte_list_pagetables(struct dmar_domain *domain, int level, struct dma_pte *pte, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815b73f0)
Location: drivers/iommu/intel-iommu.c:1195
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
```
**Symbols:**

```
ffffffff815b73f0-ffffffff815b747b: dma_pte_list_pagetables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *dma_pte_list_pagetables(struct dmar_domain *domain, int level, struct dma_pte *pte, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815cd1d0)
Location: drivers/iommu/intel-iommu.c:1200
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
```
**Symbols:**

```
ffffffff815cd1d0-ffffffff815cd250: dma_pte_list_pagetables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *dma_pte_list_pagetables(struct dmar_domain *domain, int level, struct dma_pte *pte, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81633fd0)
Location: drivers/iommu/intel-iommu.c:1176
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
```
**Symbols:**

```
ffffffff81633fd0-ffffffff81634050: dma_pte_list_pagetables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *dma_pte_list_pagetables(struct dmar_domain *domain, int level, struct dma_pte *pte, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8166f4e0)
Location: drivers/iommu/intel-iommu.c:1178
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
```
**Symbols:**

```
ffffffff8166f4e0-ffffffff8166f55f: dma_pte_list_pagetables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *dma_pte_list_pagetables(struct dmar_domain *domain, int level, struct dma_pte *pte, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168da50)
Location: drivers/iommu/intel-iommu.c:1054
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
```
**Symbols:**

```
ffffffff8168da50-ffffffff8168dacf: dma_pte_list_pagetables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *dma_pte_list_pagetables(struct dmar_domain *domain, int level, struct dma_pte *pte, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c5470)
Location: drivers/iommu/intel-iommu.c:1059
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
```
**Symbols:**

```
ffffffff816c5470-ffffffff816c54f2: dma_pte_list_pagetables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *dma_pte_list_pagetables(struct dmar_domain *domain, int level, struct dma_pte *pte, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e83b0)
Location: drivers/iommu/intel-iommu.c:1070
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
```
**Symbols:**

```
ffffffff816e83b0-ffffffff816e8432: dma_pte_list_pagetables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a0fe0)
Location: drivers/iommu/intel/iommu.c:1086
Inline: True
Direct callers:
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff817a0fe0-ffffffff817a1055: dma_pte_list_pagetables.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817ae570)
Location: drivers/iommu/intel/iommu.c:1176
Inline: True
Direct callers:
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff817ae570-ffffffff817ae5e5: dma_pte_list_pagetables.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81790df0)
Location: drivers/iommu/intel/iommu.c:1195
Inline: True
Direct callers:
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff81790df0-ffffffff81790e65: dma_pte_list_pagetables.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81818540)
Location: drivers/iommu/intel/iommu.c:1201
Inline: True
Direct callers:
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff81818540-ffffffff818185b5: dma_pte_list_pagetables.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff819594d0)
Location: drivers/iommu/intel/iommu.c:1155
Inline: True
Direct callers:
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff819594d0-ffffffff81959567: dma_pte_list_pagetables.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac0950)
Location: drivers/iommu/intel/iommu.c:1107
Inline: True
Direct callers:
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff81ac0950-ffffffff81ac09e7: dma_pte_list_pagetables.isra.0 (STB_LOCAL)
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
In drivers/iommu/intel/iommu.c (ffffffff81b0d1c0)
Location: drivers/iommu/intel/iommu.c:1106
Inline: True
Direct callers:
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff81b0d1c0-ffffffff81b0d257: dma_pte_list_pagetables.isra.0 (STB_LOCAL)
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
In drivers/iommu/intel/iommu.c (ffffffff81b61bd0)
Location: drivers/iommu/intel/iommu.c:966
Inline: True
Direct callers:
  - drivers/iommu/intel/iommu.c:dma_pte_clear_level
```
**Symbols:**

```
ffffffff81b61bd0-ffffffff81b61c67: dma_pte_list_pagetables.isra.0 (STB_LOCAL)
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
struct page *dma_pte_list_pagetables(struct dmar_domain *domain, int level, struct dma_pte *pte, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ade90)
Location: drivers/iommu/intel-iommu.c:1070
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
```
**Symbols:**

```
ffffffff816ade90-ffffffff816adf12: dma_pte_list_pagetables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *dma_pte_list_pagetables(struct dmar_domain *domain, int level, struct dma_pte *pte, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168b7f0)
Location: drivers/iommu/intel-iommu.c:1070
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
```
**Symbols:**

```
ffffffff8168b7f0-ffffffff8168b872: dma_pte_list_pagetables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *dma_pte_list_pagetables(struct dmar_domain *domain, int level, struct dma_pte *pte, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816dc070)
Location: drivers/iommu/intel-iommu.c:1070
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
```
**Symbols:**

```
ffffffff816dc070-ffffffff816dc0f2: dma_pte_list_pagetables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *dma_pte_list_pagetables(struct dmar_domain *domain, int level, struct dma_pte *pte, struct page *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f6640)
Location: drivers/iommu/intel-iommu.c:1070
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dma_pte_clear_level
  - drivers/iommu/intel-iommu.c:dma_pte_list_pagetables
```
**Symbols:**

```
ffffffff816f6640-ffffffff816f66c2: dma_pte_list_pagetables (STB_LOCAL)
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
