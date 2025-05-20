# Function: <code>huge_node</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int huge_node(struct vm_area_struct *vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy **mpol, nodemask_t **nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8121d4a0)
Location: mm/mempolicy.c:1741
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff8121d4a0-ffffffff8121d589: huge_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int huge_node(struct vm_area_struct *vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy **mpol, nodemask_t **nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81238690)
Location: mm/mempolicy.c:1797
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff81238690-ffffffff81238779: huge_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int huge_node(struct vm_area_struct *vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy **mpol, nodemask_t **nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8125bbb0)
Location: mm/mempolicy.c:1854
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
```
**Symbols:**

```
ffffffff8125bbb0-ffffffff8125bc99: huge_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int huge_node(struct vm_area_struct *vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy **mpol, nodemask_t **nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81270470)
Location: mm/mempolicy.c:1894
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
```
**Symbols:**

```
ffffffff81270470-ffffffff81270559: huge_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int huge_node(struct vm_area_struct *vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy **mpol, nodemask_t **nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128bd70)
Location: mm/mempolicy.c:1940
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
```
**Symbols:**

```
ffffffff8128bd70-ffffffff8128be5e: huge_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int huge_node(struct vm_area_struct *vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy **mpol, nodemask_t **nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129b940)
Location: mm/mempolicy.c:1942
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
```
**Symbols:**

```
ffffffff8129b940-ffffffff8129ba2e: huge_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int huge_node(struct vm_area_struct *vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy **mpol, nodemask_t **nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812cf4f0)
Location: mm/mempolicy.c:2039
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:dequeue_huge_page_vma
  - mm/hugetlb.c:dequeue_huge_page_vma
  - mm/hugetlb.c:dequeue_huge_page_vma
```
**Symbols:**

```
ffffffff812cf4f0-ffffffff812cf629: huge_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int huge_node(struct vm_area_struct *vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy **mpol, nodemask_t **nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812dafc0)
Location: mm/mempolicy.c:2014
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:dequeue_huge_page_vma
  - mm/hugetlb.c:dequeue_huge_page_vma
  - mm/hugetlb.c:dequeue_huge_page_vma
```
**Symbols:**

```
ffffffff812dafc0-ffffffff812db0f9: huge_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int huge_node(struct vm_area_struct *vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy **mpol, nodemask_t **nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e2820)
Location: mm/mempolicy.c:2028
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
```
**Symbols:**

```
ffffffff812e2820-ffffffff812e2966: huge_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int huge_node(struct vm_area_struct *vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy **mpol, nodemask_t **nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (0)
Location: mm/mempolicy.c:1934
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
```
**Symbols:**

```
ffffffff81cc0578-ffffffff81cc05bc: huge_node.cold (STB_LOCAL)
ffffffff81329b30-ffffffff81329cfd: huge_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int huge_node(struct vm_area_struct *vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy **mpol, nodemask_t **nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (0)
Location: mm/mempolicy.c:2003
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:dequeue_huge_page_vma
```
**Symbols:**

```
ffffffff81e72976-ffffffff81e729ad: huge_node.cold (STB_LOCAL)
ffffffff81398f70-ffffffff81399137: huge_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int huge_node(struct vm_area_struct *vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy **mpol, nodemask_t **nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (0)
Location: mm/mempolicy.c:2018
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:dequeue_huge_page_vma
```
**Symbols:**

```
ffffffff8206720b-ffffffff82067242: huge_node.cold (STB_LOCAL)
ffffffff81418df0-ffffffff81418f8e: huge_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int huge_node(struct vm_area_struct *vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy **mpol, nodemask_t **nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (0)
Location: mm/mempolicy.c:2029
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio_vma
  - mm/hugetlb.c:dequeue_hugetlb_folio_vma
```
**Symbols:**

```
ffffffff820e6acd-ffffffff820e6b04: huge_node.cold (STB_LOCAL)
ffffffff8144c2c0-ffffffff8144c467: huge_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int huge_node(struct vm_area_struct *vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy **mpol, nodemask_t **nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81485640)
Location: mm/mempolicy.c:1973
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:dequeue_hugetlb_folio_vma
```
**Symbols:**

```
ffffffff81485640-ffffffff814856f0: huge_node (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int huge_node(struct vm_area_struct *vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy **mpol, nodemask_t **nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffff80001033a8a0)
Location: mm/mempolicy.c:1942
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
```
**Symbols:**

```
ffff80001033a8a0-ffff80001033a9c8: huge_node (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int huge_node(struct vm_area_struct *vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy **mpol, nodemask_t **nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c0000000004151f0)
Location: mm/mempolicy.c:1942
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
```
**Symbols:**

```
c0000000004151f0-c000000000415358: huge_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (0)
Location: include/linux/mempolicy.h:271
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int huge_node(struct vm_area_struct *vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy **mpol, nodemask_t **nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81293f20)
Location: mm/mempolicy.c:1942
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
```
**Symbols:**

```
ffffffff81293f20-ffffffff8129400e: huge_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int huge_node(struct vm_area_struct *vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy **mpol, nodemask_t **nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81285b30)
Location: mm/mempolicy.c:1942
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
```
**Symbols:**

```
ffffffff81285b30-ffffffff81285c1e: huge_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int huge_node(struct vm_area_struct *vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy **mpol, nodemask_t **nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81291d30)
Location: mm/mempolicy.c:1942
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
```
**Symbols:**

```
ffffffff81291d30-ffffffff81291e1e: huge_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int huge_node(struct vm_area_struct *vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy **mpol, nodemask_t **nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812a1b40)
Location: mm/mempolicy.c:1942
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
```
**Symbols:**

```
ffffffff812a1b40-ffffffff812a1c2e: huge_node (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
