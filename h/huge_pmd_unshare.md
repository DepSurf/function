# Function: <code>huge_pmd_unshare</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int huge_pmd_unshare(struct mm_struct *mm, long unsigned int *addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811dd520)
Location: mm/hugetlb.c:4250
Inline: False
Direct callers:
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:hugetlb_change_protection
```
**Symbols:**

```
ffffffff811dd520-ffffffff811dd679: huge_pmd_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int huge_pmd_unshare(struct mm_struct *mm, long unsigned int *addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811fb7f0)
Location: mm/hugetlb.c:4272
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff811fb7f0-ffffffff811fb96f: huge_pmd_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int huge_pmd_unshare(struct mm_struct *mm, long unsigned int *addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8120c2f0)
Location: mm/hugetlb.c:4385
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff8120c2f0-ffffffff8120c467: huge_pmd_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int huge_pmd_unshare(struct mm_struct *mm, long unsigned int *addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81217c90)
Location: mm/hugetlb.c:4545
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff81217c90-ffffffff81217dea: huge_pmd_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int huge_pmd_unshare(struct mm_struct *mm, long unsigned int *addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812329f0)
Location: mm/hugetlb.c:4605
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff812329f0-ffffffff81232b85: huge_pmd_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int huge_pmd_unshare(struct mm_struct *mm, long unsigned int *addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81255a60)
Location: mm/hugetlb.c:4634
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff81255a60-ffffffff81255bf1: huge_pmd_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int huge_pmd_unshare(struct mm_struct *mm, long unsigned int *addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81269eb0)
Location: mm/hugetlb.c:4718
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff81269eb0-ffffffff8126a041: huge_pmd_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int huge_pmd_unshare(struct mm_struct *mm, long unsigned int *addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81284fe0)
Location: mm/hugetlb.c:4823
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff81284fe0-ffffffff81285174: huge_pmd_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int huge_pmd_unshare(struct mm_struct *mm, long unsigned int *addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81294b80)
Location: mm/hugetlb.c:4940
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff81294b80-ffffffff81294d14: huge_pmd_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int huge_pmd_unshare(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int *addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c8130)
Location: mm/hugetlb.c:5424
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff812c8130-ffffffff812c8309: huge_pmd_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int huge_pmd_unshare(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int *addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d3d10)
Location: mm/hugetlb.c:5436
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff812d3d10-ffffffff812d3eda: huge_pmd_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int huge_pmd_unshare(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int *addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812dac50)
Location: mm/hugetlb.c:5711
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff812dac50-ffffffff812dade7: huge_pmd_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int huge_pmd_unshare(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int *addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:6048
Inline: False
Direct callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff81cbfb8f-ffffffff81cbfbaf: huge_pmd_unshare.cold (STB_LOCAL)
ffffffff81321c60-ffffffff81321e0b: huge_pmd_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int huge_pmd_unshare(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int *addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:6768
Inline: False
Direct callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
```
**Symbols:**

```
ffffffff81e71f0c-ffffffff81e71f2c: huge_pmd_unshare.cold (STB_LOCAL)
ffffffff8138eda0-ffffffff8138f024: huge_pmd_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int huge_pmd_unshare(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:7113
Inline: False
Direct callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
```
**Symbols:**

```
ffffffff820668cd-ffffffff820668e9: huge_pmd_unshare.cold (STB_LOCAL)
ffffffff8140d890-ffffffff8140db04: huge_pmd_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int huge_pmd_unshare(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:7207
Inline: False
Direct callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
```
**Symbols:**

```
ffffffff820e60e2-ffffffff820e60fe: huge_pmd_unshare.cold (STB_LOCAL)
ffffffff81440c40-ffffffff81440ec0: huge_pmd_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int huge_pmd_unshare(struct mm_struct *mm, struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:7344
Inline: False
Direct callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
```
**Symbols:**

```
ffffffff821c3241-ffffffff821c325d: huge_pmd_unshare.cold (STB_LOCAL)
ffffffff8147ad70-ffffffff8147afe7: huge_pmd_unshare (STB_GLOBAL)
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
int huge_pmd_unshare(struct mm_struct *mm, long unsigned int *addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010333918)
Location: mm/hugetlb.c:4940
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffff800010333918-ffff800010333a58: huge_pmd_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (0)
Location: include/linux/hugetlb.h:155
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int huge_pmd_unshare(struct mm_struct *mm, long unsigned int *addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c000000000410370)
Location: mm/hugetlb.c:4963
Inline: True
Direct callers:
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
c000000000410370-c000000000410380: huge_pmd_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int huge_pmd_unshare(struct mm_struct *mm, long unsigned int *addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022faae)
Location: mm/hugetlb.c:4940
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffe00022faae-ffffffe00022fba4: huge_pmd_unshare (STB_GLOBAL)
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
int huge_pmd_unshare(struct mm_struct *mm, long unsigned int *addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128d160)
Location: mm/hugetlb.c:4940
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff8128d160-ffffffff8128d2f4: huge_pmd_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int huge_pmd_unshare(struct mm_struct *mm, long unsigned int *addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127ef70)
Location: mm/hugetlb.c:4940
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff8127ef70-ffffffff8127f0de: huge_pmd_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int huge_pmd_unshare(struct mm_struct *mm, long unsigned int *addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128af70)
Location: mm/hugetlb.c:4940
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff8128af70-ffffffff8128b104: huge_pmd_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int huge_pmd_unshare(struct mm_struct *mm, long unsigned int *addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8129ad90)
Location: mm/hugetlb.c:4940
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff8129ad90-ffffffff8129af24: huge_pmd_unshare (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, addr, ptep</code> ➡️ <code>mm, vma, addr, ptep</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int *addr</code> ➡️ <code>long unsigned int addr</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
