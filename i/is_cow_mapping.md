# Function: <code>is_cow_mapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: mm/internal.h:257
Inline: True
```
```
In mm/memory.c (ffffffff811c0d7d)
Location: mm/internal.h:257
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/huge_memory.c (0)
Location: mm/internal.h:257
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811d5638)
Location: mm/internal.h:229
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811dc26e)
Location: mm/internal.h:229
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vm_insert_pfn_prot
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/huge_memory.c (ffffffff81213fe8)
Location: mm/internal.h:229
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811e5643)
Location: mm/internal.h:232
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811ebd7d)
Location: mm/internal.h:232
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vm_insert_pfn_prot
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/huge_memory.c (ffffffff812263e3)
Location: mm/internal.h:232
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811efee8)
Location: mm/internal.h:246
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811f6c9d)
Location: mm/internal.h:246
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vm_insert_pfn_prot
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/huge_memory.c (ffffffff812315dd)
Location: mm/internal.h:246
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812072d5)
Location: mm/internal.h:247
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8120f1cd)
Location: mm/internal.h:247
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vm_insert_pfn_prot
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/huge_memory.c (ffffffff8124f753)
Location: mm/internal.h:247
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81227c1e)
Location: mm/internal.h:247
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8122ef4e)
Location: mm/internal.h:247
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vm_insert_pfn_prot
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mprotect.c (ffffffff812391fa)
Location: mm/internal.h:247
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/huge_memory.c (ffffffff812737f5)
Location: mm/internal.h:247
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8123b5f5)
Location: mm/internal.h:247
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812432ce)
Location: mm/internal.h:247
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mprotect.c (ffffffff8124d77e)
Location: mm/internal.h:247
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/huge_memory.c (ffffffff81287b93)
Location: mm/internal.h:247
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124caa3)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812550fe)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mprotect.c (ffffffff8125f78a)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/huge_memory.c (ffffffff812a22d3)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125afd3)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8126366e)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mprotect.c (ffffffff8126df9a)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/huge_memory.c (ffffffff812b3683)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8128983f)
Location: mm/internal.h:295
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81293900)
Location: mm/internal.h:295
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_one_pte
  - mm/memory.c:copy_one_pte
  - mm/memory.c:copy_one_pte
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mprotect.c (ffffffff8129e843)
Location: mm/internal.h:295
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/huge_memory.c (ffffffff812e90c4)
Location: mm/internal.h:295
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81293508)
Location: mm/internal.h:299
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8129e1f9)
Location: mm/internal.h:299
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mprotect.c (ffffffff812a9bf9)
Location: mm/internal.h:299
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/huge_memory.c (ffffffff812f7de2)
Location: mm/internal.h:299
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pud_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81298e9e)
Location: include/linux/mm.h:1329
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812a3910)
Location: include/linux/mm.h:1329
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mprotect.c (ffffffff812af084)
Location: include/linux/mm.h:1329
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff812dcc20)
Location: include/linux/mm.h:1329
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff812fe3d1)
Location: include/linux/mm.h:1329
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pud_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In fs/proc/task_mmu.c (ffffffff813cef91)
Location: include/linux/mm.h:1329
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812d73d0)
Location: include/linux/mm.h:1333
Inline: True
Inline callers:
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff812e4c10)
Location: include/linux/mm.h:1333
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mprotect.c (ffffffff812f087a)
Location: include/linux/mm.h:1333
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff81323e1e)
Location: include/linux/mm.h:1333
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff81347f71)
Location: include/linux/mm.h:1333
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pud_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In fs/proc/task_mmu.c (ffffffff81420471)
Location: include/linux/mm.h:1333
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81336f80)
Location: include/linux/mm.h:1279
Inline: True
Inline callers:
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff8134653b)
Location: include/linux/mm.h:1279
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mprotect.c (ffffffff81353bf6)
Location: include/linux/mm.h:1279
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff813917f8)
Location: include/linux/mm.h:1279
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff813b9b28)
Location: include/linux/mm.h:1279
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In fs/proc/task_mmu.c (ffffffff8149a87a)
Location: include/linux/mm.h:1279
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813ae4ad)
Location: include/linux/mm.h:1367
Inline: True
Inline callers:
  - mm/gup.c:check_vma_flags
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813c00b6)
Location: include/linux/mm.h:1367
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mprotect.c (ffffffff813ce0cb)
Location: include/linux/mm.h:1367
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff81411fc4)
Location: include/linux/mm.h:1367
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff8143f448)
Location: include/linux/mm.h:1367
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pud_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In fs/proc/task_mmu.c (ffffffff8152ed9a)
Location: include/linux/mm.h:1367
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e28f5)
Location: include/linux/mm.h:1551
Inline: True
Inline callers:
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff813f4d4c)
Location: include/linux/mm.h:1551
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mprotect.c (ffffffff81402968)
Location: include/linux/mm.h:1551
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff81445457)
Location: include/linux/mm.h:1551
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff81474bef)
Location: include/linux/mm.h:1551
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/proc/task_mmu.c (ffffffff815670aa)
Location: include/linux/mm.h:1551
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8140d132)
Location: include/linux/mm.h:1605
Inline: True
Inline callers:
  - mm/gup.c:check_vma_flags
```
```
In mm/memory.c (ffffffff814213bc)
Location: include/linux/mm.h:1605
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mprotect.c (ffffffff8142ef86)
Location: include/linux/mm.h:1605
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8147b6de)
Location: include/linux/mm.h:1605
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff814a4025)
Location: include/linux/mm.h:1605
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8159cc1d)
Location: include/linux/mm.h:1605
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffff8000102f258c)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffff8000102fa894)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mprotect.c (ffff8000103051e4)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/huge_memory.c (ffff80001035478c)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0514a18)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (c0517998)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:vm_normal_page
```
```
In mm/mprotect.c (c0523470)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003b8d80)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (c0000000003c4ee8)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mprotect.c (c0000000003d2508)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/huge_memory.c (c00000000043b3d8)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffe000204d00)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffe00020a35a)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffe00021132c)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81253623)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8125bcbe)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mprotect.c (ffffffff812665ea)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/huge_memory.c (ffffffff812abc63)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81246337)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8124e281)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mprotect.c (ffffffff81258cc2)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/huge_memory.c (ffffffff8129d537)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812513c3)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81259a5e)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mprotect.c (ffffffff8126438a)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/huge_memory.c (ffffffff812a9a73)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81260d44)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8126945e)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mprotect.c (ffffffff81273d4a)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/huge_memory.c (ffffffff812b98c6)
Location: mm/internal.h:255
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
</details>
</li>
</ul>

## Differences
