# Function: <code>pmd_page_vaddr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81f62ff9)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034826)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81f6a39e)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bbce)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81068c10)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
Direct callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/fault.c (ffffffff8106a35c)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c320)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/gup.c (ffffffff810714c8)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In mm/gup.c (ffffffff811ba46f)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811bb830)
Location: arch/x86/include/asm/pgtable.h:522
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
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:__get_locked_pte
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
```
```
In mm/mincore.c (ffffffff811c27ee)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811c87d7)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811c95e4)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811ca965)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - mm/rmap.c:__page_check_address
```
```
In mm/vmalloc.c (ffffffff811cc62e)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/pagewalk.c (ffffffff811cfffe)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
```
```
In mm/madvise.c (ffffffff811d15b5)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff811d438d)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff811e00f1)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff8181f221)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff811e569b)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff811f0bee)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff811f4a0e)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memcontrol.c (ffffffff811fb053)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In mm/userfaultfd.c (ffffffff81207a52)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mfill_zeropage
```
```
In fs/userfaultfd.c (ffffffff8125b078)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff8127837a)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In lib/ioremap.c (ffffffff813eb251)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
```
**Symbols:**

```
ffffffff81068c10-ffffffff81068c4b: pmd_page_vaddr (STB_LOCAL)
ffffffff811bb830-ffffffff811bb86b: pmd_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81f8aba7)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810339e9)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81f926a4)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bcb4)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81069b9b)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff81069fb4)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c1a8)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/gup.c (ffffffff81071777)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810741ee)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/gup.c (ffffffff811d5841)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811dae49)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
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
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
```
```
In mm/mincore.c (ffffffff811de3a9)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811e4a86)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e59b2)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811e7817)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:__page_check_address
```
```
In mm/vmalloc.c (ffffffff811e9692)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/pagewalk.c (ffffffff811ed193)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
```
```
In mm/madvise.c (ffffffff811eeb6e)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff811f2182)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff811fee06)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff818998c7)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81204144)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff8121196b)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8121623e)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8121be4b)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8122112b)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff8122d88e)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/userfaultfd.c (ffffffff81283ba7)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff812a5665)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In lib/ioremap.c (ffffffff814315c9)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff8176094d)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff81068900-ffffffff81068938: pmd_page_vaddr (STB_LOCAL)
ffffffff811d6260-ffffffff811d6298: pmd_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81fc5f95)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81033613)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81fcd970)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ec2e)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106d759)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8106db54)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8106fdc8)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/gup.c (ffffffff81075307)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81077d66)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/gup.c (ffffffff811e5841)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811eaa4f)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
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
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
```
```
In mm/mincore.c (ffffffff811ee1c7)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811f4a72)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f5bee)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff811f6fa1)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff811f7583)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
```
```
In mm/rmap.c (ffffffff811f8ba7)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:__page_check_address
```
```
In mm/vmalloc.c (ffffffff811fa9e2)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff811ff4ad)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81202b7a)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff81210641)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff818cdf79)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812160b2)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81223b2a)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812287e1)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8122e355)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff81233874)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff8123fdda)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/userfaultfd.c (ffffffff81297797)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff812bafc3)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In lib/ioremap.c (ffffffff8144d839)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178dac2)
Location: arch/x86/include/asm/pgtable.h:559
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff8106c550-ffffffff8106c588: pmd_page_vaddr (STB_LOCAL)
ffffffff811e61f0-ffffffff811e6228: pmd_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff820a6e4c)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810317cc)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff820adfba)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e2ca)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106cda7)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8106d891)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8106f4f8)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810766cf)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/shmem.c (ffffffff811dcf05)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
```
In mm/gup.c (ffffffff811f0a69)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811f1bcd)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
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
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mincore.c (ffffffff811f91d0)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811ff935)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812009c5)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81201e99)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812026b3)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
```
```
In mm/vmalloc.c (ffffffff812057ed)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8120a158)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8120dc3b)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff8121c02b)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff8190540e)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812218a2)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8122f46a)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81231e79)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff81239cc5)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff8123f11a)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff8124bcb7)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/userfaultfd.c (ffffffff812a50d4)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff812c813f)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff817abc70)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff818ed4e7)
Location: arch/x86/include/asm/pgtable.h:698
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8106b960-ffffffff8106b998: pmd_page_vaddr (STB_LOCAL)
ffffffff811f8e11-ffffffff811f8e47: pmd_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff826ad4b2)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81033a49)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff826b44e3)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061fb7)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81071a2a)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff810722ac)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81074a7b)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81079550)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107c935)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff826c58b9)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In mm/shmem.c (ffffffff811eee38)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff812055f0)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81208a2d)
Location: arch/x86/include/asm/pgtable.h:708
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
In mm/mincore.c (ffffffff812115b5)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81218049)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812193d5)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8121aa2d)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8121b011)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
```
```
In mm/vmalloc.c (ffffffff8121f7f2)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff812233ab)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81228dcc)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff8123744f)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff8198f432)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8123cbc9)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8124b399)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81252bfa)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff81258be2)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff8125ed68)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff8126c04b)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff8126e830)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff812c8603)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff812eba8c)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff81823214)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff8197361a)
Location: arch/x86/include/asm/pgtable.h:708
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81070300-ffffffff81070352: pmd_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff826d6891)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034d9b)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff826ddc32)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81065053)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81074706)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff810752f4)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810773cb)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8107ccda)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107f636)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff826ef9a5)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f028e)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/shmem.c (ffffffff8120f994)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff81226a7a)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81229aab)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8123233d)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8123911d)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8123ac67)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8123c73e)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8123d21b)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
```
```
In mm/vmalloc.c (ffffffff81240f64)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff81246231)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81248424)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8124a3b7)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff8125a99d)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff819ebca6)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812604c0)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8126df53)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812770f0)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff8127ce44)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff81283050)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff81288b4f)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff81290aac)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812934c1)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff812f18a6)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff81318f57)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d4dd)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff819cfab6)
Location: arch/x86/include/asm/pgtable.h:750
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff810731f0-ffffffff81073236: pmd_page_vaddr (STB_LOCAL)
ffffffff81228da0-ffffffff81228de6: pmd_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8288c7da)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81035f7b)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8289407b)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106acc3)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8107a5f6)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8107b0f4)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8107dcbb)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff810836f5)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81086216)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff8108a3d3)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a6f96)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/shmem.c (ffffffff81222754)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff81239b76)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8123cfc2)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
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
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mincore.c (ffffffff81245b10)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8124d6b5)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124ee72)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81250b42)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812516f3)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff81254c74)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8125a651)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8125c9f4)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8125e9f7)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff8126e863)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81a26f14)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81274c23)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81282dc3)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff8128893f)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812919a8)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812990a0)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8129d852)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff812a5a8e)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812a7a12)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81306266)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff81330004)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff8188f4b2)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a090b0)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81079290-ffffffff810792d6: pmd_page_vaddr (STB_LOCAL)
ffffffff8123c640-ffffffff8123c686: pmd_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff828a3c7a)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810380db)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828ab829)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e47b)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e341)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8107ea4c)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810815bb)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81087366)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089c4e)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108e128)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf64c)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/shmem.c (ffffffff81231d5a)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8124adb0)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124ec3d)
Location: arch/x86/include/asm/pgtable.h:792
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
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8125f6b5)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812611cc)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81262e22)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812639ba)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff81267024)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff81275739)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81277bec)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8127b252)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/mempolicy.c (ffffffff81289f2d)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81a977bf)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8128f713)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff8129f4f1)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812a3580)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812abd5d)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812b4493)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812b8b2b)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812c1181)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812c4be2)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff813277c1)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff81357e39)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff818d94b2)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a78932)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8107cea0-ffffffff8107cee6: pmd_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff828a6d14)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810388ab)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828ae837)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106fa2b)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107f3d1)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8107fadc)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8108267b)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81088056)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108a8be)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108edc5)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c5ad3)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/shmem.c (ffffffff8123fe1a)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff812592a0)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125d1fd)
Location: arch/x86/include/asm/pgtable.h:792
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
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8126dec5)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8126f968)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812715d2)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81271e9b)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
```
```
In mm/vmalloc.c (ffffffff81275924)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff81284709)
Location: arch/x86/include/asm/pgtable.h:792
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
In mm/swap_state.c (ffffffff812876dc)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8128ad32)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/mempolicy.c (ffffffff81299a9d)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81acf086)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8129f494)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812ae85d)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812b4a80)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812bde4c)
Location: arch/x86/include/asm/pgtable.h:792
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
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812caa0b)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812d30d1)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812d657d)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff8133a5a1)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff81370069)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff8190b4b2)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81aafce2)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8107df30-ffffffff8107df76: pmd_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82cccee8)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b093)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81047ac0)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076f33)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81085d5b)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff81086cea)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a4f6)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c03b)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pte_range
  - arch/x86/mm/pat/set_memory.c:unmap_pte_range
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff81095168)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8d60)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In mm/shmem.c (ffffffff8126e638)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff81287f8b)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8128d80a)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pte_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
Direct callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_pte_range
```
```
In mm/mincore.c (ffffffff812964b6)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8129e560)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8129ffd4)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812a176b)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/pagewalk.c (ffffffff812a2523)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/vmalloc.c (ffffffff812a7333)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pte_range
```
```
In mm/madvise.c (ffffffff812b689b)
Location: arch/x86/include/asm/pgtable.h:828
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
In mm/swap_state.c (ffffffff812b88b4)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - mm/swap_state.c:swap_ra_info
```
```
In mm/swapfile.c (ffffffff812bda66)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/mempolicy.c (ffffffff812cedf0)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7a3a)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812d3ae2)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812e3eb9)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812ea01e)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff812f370c)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812fba9b)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff81300849)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81307ed3)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage_pte
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/hmm.c (ffffffff8130b563)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff813723e0)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813b8089)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffff815e9805)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc4aa)
Location: arch/x86/include/asm/pgtable.h:828
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810862cf-ffffffff81086303: pmd_page_vaddr (STB_LOCAL)
ffffffff8128bf10-ffffffff8128bf50: pmd_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82fb8d24)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b8a3)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81bd4d47)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077563)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086dfb)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff810885ca)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a7c6)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d0dd)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff81bda28c)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd67e6)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In kernel/events/core.c (ffffffff8123cb9e)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/shmem.c (ffffffff81279036)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff81291c6b)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129fcbd)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pte_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
Direct callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
```
```
In mm/mincore.c (ffffffff812a1429)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812a9920)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812ab43c)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812ad02b)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/pagewalk.c (ffffffff812ade5f)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/vmalloc.c (ffffffff812b25b3)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pte_range
```
```
In mm/ioremap.c (ffffffff812b80aa)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_pte_range
```
```
In mm/madvise.c (ffffffff812c2aeb)
Location: arch/x86/include/asm/pgtable.h:827
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
In mm/swap_state.c (ffffffff812c4034)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
```
```
In mm/swapfile.c (ffffffff812c9586)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/mempolicy.c (ffffffff812da730)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81c4077b)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812df4e2)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812efc19)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812f51fb)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff812feee9)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff813076eb)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8130c9e9)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81313ed4)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/hmm.c (ffffffff81317423)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81380230)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813c9f49)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff81bd148a)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81bd8c13-ffffffff81bd8c47: pmd_page_vaddr (STB_LOCAL)
ffffffff81296e90-ffffffff81296ed0: pmd_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff831c33e2)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103d242)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81bc7199)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077fea)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81087ab1)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8108923c)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff8108b3f6)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108dc93)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff81bcc3b0)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e1250)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In kernel/events/core.c (ffffffff81243eb3)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/filemap.c (ffffffff8125fd39)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/shmem.c (ffffffff8127dfe3)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8129778c)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812a09cd)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
Direct callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
```
```
In mm/mincore.c (ffffffff812a6c27)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812aedac)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812b083d)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812b28a5)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812b3253)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/vmalloc.c (ffffffff812b8ce8)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff812c9968)
Location: arch/x86/include/asm/pgtable.h:827
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
In mm/swap_state.c (ffffffff812cae25)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
```
```
In mm/swapfile.c (ffffffff812cff14)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/mempolicy.c (ffffffff812e1fa0)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81c327e4)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812e7dff)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812f5593)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812fb742)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff81305aeb)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff8130de6d)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff81313158)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff8131a092)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/hmm.c (ffffffff8131d858)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff813875b7)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813d15ab)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff81bc3494)
Location: arch/x86/include/asm/pgtable.h:827
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81bcaac3-ffffffff81bcaaf7: pmd_page_vaddr (STB_LOCAL)
ffffffff8129c310-ffffffff8129c35a: pmd_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff832a3e1c)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81042d7f)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81c9a792)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810857fc)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81096e32)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff81098692)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a996)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109d543)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff81ca2442)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c4ada)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In kernel/events/core.c (ffffffff8127e823)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/filemap.c (ffffffff8129c6a9)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (ffffffff812d814c)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812e1a84)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
Direct callers:
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
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
```
```
In mm/mincore.c (ffffffff812e8107)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812f059c)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812f21cd)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812f44c8)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812f4de2)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/vmalloc.c (ffffffff812fb29c)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff8130e988)
Location: arch/x86/include/asm/pgtable.h:798
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
In mm/swap_state.c (ffffffff8130fe32)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
```
```
In mm/swapfile.c (ffffffff81315425)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/mempolicy.c (ffffffff81329080)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81d5123c)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_remap_range
  - mm/sparse-vmemmap.c:vmemmap_remap_range
```
```
In mm/ksm.c (ffffffff8132fd2f)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff8133fb95)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff813455a3)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff8134f95b)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff81358ccc)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8135f4bd)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81366dc7)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff8136abf8)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff813d488e)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81422aab)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff81c944a4)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81c9ffab-ffffffff81c9ffdf: pmd_page_vaddr (STB_LOCAL)
ffffffff812dce10-ffffffff812dce5a: pmd_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff834530a4)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8104acbc)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/tboot.c (ffffffff81e49bff)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095bc4)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810a984e)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff810ab2ec)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff810adc85)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b0e1f)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff81e51b21)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83477509)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In kernel/events/core.c (ffffffff812d3491)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/filemap.c (ffffffff812f3847)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (ffffffff81338035)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8133edd1)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:insert_pages
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
Direct callers:
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
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
```
```
In mm/mincore.c (ffffffff8134941d)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff8134c685)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff81353ad1)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81355f6c)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81358498)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81358cd4)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/vmalloc.c (ffffffff813627a5)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff81376816)
Location: arch/x86/include/asm/pgtable.h:796
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
In mm/swap_state.c (ffffffff8137a82c)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
```
```
In mm/swapfile.c (ffffffff813809c1)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/mempolicy.c (ffffffff813982e4)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff8139c092)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_range
  - mm/sparse-vmemmap.c:__split_vmemmap_huge_pmd
Direct callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff813a00fa)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff813b4aee)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff813b701e)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813bb5d3)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff813c7c19)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff813d2eeb)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff813d9bd6)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff813e4228)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff813e8e5e)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff8145fd3b)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81499bc4)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff81e434d2)
Location: arch/x86/include/asm/pgtable.h:796
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810a8020-ffffffff810a806f: pmd_page_vaddr (STB_LOCAL)
ffffffff8133ca80-ffffffff8133cada: pmd_page_vaddr (STB_LOCAL)
ffffffff8139c300-ffffffff8139c34f: pmd_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff83e70596)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81056b93)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/tboot.c (ffffffff81067f46)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab80c)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810c2c5f)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff810c36a7)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7ea4)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cb534)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810d4dab)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea0b60)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In kernel/events/core.c (ffffffff8133b70f)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/filemap.c (ffffffff8135dba6)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/vmscan.c (ffffffff8137e450)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pte_range
```
```
In mm/gup.c (ffffffff813af7df)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813b60b6)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:insert_pages
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
Direct callers:
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
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
```
```
In mm/mincore.c (ffffffff813c17f9)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff813c520c)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff813cdf8a)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff813d05a3)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff813d2ad9)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813d35ab)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/vmalloc.c (ffffffff813de141)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff813f4181)
Location: arch/x86/include/asm/pgtable.h:813
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
In mm/swap_state.c (ffffffff813f8349)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
```
```
In mm/swapfile.c (ffffffff813ff424)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb_vmemmap.c (ffffffff814141d1)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/mempolicy.c (ffffffff81418087)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff820cb0b9)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8141efdd)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81433c59)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff81438b70)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8143d9bc)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff8144bdf5)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff81458710)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8145ff97)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff8146bcc9)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff81470dcd)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff814ef626)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152de16)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff8201e579)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff813b6690-ffffffff813b66f1: pmd_page_vaddr (STB_LOCAL)
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
Location: arch/x86/include/asm/pgtable.h:814
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81057b6b)
Location: arch/x86/include/asm/pgtable.h:814
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af3cc)
Location: arch/x86/include/asm/pgtable.h:814
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810c633f)
Location: arch/x86/include/asm/pgtable.h:814
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff810c6ef0)
Location: arch/x86/include/asm/pgtable.h:814
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff810cb5e4)
Location: arch/x86/include/asm/pgtable.h:814
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ceb42)
Location: arch/x86/include/asm/pgtable.h:814
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810d82ab)
Location: arch/x86/include/asm/pgtable.h:814
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4c6b)
Location: arch/x86/include/asm/pgtable.h:814
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In mm/memory.c (ffffffff813eccf4)
Location: arch/x86/include/asm/pgtable.h:814
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
```
```
In mm/pagewalk.c (ffffffff81407f28)
Location: arch/x86/include/asm/pgtable.h:814
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/pgtable-generic.c (ffffffff8140984f)
Location: arch/x86/include/asm/pgtable.h:814
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/vmalloc.c (ffffffff8141299b)
Location: arch/x86/include/asm/pgtable.h:814
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/hugetlb_vmemmap.c (ffffffff81447731)
Location: arch/x86/include/asm/pgtable.h:814
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff8214f349)
Location: arch/x86/include/asm/pgtable.h:814
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In arch/x86/power/hibernate.c (ffffffff8209e573)
Location: arch/x86/include/asm/pgtable.h:814
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
Location: arch/x86/include/asm/pgtable.h:1029
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105ee0b)
Location: arch/x86/include/asm/pgtable.h:1029
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5f5c)
Location: arch/x86/include/asm/pgtable.h:1029
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810ce78f)
Location: arch/x86/include/asm/pgtable.h:1029
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff810cf38a)
Location: arch/x86/include/asm/pgtable.h:1029
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff810d3b44)
Location: arch/x86/include/asm/pgtable.h:1029
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d7222)
Location: arch/x86/include/asm/pgtable.h:1029
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810e0b2b)
Location: arch/x86/include/asm/pgtable.h:1029
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f586b)
Location: arch/x86/include/asm/pgtable.h:1029
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In mm/memory.c (ffffffff81418249)
Location: arch/x86/include/asm/pgtable.h:1029
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
```
```
In mm/pagewalk.c (ffffffff81434608)
Location: arch/x86/include/asm/pgtable.h:1029
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/pgtable-generic.c (ffffffff81436089)
Location: arch/x86/include/asm/pgtable.h:1029
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/vmalloc.c (ffffffff8143f40b)
Location: arch/x86/include/asm/pgtable.h:1029
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/hugetlb_vmemmap.c (ffffffff81480f22)
Location: arch/x86/include/asm/pgtable.h:1029
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_pmd_entry
  - mm/hugetlb_vmemmap.c:vmemmap_split_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff82232219)
Location: arch/x86/include/asm/pgtable.h:1029
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In arch/x86/power/hibernate.c (ffffffff82176573)
Location: arch/x86/include/asm/pgtable.h:1029
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
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/mm/flush.c (c031edcc)
Location: arch/arm/include/asm/pgtable.h:189
Inline: True
Inline callers:
  - arch/arm/mm/flush.c:__flush_anon_page
  - arch/arm/mm/flush.c:flush_icache_alias
```
```
In arch/arm/mm/mmu.c (c15087f0)
Location: arch/arm/include/asm/pgtable.h:189
Inline: True
Inline callers:
  - arch/arm/mm/mmu.c:arm_pte_alloc
  - arch/arm/mm/mmu.c:pte_offset_late_fixmap
```
```
In arch/arm/mm/dump.c (c0320420)
Location: arch/arm/include/asm/pgtable.h:189
Inline: True
Inline callers:
  - arch/arm/mm/dump.c:walk_pmd
```
```
In arch/arm/mm/highmem.c (c0321d5c)
Location: arch/arm/include/asm/pgtable.h:189
Inline: True
Inline callers:
  - arch/arm/mm/highmem.c:kmap_atomic_pfn
```
```
In arch/arm/mm/copypage-v6.c (0)
Location: arch/arm/include/asm/pgtable.h:189
Inline: True
```
```
In mm/memory.c (c0518388)
Location: arch/arm/include/asm/pgtable.h:189
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
```
```
In mm/vmalloc.c (c05282c8)
Location: arch/arm/include/asm/pgtable.h:189
Inline: True
```
```
In lib/ioremap.c (c0e84324)
Location: arch/arm/include/asm/pgtable.h:189
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
</details>
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
Location: arch/riscv/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - arch/riscv/mm/fault.c:do_page_fault
```
```
In mm/shmem.c (ffffffe0001ee30e)
Location: arch/riscv/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffe000204640)
Location: arch/riscv/include/asm/pgtable.h:173
Inline: True
```
```
In mm/memory.c (ffffffe000206772)
Location: arch/riscv/include/asm/pgtable.h:173
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
In mm/mincore.c (ffffffe00020bb40)
Location: arch/riscv/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffe0002111b8)
Location: arch/riscv/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffe000211bbc)
Location: arch/riscv/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffe000212712)
Location: arch/riscv/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffe000212a8e)
Location: arch/riscv/include/asm/pgtable.h:173
Inline: True
```
```
In mm/vmalloc.c (ffffffe000215224)
Location: arch/riscv/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffe000220536)
Location: arch/riscv/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffe000223236)
Location: arch/riscv/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffe0002263de)
Location: arch/riscv/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffe000048f9e)
Location: arch/riscv/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffe00023492c)
Location: arch/riscv/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffe00023f80e)
Location: arch/riscv/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
```
```
In mm/memcontrol.c (ffffffe000246838)
Location: arch/riscv/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffe000250522)
Location: arch/riscv/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffe000251f48)
Location: arch/riscv/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffe0002a879a)
Location: arch/riscv/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffe0002d351e)
Location: arch/riscv/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffe0008b3182)
Location: arch/riscv/include/asm/pgtable.h:173
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
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82894d1d)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038a0b)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8289c856)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e9cb)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e3d1)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8107eadc)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8108167b)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81087056)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108987e)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108dd85)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b0a6b)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/shmem.c (ffffffff8123846a)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff812518f0)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125584d)
Location: arch/x86/include/asm/pgtable.h:792
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
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81266515)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81267fb8)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81269c22)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8126a4eb)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
```
```
In mm/vmalloc.c (ffffffff8126df74)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8127cd59)
Location: arch/x86/include/asm/pgtable.h:792
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
In mm/swap_state.c (ffffffff8127fca7)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81283312)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/mempolicy.c (ffffffff8129207d)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81a6def6)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81297a74)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a6e3d)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812ad060)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b642c)
Location: arch/x86/include/asm/pgtable.h:792
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
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812c2feb)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812cb6b1)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812ceb5d)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81332b81)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff81368649)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff818ab4b2)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a4eb32)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8107cf30-ffffffff8107cf76: pmd_page_vaddr (STB_LOCAL)
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
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff82894a1c)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ef17)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106d50c)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff8106de4b)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810702eb)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pgtable.c (ffffffff81075c46)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810785f1)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff8107c88e)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8bf0)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/shmem.c (ffffffff8122b48d)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff812447d9)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81247f1c)
Location: arch/x86/include/asm/pgtable.h:792
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
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81258c00)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8125a283)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8125be88)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8125c99e)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff8125ff61)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8126ebbe)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81271afb)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81274f69)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/mempolicy.c (ffffffff81283c19)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a437)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81289640)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81298c96)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff8129e0c2)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812a75f3)
Location: arch/x86/include/asm/pgtable.h:792
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
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812b4093)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff812bc53c)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812bf7b7)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff813234ed)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff8135994b)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff81865403)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a0bc47)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff828a7d14)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103886b)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828af819)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ee7b)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e381)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8107ea8c)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8108162b)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81087006)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108982e)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108dd35)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c396a)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/shmem.c (ffffffff8123620a)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8124f690)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812535ed)
Location: arch/x86/include/asm/pgtable.h:792
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
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812642b5)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81265d58)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812679c2)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8126828b)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
```
```
In mm/vmalloc.c (ffffffff8126bd14)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8127aaf9)
Location: arch/x86/include/asm/pgtable.h:792
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
In mm/swap_state.c (ffffffff8127dacc)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81281122)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/mempolicy.c (ffffffff8128fe8d)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81ada306)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81295884)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a4c4d)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812aae70)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b423c)
Location: arch/x86/include/asm/pgtable.h:792
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
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812c0dfb)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812c94c1)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812cc96d)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81330651)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff81366119)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff818fc4b2)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81abaf22)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8107cee0-ffffffff8107cf26: pmd_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff828a7d1a)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103986b)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828af847)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810710fb)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81080471)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff81080b7c)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8108374b)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81089136)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108bace)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff81090115)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c6b10)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/shmem.c (ffffffff812464e7)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8125f000)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81262fdd)
Location: arch/x86/include/asm/pgtable.h:792
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
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81273c75)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812756fa)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81277358)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81277c0b)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
```
```
In mm/vmalloc.c (ffffffff8127b724)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8128a6d9)
Location: arch/x86/include/asm/pgtable.h:792
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
In mm/swap_state.c (ffffffff8128d67c)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81290e2c)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/mempolicy.c (ffffffff8129f326)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81ae67bc)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812a56a1)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812b57a9)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812bb1c0)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812c470c)
Location: arch/x86/include/asm/pgtable.h:792
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
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812d18bb)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812da1a1)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812dd6e2)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81342f9f)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff81379d02)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff8191d4b2)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81ac7372)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8107efd0-ffffffff8107f016: pmd_page_vaddr (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
