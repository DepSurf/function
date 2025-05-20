# Function: <code>ptlock_ptr</code>

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
In arch/x86/xen/mmu.c (ffffffff810203b9)
Location: include/linux/mm.h:1546
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/mm.h:1546
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:1546
Inline: True
```
```
In mm/memory.c (ffffffff811bbc1d)
Location: include/linux/mm.h:1546
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (ffffffff811c27d2)
Location: include/linux/mm.h:1546
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811c87be)
Location: include/linux/mm.h:1546
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811c95b0)
Location: include/linux/mm.h:1546
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811ca9d5)
Location: include/linux/mm.h:1546
Inline: True
Inline callers:
  - mm/rmap.c:__page_check_address
  - mm/rmap.c:__page_check_address
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/mm.h:1546
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/mm.h:1546
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:1546
Inline: True
```
```
In mm/hugetlb.c (ffffffff811dd952)
Location: include/linux/mm.h:1546
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_huge_pmd
```
```
In mm/mempolicy.c (ffffffff811dfee6)
Location: include/linux/mm.h:1546
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:1546
Inline: True
```
```
In mm/migrate.c (ffffffff811f0c3e)
Location: include/linux/mm.h:1546
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff811f67a3)
Location: include/linux/mm.h:1546
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:page_check_address_pmd
```
```
In mm/memcontrol.c (ffffffff811fb036)
Location: include/linux/mm.h:1546
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:1546
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8127835d)
Location: include/linux/mm.h:1546
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/x86/xen/mmu.c (ffffffff8102039f)
Location: include/linux/mm.h:1662
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/mm.h:1662
Inline: True
```
```
In mm/gup.c (ffffffff8122ec3f)
Location: include/linux/mm.h:1662
Inline: True
```
```
In mm/memory.c (ffffffff811daef6)
Location: include/linux/mm.h:1662
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (0)
Location: include/linux/mm.h:1662
Inline: True
```
```
In mm/mprotect.c (ffffffff811e4a7a)
Location: include/linux/mm.h:1662
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e5997)
Location: include/linux/mm.h:1662
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811e7868)
Location: include/linux/mm.h:1662
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:__page_check_address
  - mm/rmap.c:__page_check_address
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/mm.h:1662
Inline: True
```
```
In mm/madvise.c (ffffffff811eeb62)
Location: include/linux/mm.h:1662
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:1662
Inline: True
```
```
In mm/hugetlb.c (ffffffff811fded6)
Location: include/linux/mm.h:1662
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff811feca2)
Location: include/linux/mm.h:1662
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:1662
Inline: True
```
```
In mm/migrate.c (ffffffff81211a12)
Location: include/linux/mm.h:1662
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812155f3)
Location: include/linux/mm.h:1662
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (0)
Location: include/linux/mm.h:1662
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:1662
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:1662
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:1662
Inline: True
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
In arch/x86/xen/mmu.c (ffffffff81020a5c)
Location: include/linux/mm.h:1636
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/mm.h:1636
Inline: True
```
```
In mm/gup.c (ffffffff812411ad)
Location: include/linux/mm.h:1636
Inline: True
```
```
In mm/memory.c (ffffffff811eab0e)
Location: include/linux/mm.h:1636
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (0)
Location: include/linux/mm.h:1636
Inline: True
```
```
In mm/mprotect.c (ffffffff811f4a6e)
Location: include/linux/mm.h:1636
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f5be7)
Location: include/linux/mm.h:1636
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff811f7144)
Location: include/linux/mm.h:1636
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/mm.h:1636
Inline: True
```
```
In mm/rmap.c (ffffffff811f8c0d)
Location: include/linux/mm.h:1636
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:__page_check_address
  - mm/rmap.c:__page_check_address
```
```
In mm/madvise.c (ffffffff811ff4a2)
Location: include/linux/mm.h:1636
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:1636
Inline: True
```
```
In mm/hugetlb.c (ffffffff8120e9bf)
Location: include/linux/mm.h:1636
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff812104ed)
Location: include/linux/mm.h:1636
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:1636
Inline: True
```
```
In mm/migrate.c (ffffffff81223bd3)
Location: include/linux/mm.h:1636
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81227c82)
Location: include/linux/mm.h:1636
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (0)
Location: include/linux/mm.h:1636
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:1636
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:1636
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:1636
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:1636
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff81020cf1)
Location: include/linux/mm.h:1689
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/mm.h:1689
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/mm.h:1689
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:1689
Inline: True
```
```
In mm/memory.c (ffffffff811f1bc9)
Location: include/linux/mm.h:1689
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (0)
Location: include/linux/mm.h:1689
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/mm.h:1689
Inline: True
```
```
In mm/mremap.c (ffffffff812009c1)
Location: include/linux/mm.h:1689
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81202038)
Location: include/linux/mm.h:1689
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/mm.h:1689
Inline: True
```
```
In mm/madvise.c (ffffffff8120a150)
Location: include/linux/mm.h:1689
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:1689
Inline: True
```
```
In mm/hugetlb.c (ffffffff8121a36d)
Location: include/linux/mm.h:1689
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8121aa1d)
Location: include/linux/mm.h:1689
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:1689
Inline: True
```
```
In mm/migrate.c (ffffffff8122f513)
Location: include/linux/mm.h:1689
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81233e72)
Location: include/linux/mm.h:1689
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (0)
Location: include/linux/mm.h:1689
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:1689
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:1689
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:1689
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:1689
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff81021891)
Location: include/linux/mm.h:1791
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/mm.h:1791
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/mm.h:1791
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:1791
Inline: True
```
```
In mm/memory.c (ffffffff81208a29)
Location: include/linux/mm.h:1791
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (0)
Location: include/linux/mm.h:1791
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/mm.h:1791
Inline: True
```
```
In mm/mremap.c (ffffffff812193cd)
Location: include/linux/mm.h:1791
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8121a778)
Location: include/linux/mm.h:1791
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/mm.h:1791
Inline: True
```
```
In mm/madvise.c (ffffffff812233a3)
Location: include/linux/mm.h:1791
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:1791
Inline: True
```
```
In mm/hugetlb.c (ffffffff812354a9)
Location: include/linux/mm.h:1791
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81235c9a)
Location: include/linux/mm.h:1791
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:1791
Inline: True
```
```
In mm/migrate.c (ffffffff8124ce13)
Location: include/linux/mm.h:1791
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81251916)
Location: include/linux/mm.h:1791
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (0)
Location: include/linux/mm.h:1791
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:1791
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:1791
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:1791
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:1791
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff8102249c)
Location: include/linux/mm.h:1878
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/mm.h:1878
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/mm.h:1878
Inline: True
```
```
In mm/gup.c (ffffffff81225ee4)
Location: include/linux/mm.h:1878
Inline: True
```
```
In mm/memory.c (ffffffff81229a85)
Location: include/linux/mm.h:1878
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (0)
Location: include/linux/mm.h:1878
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/mm.h:1878
Inline: True
```
```
In mm/mremap.c (ffffffff8123ac41)
Location: include/linux/mm.h:1878
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8123c7da)
Location: include/linux/mm.h:1878
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/mm.h:1878
Inline: True
```
```
In mm/madvise.c (ffffffff8124620d)
Location: include/linux/mm.h:1878
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:1878
Inline: True
```
```
In mm/hugetlb.c (ffffffff812583b9)
Location: include/linux/mm.h:1878
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8125a6fb)
Location: include/linux/mm.h:1878
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:1878
Inline: True
```
```
In mm/migrate.c (ffffffff812708fe)
Location: include/linux/mm.h:1878
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81275e44)
Location: include/linux/mm.h:1878
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (0)
Location: include/linux/mm.h:1878
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:1878
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:1878
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:1878
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:1878
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff81021cce)
Location: include/linux/mm.h:1956
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/mm.h:1956
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/mm.h:1956
Inline: True
```
```
In mm/gup.c (ffffffff81239654)
Location: include/linux/mm.h:1956
Inline: True
```
```
In mm/memory.c (ffffffff8123cf9f)
Location: include/linux/mm.h:1956
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (0)
Location: include/linux/mm.h:1956
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/mm.h:1956
Inline: True
```
```
In mm/mremap.c (ffffffff8124f40e)
Location: include/linux/mm.h:1956
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81250be6)
Location: include/linux/mm.h:1956
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/mm.h:1956
Inline: True
```
```
In mm/madvise.c (ffffffff8125a62d)
Location: include/linux/mm.h:1956
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:1956
Inline: True
```
```
In mm/hugetlb.c (ffffffff8126ca89)
Location: include/linux/mm.h:1956
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8126e57d)
Location: include/linux/mm.h:1956
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:1956
Inline: True
```
```
In mm/migrate.c (ffffffff81284f1e)
Location: include/linux/mm.h:1956
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff8128aca4)
Location: include/linux/mm.h:1956
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (0)
Location: include/linux/mm.h:1956
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:1956
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:1956
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:1956
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:1956
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff810250b7)
Location: include/linux/mm.h:1951
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/mm.h:1951
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/mm.h:1951
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:1951
Inline: True
```
```
In mm/memory.c (ffffffff8124ec17)
Location: include/linux/mm.h:1951
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (0)
Location: include/linux/mm.h:1951
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/mm.h:1951
Inline: True
```
```
In mm/mremap.c (ffffffff81261761)
Location: include/linux/mm.h:1951
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81262ec6)
Location: include/linux/mm.h:1951
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/mm.h:1951
Inline: True
```
```
In mm/madvise.c (ffffffff8127570c)
Location: include/linux/mm.h:1951
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:1951
Inline: True
```
```
In mm/hugetlb.c (ffffffff81287eb3)
Location: include/linux/mm.h:1951
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81289baf)
Location: include/linux/mm.h:1951
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:1951
Inline: True
```
```
In mm/migrate.c (ffffffff8129f58e)
Location: include/linux/mm.h:1951
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812a58c5)
Location: include/linux/mm.h:1951
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812ab8c7)
Location: include/linux/mm.h:1951
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:1951
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:1951
Inline: True
```
```
In mm/hmm.c (ffffffff812c3e60)
Location: include/linux/mm.h:1951
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:1951
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:1951
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff81025697)
Location: include/linux/mm.h:1923
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/memory.c (ffffffff8125d1d7)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/mremap.c (ffffffff8126ff1f)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81271676)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/madvise.c (ffffffff812846dc)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/hugetlb.c (ffffffff81297ab3)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8129971f)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/migrate.c (ffffffff812b092e)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812b6d85)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812bd0fb)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/hmm.c (ffffffff812d5ba8)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:1923
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff81027b68)
Location: include/linux/mm.h:2189
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/mm.h:2189
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/mm.h:2189
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:2189
Inline: True
```
```
In mm/memory.c (ffffffff8128d7f5)
Location: include/linux/mm.h:2189
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_set_pmd
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (0)
Location: include/linux/mm.h:2189
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/mm.h:2189
Inline: True
```
```
In mm/mremap.c (ffffffff8129fdfe)
Location: include/linux/mm.h:2189
Inline: True
Inline callers:
  - mm/mremap.c:move_normal_pmd
  - mm/mremap.c:move_normal_pmd
```
```
In mm/page_vma_mapped.c (ffffffff812a1bdc)
Location: include/linux/mm.h:2189
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/pagewalk.c (0)
Location: include/linux/mm.h:2189
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/mm.h:2189
Inline: True
```
```
In mm/madvise.c (ffffffff812b6871)
Location: include/linux/mm.h:2189
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:2189
Inline: True
```
```
In mm/hugetlb.c (ffffffff812cb149)
Location: include/linux/mm.h:2189
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff812cea5b)
Location: include/linux/mm.h:2189
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:2189
Inline: True
```
```
In mm/migrate.c (ffffffff812e6a6e)
Location: include/linux/mm.h:2189
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812ebee5)
Location: include/linux/mm.h:2189
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812f2811)
Location: include/linux/mm.h:2189
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:2189
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:2189
Inline: True
```
```
In mm/hmm.c (ffffffff8130b7fc)
Location: include/linux/mm.h:2189
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:2189
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:2189
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff81027a6a)
Location: include/linux/mm.h:2194
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/mm.h:2194
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/mm.h:2194
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:2194
Inline: True
```
```
In mm/memory.c (ffffffff8129fca7)
Location: include/linux/mm.h:2194
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_set_pmd
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (0)
Location: include/linux/mm.h:2194
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/mm.h:2194
Inline: True
```
```
In mm/mremap.c (ffffffff812ab279)
Location: include/linux/mm.h:2194
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812ad6d9)
Location: include/linux/mm.h:2194
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/pagewalk.c (0)
Location: include/linux/mm.h:2194
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/mm.h:2194
Inline: True
```
```
In mm/madvise.c (ffffffff812c2ac1)
Location: include/linux/mm.h:2194
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:2194
Inline: True
```
```
In mm/hugetlb.c (ffffffff812d6d59)
Location: include/linux/mm.h:2194
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff812da39b)
Location: include/linux/mm.h:2194
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:2194
Inline: True
```
```
In mm/migrate.c (ffffffff812f1dbe)
Location: include/linux/mm.h:2194
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812f6f55)
Location: include/linux/mm.h:2194
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812fce35)
Location: include/linux/mm.h:2194
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:2194
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:2194
Inline: True
```
```
In mm/hmm.c (ffffffff813176e8)
Location: include/linux/mm.h:2194
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:2194
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:2194
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff8102a255)
Location: include/linux/mm.h:2202
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/mm.h:2202
Inline: True
```
```
In mm/filemap.c (ffffffff8125fd12)
Location: include/linux/mm.h:2202
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/shmem.c (0)
Location: include/linux/mm.h:2202
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:2202
Inline: True
```
```
In mm/memory.c (ffffffff812a553f)
Location: include/linux/mm.h:2202
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (0)
Location: include/linux/mm.h:2202
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/mm.h:2202
Inline: True
```
```
In mm/mremap.c (ffffffff812b0679)
Location: include/linux/mm.h:2202
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812b2625)
Location: include/linux/mm.h:2202
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (0)
Location: include/linux/mm.h:2202
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/mm.h:2202
Inline: True
```
```
In mm/madvise.c (ffffffff812c9941)
Location: include/linux/mm.h:2202
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:2202
Inline: True
```
```
In mm/hugetlb.c (ffffffff812de985)
Location: include/linux/mm.h:2202
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff812e1bf8)
Location: include/linux/mm.h:2202
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:2202
Inline: True
```
```
In mm/migrate.c (ffffffff812f80ee)
Location: include/linux/mm.h:2202
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812fd304)
Location: include/linux/mm.h:2202
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81303baa)
Location: include/linux/mm.h:2202
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:2202
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:2202
Inline: True
```
```
In mm/hmm.c (ffffffff8131d3e4)
Location: include/linux/mm.h:2202
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:2202
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:2202
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff8102e842)
Location: include/linux/mm.h:2231
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/mm.h:2231
Inline: True
```
```
In mm/filemap.c (ffffffff8129c682)
Location: include/linux/mm.h:2231
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:2231
Inline: True
```
```
In mm/memory.c (ffffffff812e6a36)
Location: include/linux/mm.h:2231
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (0)
Location: include/linux/mm.h:2231
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/mm.h:2231
Inline: True
```
```
In mm/mremap.c (ffffffff812f1f9d)
Location: include/linux/mm.h:2231
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812f4214)
Location: include/linux/mm.h:2231
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (0)
Location: include/linux/mm.h:2231
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/mm.h:2231
Inline: True
```
```
In mm/madvise.c (ffffffff8130e961)
Location: include/linux/mm.h:2231
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:2231
Inline: True
```
```
In mm/hugetlb.c (ffffffff81325d6a)
Location: include/linux/mm.h:2231
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81328cd2)
Location: include/linux/mm.h:2231
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:2231
Inline: True
```
```
In mm/migrate.c (ffffffff81342755)
Location: include/linux/mm.h:2231
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81346fc4)
Location: include/linux/mm.h:2231
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8134d8e0)
Location: include/linux/mm.h:2231
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:2231
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/mm.h:2231
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:2231
Inline: True
```
```
In mm/hmm.c (ffffffff8136a77e)
Location: include/linux/mm.h:2231
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:2231
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:2231
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff810339c2)
Location: include/linux/mm.h:2309
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/mm.h:2309
Inline: True
```
```
In mm/filemap.c (ffffffff812f3822)
Location: include/linux/mm.h:2309
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:2309
Inline: True
```
```
In mm/memory.c (ffffffff8133d8a7)
Location: include/linux/mm.h:2309
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (0)
Location: include/linux/mm.h:2309
Inline: True
```
```
In mm/mlock.c (ffffffff8134c666)
Location: include/linux/mm.h:2309
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (0)
Location: include/linux/mm.h:2309
Inline: True
```
```
In mm/mremap.c (ffffffff81355d0d)
Location: include/linux/mm.h:2309
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff813589a0)
Location: include/linux/mm.h:2309
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (0)
Location: include/linux/mm.h:2309
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/mm.h:2309
Inline: True
```
```
In mm/madvise.c (ffffffff813767f5)
Location: include/linux/mm.h:2309
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:2309
Inline: True
```
```
In mm/hugetlb.c (ffffffff81394ad5)
Location: include/linux/mm.h:2309
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81397f2a)
Location: include/linux/mm.h:2309
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:2309
Inline: True
```
```
In mm/migrate.c (ffffffff813b4d04)
Location: include/linux/mm.h:2309
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
```
```
In mm/migrate_device.c (0)
Location: include/linux/mm.h:2309
Inline: True
```
```
In mm/huge_memory.c (ffffffff813bd304)
Location: include/linux/mm.h:2309
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813c6b48)
Location: include/linux/mm.h:2309
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:2309
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/mm.h:2309
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:2309
Inline: True
```
```
In mm/hmm.c (ffffffff813e837d)
Location: include/linux/mm.h:2309
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:2309
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:2309
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
In arch/x86/xen/mmu_pv.c (ffffffff8103b410)
Location: include/linux/mm.h:2473
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/mm.h:2473
Inline: True
```
```
In mm/filemap.c (ffffffff8135db7d)
Location: include/linux/mm.h:2473
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/vmscan.c (0)
Location: include/linux/mm.h:2473
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:2473
Inline: True
```
```
In mm/memory.c (ffffffff813b68cb)
Location: include/linux/mm.h:2473
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (0)
Location: include/linux/mm.h:2473
Inline: True
```
```
In mm/mlock.c (ffffffff813c51fa)
Location: include/linux/mm.h:2473
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (0)
Location: include/linux/mm.h:2473
Inline: True
```
```
In mm/mremap.c (ffffffff813d032d)
Location: include/linux/mm.h:2473
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff813d30af)
Location: include/linux/mm.h:2473
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (0)
Location: include/linux/mm.h:2473
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/mm.h:2473
Inline: True
```
```
In mm/madvise.c (ffffffff813f4159)
Location: include/linux/mm.h:2473
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:2473
Inline: True
```
```
In mm/hugetlb.c (ffffffff8140ddfb)
Location: include/linux/mm.h:2473
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
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81417c1c)
Location: include/linux/mm.h:2473
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:2473
Inline: True
```
```
In mm/migrate.c (ffffffff81433eb4)
Location: include/linux/mm.h:2473
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
```
```
In mm/migrate_device.c (0)
Location: include/linux/mm.h:2473
Inline: True
```
```
In mm/huge_memory.c (ffffffff8143fa34)
Location: include/linux/mm.h:2473
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81448f8a)
Location: include/linux/mm.h:2473
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:2473
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/mm.h:2473
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:2473
Inline: True
```
```
In mm/hmm.c (ffffffff81470289)
Location: include/linux/mm.h:2473
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:2473
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:2473
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
In arch/x86/xen/mmu_pv.c (ffffffff8103b4e5)
Location: include/linux/mm.h:2793
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/mm.h:2793
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/mm.h:2793
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:2793
Inline: True
```
```
In mm/memory.c (ffffffff813efa7f)
Location: include/linux/mm.h:2793
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/mremap.c (ffffffff8140509d)
Location: include/linux/mm.h:2793
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81407c72)
Location: include/linux/mm.h:2793
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81409aa9)
Location: include/linux/mm.h:2793
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map_lock
  - mm/pgtable-generic.c:pte_offset_map_nolock
```
```
In mm/hugetlb.c (ffffffff814411da)
Location: include/linux/mm.h:2793
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
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8144b1e1)
Location: include/linux/mm.h:2793
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/migrate.c (ffffffff81469804)
Location: include/linux/mm.h:2793
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/migrate_device.c (ffffffff8146f10a)
Location: include/linux/mm.h:2793
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81475274)
Location: include/linux/mm.h:2793
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (0)
Location: include/linux/mm.h:2793
Inline: True
```
```
In mm/hmm.c (ffffffff814a4a59)
Location: include/linux/mm.h:2793
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:2793
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
In arch/x86/xen/mmu_pv.c (ffffffff810419a5)
Location: include/linux/mm.h:2885
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/mm.h:2885
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/mm.h:2885
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:2885
Inline: True
```
```
In mm/memory.c (ffffffff8141b0d8)
Location: include/linux/mm.h:2885
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/mremap.c (ffffffff8143157d)
Location: include/linux/mm.h:2885
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81434347)
Location: include/linux/mm.h:2885
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff814362c9)
Location: include/linux/mm.h:2885
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map_lock
  - mm/pgtable-generic.c:pte_offset_map_nolock
```
```
In mm/hugetlb.c (ffffffff8147b30b)
Location: include/linux/mm.h:2885
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
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81484beb)
Location: include/linux/mm.h:2885
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/migrate.c (ffffffff81498734)
Location: include/linux/mm.h:2885
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/migrate_device.c (ffffffff8149dc0b)
Location: include/linux/mm.h:2885
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a4ce4)
Location: include/linux/mm.h:2885
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814acc2c)
Location: include/linux/mm.h:2885
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/hmm.c (ffffffff814d5a81)
Location: include/linux/mm.h:2885
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:2885
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8159d5c7)
Location: include/linux/mm.h:2885
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
In arch/arm64/mm/mmu.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In virt/kvm/arm/mmu.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/memory.c (ffff8000102f45cc)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/mremap.c (ffff800010306088)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffff8000103072f8)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/madvise.c (ffff80001031ea4c)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/hugetlb.c (ffff800010335d9c)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffff800010338398)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/migrate.c (ffff800010350ed4)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffff800010357aec)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/hmm.c (ffff80001037b37c)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:1923
Inline: True
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
In arch/arm/mm/mmu.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/memory.c (c051bdd8)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/mremap.c (c0523ed8)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (c0524d88)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/madvise.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/migrate.c (c055254c)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:1923
Inline: True
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
In arch/powerpc/mm/pgtable-frag.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In arch/powerpc/mm/book3s64/hash_pgtable.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In arch/powerpc/mm/book3s64/pgtable.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In arch/powerpc/mm/book3s64/radix_pgtable.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In arch/powerpc/mm/book3s64/subpage_prot.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In arch/powerpc/mm/hugetlbpage.c (c0000000000a589c)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:huge_pte_alloc
```
```
In mm/shmem.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/gup.c (c0000000003b7ef8)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (c0000000003bb184)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/mremap.c (c0000000003d3608)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/page_vma_mapped.c (c0000000003d599c)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/madvise.c (c0000000003f3054)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/hugetlb.c (c0000000004104c0)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (c0000000004111e0)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/migrate.c (c000000000434794)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (c00000000043fd64)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (c0000000004478d8)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/hmm.c (c00000000046fd40)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (c00000000051454c)
Location: include/linux/mm.h:1923
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:1923
Inline: True
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
In mm/shmem.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/memory.c (ffffffe000206758)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/mremap.c (ffffffe000211bb2)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffe00021273a)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/madvise.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/migrate.c (ffffffe00023f80e)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:1923
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff810257f7)
Location: include/linux/mm.h:1923
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/memory.c (ffffffff81255827)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/mremap.c (ffffffff8126856f)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81269cc6)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/madvise.c (ffffffff8127cd2c)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/hugetlb.c (ffffffff81290093)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81291cff)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/migrate.c (ffffffff812a8f0e)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812af365)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b56db)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/hmm.c (ffffffff812ce188)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:1923
Inline: True
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
In arch/x86/mm/pgtable.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/memory.c (ffffffff81247f10)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/mremap.c (ffffffff8125a7a0)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8125bf11)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/madvise.c (ffffffff8126ebb1)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/hugetlb.c (ffffffff81281d54)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81283948)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/migrate.c (ffffffff8129a89e)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812a0855)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/hmm.c (ffffffff812bf037)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:1923
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff81025657)
Location: include/linux/mm.h:1923
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/memory.c (ffffffff812535c7)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/mremap.c (ffffffff8126630f)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81267a66)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/madvise.c (ffffffff8127aacc)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128dea3)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8128fb0f)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/migrate.c (ffffffff812a6d1e)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812ad175)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b34eb)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/hmm.c (ffffffff812cbf98)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:1923
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff810260cf)
Location: include/linux/mm.h:1923
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/memory.c (ffffffff81262fbe)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/mremap.c (ffffffff81275ca0)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812773fc)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/madvise.c (ffffffff8128a6ac)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/hugetlb.c (ffffffff8129dc51)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8129e35d)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/migrate.c (ffffffff812b704e)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812bd4f5)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812c394b)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In mm/hmm.c (ffffffff812dcd09)
Location: include/linux/mm.h:1923
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:1923
Inline: True
```
</details>
</li>
</ul>

## Differences
