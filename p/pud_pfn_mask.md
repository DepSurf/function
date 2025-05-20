# Function: <code>pud_pfn_mask</code>

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
In arch/x86/xen/mmu.c (ffffffff8101e674)
Location: arch/x86/include/asm/pgtable_types.h:279
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034584)
Location: arch/x86/include/asm/pgtable_types.h:279
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81f6a367)
Location: arch/x86/include/asm/pgtable_types.h:279
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ba65)
Location: arch/x86/include/asm/pgtable_types.h:279
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81068c5b)
Location: arch/x86/include/asm/pgtable_types.h:279
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
```
```
In arch/x86/mm/fault.c (ffffffff8106a280)
Location: arch/x86/include/asm/pgtable_types.h:279
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff81f77df9)
Location: arch/x86/include/asm/pgtable_types.h:279
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c5a7)
Location: arch/x86/include/asm/pgtable_types.h:279
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/gup.c (ffffffff810715e8)
Location: arch/x86/include/asm/pgtable_types.h:279
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pud
  - arch/x86/mm/gup.c:gup_huge_pud
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In mm/gup.c (ffffffff811ba837)
Location: arch/x86/include/asm/pgtable_types.h:279
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811bbea0)
Location: arch/x86/include/asm/pgtable_types.h:279
Inline: True
Inline callers:
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mprotect.c (ffffffff811c8589)
Location: arch/x86/include/asm/pgtable_types.h:279
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811c93c9)
Location: arch/x86/include/asm/pgtable_types.h:279
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811ca865)
Location: arch/x86/include/asm/pgtable_types.h:279
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811cc600)
Location: arch/x86/include/asm/pgtable_types.h:279
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/pagewalk.c (ffffffff811cfe64)
Location: arch/x86/include/asm/pgtable_types.h:279
Inline: True
```
```
In mm/swapfile.c (ffffffff811d4212)
Location: arch/x86/include/asm/pgtable_types.h:279
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811dd6d3)
Location: arch/x86/include/asm/pgtable_types.h:279
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff8181f2f6)
Location: arch/x86/include/asm/pgtable_types.h:279
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff811f6f44)
Location: arch/x86/include/asm/pgtable_types.h:279
Inline: True
Inline callers:
  - mm/huge_memory.c:page_check_address_pmd
  - mm/huge_memory.c:page_check_address_pmd
  - mm/huge_memory.c:split_huge_page_address
  - mm/huge_memory.c:split_huge_page_address
```
```
In mm/userfaultfd.c (ffffffff8120778f)
Location: arch/x86/include/asm/pgtable_types.h:279
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8125af40)
Location: arch/x86/include/asm/pgtable_types.h:279
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff813eb124)
Location: arch/x86/include/asm/pgtable_types.h:279
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
In arch/x86/xen/mmu.c (ffffffff81f8ab43)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103374e)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81f92643)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bb53)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff810699d0)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff81069eb8)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff81fa0540)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8106dc0a)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/gup.c (ffffffff81071bc3)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
  - arch/x86/mm/gup.c:gup_huge_pud
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810740ca)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/gup.c (ffffffff811d57fc)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811da95d)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811e47c0)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e57b1)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811e773f)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811e965b)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/pagewalk.c (ffffffff811ed008)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
```
```
In mm/swapfile.c (ffffffff811f208b)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811fb9c8)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff818999aa)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff8121673f)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8122d067)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81283b07)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff8143151f)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81760866)
Location: arch/x86/include/asm/pgtable_types.h:317
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
In arch/x86/xen/mmu.c (ffffffff81fc5f31)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103337e)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81fcd90f)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105eacd)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106d5aa)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8106da58)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff81fdbab1)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81071896)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/gup.c (ffffffff81075733)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
  - arch/x86/mm/gup.c:gup_huge_pud
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81077c42)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/gup.c (ffffffff811e57fc)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811ea4ca)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811f47e0)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f59f0)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff811f6ed9)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff811f73f8)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
```
```
In mm/rmap.c (ffffffff811f8acf)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811fa9ab)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81202a7e)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8120c4c8)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff818ce05c)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff81228cff)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8123f587)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812976f9)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff8144d78f)
Location: arch/x86/include/asm/pgtable_types.h:317
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178d9c6)
Location: arch/x86/include/asm/pgtable_types.h:317
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
In arch/x86/xen/mmu_pv.c (ffffffff820a6d64)
Location: arch/x86/include/asm/pgtable_types.h:354
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103155a)
Location: arch/x86/include/asm/pgtable_types.h:354
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff820adf59)
Location: arch/x86/include/asm/pgtable_types.h:354
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e16f)
Location: arch/x86/include/asm/pgtable_types.h:354
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106cbeb)
Location: arch/x86/include/asm/pgtable_types.h:354
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8106d788)
Location: arch/x86/include/asm/pgtable_types.h:354
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff820bca73)
Location: arch/x86/include/asm/pgtable_types.h:354
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810708d8)
Location: arch/x86/include/asm/pgtable_types.h:354
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81074088)
Location: arch/x86/include/asm/pgtable_types.h:354
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107652f)
Location: arch/x86/include/asm/pgtable_types.h:354
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/gup.c (ffffffff811f0926)
Location: arch/x86/include/asm/pgtable_types.h:354
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811f1a88)
Location: arch/x86/include/asm/pgtable_types.h:354
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811ff739)
Location: arch/x86/include/asm/pgtable_types.h:354
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812007ba)
Location: arch/x86/include/asm/pgtable_types.h:354
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81201d7a)
Location: arch/x86/include/asm/pgtable_types.h:354
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812023f5)
Location: arch/x86/include/asm/pgtable_types.h:354
Inline: True
```
```
In mm/rmap.c (ffffffff81203abf)
Location: arch/x86/include/asm/pgtable_types.h:354
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81205724)
Location: arch/x86/include/asm/pgtable_types.h:354
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8120daa7)
Location: arch/x86/include/asm/pgtable_types.h:354
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81217e48)
Location: arch/x86/include/asm/pgtable_types.h:354
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff819054f1)
Location: arch/x86/include/asm/pgtable_types.h:354
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff812349f0)
Location: arch/x86/include/asm/pgtable_types.h:354
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/userfaultfd.c (ffffffff8124aedb)
Location: arch/x86/include/asm/pgtable_types.h:354
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812a5032)
Location: arch/x86/include/asm/pgtable_types.h:354
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff817abbb3)
Location: arch/x86/include/asm/pgtable_types.h:354
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff818ed440)
Location: arch/x86/include/asm/pgtable_types.h:354
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826a6477)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826ad4af)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810337b7)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff826b4469)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061e4d)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8107184b)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810721b7)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff826c34e1)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810760d5)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81079ef4)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107c732)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff81080221)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pud_page_vaddr
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5eb7)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff8120551e)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff81208811)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81217cd0)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81218f8b)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8121a8a0)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8121b306)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
```
```
In mm/rmap.c (ffffffff8121c7d0)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8121f71e)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81228d92)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81232c36)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8198f536)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff81249faf)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
```
```
In mm/huge_memory.c (ffffffff812543f8)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/userfaultfd.c (ffffffff8126b15a)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812c8455)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff81823162)
Location: arch/x86/include/asm/pgtable_types.h:379
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff8197356e)
Location: arch/x86/include/asm/pgtable_types.h:379
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826cf602)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826d67f4)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034b34)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff826ddbea)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81064efa)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8107450d)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8107521a)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff826ed743)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81078bc0)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff8107cb5b)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107f4d2)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff81083460)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efc92)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f0331)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff8122699c)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8122984a)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81239b72)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
  - mm/mprotect.c:change_protection
```
```
In mm/mremap.c (ffffffff8123a957)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8123c644)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8123d084)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
```
```
In mm/rmap.c (ffffffff8123e5b3)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81240e9c)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8124a092)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81255c82)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff819ebdd6)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff8126ef23)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
```
```
In mm/huge_memory.c (ffffffff81278278)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff81288a25)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff8128fb4b)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812f159e)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d445)
Location: arch/x86/include/asm/pgtable_types.h:378
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff819cfa13)
Location: arch/x86/include/asm/pgtable_types.h:378
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288562f)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8288c73d)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81035d14)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff82894032)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ab6a)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8107a3fd)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8107b01a)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828a42d5)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8107f528)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81083591)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810860c4)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff8108a012)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a694f)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a7039)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff81239a7c)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8123cd5a)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff8124d491)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124eb5a)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81250a61)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81251547)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81252b43)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81254bac)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8125e6d2)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8126a0d2)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a27044)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812835d3)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
```
```
In mm/huge_memory.c (ffffffff8128c8b8)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff8129d725)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff812a4a6b)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81305f5e)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff8188f41a)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a08ee8)
Location: arch/x86/include/asm/pgtable_types.h:402
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289c6ad)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a3bde)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81037e74)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828ab7e0)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e324)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e140)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8107e996)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828bc794)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81082fcc)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81087208)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089a15)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108ddc0)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bf000)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf6f2)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff8124acb6)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8124e9c8)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8125fc90)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81260eaf)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81262d41)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81263811)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81264ec3)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81266f5c)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8127b8ca)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81285206)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a978e4)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff812a759a)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff812b8a6f)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812c002a)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff812c4e75)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff813274f1)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff818d941a)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a787f2)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289f69d)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a6c78)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038644)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828ae7ee)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f8d4)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107f1d0)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8107fa26)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c2c3b)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8108409c)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81087ef8)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108a685)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108ea20)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c5479)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c5b7e)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff812591a6)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8125cf65)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8126e550)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126f648)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812714f1)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81271d1a)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
```
```
In mm/rmap.c (ffffffff81273753)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8127585c)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8128b3aa)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81294da6)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81acf1b2)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812af055)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b8a3a)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff812ca94f)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812d1f7a)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff812d6825)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff8133a2d1)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff8190b41a)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81aafba2)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82cc5b8a)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82ccc336)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103afec)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81047a66)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076ddb)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81085b48)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff81086c17)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff82ce5ff7)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a398)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c36c)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff81094d70)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82ce868a)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff810952d1)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
```
```
In mm/gup.c (ffffffff8128a9f8)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8128d593)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8129eee5)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff8129fb62)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pmd
  - mm/mremap.c:get_old_pmd
```
```
In mm/page_vma_mapped.c (ffffffff812a1da5)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812a2616)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
```
```
In mm/rmap.c (ffffffff812a4927)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812a7272)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
```
```
In mm/swapfile.c (ffffffff812bdd86)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812c83c8)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7b6f)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812e50ed)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ed5e8)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff81300788)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81307d71)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff8130b933)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130ca22)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
```
In fs/userfaultfd.c (ffffffff81372320)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
```
```
In lib/ioremap.c (ffffffff815e99ce)
Location: arch/x86/include/asm/pgtable_types.h:425
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
  - lib/ioremap.c:ioremap_pud_range
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc441)
Location: arch/x86/include/asm/pgtable_types.h:425
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82fb147e)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82fb8174)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b7fc)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81bd4cec)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107740b)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086c0f)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810884f7)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff82fd397d)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a608)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c60c)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff81094130)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82fd60a8)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81bda340)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
```
```
In kernel/events/core.c (ffffffff8123cad7)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff812946b8)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8129fa44)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812aa2a9)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812aba41)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812ad5d1)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812adf56)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
```
```
In mm/rmap.c (ffffffff812b00b7)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b24f2)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
```
```
In mm/ioremap.c (ffffffff812b84b8)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_page_range
  - mm/ioremap.c:ioremap_page_range
```
```
In mm/swapfile.c (ffffffff812c98aa)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812d3f98)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81c4089a)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812f04b0)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f8d08)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff8130c928)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81313aa1)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff81317823)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff81318962)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
```
In fs/userfaultfd.c (ffffffff81380170)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81bd1421)
Location: arch/x86/include/asm/pgtable_types.h:426
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff831bb609)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff831c27de)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103d19b)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81bc7136)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077e94)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810878c1)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff81089176)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff831de577)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff8108b258)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d028)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff81094ad2)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff831e0b0e)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81bcc468)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
```
```
In kernel/events/core.c (ffffffff81243dec)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff8129a7bb)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff812a52bd)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812af6e9)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812b0e3d)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812b27a1)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812b3346)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
```
```
In mm/rmap.c (ffffffff812b56ab)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b8c15)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff812d0518)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff812dae7d)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81c328f7)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812f67c7)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ff25a)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff81313098)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81319c43)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff8131da23)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131eb52)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
```
In fs/userfaultfd.c (ffffffff813874f9)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81bc342b)
Location: arch/x86/include/asm/pgtable_types.h:424
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8329bb48)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff832a31ea)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81042cd9)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81c9a72b)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810856a5)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81096c2b)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810985d1)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff832c184d)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a7f8)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109c898)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810a4a3a)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff832c41ec)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81ca256d)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
```
```
In kernel/events/core.c (ffffffff8127e75f)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff812db170)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff812e681a)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812f0f1b)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812f2585)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812f43c8)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812f4ec9)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
```
```
In mm/rmap.c (ffffffff812f7340)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812fb1ca)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81315a63)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81321eb3)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81d512fb)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_remap_range
```
```
In mm/migrate.c (ffffffff81340e04)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
```
```
In mm/huge_memory.c (ffffffff81348e62)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff8135fb6e)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff813669f3)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff8136adc3)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136bf32)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
```
In fs/userfaultfd.c (ffffffff813d47d2)
Location: arch/x86/include/asm/pgtable_types.h:422
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81c94431)
Location: arch/x86/include/asm/pgtable_types.h:422
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8344a33a)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83452459)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8104ac13)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/tboot.c (ffffffff81e49b96)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095a72)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810a9756)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810ab22c)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff83473efa)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810adac7)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b0079)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810b92ce)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810b9833)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81e51dbc)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
```
```
In kernel/events/core.c (ffffffff812d33cf)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/percpu.c (ffffffff8348b9e1)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff8133ad30)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8133d807)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:follow_pte
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81354ae2)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8135642a)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff813583b9)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81358ddc)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
```
```
In mm/rmap.c (ffffffff8135c95a)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff813626cd)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81381060)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8138f0de)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8139bfbe)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_range
```
```
In mm/migrate_device.c (ffffffff813b7ce2)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
```
```
In mm/huge_memory.c (ffffffff813bf2d3)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff813da7aa)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff813e3d81)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff813e883c)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff813ea15f)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
```
In fs/userfaultfd.c (ffffffff8145fc7d)
Location: arch/x86/include/asm/pgtable_types.h:424
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81e4345b)
Location: arch/x86/include/asm/pgtable_types.h:424
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83e64949)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e6f9ca)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81056903)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/tboot.c (ffffffff81067ef3)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab6b7)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810c2b61)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810c35ce)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff83e9bb58)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7cdb)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ca70a)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810d4c43)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810d54c9)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea0c47)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In kernel/events/core.c (ffffffff8133b645)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff8137feb0)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/percpu.c (ffffffff83ebc902)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff813b2ad1)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_p4d_mask
```
```
In mm/memory.c (ffffffff813b6827)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:follow_pte
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff813cf03b)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813d0a53)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff813d29ec)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813d36bb)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
```
```
In mm/rmap.c (ffffffff813d703a)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff813de063)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813ff894)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8140dbd4)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/hugetlb_vmemmap.c (ffffffff814140e6)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse-vmemmap.c (ffffffff820cb07a)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate_device.c (ffffffff814399a4)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
```
```
In mm/huge_memory.c (ffffffff8143ec72)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff814609cb)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8146b7a9)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff814707bf)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff8147221c)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
```
In fs/userfaultfd.c (ffffffff814ef566)
Location: arch/x86/include/asm/pgtable_types.h:403
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff8201e4ff)
Location: arch/x86/include/asm/pgtable_types.h:403
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83684fc9)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8369078a)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810578d3)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/tboot.c (ffffffff81069799)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af277)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810c6241)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810c6e1e)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff836bf5f8)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810cb41b)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cdd4a)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810d814d)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810d89df)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4d57)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In kernel/events/core.c (ffffffff8136d023)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813b139c)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/percpu.c (ffffffff836e4f82)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff813e7567)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_p4d_mask
```
```
In mm/memory.c (ffffffff813eb245)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:follow_pte
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:remap_p4d_range
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8140370f)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff81405475)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff8140772c)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8140810f)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
```
```
In mm/rmap.c (ffffffff8140bf3d)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff814128bd)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81432544)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
```
```
In mm/hugetlb.c (ffffffff81440f87)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/hugetlb_vmemmap.c (ffffffff81447646)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse-vmemmap.c (ffffffff8214f30a)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate_device.c (ffffffff8146e74c)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
```
```
In mm/huge_memory.c (ffffffff81474443)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff8149519e)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814a05ac)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff814a54ef)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a69ed)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
```
In fs/userfaultfd.c (ffffffff81524d2d)
Location: arch/x86/include/asm/pgtable_types.h:404
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff8209e4f9)
Location: arch/x86/include/asm/pgtable_types.h:404
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff838b4169)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff838c025a)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105eb73)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/tboot.c (ffffffff81070cd9)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5e07)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810ce691)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810cf2de)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff838f0098)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810d396b)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d642a)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810e09cd)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810e125f)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f5957)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In kernel/events/core.c (ffffffff81396263)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813da91c)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/percpu.c (ffffffff83917793)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff81412241)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8141526e)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:follow_pte
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8142fc8f)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff8143198c)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff81433dba)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8143482f)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
```
```
In mm/rmap.c (ffffffff814387dd)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8143f32d)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff8146b964)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
```
```
In mm/hugetlb.c (ffffffff8147b0b7)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff822321da)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate_device.c (ffffffff8149d1bd)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/huge_memory.c (ffffffff814a39f2)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff814c4b06)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814cfc4c)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff814d64af)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d78ed)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
```
In fs/userfaultfd.c (ffffffff815589be)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff821764f9)
Location: arch/x86/include/asm/pgtable_types.h:432
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
In <code>riscv64</code>: Absent ⚠️
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288d69d)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82894c81)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810387a4)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8289c80d)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e874)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e1d0)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8107ea26)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828adc11)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8108309c)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81086ef8)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089645)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108d9e0)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b0411)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b0b16)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff812517f6)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812555b5)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81266ba0)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81267c98)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81269b41)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8126a36a)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
```
```
In mm/rmap.c (ffffffff8126bda3)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8126deac)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8128398a)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128d386)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a6e022)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812a7635)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b101a)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff812c2f2f)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812ca55a)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff812cee05)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff813328b1)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff818ab41a)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a4e9f2)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288b5ea)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81028184)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828949d3)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105eeb7)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106d431)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8106ddc6)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828a5e99)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81071d21)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pgtable.c (ffffffff81075b26)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810783ce)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff8107c470)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a85cf)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8c9b)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff812446de)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff81247cee)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81258a54)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81259fe6)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8125be0f)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8125c824)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff8125de3c)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8125fece)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81275833)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8127f16c)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a532)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff8129908b)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
```
```
In mm/huge_memory.c (ffffffff812a241a)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff812b401a)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff812bb598)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff812bfa93)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff8132346d)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff818653c0)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a0bad5)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a069d)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7c78)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038604)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828af7d0)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ed24)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e180)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8107e9d6)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c0b10)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8108304c)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81086ea8)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810895f5)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108d990)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c3310)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c3a15)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff8124f596)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81253355)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81264940)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81265a38)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812678e1)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8126810a)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
```
```
In mm/rmap.c (ffffffff81269b43)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8126bc4c)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8128179a)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128b196)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81ada432)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812a5445)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
```
```
In mm/huge_memory.c (ffffffff812aee2a)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff812c0d3f)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812c836a)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff812ccc15)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff81330381)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff818fc41a)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81abade2)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a06a2)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7c7e)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81039604)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828af7fe)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81070fa4)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81080270)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff81080ac6)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c3c5b)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81085458)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81088fd8)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108b895)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108fd70)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c64b6)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c6bbb)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff8125ef06)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81262d65)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81274309)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812753da)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81277277)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81277a8a)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
```
```
In mm/rmap.c (ffffffff812794b3)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8127b65c)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff812914d5)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8129afb6)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81ae68e8)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812b4b75)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
```
```
In mm/huge_memory.c (ffffffff812bf17a)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff812d17ff)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812d907a)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff812dd9a5)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff81342cd8)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff8191d41a)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81ac7232)
Location: arch/x86/include/asm/pgtable_types.h:401
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
  - lib/ioremap.c:ioremap_pud_range
```
</details>
</li>
</ul>

## Differences
