# Function: <code>pte_offset_kernel</code>

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
In arch/x86/xen/mmu.c (ffffffff81f62ff9)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034823)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81f6a38d)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bbc3)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff810690f0)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
```
```
In arch/x86/mm/fault.c (ffffffff8106a352)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c308)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/gup.c (ffffffff810714a5)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In mm/gup.c (ffffffff811ba46f)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811bc2fa)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (ffffffff811c27b9)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811c87c1)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811c95cb)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811ca955)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/rmap.c:__page_check_address
```
```
In mm/vmalloc.c (ffffffff811cc624)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/pagewalk.c (ffffffff811cffed)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
```
```
In mm/madvise.c (ffffffff811d15b5)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff811d437d)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff811e00c2)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff8181f20a)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff811e5684)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff811f0bdb)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff811f49df)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memcontrol.c (ffffffff811fb021)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In mm/userfaultfd.c (ffffffff81207a21)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mfill_zeropage
```
```
In fs/userfaultfd.c (ffffffff8125b065)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff81278348)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In lib/ioremap.c (ffffffff813eb244)
Location: arch/x86/include/asm/pgtable.h:565
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
In arch/x86/xen/mmu.c (ffffffff81f8aba7)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810339e6)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81f92694)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bca9)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81069b74)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff81069fb4)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c190)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/gup.c (ffffffff81071758)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In mm/gup.c (ffffffff811d582d)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811db94f)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811de3a9)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811e4a86)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e59b2)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811e7807)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:__page_check_address
```
```
In mm/vmalloc.c (ffffffff811e9688)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/pagewalk.c (ffffffff811ed193)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
```
```
In mm/madvise.c (ffffffff811eeb6e)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff811f2182)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff811fee06)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff818998ae)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81204144)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff8121196b)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8121623e)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8121be4b)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8122112b)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff8122d88e)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/userfaultfd.c (ffffffff81283b97)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff812a5665)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In lib/ioremap.c (ffffffff814315bc)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff8176093c)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/xen/mmu.c (ffffffff81fc5f95)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81033610)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81fcd960)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ec23)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106d738)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff8106db54)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8106fdb0)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/gup.c (ffffffff810752e8)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In mm/gup.c (ffffffff811e582d)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811eb47f)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811ee1c7)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811f4a72)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f5bee)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff811f6f8c)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff811f7583)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
```
```
In mm/rmap.c (ffffffff811f8b97)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:__page_check_address
```
```
In mm/vmalloc.c (ffffffff811fa9d8)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff811ff4ad)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81202b7a)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff81210641)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff818cdf60)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812160b2)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81223b2a)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812287e1)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8122e355)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff81233874)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff8123fdda)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/userfaultfd.c (ffffffff8129778a)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff812bafc3)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In lib/ioremap.c (ffffffff8144d82c)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178dab1)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/xen/mmu_pv.c (ffffffff820a6e4c)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810317c9)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff820adfaa)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e2bf)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106cd86)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff8106d891)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8106f4e2)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In mm/shmem.c (ffffffff811dcf05)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
```
In mm/gup.c (ffffffff811f0a66)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811f1bcd)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811f91d0)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811ff935)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812009c5)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81201e84)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812026b3)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
```
```
In mm/vmalloc.c (ffffffff812057ed)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8120a158)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8120dc2a)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff8121c02b)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff819053f5)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812218a2)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8122f46a)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81231e79)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff81239cc5)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff8123f11a)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff8124bcb7)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/userfaultfd.c (ffffffff812a50c7)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff812c813f)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff817abc5f)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff818ed4da)
Location: arch/x86/include/asm/pgtable.h:741
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
In arch/x86/xen/mmu_pv.c (ffffffff826ad4b2)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81033a46)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff826b44d3)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061fac)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81071a17)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff810722a2)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81074a62)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pti.c (ffffffff826c58b9)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In mm/shmem.c (ffffffff811eee1c)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff812055ed)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81208a0d)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff81211597)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81218027)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812193b2)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8121aa18)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8121b011)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
```
```
In mm/vmalloc.c (ffffffff8121f7e5)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff81223387)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81228dcc)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff81237431)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff8198f416)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8123cbaa)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8124b37a)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81252bfa)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff81258be2)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff8125ed4a)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff8126c02b)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff8126e823)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff812c85f3)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff812eba6d)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff81823203)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff8197360d)
Location: arch/x86/include/asm/pgtable.h:750
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
In arch/x86/xen/mmu_pv.c (ffffffff826d6891)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034d8a)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff826ddc28)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81065048)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81074706)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff810752ea)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810773cb)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107f62a)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff826ef9a5)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f028e)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/shmem.c (ffffffff8120f994)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff81226a74)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81229aab)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (ffffffff8123233d)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8123911d)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8123ac61)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8123c738)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8123d215)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
```
```
In mm/vmalloc.c (ffffffff81240f5a)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff81246231)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81248412)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8124a3b7)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff8125a99d)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff819ebca6)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812604c0)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8126df53)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812770e5)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff8127ce44)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff81283050)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff81288b49)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff81290aac)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812934b4)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff812f18a0)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff81318f57)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d4cc)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff819cfaa9)
Location: arch/x86/include/asm/pgtable.h:792
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
In arch/x86/xen/mmu_pv.c (ffffffff8288c7da)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81035f6a)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff82894070)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106acb8)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8107a5f6)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff8107b0ea)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8107dcbb)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81086216)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff8108a3cd)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a6f96)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/shmem.c (ffffffff81222754)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff81239b70)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8123cfc2)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (ffffffff81245b10)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8124d6b5)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124ee72)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81250b3c)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812516ed)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff81254c6a)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8125a651)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8125c9e2)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8125e9f7)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff8126e863)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81a26f14)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81274c23)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81282dc3)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81288934)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812919a8)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812990a0)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8129d84c)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff812a5a8e)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812a7a08)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81306260)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff81330004)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff8188f4a1)
Location: arch/x86/include/asm/pgtable.h:817
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a090a2)
Location: arch/x86/include/asm/pgtable.h:817
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
In arch/x86/xen/mmu_pv.c (ffffffff828a3c7a)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810380ca)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828ab81e)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e470)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e341)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff8107ea42)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810815bb)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089c42)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108e122)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf64c)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/shmem.c (ffffffff81231d5a)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8124ada6)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124ec3d)
Location: arch/x86/include/asm/pgtable.h:834
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
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (ffffffff81257c61)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8125f6b5)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812611cc)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81262e1c)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812639b4)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff8126701a)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff81275739)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81277bdb)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8127b248)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/mempolicy.c (ffffffff81289f2d)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81a977af)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8128f713)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff8129f4f1)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812a3575)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812abd5d)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812b4493)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812b8b25)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812c1181)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812c4bd8)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff813277bb)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff81357e39)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff818d94a1)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a78924)
Location: arch/x86/include/asm/pgtable.h:834
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
In arch/x86/xen/mmu_pv.c (ffffffff828a6d14)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103889a)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828ae82c)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106fa20)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107f3d1)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff8107fad2)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8108267b)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108a8b2)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108edbf)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c5ad3)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/shmem.c (ffffffff8123fe1a)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff81259296)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125d1fd)
Location: arch/x86/include/asm/pgtable.h:834
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
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (ffffffff81266171)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8126dec5)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8126f968)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812715cc)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81271e91)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
```
```
In mm/vmalloc.c (ffffffff8127591a)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff81284709)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812876cb)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8128ad28)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/mempolicy.c (ffffffff81299a9d)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81acf076)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8129f494)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812ae85d)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812b4a75)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812bde4c)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812c5db3)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812caa05)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812d30d1)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812d6573)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff8133a59b)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff81370069)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff8190b4a1)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81aafcd4)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
In arch/x86/xen/mmu_pv.c (ffffffff82cccee4)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b082)
Location: include/linux/pgtable.h:70
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81047aba)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076f29)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81085d55)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff81086ce0)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c015)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pte_range
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff81095160)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8d54)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In mm/shmem.c (ffffffff8126e635)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff81287f8b)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8128d80a)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault
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
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pte_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff812964b6)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8129e560)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8129ffd4)
Location: include/linux/pgtable.h:70
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812a1755)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/pagewalk.c (ffffffff812a2523)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/vmalloc.c (ffffffff812a7329)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pte_range
```
```
In mm/madvise.c (ffffffff812b6894)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812b88aa)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/swap_state.c:swap_ra_info
```
```
In mm/swapfile.c (ffffffff812bda55)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/mempolicy.c (ffffffff812cedf0)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7a2b)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812d3ae2)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812e3eb9)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812ea017)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff812f3709)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812fba98)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff81300842)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81307ed3)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage_pte
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/hmm.c (ffffffff8130b55c)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff813723d9)
Location: include/linux/pgtable.h:70
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813b8089)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffff815e97f8)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc499)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff82fb8d20)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b892)
Location: include/linux/pgtable.h:70
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81bd4d40)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077559)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086df7)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff810885c0)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d0da)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff81bda284)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd67da)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In kernel/events/core.c (ffffffff8123cb94)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/shmem.c (ffffffff81279033)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff81291c6b)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129fcbd)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault
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
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pte_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff812a1429)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812a9920)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812ab43c)
Location: include/linux/pgtable.h:70
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812ad015)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/pagewalk.c (ffffffff812ade5f)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/vmalloc.c (ffffffff812b25a9)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pte_range
```
```
In mm/ioremap.c (ffffffff812b809d)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_pte_range
```
```
In mm/madvise.c (ffffffff812c2ae4)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812c402a)
Location: include/linux/pgtable.h:70
Inline: True
```
```
In mm/swapfile.c (ffffffff812c9575)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/mempolicy.c (ffffffff812da730)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81c40761)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812df4e2)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812efc19)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812f51f4)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff812feee6)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff813076e8)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8130c9e2)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81313ed4)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/hmm.c (ffffffff8131741c)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81380229)
Location: include/linux/pgtable.h:70
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813c9f49)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff81bd1479)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff831c33e2)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103d231)
Location: include/linux/pgtable.h:70
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81bc7192)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077fe0)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81087aad)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff8108922f)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108dc90)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff81bcc3a8)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e1235)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In kernel/events/core.c (ffffffff81243ea8)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/filemap.c (ffffffff8125fd39)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/shmem.c (ffffffff8127dfe0)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8129778c)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812a555a)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff812a6c27)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812aedac)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812b083d)
Location: include/linux/pgtable.h:70
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812b2894)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812b3253)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/vmalloc.c (ffffffff812b8cde)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff812c9961)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812cae17)
Location: include/linux/pgtable.h:70
Inline: True
```
```
In mm/swapfile.c (ffffffff812cff14)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/mempolicy.c (ffffffff812e1fa0)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81c327ca)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812e7dff)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812f5593)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812fb73b)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff81305ae8)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff8130de6a)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff81313151)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff8131a092)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/hmm.c (ffffffff8131d851)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff813875b0)
Location: include/linux/pgtable.h:70
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813d15ab)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff81bc3483)
Location: include/linux/pgtable.h:70
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff832a3e1c)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81042d6e)
Location: include/linux/pgtable.h:89
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81c9a78b)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810857f2)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81096e2f)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff81098688)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109d540)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff81ca243a)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c4abf)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In kernel/events/core.c (ffffffff8127e819)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/filemap.c (ffffffff8129c6a9)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (ffffffff812d814c)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812e6a51)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
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
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff812e8107)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812f059c)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812f21cd)
Location: include/linux/pgtable.h:89
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812f44b9)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812f4de2)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/vmalloc.c (ffffffff812fb292)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff8130e981)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8130fe24)
Location: include/linux/pgtable.h:89
Inline: True
```
```
In mm/swapfile.c (ffffffff81315414)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/mempolicy.c (ffffffff81329080)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81d51223)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_remap_range
  - mm/sparse-vmemmap.c:vmemmap_remap_range
```
```
In mm/ksm.c (ffffffff8132fd2f)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff8133fb95)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff8134559c)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff8134f958)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff81358cc9)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8135f4bd)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81366dc7)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff8136abf1)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff813d4887)
Location: include/linux/pgtable.h:89
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81422aab)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff81c94493)
Location: include/linux/pgtable.h:89
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff834530a4)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8104acaa)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/tboot.c (ffffffff81e49bf7)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095bba)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810a9848)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff810ab2e1)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b0e1c)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff81e51b19)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff834774f8)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In kernel/events/core.c (ffffffff812d3487)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/filemap.c (ffffffff812f383f)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (ffffffff81338026)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8133d8ca)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
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
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:insert_pages
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff8134941d)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff8134c685)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff81353ad1)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81355f6c)
Location: include/linux/pgtable.h:90
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81358489)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81358cd4)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/vmalloc.c (ffffffff8136279b)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff81376816)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8137a81e)
Location: include/linux/pgtable.h:90
Inline: True
```
```
In mm/swapfile.c (ffffffff813809b1)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/mempolicy.c (ffffffff813982e4)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81f219a8)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_range
  - mm/sparse-vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/ksm.c (ffffffff813a00fa)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff813b4aee)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff813b701e)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813bb5cc)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff813c7c19)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff813d2eeb)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff813d9bd6)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff813e4228)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff813e8e57)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff8145fd34)
Location: include/linux/pgtable.h:90
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81499bc4)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff81e434c1)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff83e70596)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81056b81)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/tboot.c (ffffffff81067f39)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab802)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810c2c5c)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff810c369c)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cb531)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810d4da1)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea0b50)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In kernel/events/core.c (ffffffff8133b705)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/filemap.c (ffffffff8135db8f)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/vmscan.c (ffffffff8137e44c)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pte_range
```
```
In mm/gup.c (ffffffff813af7df)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813b68ee)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
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
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:insert_pages
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff813c17f9)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff813c520c)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff813cdf8a)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff813d05a3)
Location: include/linux/pgtable.h:90
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff813d2ac6)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813d35ab)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/vmalloc.c (ffffffff813de137)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff813f417a)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff813f833b)
Location: include/linux/pgtable.h:90
Inline: True
```
```
In mm/swapfile.c (ffffffff813ff413)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb_vmemmap.c (ffffffff814141ce)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/mempolicy.c (ffffffff81418087)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff820cb091)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8141efdd)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81433c59)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff81438b70)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8143d9b8)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff8144bdf5)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff8145870d)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8145ff97)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff8146bcc9)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff81470dc9)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff814ef623)
Location: include/linux/pgtable.h:90
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152de16)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff8201e568)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff83691410)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81057b59)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af3c2)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810c633c)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff810c6ee5)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ceb3f)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810d82a1)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4c5b)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In mm/memory.c (ffffffff813ecce2)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
```
```
In mm/pagewalk.c (ffffffff81407f25)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/pgtable-generic.c (ffffffff81409841)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/vmalloc.c (ffffffff81412991)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/hugetlb_vmemmap.c (ffffffff8144772e)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff8214f321)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In arch/x86/power/hibernate.c (ffffffff8209e562)
Location: include/linux/pgtable.h:90
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff838c0f20)
Location: include/linux/pgtable.h:92
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105edf9)
Location: include/linux/pgtable.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5f52)
Location: include/linux/pgtable.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810ce78c)
Location: include/linux/pgtable.h:92
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff810cf37f)
Location: include/linux/pgtable.h:92
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d721f)
Location: include/linux/pgtable.h:92
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810e0b21)
Location: include/linux/pgtable.h:92
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f585b)
Location: include/linux/pgtable.h:92
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In mm/memory.c (ffffffff81418237)
Location: include/linux/pgtable.h:92
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
```
```
In mm/pagewalk.c (ffffffff81434605)
Location: include/linux/pgtable.h:92
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/pgtable-generic.c (ffffffff8143607c)
Location: include/linux/pgtable.h:92
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/vmalloc.c (ffffffff8143f401)
Location: include/linux/pgtable.h:92
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/hugetlb_vmemmap.c (ffffffff81480f18)
Location: include/linux/pgtable.h:92
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_pmd_entry
  - mm/hugetlb_vmemmap.c:vmemmap_split_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff822321f1)
Location: include/linux/pgtable.h:92
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In arch/x86/power/hibernate.c (ffffffff82176562)
Location: include/linux/pgtable.h:92
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/mm/fault.c (ffffffe0000b9e1a)
Location: arch/riscv/include/asm/pgtable.h:196
Inline: True
Inline callers:
  - arch/riscv/mm/fault.c:do_page_fault
```
```
In mm/shmem.c (ffffffe0001ee308)
Location: arch/riscv/include/asm/pgtable.h:196
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffe00020460a)
Location: arch/riscv/include/asm/pgtable.h:196
Inline: True
```
```
In mm/memory.c (ffffffe00020675c)
Location: arch/riscv/include/asm/pgtable.h:196
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
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffe00020bb28)
Location: arch/riscv/include/asm/pgtable.h:196
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffe00021119e)
Location: arch/riscv/include/asm/pgtable.h:196
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffe000211ba2)
Location: arch/riscv/include/asm/pgtable.h:196
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffe000212712)
Location: arch/riscv/include/asm/pgtable.h:196
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffe000212a8e)
Location: arch/riscv/include/asm/pgtable.h:196
Inline: True
```
```
In mm/vmalloc.c (ffffffe000215224)
Location: arch/riscv/include/asm/pgtable.h:196
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffe00022052c)
Location: arch/riscv/include/asm/pgtable.h:196
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffe000223236)
Location: arch/riscv/include/asm/pgtable.h:196
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffe0002263de)
Location: arch/riscv/include/asm/pgtable.h:196
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffe000048f9e)
Location: arch/riscv/include/asm/pgtable.h:196
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffe000234916)
Location: arch/riscv/include/asm/pgtable.h:196
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffe00023f806)
Location: arch/riscv/include/asm/pgtable.h:196
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
```
```
In mm/memcontrol.c (ffffffe00024682e)
Location: arch/riscv/include/asm/pgtable.h:196
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffe0002504fe)
Location: arch/riscv/include/asm/pgtable.h:196
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffe000251f48)
Location: arch/riscv/include/asm/pgtable.h:196
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffe0002a879a)
Location: arch/riscv/include/asm/pgtable.h:196
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffe0002d34fc)
Location: arch/riscv/include/asm/pgtable.h:196
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffe0008b3182)
Location: arch/riscv/include/asm/pgtable.h:196
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
In arch/x86/xen/mmu_pv.c (ffffffff82894d1d)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810389fa)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8289c84b)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e9c0)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e3d1)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff8107ead2)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8108167b)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089872)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108dd7f)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b0a6b)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/shmem.c (ffffffff8123846a)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff812518e6)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125584d)
Location: arch/x86/include/asm/pgtable.h:834
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
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (ffffffff8125e7c1)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81266515)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81267fb8)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81269c1c)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8126a4e1)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
```
```
In mm/vmalloc.c (ffffffff8126df6a)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8127cd59)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8127fc95)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81283308)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/mempolicy.c (ffffffff8129207d)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81a6dee6)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81297a74)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a6e3d)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812ad055)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b642c)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812be393)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812c2fe5)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812cb6b1)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812ceb53)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81332b7b)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff81368649)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff818ab4a1)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a4eb24)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
In arch/x86/kernel/espfix_64.c (ffffffff81028330)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff82894a19)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ef07)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106d508)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff8106de4b)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810702c5)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810785e4)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff8107c883)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8bf0)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/shmem.c (ffffffff8122b48d)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff812447cd)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81247f1c)
Location: arch/x86/include/asm/pgtable.h:834
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
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff81250c00)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81258c00)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8125a283)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8125be85)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8125c997)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff8125ff61)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8126ebbe)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81271aed)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81274f69)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/mempolicy.c (ffffffff81283c19)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a417)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81289640)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81298c8c)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff8129e0a4)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812a75f3)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812af479)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812b4093)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff812bc53c)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812bf7b4)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff813234ea)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff8135994b)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff81865403)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a0bc30)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
In arch/x86/xen/mmu_pv.c (ffffffff828a7d14)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103885a)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828af80e)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ee70)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e381)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff8107ea82)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8108162b)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089822)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108dd2f)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c396a)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/shmem.c (ffffffff8123620a)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8124f686)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812535ed)
Location: arch/x86/include/asm/pgtable.h:834
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
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (ffffffff8125c561)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812642b5)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81265d58)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812679bc)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81268281)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
```
```
In mm/vmalloc.c (ffffffff8126bd0a)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8127aaf9)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8127dabb)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81281118)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/mempolicy.c (ffffffff8128fe8d)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81ada2f6)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81295884)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a4c4d)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812aae65)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b423c)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812bc1a3)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812c0df5)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812c94c1)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812cc963)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff8133064b)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff81366119)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff818fc4a1)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81abaf14)
Location: arch/x86/include/asm/pgtable.h:834
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
In arch/x86/xen/mmu_pv.c (ffffffff828a7d1a)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103985a)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828af83c)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810710f0)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81080471)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff81080b72)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8108374b)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108bac2)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8109010f)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c6b10)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/shmem.c (ffffffff812464e7)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8125eff6)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81262fdd)
Location: arch/x86/include/asm/pgtable.h:834
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
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mincore.c (ffffffff8126bf4a)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81273c75)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812756fa)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81277352)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81277c01)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
```
```
In mm/vmalloc.c (ffffffff8127b71a)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8128a6d9)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8128d66b)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81290e22)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/mempolicy.c (ffffffff8129f326)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81ae67ac)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812a56a1)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812b57a9)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812bb1b5)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812c470c)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812cc974)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812d18b5)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812da1a1)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812dd6d8)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81342f99)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff81379d02)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff8191d4a1)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81ac7364)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
</details>
</li>
</ul>

## Differences
