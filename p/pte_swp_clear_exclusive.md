# Function: <code>pte_swp_clear_exclusive</code>

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
In mm/gup.c (ffffffff813386ca)
Location: arch/x86/include/asm/pgtable.h:1296
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81343aa2)
Location: arch/x86/include/asm/pgtable.h:1296
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mincore.c (ffffffff81349546)
Location: arch/x86/include/asm/pgtable.h:1296
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81353e37)
Location: arch/x86/include/asm/pgtable.h:1296
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81358684)
Location: arch/x86/include/asm/pgtable.h:1296
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8135e7ed)
Location: arch/x86/include/asm/pgtable.h:1296
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81376b97)
Location: arch/x86/include/asm/pgtable.h:1296
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8137c18c)
Location: arch/x86/include/asm/pgtable.h:1296
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff81380a35)
Location: arch/x86/include/asm/pgtable.h:1296
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81390fb8)
Location: arch/x86/include/asm/pgtable.h:1296
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff813b4b8a)
Location: arch/x86/include/asm/pgtable.h:1296
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait_huge
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff813b71f0)
Location: arch/x86/include/asm/pgtable.h:1296
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff813ce844)
Location: arch/x86/include/asm/pgtable.h:1296
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff813d9031)
Location: arch/x86/include/asm/pgtable.h:1296
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff813e447a)
Location: arch/x86/include/asm/pgtable.h:1296
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff813e8467)
Location: arch/x86/include/asm/pgtable.h:1296
Inline: True
```
```
In fs/userfaultfd.c (ffffffff8145da56)
Location: arch/x86/include/asm/pgtable.h:1296
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff814995e0)
Location: arch/x86/include/asm/pgtable.h:1296
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/memory.c (ffffffff813bb184)
Location: arch/x86/include/asm/pgtable.h:1314
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mincore.c (ffffffff813c192f)
Location: arch/x86/include/asm/pgtable.h:1314
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff813ce2e1)
Location: arch/x86/include/asm/pgtable.h:1314
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff813d2dfc)
Location: arch/x86/include/asm/pgtable.h:1314
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff813d964b)
Location: arch/x86/include/asm/pgtable.h:1314
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff813f4361)
Location: arch/x86/include/asm/pgtable.h:1314
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff813f992c)
Location: arch/x86/include/asm/pgtable.h:1314
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff813ff33c)
Location: arch/x86/include/asm/pgtable.h:1314
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff814127cc)
Location: arch/x86/include/asm/pgtable.h:1314
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/ksm.c (ffffffff81421a8c)
Location: arch/x86/include/asm/pgtable.h:1314
Inline: True
```
```
In mm/migrate.c (ffffffff81433d1a)
Location: arch/x86/include/asm/pgtable.h:1314
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait_huge
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff81438c09)
Location: arch/x86/include/asm/pgtable.h:1314
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (ffffffff8145342b)
Location: arch/x86/include/asm/pgtable.h:1314
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8145f025)
Location: arch/x86/include/asm/pgtable.h:1314
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff8146bf51)
Location: arch/x86/include/asm/pgtable.h:1314
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff81470398)
Location: arch/x86/include/asm/pgtable.h:1314
Inline: True
```
```
In fs/userfaultfd.c (ffffffff814ed484)
Location: arch/x86/include/asm/pgtable.h:1314
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152e888)
Location: arch/x86/include/asm/pgtable.h:1314
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/memory.c (ffffffff813f056e)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mincore.c (ffffffff813f67c8)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mprotect.c (ffffffff81402bbe)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff814073a4)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/rmap.c (ffffffff8140dee3)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81427a4e)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8142c7c3)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff81433931)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/swapfile.c:generic_max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81445ddc)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/ksm.c (ffffffff81456834)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate.c (ffffffff814696ec)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8146f49f)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff8147f001)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In mm/memcontrol.c (ffffffff81489164)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81494fd5)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff814a0cac)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814a4bcb)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/userfaultfd.c (ffffffff8152418b)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81566bc9)
Location: arch/x86/include/asm/pgtable.h:1313
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/memory.c (ffffffff8142000e)
Location: arch/x86/include/asm/pgtable.h:1541
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mincore.c (ffffffff81422478)
Location: arch/x86/include/asm/pgtable.h:1541
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mprotect.c (ffffffff8142f1d1)
Location: arch/x86/include/asm/pgtable.h:1541
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81433a14)
Location: arch/x86/include/asm/pgtable.h:1541
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/rmap.c (ffffffff8143a6b8)
Location: arch/x86/include/asm/pgtable.h:1541
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81461262)
Location: arch/x86/include/asm/pgtable.h:1541
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81465f0b)
Location: arch/x86/include/asm/pgtable.h:1541
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff8146cd21)
Location: arch/x86/include/asm/pgtable.h:1541
Inline: True
Inline callers:
  - mm/swapfile.c:generic_max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8147f812)
Location: arch/x86/include/asm/pgtable.h:1541
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff81485151)
Location: arch/x86/include/asm/pgtable.h:1541
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/ksm.c (ffffffff8149132e)
Location: arch/x86/include/asm/pgtable.h:1541
Inline: True
Inline callers:
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate.c (ffffffff8149861c)
Location: arch/x86/include/asm/pgtable.h:1541
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8149dfa8)
Location: arch/x86/include/asm/pgtable.h:1541
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff814afcd9)
Location: arch/x86/include/asm/pgtable.h:1541
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In mm/memcontrol.c (ffffffff814b901d)
Location: arch/x86/include/asm/pgtable.h:1541
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff814c48d5)
Location: arch/x86/include/asm/pgtable.h:1541
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff814d243a)
Location: arch/x86/include/asm/pgtable.h:1541
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814d5bf8)
Location: arch/x86/include/asm/pgtable.h:1541
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/userfaultfd.c (ffffffff815586d7)
Location: arch/x86/include/asm/pgtable.h:1541
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8159d38b)
Location: arch/x86/include/asm/pgtable.h:1541
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_category
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
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
