# Function: <code>huge_pte_offset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
pte_t *huge_pte_offset(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811dd680)
Location: mm/hugetlb.c:4305
Inline: False
Direct callers:
  - mm/rmap.c:__page_check_address
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/migrate.c:remove_migration_pte
```
**Symbols:**

```
ffffffff811dd680-ffffffff811dd776: huge_pte_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
pte_t *huge_pte_offset(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811fb970)
Location: mm/hugetlb.c:4327
Inline: False
Direct callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:__page_check_address
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/migrate.c:remove_migration_pte
```
**Symbols:**

```
ffffffff811fb970-ffffffff811fba54: huge_pte_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
pte_t *huge_pte_offset(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8120c470)
Location: mm/hugetlb.c:4440
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:__page_check_address
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/migrate.c:remove_migration_pte
```
**Symbols:**

```
ffffffff8120c470-ffffffff8120c554: huge_pte_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
pte_t *huge_pte_offset(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81217df0)
Location: mm/hugetlb.c:4603
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffff81217df0-ffffffff81217ed4: huge_pte_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
pte_t *huge_pte_offset(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81232b90)
Location: mm/hugetlb.c:4674
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffff81232b90-ffffffff81232d2e: huge_pte_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pte_t *huge_pte_offset(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81255c00)
Location: mm/hugetlb.c:4703
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffff81255c00-ffffffff81255d53: huge_pte_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pte_t *huge_pte_offset(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8126a050)
Location: mm/hugetlb.c:4792
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffff8126a050-ffffffff8126a1a3: huge_pte_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pte_t *huge_pte_offset(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81285180)
Location: mm/hugetlb.c:4897
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffff81285180-ffffffff812852da: huge_pte_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pte_t *huge_pte_offset(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81294d20)
Location: mm/hugetlb.c:5014
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffff81294d20-ffffffff81294e7a: huge_pte_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pte_t *huge_pte_offset(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c8310)
Location: mm/hugetlb.c:5501
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/pagewalk.c:walk_hugetlb_range
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffff812c8310-ffffffff812c8428: huge_pte_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pte_t *huge_pte_offset(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d3ee0)
Location: mm/hugetlb.c:5513
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/pagewalk.c:walk_hugetlb_range
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffff812d3ee0-ffffffff812d3ff8: huge_pte_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pte_t *huge_pte_offset(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812dadf0)
Location: mm/hugetlb.c:5793
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/pagewalk.c:__walk_page_range
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffff812dadf0-ffffffff812daedc: huge_pte_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
pte_t *huge_pte_offset(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:6130
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/pagewalk.c:__walk_page_range
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffff81cbfbaf-ffffffff81cbfbc8: huge_pte_offset.cold (STB_LOCAL)
ffffffff81321e10-ffffffff81321f18: huge_pte_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
pte_t *huge_pte_offset(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:6857
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/pagewalk.c:__walk_page_range
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
```
**Symbols:**

```
ffffffff81e71f2c-ffffffff81e71f45: huge_pte_offset.cold (STB_LOCAL)
ffffffff8138f030-ffffffff8138f152: huge_pte_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
pte_t *huge_pte_offset(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:7196
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/pagewalk.c:__walk_page_range
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
```
**Symbols:**

```
ffffffff820668e9-ffffffff82066902: huge_pte_offset.cold (STB_LOCAL)
ffffffff8140db20-ffffffff8140dc4f: huge_pte_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
pte_t *huge_pte_offset(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:7295
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/pagewalk.c:__walk_page_range
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
```
**Symbols:**

```
ffffffff820e60fe-ffffffff820e6117: huge_pte_offset.cold (STB_LOCAL)
ffffffff81440ed0-ffffffff81441002: huge_pte_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
pte_t *huge_pte_offset(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:7432
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/pagewalk.c:__walk_page_range
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
```
**Symbols:**

```
ffffffff821c325d-ffffffff821c3276: huge_pte_offset.cold (STB_LOCAL)
ffffffff8147b000-ffffffff8147b132: huge_pte_offset (STB_GLOBAL)
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
pte_t *huge_pte_offset(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/hugetlbpage.c (ffff8000100b1008)
Location: arch/arm64/mm/hugetlbpage.c:258
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffff8000100b1008-ffff8000100b1150: huge_pte_offset (STB_GLOBAL)
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
pte_t *huge_pte_offset(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/hugetlbpage.c (c0000000000a5420)
Location: arch/powerpc/mm/hugetlbpage.c:35
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
c0000000000a5420-c0000000000a5460: huge_pte_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
pte_t *huge_pte_offset(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022fba4)
Location: mm/hugetlb.c:5014
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffe00022fba4-ffffffe00022fc4a: huge_pte_offset (STB_GLOBAL)
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
pte_t *huge_pte_offset(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128d300)
Location: mm/hugetlb.c:5014
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffff8128d300-ffffffff8128d45a: huge_pte_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
pte_t *huge_pte_offset(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127f0e0)
Location: mm/hugetlb.c:5014
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffff8127f0e0-ffffffff8127f210: huge_pte_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pte_t *huge_pte_offset(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128b110)
Location: mm/hugetlb.c:5014
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffff8128b110-ffffffff8128b26a: huge_pte_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pte_t *huge_pte_offset(struct mm_struct *mm, long unsigned int addr, long unsigned int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8129af30)
Location: mm/hugetlb.c:5014
Inline: False
Direct callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffff8129af30-ffffffff8129b08a: huge_pte_offset (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int sz</code>
</li>
</ul>
</details>
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
