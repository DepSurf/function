# Function: <code>userfaultfd_wp</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81294d8a)
Location: include/linux/userfaultfd_k.h:60
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
```
```
In mm/userfaultfd.c (ffffffff8130908a)
Location: include/linux/userfaultfd_k.h:60
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
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
In mm/memory.c (ffffffff8129f603)
Location: include/linux/userfaultfd_k.h:60
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
```
```
In mm/userfaultfd.c (ffffffff81314ed2)
Location: include/linux/userfaultfd_k.h:60
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
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
In mm/memory.c (ffffffff812a4607)
Location: include/linux/userfaultfd_k.h:97
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/huge_memory.c (ffffffff812fea8b)
Location: include/linux/userfaultfd_k.h:97
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/userfaultfd.c (ffffffff8131b60f)
Location: include/linux/userfaultfd_k.h:97
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
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
In mm/memory.c (ffffffff812e58d9)
Location: include/linux/userfaultfd_k.h:102
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/huge_memory.c (ffffffff8134868a)
Location: include/linux/userfaultfd_k.h:102
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/userfaultfd.c (ffffffff813688de)
Location: include/linux/userfaultfd_k.h:102
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
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
In mm/gup.c (ffffffff81338876)
Location: include/linux/userfaultfd_k.h:119
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81347bf4)
Location: include/linux/userfaultfd_k.h:119
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/rmap.c (ffffffff8135d83a)
Location: include/linux/userfaultfd_k.h:119
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81392bdd)
Location: include/linux/userfaultfd_k.h:119
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff813bccbf)
Location: include/linux/userfaultfd_k.h:119
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff813c3cce)
Location: include/linux/userfaultfd_k.h:119
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/userfaultfd.c (ffffffff813e61fd)
Location: include/linux/userfaultfd_k.h:119
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
```
```
In fs/userfaultfd.c (ffffffff8145ebb4)
Location: include/linux/userfaultfd_k.h:119
Inline: True
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
In mm/gup.c (ffffffff813b003f)
Location: include/linux/userfaultfd_k.h:119
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813bffd5)
Location: include/linux/userfaultfd_k.h:119
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mmap.c (ffffffff813c8b54)
Location: include/linux/userfaultfd_k.h:119
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/mprotect.c (ffffffff813cdd7a)
Location: include/linux/userfaultfd_k.h:119
Inline: True
Inline callers:
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/rmap.c (ffffffff813d869a)
Location: include/linux/userfaultfd_k.h:119
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81411580)
Location: include/linux/userfaultfd_k.h:119
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff8143f2e5)
Location: include/linux/userfaultfd_k.h:119
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:can_change_pmd_writable
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81447d04)
Location: include/linux/userfaultfd_k.h:119
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/userfaultfd.c (ffffffff8146dcbd)
Location: include/linux/userfaultfd_k.h:119
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
```
```
In fs/userfaultfd.c (ffffffff814ee765)
Location: include/linux/userfaultfd_k.h:119
Inline: True
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
In mm/gup.c (ffffffff813e466b)
Location: include/linux/userfaultfd_k.h:132
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813f4c8b)
Location: include/linux/userfaultfd_k.h:132
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mmap.c (ffffffff813fcdea)
Location: include/linux/userfaultfd_k.h:132
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/mprotect.c (ffffffff81403a29)
Location: include/linux/userfaultfd_k.h:132
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_p4d_range
  - mm/mprotect.c:change_p4d_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/rmap.c (ffffffff8140ce87)
Location: include/linux/userfaultfd_k.h:132
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81444a4b)
Location: include/linux/userfaultfd_k.h:132
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff81474a8d)
Location: include/linux/userfaultfd_k.h:132
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:can_change_pmd_writable
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8147d6b0)
Location: include/linux/userfaultfd_k.h:132
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/userfaultfd.c (ffffffff814a26e9)
Location: include/linux/userfaultfd_k.h:132
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
```
```
In fs/userfaultfd.c (ffffffff815256e8)
Location: include/linux/userfaultfd_k.h:132
Inline: True
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
In mm/gup.c (ffffffff8140f013)
Location: include/linux/userfaultfd_k.h:147
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff814212f2)
Location: include/linux/userfaultfd_k.h:147
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mmap.c (ffffffff814297ba)
Location: include/linux/userfaultfd_k.h:147
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/mprotect.c (ffffffff8142ffa9)
Location: include/linux/userfaultfd_k.h:147
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_p4d_range
  - mm/mprotect.c:change_p4d_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/rmap.c (ffffffff81439579)
Location: include/linux/userfaultfd_k.h:147
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8147eaad)
Location: include/linux/userfaultfd_k.h:147
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff814a4201)
Location: include/linux/userfaultfd_k.h:147
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:can_change_pmd_writable
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814acbbf)
Location: include/linux/userfaultfd_k.h:147
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/userfaultfd.c (ffffffff814d27a8)
Location: include/linux/userfaultfd_k.h:147
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
```
```
In fs/userfaultfd.c (ffffffff81559b80)
Location: include/linux/userfaultfd_k.h:147
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unregister
```
```
In fs/proc/task_mmu.c (ffffffff8159a87d)
Location: include/linux/userfaultfd_k.h:147
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_scan_test_walk
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
