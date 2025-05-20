# Function: <code>pte_present</code>

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
In arch/x86/xen/mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:463
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:463
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff8106aebc)
Location: arch/x86/include/asm/pgtable.h:463
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
```
```
In mm/gup.c (ffffffff811ba4a1)
Location: arch/x86/include/asm/pgtable.h:463
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811bd91c)
Location: arch/x86/include/asm/pgtable.h:463
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811c2820)
Location: arch/x86/include/asm/pgtable.h:463
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (0)
Location: arch/x86/include/asm/pgtable.h:463
Inline: True
```
```
In mm/mprotect.c (ffffffff811c893b)
Location: arch/x86/include/asm/pgtable.h:463
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/pgtable.h:463
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:463
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:463
Inline: True
```
```
In mm/madvise.c (ffffffff811d1534)
Location: arch/x86/include/asm/pgtable.h:463
Inline: True
Inline callers:
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/hugetlb.c (ffffffff811db0c0)
Location: arch/x86/include/asm/pgtable.h:463
Inline: True
Inline callers:
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/pgtable.h:463
Inline: True
```
```
In mm/migrate.c (ffffffff811f0c86)
Location: arch/x86/include/asm/pgtable.h:463
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff811f4ac5)
Location: arch/x86/include/asm/pgtable.h:463
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff811fa891)
Location: arch/x86/include/asm/pgtable.h:463
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff81276a88)
Location: arch/x86/include/asm/pgtable.h:463
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In arch/x86/xen/mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff81069fc2)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
```
```
In mm/gup.c (ffffffff811d48f3)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811dae9a)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811de3f9)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (0)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
```
```
In mm/mprotect.c (ffffffff811e4bf9)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
```
```
In mm/madvise.c (ffffffff811eebb3)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/hugetlb.c (ffffffff811fcc1b)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
```
```
In mm/migrate.c (ffffffff812117c9)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff8121bc4d)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8121e7a3)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff812a47c8)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In arch/x86/xen/mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff8106db62)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
```
```
In mm/gup.c (ffffffff811e493c)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811eaaa7)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811ee205)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (0)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
```
```
In mm/mprotect.c (ffffffff811f4c22)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f5d2f)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff811f6b92)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
```
```
In mm/madvise.c (ffffffff811ff4f2)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/hugetlb.c (ffffffff8120d6fb)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
```
```
In mm/migrate.c (ffffffff81223989)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff8122e5f8)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff81230dd3)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff812ba148)
Location: arch/x86/include/asm/pgtable.h:492
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/pgtable.h:631
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:631
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff8106d89f)
Location: arch/x86/include/asm/pgtable.h:631
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
```
```
In mm/gup.c (ffffffff811eef7c)
Location: arch/x86/include/asm/pgtable.h:631
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811f5aed)
Location: arch/x86/include/asm/pgtable.h:631
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811f9210)
Location: arch/x86/include/asm/pgtable.h:631
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (0)
Location: arch/x86/include/asm/pgtable.h:631
Inline: True
```
```
In mm/mprotect.c (ffffffff811ffadd)
Location: arch/x86/include/asm/pgtable.h:631
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81200b1d)
Location: arch/x86/include/asm/pgtable.h:631
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81201a72)
Location: arch/x86/include/asm/pgtable.h:631
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:631
Inline: True
```
```
In mm/madvise.c (ffffffff8120a1b4)
Location: arch/x86/include/asm/pgtable.h:631
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/hugetlb.c (ffffffff8121956d)
Location: arch/x86/include/asm/pgtable.h:631
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/pgtable.h:631
Inline: True
```
```
In mm/migrate.c (ffffffff8122f2e9)
Location: arch/x86/include/asm/pgtable.h:631
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff8123972c)
Location: arch/x86/include/asm/pgtable.h:631
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8123c633)
Location: arch/x86/include/asm/pgtable.h:631
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff812c7898)
Location: arch/x86/include/asm/pgtable.h:631
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In arch/x86/xen/mmu_pv.c (ffffffff826ad065)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff8198c247)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/fault.c (ffffffff810722e3)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In mm/gup.c (ffffffff81206038)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8120d5c0)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff81211617)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff81212421)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/mprotect.c (ffffffff81218211)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81219549)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8121a4c5)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/vmalloc.c (ffffffff8121f81f)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff81223474)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81226071)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - mm/swap_state.c:do_swap_page_readahead
```
```
In mm/hugetlb.c (ffffffff8123542f)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff812374a1)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8124b7dc)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff81258d9d)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff8125c2b3)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff8126e6ca)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff812eb4a5)
Location: arch/x86/include/asm/pgtable.h:646
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff826d63c3)
Location: arch/x86/include/asm/pgtable.h:688
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff819e8c0b)
Location: arch/x86/include/asm/pgtable.h:688
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/fault.c (ffffffff8107532d)
Location: arch/x86/include/asm/pgtable.h:688
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In mm/gup.c (ffffffff81226361)
Location: arch/x86/include/asm/pgtable.h:688
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81229ae9)
Location: arch/x86/include/asm/pgtable.h:688
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:handle_pte_fault
```
```
In mm/mincore.c (ffffffff8123238b)
Location: arch/x86/include/asm/pgtable.h:688
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff8123317e)
Location: arch/x86/include/asm/pgtable.h:688
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/mprotect.c (ffffffff81239196)
Location: arch/x86/include/asm/pgtable.h:688
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8123ade9)
Location: arch/x86/include/asm/pgtable.h:688
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8123c78c)
Location: arch/x86/include/asm/pgtable.h:688
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/vmalloc.c (ffffffff81240f9c)
Location: arch/x86/include/asm/pgtable.h:688
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff812462f0)
Location: arch/x86/include/asm/pgtable.h:688
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81248627)
Location: arch/x86/include/asm/pgtable.h:688
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/hugetlb.c (ffffffff81258372)
Location: arch/x86/include/asm/pgtable.h:688
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8125a626)
Location: arch/x86/include/asm/pgtable.h:688
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8126e4ad)
Location: arch/x86/include/asm/pgtable.h:688
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff8127cec2)
Location: arch/x86/include/asm/pgtable.h:688
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff8127fbb5)
Location: arch/x86/include/asm/pgtable.h:688
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81288b7a)
Location: arch/x86/include/asm/pgtable.h:688
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/hmm.c (ffffffff81293513)
Location: arch/x86/include/asm/pgtable.h:688
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813187d8)
Location: arch/x86/include/asm/pgtable.h:688
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff8288c30e)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff81a24494)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/fault.c (ffffffff8107b12d)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In mm/gup.c (ffffffff8123a6bd)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8123cff8)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mincore.c (ffffffff81245b5e)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff8124694c)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/mprotect.c (ffffffff8124d8ef)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124efe9)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81250b97)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/vmalloc.c (ffffffff81254cac)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8125a710)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8125cbfd)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/hugetlb.c (ffffffff8126ca42)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8126e4a6)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8128333b)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff81291a2c)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff81294525)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8129d87d)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/hmm.c (ffffffff812a7a6e)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8132fa38)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff828a37b8)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff81a945e7)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:set_pte_init
```
```
In arch/x86/mm/fault.c (ffffffff8107ea82)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In mm/gup.c (ffffffff8124b9e0)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124ec73)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mincore.c (ffffffff81257cbb)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff81258be8)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/mprotect.c (ffffffff8125f72b)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8126134b)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81262e77)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/vmalloc.c (ffffffff8126705c)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff812757ed)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81277dda)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8127b0d7)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81287e6d)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff81289adb)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8129f3b6)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff812abdd5)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812b07e5)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812b8b56)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812c3cfa)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (ffffffff81357898)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff828a6856)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff81acbec7)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:set_pte_init
```
```
In arch/x86/mm/fault.c (ffffffff8107fb12)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In mm/gup.c (ffffffff81259ed0)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125d238)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mincore.c (ffffffff812661cb)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff812670b8)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/mprotect.c (ffffffff8126df3b)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8126faee)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81271627)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/vmalloc.c (ffffffff8127595c)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff812847bd)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812878ca)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8128abb7)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81297a6d)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8129964b)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812aea8e)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff812bdeec)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812c2245)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812caa36)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812d5a55)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (ffffffff8136fac8)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff82ccc41d)
Location: arch/x86/include/asm/pgtable.h:766
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/mm/init_64.c (ffffffff81bc3b31)
Location: arch/x86/include/asm/pgtable.h:766
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pte_table
  - arch/x86/mm/init_64.c:set_pte_init
```
```
In arch/x86/mm/fault.c (ffffffff81086d22)
Location: arch/x86/include/asm/pgtable.h:766
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In mm/gup.c (ffffffff812883c8)
Location: arch/x86/include/asm/pgtable.h:766
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8128d840)
Location: arch/x86/include/asm/pgtable.h:766
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_one_pte
```
```
In mm/mincore.c (ffffffff81296510)
Location: arch/x86/include/asm/pgtable.h:766
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff81296a71)
Location: arch/x86/include/asm/pgtable.h:766
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec_fill
```
```
In mm/mprotect.c (ffffffff8129e724)
Location: arch/x86/include/asm/pgtable.h:766
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812a011a)
Location: arch/x86/include/asm/pgtable.h:766
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812a18e7)
Location: arch/x86/include/asm/pgtable.h:766
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/vmalloc.c (ffffffff812a736a)
Location: arch/x86/include/asm/pgtable.h:766
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff812b6966)
Location: arch/x86/include/asm/pgtable.h:766
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812b984b)
Location: arch/x86/include/asm/pgtable.h:766
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff812bd8e6)
Location: arch/x86/include/asm/pgtable.h:766
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff812cb103)
Location: arch/x86/include/asm/pgtable.h:766
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff812ce94c)
Location: arch/x86/include/asm/pgtable.h:766
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812e4180)
Location: arch/x86/include/asm/pgtable.h:766
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff812f37a3)
Location: arch/x86/include/asm/pgtable.h:766
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812f911e)
Location: arch/x86/include/asm/pgtable.h:766
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8130087a)
Location: arch/x86/include/asm/pgtable.h:766
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff8130b6b9)
Location: arch/x86/include/asm/pgtable.h:766
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (ffffffff813b6f68)
Location: arch/x86/include/asm/pgtable.h:766
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In arch/x86/xen/mmu_pv.c (ffffffff82fb825b)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/mm/init_64.c (ffffffff81c3ca4b)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pte_table
  - arch/x86/mm/init_64.c:set_pte_init
```
```
In arch/x86/mm/fault.c (ffffffff81088602)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In kernel/events/core.c (ffffffff8123cbd5)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff812920a8)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129fcf2)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff812a1483)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff812a18e1)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec_fill
```
```
In mm/mprotect.c (ffffffff812a9ae4)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812ab577)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812ad1a4)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
  - mm/page_vma_mapped.c:map_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/vmalloc.c (ffffffff812b25ea)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff812c2bb6)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812c52b4)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff812c9406)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff812d6d13)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff812da28c)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812f01b5)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff812fef80)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff81304faf)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8130ca1a)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff81317581)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (ffffffff813c8608)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In arch/x86/xen/mmu_pv.c (ffffffff831c28c6)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/mm/init_64.c (ffffffff81c2f05f)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:set_pte_init
```
```
In arch/x86/mm/fault.c (ffffffff81089274)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In kernel/events/core.c (ffffffff81243eea)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff81297c74)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812a556c)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff812a6c7a)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff812a70a1)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec_fill
```
```
In mm/mprotect.c (ffffffff812aef6f)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812b097a)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812b2907)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/vmalloc.c (ffffffff812b8d28)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff812c9a32)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812cbf62)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff812cff88)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff812ddf43)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff812e1aec)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812f588f)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff81305b8c)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff8130a43f)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8131318a)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff8131d281)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (ffffffff813cf648)
Location: arch/x86/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In arch/x86/xen/mmu_pv.c (ffffffff832a32d2)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/mm/init_64.c (ffffffff81d4d760)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:set_pte_init
```
```
In arch/x86/mm/fault.c (ffffffff810986cb)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In kernel/events/core.c (ffffffff8127e85a)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff812d86b4)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812e6a63)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff812e815a)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff812e8590)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec_fill
```
```
In mm/mprotect.c (ffffffff812f075f)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812f230a)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812f452c)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812f8bff)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
```
```
In mm/vmalloc.c (ffffffff812fb2dc)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_range_noflush
```
```
In mm/madvise.c (ffffffff8130ea52)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81311132)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff81315499)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81325153)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff81328bc7)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8133fe5b)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff8134f9f6)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff81355b9f)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8135eb25)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff8136a61c)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (ffffffff81420a28)
Location: arch/x86/include/asm/pgtable.h:736
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In arch/x86/xen/mmu_pv.c (ffffffff83452541)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/mm/init_64.c (ffffffff81f1d482)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:set_pte_init
```
```
In arch/x86/mm/fault.c (ffffffff810ab324)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In kernel/events/core.c (ffffffff812d34c7)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff81338619)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8133d8e2)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_set_pte
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff813494b2)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff8134c6c4)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff81353e05)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff813560ae)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff813584f7)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8135f1e3)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff813627e4)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/madvise.c (ffffffff81376880)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8137c167)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff81380a10)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81393aa0)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff81397e07)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff813b49c7)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff813b73f4)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff813c7cca)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff813ce7b8)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff813d8fa5)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff813e4454)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff813e81df)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (ffffffff8145da39)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81499908)
Location: arch/x86/include/asm/pgtable.h:734
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_soft_dirty
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
In arch/x86/xen/mmu_pv.c (ffffffff83e6fb0f)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/mm/init_64.c (ffffffff820c5809)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/fault.c (ffffffff810c36df)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In kernel/events/core.c (ffffffff8133b745)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff81378232)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
```
```
In mm/gup.c (ffffffff813afe5d)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813b6906)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_set_pte
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff813c18a1)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff813c524c)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff813ce033)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff813d06f0)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff813d2b38)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff813da09b)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff813de180)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/madvise.c (ffffffff813f41ee)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff813f9907)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff813ff317)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8140e708)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff81417a8e)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81421a25)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
```
```
In mm/migrate.c (ffffffff81433b17)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff81438f1d)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff8144beb4)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff81453201)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8145ef95)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff8146bf2c)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814700ed)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (ffffffff814ed46a)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152db18)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6614)
Location: arch/x86/include/asm/pgtable.h:751
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
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
In arch/x86/xen/mmu_pv.c (ffffffff836908c9)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/mm/init_64.c (ffffffff82149879)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/fault.c (ffffffff810c6f28)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In kernel/events/core.c (ffffffff8136d104)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813aba82)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
```
```
In mm/gup.c (ffffffff813e44a0)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813eb2a9)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff813f673a)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mlock.c (ffffffff813f9675)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff814028d2)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81404bd1)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff8140737b)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/rmap.c (ffffffff8140e7de)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff814129da)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/madvise.c (ffffffff81427874)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8142c79a)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff814321fb)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81441aae)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8144b011)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/ksm.c (ffffffff8145679d)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate.c (ffffffff81469592)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff8146f761)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff814816dd)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff81488e60)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81494f45)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff814a0c87)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814a48c3)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/userfaultfd.c (ffffffff81524160)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81565f48)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
```
In fs/hugetlbfs/inode.c (ffffffff8162e6da)
Location: arch/x86/include/asm/pgtable.h:752
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
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
In arch/x86/xen/mmu_pv.c (ffffffff838c0399)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/mm/init_64.c (ffffffff8222c339)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/fault.c (ffffffff810cf3c2)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In kernel/events/core.c (ffffffff81396344)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813d61a2)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
```
```
In mm/gup.c (ffffffff8140ecc2)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff814152d3)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:set_pte_range
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff814223ea)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mlock.c (ffffffff81425218)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff8142ef05)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff814311b5)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff814339eb)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/rmap.c (ffffffff8143afea)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8143f44a)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/madvise.c (ffffffff81461052)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81465ee6)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff8146b5eb)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8147bd1e)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff81484a11)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/ksm.c (ffffffff8149121e)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate.c (ffffffff814984d4)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff8149d310)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff814b0678)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff814b8d80)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff814c4845)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff814d2b5e)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814d58f3)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/userfaultfd.c (ffffffff815586ab)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8159df18)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_category
  - fs/proc/task_mmu.c:make_uffd_wp_pte
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
```
In fs/hugetlbfs/inode.c (ffffffff81667baa)
Location: arch/x86/include/asm/pgtable.h:967
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/pgtable.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
```
```
In arch/powerpc/mm/book3s64/hash_utils.c (c00000000008d5c0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_utils.c:hash_page_mm
```
```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000eebe74)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable
```
```
In arch/powerpc/mm/hugetlbpage.c (c0000000000a62c0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:follow_huge_pd
```
```
In arch/powerpc/kvm/book3s_64_vio_hv.c (c000000000118e60)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_64_vio_hv.c:kvmppc_rm_h_put_tce_indirect
```
```
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c00000000011caf8)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_get_hpa
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:real_vmalloc_addr
```
```
In arch/powerpc/perf/callchain.c (c000000000125000)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
Inline callers:
  - arch/powerpc/perf/callchain.c:read_user_stack_slow
```
```
In mm/gup.c (c0000000003b7750)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003bb1d0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (c0000000003c86f4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (c0000000003c9af4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/mprotect.c (c0000000003d21e4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d3784)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
```
```
In mm/page_vma_mapped.c (c0000000003d5bf0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/vmalloc.c (c0000000003dbbf4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_page_range
```
```
In mm/madvise.c (c0000000003f3110)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (c0000000003f7e50)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (c0000000003fc250)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (c0000000004104d0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (c0000000004110a4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (c0000000004344d0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (c00000000044a25c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (c000000000450d14)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (c00000000045ec04)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/hmm.c (c00000000046fb6c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (c00000000054c7d4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:556
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In arch/riscv/mm/init.c (0)
Location: arch/riscv/include/asm/pgtable.h:204
Inline: True
```
```
In arch/riscv/mm/fault.c (ffffffe0000b9e1a)
Location: arch/riscv/include/asm/pgtable.h:204
Inline: True
Inline callers:
  - arch/riscv/mm/fault.c:do_page_fault
```
```
In mm/shmem.c (ffffffe0001ee3e0)
Location: arch/riscv/include/asm/pgtable.h:204
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffe000204666)
Location: arch/riscv/include/asm/pgtable.h:204
Inline: True
```
```
In mm/memory.c (ffffffe000206786)
Location: arch/riscv/include/asm/pgtable.h:204
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffe00020bb8c)
Location: arch/riscv/include/asm/pgtable.h:204
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffe00020c854)
Location: arch/riscv/include/asm/pgtable.h:204
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/mprotect.c (ffffffe00021122c)
Location: arch/riscv/include/asm/pgtable.h:204
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffe000211c46)
Location: arch/riscv/include/asm/pgtable.h:204
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffe000212736)
Location: arch/riscv/include/asm/pgtable.h:204
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffe0002141e2)
Location: arch/riscv/include/asm/pgtable.h:204
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffe000215238)
Location: arch/riscv/include/asm/pgtable.h:204
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffe000220594)
Location: arch/riscv/include/asm/pgtable.h:204
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffe00022338c)
Location: arch/riscv/include/asm/pgtable.h:204
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffe00022647c)
Location: arch/riscv/include/asm/pgtable.h:204
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffe000231f04)
Location: arch/riscv/include/asm/pgtable.h:204
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (0)
Location: arch/riscv/include/asm/pgtable.h:204
Inline: True
```
```
In mm/ksm.c (ffffffe0002349b0)
Location: arch/riscv/include/asm/pgtable.h:204
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffe00023f6d8)
Location: arch/riscv/include/asm/pgtable.h:204
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/memcontrol.c (ffffffe000241c3a)
Location: arch/riscv/include/asm/pgtable.h:204
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffe000250580)
Location: arch/riscv/include/asm/pgtable.h:204
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffe0002521f6)
Location: arch/riscv/include/asm/pgtable.h:204
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffe0002b2dc0)
Location: arch/riscv/include/asm/pgtable.h:204
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffe0002d2e12)
Location: arch/riscv/include/asm/pgtable.h:204
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffe0008b31ba)
Location: arch/riscv/include/asm/pgtable.h:204
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/xen/mmu_pv.c (ffffffff8289485f)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff81a6ad37)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:set_pte_init
```
```
In arch/x86/mm/fault.c (ffffffff8107eb12)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In mm/gup.c (ffffffff81252520)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81255888)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mincore.c (ffffffff8125e81b)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff8125f708)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/mprotect.c (ffffffff8126658b)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8126813e)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81269c77)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/vmalloc.c (ffffffff8126dfac)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8127ce0d)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8127fe61)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81283197)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8129004d)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff81291c2b)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a706e)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff812b64cc)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812ba825)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812c3016)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812ce035)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (ffffffff813680a8)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In arch/x86/mm/init_64.c (ffffffff81a271c4)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:set_pte_init
```
```
In arch/x86/mm/fault.c (ffffffff8106de5f)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In mm/gup.c (ffffffff81245282)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81247f35)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff81250c38)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff81251b28)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/mprotect.c (ffffffff81258e0b)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8125a36a)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8125beda)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/vmalloc.c (ffffffff8125ff7b)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8126ebfa)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81271ca3)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81274c80)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81281d04)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff812838aa)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff81298aa3)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff812a7676)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812ab9e5)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812b4093)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/hmm.c (ffffffff812beea6)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (ffffffff81358998)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff828a7856)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff81ad7147)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:set_pte_init
```
```
In arch/x86/mm/fault.c (ffffffff8107eac2)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In mm/gup.c (ffffffff812502c0)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81253628)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mincore.c (ffffffff8125c5bb)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff8125d4a8)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/mprotect.c (ffffffff8126432b)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81265ede)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81267a17)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/vmalloc.c (ffffffff8126bd4c)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8127abad)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8127dcba)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81280fa7)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8128de5d)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8128fa3b)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a4e7e)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff812b42dc)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812b8635)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812c0e26)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812cbe45)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (ffffffff81365b78)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff828a785c)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff81ae3607)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:set_pte_init
```
```
In arch/x86/mm/fault.c (ffffffff81080bb2)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In mm/gup.c (ffffffff8125fc4d)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81263014)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mincore.c (ffffffff8126bfa4)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff8126ce8e)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/mprotect.c (ffffffff81273ceb)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81275880)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812773ad)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/vmalloc.c (ffffffff8127b75c)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8128a78e)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8128d86a)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81290cb7)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8129dc0d)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8129e28b)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812b59da)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/khugepaged.c (ffffffff812c47ac)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812c8c75)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812d18e6)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812dcba3)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (ffffffff81379208)
Location: arch/x86/include/asm/pgtable.h:730
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
</details>
</li>
</ul>

## Differences
