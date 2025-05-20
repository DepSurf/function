# Function: <code>is_pte_marker_entry</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8134329b)
Location: include/linux/swapops.h:303
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff8134950a)
Location: include/linux/swapops.h:303
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:303
Inline: True
```
```
In mm/rmap.c (ffffffff8135d9f8)
Location: include/linux/swapops.h:303
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81390ea9)
Location: include/linux/swapops.h:303
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/memcontrol.c (ffffffff813ce873)
Location: include/linux/swapops.h:303
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff813e44a9)
Location: include/linux/swapops.h:303
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff813e8496)
Location: include/linux/swapops.h:303
Inline: True
```
```
In fs/userfaultfd.c (ffffffff8145da80)
Location: include/linux/swapops.h:303
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff814995ca)
Location: include/linux/swapops.h:303
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
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
In mm/shmem.c (ffffffff8138c4a8)
Location: include/linux/swapops.h:413
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/memory.c (ffffffff813bb1c6)
Location: include/linux/swapops.h:413
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff813c18f2)
Location: include/linux/swapops.h:413
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:413
Inline: True
```
```
In mm/rmap.c (ffffffff813d8869)
Location: include/linux/swapops.h:413
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (0)
Location: include/linux/swapops.h:413
Inline: True
```
```
In mm/hugetlb.c (ffffffff81412786)
Location: include/linux/swapops.h:413
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/memcontrol.c (ffffffff81453454)
Location: include/linux/swapops.h:413
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff8146bf7a)
Location: include/linux/swapops.h:413
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814703c1)
Location: include/linux/swapops.h:413
Inline: True
```
```
In fs/userfaultfd.c (ffffffff814ed4ad)
Location: include/linux/swapops.h:413
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152e872)
Location: include/linux/swapops.h:413
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
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
In mm/shmem.c (ffffffff813bea9e)
Location: include/linux/swapops.h:404
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/memory.c (ffffffff813efebc)
Location: include/linux/swapops.h:404
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff813f678b)
Location: include/linux/swapops.h:404
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:404
Inline: True
```
```
In mm/rmap.c (ffffffff8140d0a2)
Location: include/linux/swapops.h:404
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (0)
Location: include/linux/swapops.h:404
Inline: True
```
```
In mm/hugetlb.c (ffffffff81445d8b)
Location: include/linux/swapops.h:404
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/khugepaged.c (ffffffff8147f046)
Location: include/linux/swapops.h:404
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In mm/memcontrol.c (ffffffff8148918d)
Location: include/linux/swapops.h:404
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff814a0cd5)
Location: include/linux/swapops.h:404
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814a4b95)
Location: include/linux/swapops.h:404
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/userfaultfd.c (ffffffff815241b4)
Location: include/linux/swapops.h:404
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81566b80)
Location: include/linux/swapops.h:404
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
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
In mm/shmem.c (ffffffff813e9ab0)
Location: include/linux/swapops.h:409
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/memory.c (ffffffff8141b458)
Location: include/linux/swapops.h:409
Inline: True
Inline callers:
  - mm/memory.c:set_pte_range
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff8142243b)
Location: include/linux/swapops.h:409
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:409
Inline: True
```
```
In mm/rmap.c (ffffffff8143986c)
Location: include/linux/swapops.h:409
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (0)
Location: include/linux/swapops.h:409
Inline: True
```
```
In mm/hugetlb.c (ffffffff8147f7c3)
Location: include/linux/swapops.h:409
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/khugepaged.c (ffffffff814afd1e)
Location: include/linux/swapops.h:409
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In mm/memcontrol.c (ffffffff814b9046)
Location: include/linux/swapops.h:409
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff814d245d)
Location: include/linux/swapops.h:409
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814d5bc2)
Location: include/linux/swapops.h:409
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/userfaultfd.c (ffffffff81558701)
Location: include/linux/swapops.h:409
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8159d363)
Location: include/linux/swapops.h:409
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_category
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
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
