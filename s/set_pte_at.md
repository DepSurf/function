# Function: <code>set_pte_at</code>

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
In arch/x86/xen/mmu.c (ffffffff8101df04)
Location: arch/x86/include/asm/paravirt.h:493
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:__ptep_modify_prot_commit
```
```
In arch/x86/xen/grant-table.c (ffffffff81023d1b)
Location: arch/x86/include/asm/paravirt.h:493
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
```
```
In arch/x86/kernel/tboot.c (ffffffff81f6a3db)
Location: arch/x86/include/asm/paravirt.h:493
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff810646d4)
Location: arch/x86/include/asm/paravirt.h:493
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In arch/x86/mm/init_64.c (ffffffff8107d5d9)
Location: arch/x86/include/asm/paravirt.h:493
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff81f77ff3)
Location: arch/x86/include/asm/paravirt.h:493
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In kernel/events/uprobes.c (ffffffff8118789c)
Location: arch/x86/include/asm/paravirt.h:493
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/gup.c (ffffffff811ba738)
Location: arch/x86/include/asm/paravirt.h:493
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811bc6e6)
Location: arch/x86/include/asm/paravirt.h:493
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:do_set_pte
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_insert_page
```
```
In mm/mprotect.c (ffffffff811c89a4)
Location: arch/x86/include/asm/paravirt.h:493
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811c96ab)
Location: arch/x86/include/asm/paravirt.h:493
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811cad23)
Location: arch/x86/include/asm/paravirt.h:493
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff811ce0d1)
Location: arch/x86/include/asm/paravirt.h:493
Inline: True
```
```
In mm/swapfile.c (ffffffff811d45de)
Location: arch/x86/include/asm/paravirt.h:493
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811ddace)
Location: arch/x86/include/asm/paravirt.h:493
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/sparse-vmemmap.c (ffffffff8181f2b6)
Location: arch/x86/include/asm/paravirt.h:493
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff811e5572)
Location: arch/x86/include/asm/paravirt.h:493
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff811f0d80)
Location: arch/x86/include/asm/paravirt.h:493
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff811f559a)
Location: arch/x86/include/asm/paravirt.h:493
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/userfaultfd.c (ffffffff81207b2c)
Location: arch/x86/include/asm/paravirt.h:493
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mfill_zeropage
```
```
In fs/proc/task_mmu.c (ffffffff81278f18)
Location: arch/x86/include/asm/paravirt.h:493
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In lib/ioremap.c (ffffffff813eb2a7)
Location: arch/x86/include/asm/paravirt.h:493
Inline: True
```
```
In drivers/xen/xlate_mmu.c (ffffffff814d7135)
Location: arch/x86/include/asm/paravirt.h:493
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/mmu.c (ffffffff8101d2f4)
Location: arch/x86/include/asm/paravirt.h:466
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:__ptep_modify_prot_commit
```
```
In arch/x86/xen/grant-table.c (ffffffff8102306e)
Location: arch/x86/include/asm/paravirt.h:466
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/kernel/tboot.c (ffffffff81f926f1)
Location: arch/x86/include/asm/paravirt.h:466
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064324)
Location: arch/x86/include/asm/paravirt.h:466
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In arch/x86/mm/init_64.c (ffffffff8107f0be)
Location: arch/x86/include/asm/paravirt.h:466
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff81fa074b)
Location: arch/x86/include/asm/paravirt.h:466
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In kernel/events/uprobes.c (ffffffff81199eb4)
Location: arch/x86/include/asm/paravirt.h:466
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/gup.c (ffffffff811d4db5)
Location: arch/x86/include/asm/paravirt.h:466
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811db99d)
Location: arch/x86/include/asm/paravirt.h:466
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vm_insert_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff811e4c6f)
Location: arch/x86/include/asm/paravirt.h:466
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e5a6a)
Location: arch/x86/include/asm/paravirt.h:466
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811e868b)
Location: arch/x86/include/asm/paravirt.h:466
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff811eac77)
Location: arch/x86/include/asm/paravirt.h:466
Inline: True
```
```
In mm/madvise.c (ffffffff811eef47)
Location: arch/x86/include/asm/paravirt.h:466
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff811f246b)
Location: arch/x86/include/asm/paravirt.h:466
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811fc53a)
Location: arch/x86/include/asm/paravirt.h:466
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff81899966)
Location: arch/x86/include/asm/paravirt.h:466
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81204046)
Location: arch/x86/include/asm/paravirt.h:466
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff8120ffea)
Location: arch/x86/include/asm/paravirt.h:466
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8121634d)
Location: arch/x86/include/asm/paravirt.h:466
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8121a50c)
Location: arch/x86/include/asm/paravirt.h:466
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff8122d8de)
Location: arch/x86/include/asm/paravirt.h:466
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/proc/task_mmu.c (ffffffff812a59a0)
Location: arch/x86/include/asm/paravirt.h:466
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In lib/ioremap.c (ffffffff8143162e)
Location: arch/x86/include/asm/paravirt.h:466
Inline: True
```
```
In drivers/xen/xlate_mmu.c (ffffffff81527efa)
Location: arch/x86/include/asm/paravirt.h:466
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/mmu.c (ffffffff8101da14)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:__ptep_modify_prot_commit
```
```
In arch/x86/xen/grant-table.c (ffffffff810237be)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/kernel/tboot.c (ffffffff81fcd9bd)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff810677f4)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In arch/x86/mm/init_64.c (ffffffff81083774)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff81fdbcbc)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In kernel/events/uprobes.c (ffffffff811a961e)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/gup.c (ffffffff811e4df4)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811eb533)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vm_insert_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff811f4c96)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f5cad)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811f97b5)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff811fbee4)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
```
```
In mm/madvise.c (ffffffff811ff8a9)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff81202e62)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8120d02a)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff818ce018)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8121626c)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81222112)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812288fd)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8122e90e)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/userfaultfd.c (ffffffff8123fe19)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff8129bb02)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812bb2e8)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In lib/ioremap.c (ffffffff8144d89e)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
```
In drivers/xen/xlate_mmu.c (ffffffff81554467)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/grant-table.c (ffffffff8101b49e)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8101fcf4)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit
```
```
In arch/x86/kernel/tboot.c (ffffffff820ae007)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff81066ac4)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In arch/x86/mm/init_64.c (ffffffff8106cede)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff820bcc89)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In kernel/events/uprobes.c (ffffffff811b0b1d)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff811dcfef)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
```
In mm/gup.c (ffffffff811ef3c2)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811f5f3d)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff811ffbe4)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81200a9b)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8120459f)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff81206b10)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
```
```
In mm/madvise.c (ffffffff8120a536)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8120deec)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81218f2c)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff819054ad)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812217ae)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8122df9b)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81231f7a)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff812385ba)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff8124bcfe)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff812aa978)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff812c691b)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In drivers/xen/xlate_mmu.c (ffffffff81568fa6)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff818ed554)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/xen/grant-table.c (ffffffff8101c107)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81020954)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit
```
```
In arch/x86/kernel/ldt.c (ffffffff81031df3)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff826b4562)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106ac44)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In arch/x86/mm/init_64.c (ffffffff81071bfd)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff826c3865)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In kernel/events/uprobes.c (ffffffff811c467d)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff811eef5f)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8120651d)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8120da33)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff81218297)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812194df)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8121d579)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff8121fb62)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
```
```
In mm/madvise.c (ffffffff8122378d)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8122915e)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81233ec2)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff8198f4ef)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8123cac1)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8124b751)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81252cfd)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff81259aa4)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/userfaultfd.c (ffffffff8126c0a4)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff812ce24d)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff812ece3e)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In drivers/xen/xlate_mmu.c (ffffffff815cd156)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff81973689)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/xen/grant-table.c (ffffffff8101cb17)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81021400)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit
```
```
In arch/x86/kernel/ldt.c (ffffffff810330a0)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff826ddcb6)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106d900)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In arch/x86/mm/init_64.c (ffffffff810748fd)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff826edaf4)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff8107fea3)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff811e4bef)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff8120fa55)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff812267df)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8122e5ce)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mprotect.c (ffffffff81239447)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8123adab)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8123f57d)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff81240cdc)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
```
```
In mm/madvise.c (ffffffff81246598)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8124a473)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81256f29)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff819ebd9d)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81260387)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8126e472)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8127712c)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff8127c423)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff81290af9)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff812f8807)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff8131943a)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In drivers/xen/xlate_mmu.c (ffffffff816058b7)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff819cfb33)
Location: arch/x86/include/asm/paravirt.h:451
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/xen/grant-table.c (ffffffff8101c3a7)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81020c70)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit
```
```
In arch/x86/kernel/ldt.c (ffffffff8103484e)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/tboot.c (ffffffff828940fc)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff81073aa0)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In arch/x86/mm/init_64.c (ffffffff8107a810)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff828a4686)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff810869e3)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff811f5272)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff81222829)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8123ab27)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124242a)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mprotect.c (ffffffff8124db1b)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124efa2)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff81253c83)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff8125558b)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
```
```
In mm/madvise.c (ffffffff8125a9bb)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8125ead7)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8126b59f)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff81a2700b)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81274ad2)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81283300)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8128897b)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff81290ac6)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff812a5b2d)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff8130c500)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81330a54)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In drivers/xen/xlate_mmu.c (ffffffff81620997)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff81a09128)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/xen/grant-table.c (ffffffff8101df10)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810227b0)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit
```
```
In arch/x86/kernel/ldt.c (ffffffff810366f6)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff8103986d)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff828ab8b4)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077600)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In arch/x86/mm/init_64.c (ffffffff8107e57f)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff828bcb56)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a5fb)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8120cf60)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff81231e2e)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8124be5c)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812534d2)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mprotect.c (ffffffff8125fa44)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81261304)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff81265eaa)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff812678dd)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
```
```
In mm/madvise.c (ffffffff81275b09)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff81279803)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128685b)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff81a978a8)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8128f7fc)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff8129dd2e)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a35bc)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812a9e07)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812c1214)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff81333a3f)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8135887b)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In drivers/xen/xlate_mmu.c (ffffffff81654073)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff81a789a9)
Location: arch/x86/include/asm/paravirt.h:455
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
In arch/x86/xen/grant-table.c (ffffffff8101e890)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810230f0)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit
```
```
In arch/x86/kernel/ldt.c (ffffffff81036f26)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff8103a03e)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff828ae8c2)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff81078670)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In arch/x86/mm/init_64.c (ffffffff8107f60f)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff828c2ff1)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff8108b26b)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8121a251)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8123feee)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8125a34c)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81261a32)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mprotect.c (ffffffff8126e254)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8126faa7)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812747d7)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff8127623d)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In mm/madvise.c (ffffffff81284ad9)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812892e3)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In mm/hugetlb.c (ffffffff8129644a)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff81acf176)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8129f580)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812aea5f)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b4abc)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812bb377)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812d3164)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff81347605)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81370acb)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In drivers/xen/xlate_mmu.c (ffffffff81676613)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff81aafd59)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_pte_at(struct mm_struct *mm, long unsigned int addr, pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81020e10)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025960)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit
```
```
In arch/x86/kernel/ldt.c (ffffffff81038b24)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:unmap_ldt_struct
```
```
In arch/x86/kernel/alternative.c (ffffffff8103ccac)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81047b6f)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107fa70)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In arch/x86/mm/init_64.c (ffffffff8108604d)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff82ce63d7)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff810925a1)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In kernel/events/uprobes.c (ffffffff81246bca)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8126e90a)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff81288842)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81291c96)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pte_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_one_pte
Direct callers:
  - mm/memory.c:copy_one_pte
```
```
In mm/mprotect.c (ffffffff8129e7c1)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812a00e9)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
```
```
In mm/rmap.c (ffffffff812a5b59)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff812a79f5)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pte_range
```
```
In mm/madvise.c (ffffffff812b6cc8)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812bbce2)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812c99ed)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7b36)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812d3bce)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812e41b8)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ea063)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff812f05dc)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_copy
  - mm/khugepaged.c:__collapse_huge_page_copy
```
```
In mm/userfaultfd.c (ffffffff81307f56)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage_pte
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/dax.c (ffffffff8138da0c)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813b8e38)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In lib/ioremap.c (ffffffff815e98a2)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pte_range
```
```
In drivers/xen/xlate_mmu.c (ffffffff817270d7)
Location: arch/x86/include/asm/paravirt.h:457
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff8128b8d0-ffffffff8128b8dd: set_pte_at (STB_LOCAL)
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
In arch/x86/xen/grant-table.c (ffffffff81021682)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81026080)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit
```
```
In arch/x86/kernel/ldt.c (ffffffff810392c8)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103d162)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81bd4de5)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810658b0)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107f690)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In kernel/events/uprobes.c (ffffffff8125122d)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff81279307)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8129251c)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129c566)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pte_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff812a9b7e)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812ab54d)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
```
```
In mm/rmap.c (ffffffff812b0fc9)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff812b2acd)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pte_range
```
```
In mm/ioremap.c (ffffffff812b8141)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_pte_range
```
```
In mm/madvise.c (ffffffff812c2e20)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812c7792)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812d5665)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff81c40866)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812df5ce)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812f01ed)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812f5240)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff81313fe4)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/dax.c (ffffffff8139f48c)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813c7f45)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In drivers/xen/xlate_mmu.c (ffffffff81743625)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/grant-table.c (ffffffff81023a02)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81027fc0)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit
```
```
In arch/x86/kernel/ldt.c (ffffffff8103adf9)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103e99f)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81bc7234)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81065f80)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In arch/x86/kernel/paravirt.c (ffffffff81080790)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In kernel/events/uprobes.c (ffffffff81255327)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8127e2f3)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff81297fcc)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812a1a31)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff812af009)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812b0950)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
```
```
In mm/rmap.c (ffffffff812b6595)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff812b7db6)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff812c9c99)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812ce10a)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812dc3c0)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff81c328c4)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812e7f0a)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812f58c7)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812fb788)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff8131a1a3)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/dax.c (ffffffff813a61f6)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813cef75)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In drivers/xen/xlate_mmu.c (ffffffff81727011)
Location: arch/x86/include/asm/pgtable.h:1035
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/grant-table.c (ffffffff81027ca2)
Location: arch/x86/include/asm/pgtable.h:1006
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/kernel/ldt.c (ffffffff81040823)
Location: arch/x86/include/asm/pgtable.h:1006
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8104470f)
Location: arch/x86/include/asm/pgtable.h:1006
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81c9a82d)
Location: arch/x86/include/asm/pgtable.h:1006
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810700a0)
Location: arch/x86/include/asm/pgtable.h:1006
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108f6b0)
Location: arch/x86/include/asm/pgtable.h:1006
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In kernel/events/uprobes.c (ffffffff81290d69)
Location: arch/x86/include/asm/pgtable.h:1006
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff812d8a0c)
Location: arch/x86/include/asm/pgtable.h:1006
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812e2a01)
Location: arch/x86/include/asm/pgtable.h:1006
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mprotect.c (ffffffff812f0802)
Location: arch/x86/include/asm/pgtable.h:1006
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812f22e0)
Location: arch/x86/include/asm/pgtable.h:1006
Inline: True
```
```
In mm/rmap.c (ffffffff812f8bd6)
Location: arch/x86/include/asm/pgtable.h:1006
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff812fa4e8)
Location: arch/x86/include/asm/pgtable.h:1006
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff8130ecb9)
Location: arch/x86/include/asm/pgtable.h:1006
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8131358a)
Location: arch/x86/include/asm/pgtable.h:1006
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81323591)
Location: arch/x86/include/asm/pgtable.h:1006
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff81d512dc)
Location: arch/x86/include/asm/pgtable.h:1006
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_restore_pte
  - mm/sparse-vmemmap.c:vmemmap_remap_pte
  - mm/sparse-vmemmap.c:vmemmap_remap_range
```
```
In mm/ksm.c (ffffffff8132fe1b)
Location: arch/x86/include/asm/pgtable.h:1006
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff8133fe95)
Location: arch/x86/include/asm/pgtable.h:1006
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff813454fd)
Location: arch/x86/include/asm/pgtable.h:1006
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff81366e90)
Location: arch/x86/include/asm/pgtable.h:1006
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/dax.c (ffffffff813f5c66)
Location: arch/x86/include/asm/pgtable.h:1006
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81420455)
Location: arch/x86/include/asm/pgtable.h:1006
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In drivers/xen/xlate_mmu.c (ffffffff817a6091)
Location: arch/x86/include/asm/pgtable.h:1006
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/grant-table.c (ffffffff8102c121)
Location: arch/x86/include/asm/pgtable.h:1004
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/kernel/ldt.c (ffffffff810481d2)
Location: arch/x86/include/asm/pgtable.h:1004
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/alternative.c (ffffffff8104cd09)
Location: arch/x86/include/asm/pgtable.h:1004
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81e49c99)
Location: arch/x86/include/asm/pgtable.h:1004
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107d9d4)
Location: arch/x86/include/asm/pgtable.h:1004
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a0430)
Location: arch/x86/include/asm/pgtable.h:1004
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In kernel/events/uprobes.c (ffffffff812e6068)
Location: arch/x86/include/asm/pgtable.h:1004
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff81338a2d)
Location: arch/x86/include/asm/pgtable.h:1004
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81343323)
Location: arch/x86/include/asm/pgtable.h:1004
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:insert_pfn
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mprotect.c (ffffffff81353f46)
Location: arch/x86/include/asm/pgtable.h:1004
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81356085)
Location: arch/x86/include/asm/pgtable.h:1004
Inline: True
```
```
In mm/rmap.c (ffffffff8135f1b8)
Location: arch/x86/include/asm/pgtable.h:1004
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81361872)
Location: arch/x86/include/asm/pgtable.h:1004
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff81376d98)
Location: arch/x86/include/asm/pgtable.h:1004
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8137e8c6)
Location: arch/x86/include/asm/pgtable.h:1004
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81391076)
Location: arch/x86/include/asm/pgtable.h:1004
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff81f21575)
Location: arch/x86/include/asm/pgtable.h:1004
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_restore_pte
  - mm/sparse-vmemmap.c:vmemmap_remap_pte
  - mm/sparse-vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/ksm.c (ffffffff813a01e7)
Location: arch/x86/include/asm/pgtable.h:1004
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff813b1ab4)
Location: arch/x86/include/asm/pgtable.h:1004
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff813b742e)
Location: arch/x86/include/asm/pgtable.h:1004
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813bb50b)
Location: arch/x86/include/asm/pgtable.h:1004
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff813e436d)
Location: arch/x86/include/asm/pgtable.h:1004
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/proc/task_mmu.c (ffffffff8149a845)
Location: arch/x86/include/asm/pgtable.h:1004
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In drivers/xen/xlate_mmu.c (ffffffff818e004a)
Location: arch/x86/include/asm/pgtable.h:1004
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/grant-table.c (ffffffff8103305c)
Location: arch/x86/include/asm/pgtable.h:1022
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/kernel/ldt.c (ffffffff81052f1c)
Location: arch/x86/include/asm/pgtable.h:1022
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/alternative.c (ffffffff81059113)
Location: arch/x86/include/asm/pgtable.h:1022
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81067f8e)
Location: arch/x86/include/asm/pgtable.h:1022
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108ef54)
Location: arch/x86/include/asm/pgtable.h:1022
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b7fd0)
Location: arch/x86/include/asm/pgtable.h:1022
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In kernel/events/uprobes.c (ffffffff8134fcce)
Location: arch/x86/include/asm/pgtable.h:1022
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff813b02a9)
Location: arch/x86/include/asm/pgtable.h:1022
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813bb302)
Location: arch/x86/include/asm/pgtable.h:1022
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:insert_pfn
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mprotect.c (ffffffff813ce533)
Location: arch/x86/include/asm/pgtable.h:1022
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff813d06c8)
Location: arch/x86/include/asm/pgtable.h:1022
Inline: True
```
```
In mm/rmap.c (ffffffff813da070)
Location: arch/x86/include/asm/pgtable.h:1022
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff813dd210)
Location: arch/x86/include/asm/pgtable.h:1022
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff813f441c)
Location: arch/x86/include/asm/pgtable.h:1022
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff813fd44a)
Location: arch/x86/include/asm/pgtable.h:1022
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff814125d2)
Location: arch/x86/include/asm/pgtable.h:1022
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/hugetlb_vmemmap.c (ffffffff81414374)
Location: arch/x86/include/asm/pgtable.h:1022
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_restore_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_pte
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff820cb503)
Location: arch/x86/include/asm/pgtable.h:1022
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8141f0ce)
Location: arch/x86/include/asm/pgtable.h:1022
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff8143255b)
Location: arch/x86/include/asm/pgtable.h:1022
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff81439409)
Location: arch/x86/include/asm/pgtable.h:1022
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8143d917)
Location: arch/x86/include/asm/pgtable.h:1022
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff8146be1d)
Location: arch/x86/include/asm/pgtable.h:1022
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/proc/task_mmu.c (ffffffff8152ed65)
Location: arch/x86/include/asm/pgtable.h:1022
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In drivers/xen/xlate_mmu.c (ffffffff81a344eb)
Location: arch/x86/include/asm/pgtable.h:1022
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/grant-table.c (ffffffff81032ffc)
Location: arch/x86/include/asm/pgtable.h:1023
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/kernel/ldt.c (ffffffff81053eff)
Location: arch/x86/include/asm/pgtable.h:1023
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/alternative.c (ffffffff8105a6c1)
Location: arch/x86/include/asm/pgtable.h:1023
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81069816)
Location: arch/x86/include/asm/pgtable.h:1023
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81091e44)
Location: arch/x86/include/asm/pgtable.h:1023
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bb180)
Location: arch/x86/include/asm/pgtable.h:1023
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In kernel/events/uprobes.c (ffffffff81380e67)
Location: arch/x86/include/asm/pgtable.h:1023
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff813e481b)
Location: arch/x86/include/asm/pgtable.h:1023
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813efdde)
Location: arch/x86/include/asm/pgtable.h:1023
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_p4d_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mprotect.c (ffffffff81402c4a)
Location: arch/x86/include/asm/pgtable.h:1023
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81404ba2)
Location: arch/x86/include/asm/pgtable.h:1023
Inline: True
```
```
In mm/rmap.c (ffffffff8140e7b3)
Location: arch/x86/include/asm/pgtable.h:1023
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81410caa)
Location: arch/x86/include/asm/pgtable.h:1023
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff81427921)
Location: arch/x86/include/asm/pgtable.h:1023
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8143072c)
Location: arch/x86/include/asm/pgtable.h:1023
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81445ba5)
Location: arch/x86/include/asm/pgtable.h:1023
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/hugetlb_vmemmap.c (ffffffff814478cd)
Location: arch/x86/include/asm/pgtable.h:1023
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_restore_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_pte
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff8214f795)
Location: arch/x86/include/asm/pgtable.h:1023
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81453d53)
Location: arch/x86/include/asm/pgtable.h:1023
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff81467f5d)
Location: arch/x86/include/asm/pgtable.h:1023
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8146f7d8)
Location: arch/x86/include/asm/pgtable.h:1023
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81473081)
Location: arch/x86/include/asm/pgtable.h:1023
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff814a095d)
Location: arch/x86/include/asm/pgtable.h:1023
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_pte_zeropage
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/proc/task_mmu.c (ffffffff81567075)
Location: arch/x86/include/asm/pgtable.h:1023
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In drivers/xen/xlate_mmu.c (ffffffff81a7df0a)
Location: arch/x86/include/asm/pgtable.h:1023
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In arch/arm64/mm/hugetlbpage.c (ffff8000100b166c)
Location: arch/arm64/include/asm/pgtable.h:271
Inline: True
Inline callers:
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_set_wrprotect
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_set_access_flags
  - arch/arm64/mm/hugetlbpage.c:set_huge_pte_at
  - arch/arm64/mm/hugetlbpage.c:set_huge_pte_at
```
```
In kernel/events/uprobes.c (ffff8000102a562c)
Location: arch/arm64/include/asm/pgtable.h:271
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffff8000102d3234)
Location: arch/arm64/include/asm/pgtable.h:271
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffff8000102f1dc0)
Location: arch/arm64/include/asm/pgtable.h:271
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffff8000102fa0c8)
Location: arch/arm64/include/asm/pgtable.h:271
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffff8000103052d8)
Location: arch/arm64/include/asm/pgtable.h:271
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffff8000103061a4)
Location: arch/arm64/include/asm/pgtable.h:271
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffff80001030a0b8)
Location: arch/arm64/include/asm/pgtable.h:271
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffff80001030c36c)
Location: arch/arm64/include/asm/pgtable.h:271
Inline: True
```
```
In mm/madvise.c (ffff80001031ec60)
Location: arch/arm64/include/asm/pgtable.h:271
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffff800010326134)
Location: arch/arm64/include/asm/pgtable.h:271
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/sparse-vmemmap.c (ffff800010da0dfc)
Location: arch/arm64/include/asm/pgtable.h:271
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffff80001033edc0)
Location: arch/arm64/include/asm/pgtable.h:271
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffff800010352f98)
Location: arch/arm64/include/asm/pgtable.h:271
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffff800010355f34)
Location: arch/arm64/include/asm/pgtable.h:271
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffff80001035e75c)
Location: arch/arm64/include/asm/pgtable.h:271
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffff800010378cc0)
Location: arch/arm64/include/asm/pgtable.h:271
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/dax.c (ffff8000104077c4)
Location: arch/arm64/include/asm/pgtable.h:271
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In drivers/xen/xlate_mmu.c (ffff80001083f280)
Location: arch/arm64/include/asm/pgtable.h:271
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffff800010d897d0)
Location: arch/arm64/include/asm/pgtable.h:271
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/arm/mm/mmu.c (c031fba4)
Location: arch/arm/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - arch/arm/mm/mmu.c:__set_fixmap
```
```
In kernel/events/uprobes.c (c04d4a90)
Location: arch/arm/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (c04fb1c4)
Location: arch/arm/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (c05144bc)
Location: arch/arm/include/asm/pgtable.h:255
Inline: True
```
```
In mm/highmem.c (c0516314)
Location: arch/arm/include/asm/pgtable.h:255
Inline: True
```
```
In mm/memory.c (c051b3c0)
Location: arch/arm/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_page
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (c0523424)
Location: arch/arm/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0523fc0)
Location: arch/arm/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (c0525554)
Location: arch/arm/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush_young
  - mm/pgtable-generic.c:ptep_set_access_flags
```
```
In mm/rmap.c (c0526780)
Location: arch/arm/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (c0528520)
Location: arch/arm/include/asm/pgtable.h:255
Inline: True
```
```
In mm/madvise.c (c0537868)
Location: arch/arm/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (c053d970)
Location: arch/arm/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/ksm.c (c0544fe8)
Location: arch/arm/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (c0551738)
Location: arch/arm/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/userfaultfd.c (c05640dc)
Location: arch/arm/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (c0564494)
Location: arch/arm/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/proc/task_mmu.c (c06004a4)
Location: arch/arm/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In lib/ioremap.c (c0e8435c)
Location: arch/arm/include/asm/pgtable.h:255
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void set_pte_at(struct mm_struct *mm, long unsigned int addr, pte_t *ptep, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/pgtable.c (c000000000087d60)
Location: arch/powerpc/mm/pgtable.c:179
Inline: False
Direct callers:
  - arch/powerpc/mm/book3s64/hash_pgtable.c:hash__map_kernel_page
  - arch/powerpc/mm/book3s64/pgtable.c:ptep_modify_prot_commit
  - arch/powerpc/mm/book3s64/pgtable.c:set_pmd_at
  - arch/powerpc/mm/book3s64/pgtable.c:set_pmd_at
  - arch/powerpc/mm/book3s64/radix_pgtable.c:pmd_set_huge
  - arch/powerpc/mm/book3s64/radix_pgtable.c:pud_set_huge
  - arch/powerpc/mm/book3s64/radix_pgtable.c:radix__ptep_modify_prot_commit
  - arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page
  - arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page
  - arch/powerpc/mm/book3s64/hash_hugetlbpage.c:huge_ptep_modify_prot_commit
  - arch/powerpc/mm/book3s64/radix_hugetlbpage.c:radix__huge_ptep_modify_prot_commit
  - kernel/events/uprobes.c:__replace_page
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/gup.c:follow_page_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/mprotect.c:change_protection_range
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/vmalloc.c:vmap_page_range_noflush
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - fs/dax.c:dax_entry_mkclean
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
c000000000087d60-c000000000087eb0: set_pte_at (STB_GLOBAL)
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
In arch/riscv/mm/init.c (ffffffe000003d9a)
Location: arch/riscv/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - arch/riscv/mm/init.c:paging_init
  - arch/riscv/mm/init.c:paging_init
  - arch/riscv/mm/init.c:get_pmd_virt
  - arch/riscv/mm/init.c:get_pte_virt
```
```
In mm/shmem.c (ffffffe0001ee3e0)
Location: arch/riscv/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffe000204918)
Location: arch/riscv/include/asm/pgtable.h:333
Inline: True
```
```
In mm/memory.c (ffffffe000209978)
Location: arch/riscv/include/asm/pgtable.h:333
Inline: True
Inline callers:
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
In mm/mprotect.c (ffffffe00021122c)
Location: arch/riscv/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffe000211c46)
Location: arch/riscv/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffe000213f9a)
Location: arch/riscv/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffe0002158b6)
Location: arch/riscv/include/asm/pgtable.h:333
Inline: True
```
```
In mm/madvise.c (ffffffe00022071e)
Location: arch/riscv/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffe00022647c)
Location: arch/riscv/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffe000230ee0)
Location: arch/riscv/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffe000048fdc)
Location: arch/riscv/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffe0002349b0)
Location: arch/riscv/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffe00023e1de)
Location: arch/riscv/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/userfaultfd.c (ffffffe000250580)
Location: arch/riscv/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffe0002b2db8)
Location: arch/riscv/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In lib/ioremap.c (ffffffe0008b31a2)
Location: arch/riscv/include/asm/pgtable.h:333
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
In arch/x86/xen/grant-table.c (ffffffff8101e8a0)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023250)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit
```
```
In arch/x86/kernel/ldt.c (ffffffff81037086)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff8103a19e)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff8289c8e1)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077670)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In arch/x86/mm/init_64.c (ffffffff8107e60f)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff828adfc7)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a22b)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff812128a1)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8123853e)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8125299c)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125a082)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mprotect.c (ffffffff812668a4)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812680f7)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8126ce27)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff8126e88d)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In mm/madvise.c (ffffffff8127d129)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812818c3)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128ea2a)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff81a6dfe6)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81297b60)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a703f)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ad09c)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b3957)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812cb744)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff8133fbe5)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813690ab)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In drivers/xen/xlate_mmu.c (ffffffff8163c303)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff81a4eba9)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101e850)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810230b0)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit
```
```
In arch/x86/kernel/ldt.c (ffffffff81036ee6)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff81039ffe)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff828af8a4)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077620)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In arch/x86/mm/init_64.c (ffffffff8107e5bf)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff828c0ec6)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a1db)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81210641)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff812362de)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8125073c)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81257e22)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mprotect.c (ffffffff81264644)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81265e97)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8126abc7)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff8126c62d)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In mm/madvise.c (ffffffff8127aec9)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8127f6d3)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128c83a)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff81ada3f6)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81295970)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a4e4f)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812aaeac)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b1767)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812c9554)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff8133d6b5)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81366b7b)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In drivers/xen/xlate_mmu.c (ffffffff8166a453)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff81abaf99)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
In arch/x86/xen/grant-table.c (ffffffff8101eaa0)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023520)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__ptep_modify_prot_commit
```
```
In arch/x86/kernel/ldt.c (ffffffff81037ee6)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff8103affe)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff828af8d2)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff810796c0)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In arch/x86/mm/init_64.c (ffffffff810806af)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff828c4011)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff8108c47b)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8121f584)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff812465b9)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff812600ba)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81267812)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mprotect.c (ffffffff81274002)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81275839)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8127a530)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff8127c16d)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In mm/madvise.c (ffffffff8128aa95)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8128f3a6)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In mm/hugetlb.c (ffffffff8129c618)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff81ae68ac)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812a578b)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812b59ab)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812bb1fc)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812c1ad1)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812da234)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff813505c8)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8137a1d1)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In drivers/xen/xlate_mmu.c (ffffffff81684a13)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff81ac73e9)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
