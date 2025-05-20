# Function: <code>huge_pte_lock</code>

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
In mm/hugetlb.c (ffffffff811dd82f)
Location: include/linux/hugetlb.h:543
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/mempolicy.c (ffffffff811dfdea)
Location: include/linux/hugetlb.h:543
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
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
In mm/hugetlb.c (ffffffff811fc423)
Location: include/linux/hugetlb.h:539
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff811febe6)
Location: include/linux/hugetlb.h:539
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
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
In mm/hugetlb.c (ffffffff8120d419)
Location: include/linux/hugetlb.h:539
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81210426)
Location: include/linux/hugetlb.h:539
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
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
In mm/hugetlb.c (ffffffff812192b4)
Location: include/linux/hugetlb.h:607
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8121a956)
Location: include/linux/hugetlb.h:607
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
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
In mm/hugetlb.c (ffffffff81234269)
Location: include/linux/hugetlb.h:601
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81235b96)
Location: include/linux/hugetlb.h:601
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
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
In mm/hugetlb.c (ffffffff81257192)
Location: include/linux/hugetlb.h:614
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8125a5fe)
Location: include/linux/hugetlb.h:614
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
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
In mm/hugetlb.c (ffffffff8126b802)
Location: include/linux/hugetlb.h:625
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8126e47e)
Location: include/linux/hugetlb.h:625
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
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
In mm/hugetlb.c (ffffffff81286afa)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81289ab2)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/hmm.c (ffffffff812c3c96)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/hugetlb.c (ffffffff812966fa)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81299622)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/hmm.c (ffffffff812d59ec)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/hugetlb.c (ffffffff812c9c77)
Location: include/linux/hugetlb.h:903
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff812ce91f)
Location: include/linux/hugetlb.h:903
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/hmm.c (ffffffff8130b659)
Location: include/linux/hugetlb.h:903
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/hugetlb.c (ffffffff812d58b7)
Location: include/linux/hugetlb.h:930
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff812da25f)
Location: include/linux/hugetlb.h:930
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/hmm.c (ffffffff81317519)
Location: include/linux/hugetlb.h:930
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/hugetlb.c (ffffffff812de951)
Location: include/linux/hugetlb.h:1036
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff812e1abf)
Location: include/linux/hugetlb.h:1036
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/hmm.c (ffffffff8131d219)
Location: include/linux/hugetlb.h:1036
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/hugetlb.c (ffffffff81325d30)
Location: include/linux/hugetlb.h:1074
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81328b8f)
Location: include/linux/hugetlb.h:1074
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/hmm.c (ffffffff8136a5a9)
Location: include/linux/hugetlb.h:1074
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/hugetlb.c (ffffffff81394a9e)
Location: include/linux/hugetlb.h:1114
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81397dcf)
Location: include/linux/hugetlb.h:1114
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/hmm.c (ffffffff813e816c)
Location: include/linux/hugetlb.h:1114
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/page_vma_mapped.c (ffffffff813d2f0a)
Location: include/linux/hugetlb.h:1176
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/hugetlb.c (ffffffff8140ddc0)
Location: include/linux/hugetlb.h:1176
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81417a67)
Location: include/linux/hugetlb.h:1176
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/hmm.c (ffffffff8147008c)
Location: include/linux/hugetlb.h:1176
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/page_vma_mapped.c (ffffffff81407b15)
Location: include/linux/hugetlb.h:1203
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/hugetlb.c (ffffffff8144119c)
Location: include/linux/hugetlb.h:1203
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8144afe9)
Location: include/linux/hugetlb.h:1203
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/hmm.c (ffffffff814a485f)
Location: include/linux/hugetlb.h:1203
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/page_vma_mapped.c (ffffffff81434126)
Location: include/linux/hugetlb.h:1226
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/hugetlb.c (ffffffff8147b2cd)
Location: include/linux/hugetlb.h:1226
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff814849e9)
Location: include/linux/hugetlb.h:1226
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/hmm.c (ffffffff814d588f)
Location: include/linux/hugetlb.h:1226
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (ffffffff8159d499)
Location: include/linux/hugetlb.h:1226
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_scan_hugetlb_entry
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
In mm/hugetlb.c (ffff80001033373c)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffff8000103382c4)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/hmm.c (ffff80001037b250)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c00000000040fc54)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (c000000000411064)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/hmm.c (c00000000046fac8)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/hugetlb.c (ffffffe0002310c6)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/hmm.c (ffffffe0002521c2)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/hugetlb.c (ffffffff8128ecda)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81291c02)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/hmm.c (ffffffff812cdfcc)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/hugetlb.c (ffffffff81280a5d)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81283882)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/hmm.c (ffffffff812bee39)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/hugetlb.c (ffffffff8128caea)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8128fa12)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/hmm.c (ffffffff812cbddc)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/hugetlb.c (ffffffff8129c8ba)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8129e262)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/hmm.c (ffffffff812dcb3a)
Location: include/linux/hugetlb.h:745
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
</details>
</li>
</ul>

## Differences
