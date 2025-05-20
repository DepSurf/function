# Function: <code>pgd_val</code>

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
In arch/x86/xen/mmu.c (ffffffff8101e545)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
```
In arch/x86/xen/trace.c (ffffffff81027030)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pgd
```
```
In arch/x86/kernel/tboot.c (ffffffff81f6a326)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ba39)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81068c91)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
```
```
In arch/x86/mm/fault.c (ffffffff8106a24f)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff81f77dbb)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c85d)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pgd_range
  - arch/x86/mm/pageattr.c:unmap_pgd_range
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
```
```
In arch/x86/mm/gup.c (ffffffff81071887)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In mm/gup.c (ffffffff811ba7da)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811bbe63)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:__get_locked_pte
```
```
In mm/mprotect.c (ffffffff811c854d)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811c938c)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811ca851)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811cc5ac)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/pagewalk.c (ffffffff811cfe3f)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff811d035d)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/swapfile.c (ffffffff811d41d4)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811dd54c)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff8181f3b9)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff811f6f0d)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - mm/huge_memory.c:page_check_address_pmd
  - mm/huge_memory.c:split_huge_page_address
```
```
In mm/userfaultfd.c (ffffffff81207743)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8125af0e)
Location: arch/x86/include/asm/paravirt.h:446
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff813eb0ff)
Location: arch/x86/include/asm/paravirt.h:446
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
In arch/x86/xen/mmu.c (ffffffff81f8aa84)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/xen/trace.c (ffffffff810280f0)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pgd
```
```
In arch/x86/kernel/tboot.c (ffffffff81f925d6)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bb24)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81069992)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff81069ea4)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff81fa04ee)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8106ec1c)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
```
```
In arch/x86/mm/gup.c (ffffffff81071b98)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107405a)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kaslr.c (ffffffff81896e60)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107a530)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
```
```
In mm/gup.c (ffffffff811d57ad)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811dab59)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811e46ff)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e5776)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811e772b)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811e960c)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/pagewalk.c (ffffffff811ecf9d)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff811ed50d)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/swapfile.c (ffffffff811f1fee)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811fb99c)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81899a86)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff8121672b)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8122d013)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81283ad9)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81431474)
Location: arch/x86/include/asm/paravirt.h:419
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff817607fa)
Location: arch/x86/include/asm/paravirt.h:419
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
In arch/x86/xen/mmu.c (ffffffff81fc5e72)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/xen/trace.c (ffffffff81028840)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pgd
```
```
In arch/x86/kernel/tboot.c (ffffffff81fcd8a2)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ea9e)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106d56c)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8106da44)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff81fdba5f)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8107288c)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
```
```
In arch/x86/mm/gup.c (ffffffff81075708)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81077bd2)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kaslr.c (ffffffff818cb549)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107e320)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
```
```
In mm/gup.c (ffffffff811e57ad)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811ea71b)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811f471f)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f59b5)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff811f6ead)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff811f738d)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff811f78fd)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff811f8abb)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811fa95c)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff812029de)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8120c49c)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff818ce138)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff81228ceb)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8123f533)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812976cb)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff8144d6e4)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178d95a)
Location: arch/x86/include/asm/paravirt.h:410
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
In arch/x86/xen/mmu_pv.c (ffffffff820a6d53)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/xen/trace.c (ffffffff810257be)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d
```
```
In arch/x86/kernel/tboot.c (ffffffff820adeec)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e140)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106cb2d)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8106d774)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff820bca3a)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81071e4a)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810763ea)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kaslr.c (ffffffff81902b44)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff820bff04)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/gup.c (ffffffff811f0912)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811f1a4d)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811ff692)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8120077f)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81201d65)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812023d3)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81202a8d)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff81203a91)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81205710)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8120da93)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81217e1c)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff819055cd)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff812349dc)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8124ae8e)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812a5004)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff817abafa)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff818ed399)
Location: arch/x86/include/asm/paravirt.h:418
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826a63dd)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826ad497)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/xen/trace.c (ffffffff810260f4)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d
```
```
In arch/x86/kernel/tboot.c (ffffffff826b43f6)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061e12)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81071917)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff81072186)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff826c3494)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81077682)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107c6d6)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kaslr.c (ffffffff8198ca78)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff81080259)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:p4d_page_vaddr
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff826c8088)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/gup.c (ffffffff81205464)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812087d0)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81217cbf)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81218f40)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8121a871)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8121aff2)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff8121b7fd)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff8121c79f)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8121f6e0)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81228c8d)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81232bd5)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff8198f624)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff81249f4a)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
```
```
In mm/huge_memory.c (ffffffff812543c7)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8126b100)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812c8424)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff8182309e)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff819734ba)
Location: arch/x86/include/asm/paravirt.h:404
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826cf574)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826d6770)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/xen/trace.c (ffffffff81026db9)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d
```
```
In arch/x86/kernel/tboot.c (ffffffff826ddb8d)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81064ebe)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8107448a)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff810751d4)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff826ed6f0)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8107a0d6)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107f38d)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kaslr.c (ffffffff819e9381)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff810833a3)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81086469)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In mm/gup.c (ffffffff812268ff)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81229808)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81239a9f)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
```
```
In mm/mremap.c (ffffffff8123a915)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8123c60a)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8123ce4c)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff8123d5d5)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff8123e573)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81240e5c)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81249fa3)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81255c2c)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff819ebea9)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff8126eec8)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
```
```
In mm/huge_memory.c (ffffffff81278237)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812889e9)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff8128fafe)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812f1562)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d38b)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff819cf963)
Location: arch/x86/include/asm/paravirt.h:404
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828855a1)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8288c6b9)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/xen/trace.c (ffffffff81027399)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d
```
```
In arch/x86/kernel/tboot.c (ffffffff82893fd5)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ab2e)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8107a37a)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8107afd4)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828a4282)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810808b6)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81082e43)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81085f57)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kaslr.c (ffffffff81a24cc7)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff81089f54)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8108d2f9)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In mm/gup.c (ffffffff812399b5)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8123cd18)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff8124d3bd)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124eb18)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81250a27)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812512ff)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff81251b25)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff81252b03)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81254b6c)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8125e5e3)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8126a07c)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81a27117)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff81283578)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
```
```
In mm/huge_memory.c (ffffffff8128c877)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8129d6e9)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff812a4a1e)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81305f22)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff8188f364)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a08dcf)
Location: arch/x86/include/asm/paravirt.h:411
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289c61f)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a3b66)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/xen/trace.c (ffffffff8102907d)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d
```
```
In arch/x86/kernel/tboot.c (ffffffff828ab784)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e2e7)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e0ba)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8107e959)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828bc722)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810843b6)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81086a7f)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089d9c)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/kaslr.c (ffffffff81a9509b)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108dd03)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810911a7)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In mm/gup.c (ffffffff8124abe5)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8124e986)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8125fbbc)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81260e6d)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81262d07)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812635df)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff81263df5)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff81264e83)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81266f1c)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8127b846)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff812851b2)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81a979bb)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff812a755a)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812b8a33)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812bffdd)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813274b5)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff818d9364)
Location: arch/x86/include/asm/paravirt.h:411
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a786a3)
Location: arch/x86/include/asm/paravirt.h:411
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289f60f)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a6c00)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/xen/trace.c (ffffffff8102997d)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d
```
```
In arch/x86/kernel/tboot.c (ffffffff828ae792)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f897)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107f14a)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8107f9e9)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c2bc9)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810850f6)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff8108776f)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108aa0c)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/kaslr.c (ffffffff81acc97b)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108e963)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81091ee7)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In mm/gup.c (ffffffff812590d5)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8125cf23)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8126e47c)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126f606)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812714b7)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812720a9)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff81272665)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff81273713)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8127581c)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8128b326)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81294d52)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81acf289)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812aeffa)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b89fa)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812ca913)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812d1f2d)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8133a295)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff8190b364)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81aafa53)
Location: arch/x86/include/asm/paravirt.h:399
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
pgdval_t pgd_val(pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810064b6)
Location: arch/x86/include/asm/paravirt.h:413
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82ccd195)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/xen/trace.c (ffffffff8102c6e4)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff82cd073e)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tboot.c (ffffffff810479bd)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076d11)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81085a46)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff81086baf)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff82ce5fac)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810898b5)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff8108ab00)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:sync_current_stack_to_mm
  - arch/x86/mm/tlb.c:sync_current_stack_to_mm
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cd72)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81bc51d7)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81094b86)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81097a5a)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff8109db0f)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:pgd_page_vaddr
```
```
In mm/gup.c (ffffffff8128b29f)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff8128d4f6)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff8129edf3)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff8129fac8)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pmd
```
```
In mm/page_vma_mapped.c (ffffffff812a1d3d)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812a2c1b)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/pgtable-generic.c (ffffffff812a3375)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff812a48c0)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812a7201)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/swapfile.c (ffffffff812bdc58)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812c835f)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7d53)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/migrate.c (ffffffff812e2053)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - mm/migrate.c:p4d_alloc
```
```
In mm/huge_memory.c (ffffffff812ed585)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff81300725)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81307cdd)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/ptdump.c (ffffffff8130cb35)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pgd_entry
```
```
In fs/userfaultfd.c (ffffffff813722bd)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
```
```
In lib/ioremap.c (ffffffff815e9d77)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc3b7)
Location: arch/x86/include/asm/paravirt.h:413
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810064b6-ffffffff810064c3: pgd_val (STB_LOCAL)
ffffffff810258a0-ffffffff810258ad: pgd_val (STB_LOCAL)
ffffffff81085e43-ffffffff81085e50: pgd_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pgdval_t pgd_val(pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81bd1abf)
Location: arch/x86/include/asm/paravirt.h:387
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82fb8fd1)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/xen/trace.c (ffffffff8102d694)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff82fbc57e)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tboot.c (ffffffff81bd4c43)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077341)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086b09)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8108848f)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff82fd3932)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff81089a85)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cb24)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81c3e0aa)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81093f46)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81096c1e)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/events/core.c (ffffffff8123ca74)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff81294f5f)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff8129dc12)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff812aa1b3)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812aaf58)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812ad568)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812ae53b)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/pgtable-generic.c (ffffffff812aec95)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff812b0050)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b2481)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/ioremap.c (ffffffff812b82c6)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_page_range
```
```
In mm/swapfile.c (ffffffff812c9778)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812d3f2f)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81c40a7e)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/migrate.c (ffffffff812ecfc3)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/migrate.c:p4d_alloc
```
```
In mm/huge_memory.c (ffffffff812f8ca5)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8130c8c5)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81313a0d)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/ptdump.c (ffffffff81318a75)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pgd_entry
```
```
In fs/userfaultfd.c (ffffffff8138010d)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81bd1397)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81bd1abf-ffffffff81bd1acc: pgd_val (STB_LOCAL)
ffffffff81025fc0-ffffffff81025fcd: pgd_val (STB_LOCAL)
ffffffff81bd87f5-ffffffff81bd8802: pgd_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pgdval_t pgd_val(pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81bc3b60)
Location: arch/x86/include/asm/paravirt.h:409
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81bc4d63)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/xen/trace.c (ffffffff8102e23c)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81bc600a)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81bc6ffb)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:p4d_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077b83)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:p4d_offset
```
```
In arch/x86/mm/init_64.c (ffffffff810877f4)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff81088109)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff81bcb68e)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:p4d_offset
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a755)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c8f3)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff81bcc2da)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:p4d_offset
```
```
In arch/x86/mm/pti.c (ffffffff81094813)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff831e2ec3)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/events/core.c (ffffffff8123e713)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - kernel/events/core.c:p4d_offset
```
```
In mm/gup.c (ffffffff81296a43)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
```
```
In mm/memory.c (ffffffff8129c743)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
```
```
In mm/mprotect.c (ffffffff812ae7d3)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - mm/mprotect.c:p4d_offset
```
```
In mm/mremap.c (ffffffff812b0303)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812b2283)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:p4d_offset
```
```
In mm/pagewalk.c (ffffffff812b30d3)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - mm/pagewalk.c:p4d_offset
```
```
In mm/pgtable-generic.c (ffffffff812b41c5)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff812b4683)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - mm/rmap.c:p4d_offset
```
```
In mm/vmalloc.c (ffffffff812b8604)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
```
```
In mm/swapfile.c (ffffffff812d03e9)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff812d6373)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81c329e0)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/migrate.c (ffffffff812f2cf3)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - mm/migrate.c:p4d_offset
```
```
In mm/huge_memory.c (ffffffff812f9a13)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - mm/huge_memory.c:p4d_offset
```
```
In mm/memory-failure.c (ffffffff81312893)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - mm/memory-failure.c:p4d_offset
```
```
In mm/userfaultfd.c (ffffffff81319b63)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - mm/userfaultfd.c:p4d_offset
```
```
In mm/ptdump.c (ffffffff8131ec65)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pgd_entry
```
```
In fs/userfaultfd.c (ffffffff81386a73)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - fs/userfaultfd.c:p4d_offset
```
```
In arch/x86/power/hibernate.c (ffffffff81bc3183)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:p4d_offset
```
**Symbols:**

```
ffffffff81bc3b60-ffffffff81bc3b6d: pgd_val (STB_LOCAL)
ffffffff81bc4d63-ffffffff81bc4d70: pgd_val (STB_LOCAL)
ffffffff81bca69c-ffffffff81bca6a9: pgd_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pgdval_t pgd_val(pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81c94bb1)
Location: arch/x86/include/asm/paravirt.h:409
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81c9753f)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/xen/trace.c (ffffffff81032bdc)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81c98fdb)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81c9a5e0)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:p4d_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81085383)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:p4d_offset
```
```
In arch/x86/mm/init_64.c (ffffffff81096b5c)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff81097492)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff81ca0dc6)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:p4d_offset
```
```
In arch/x86/mm/pgtable.c (ffffffff81099cd5)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109c153)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff81ca231b)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:p4d_offset
```
```
In arch/x86/mm/pti.c (ffffffff810a4763)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff832c6866)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/events/core.c (ffffffff812791f3)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - kernel/events/core.c:p4d_offset
```
```
In mm/gup.c (ffffffff812d7293)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
```
```
In mm/memory.c (ffffffff812dd3ac)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
```
```
In mm/mprotect.c (ffffffff812eff73)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - mm/mprotect.c:p4d_offset
```
```
In mm/mremap.c (ffffffff812f1b33)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812f3e73)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:p4d_offset
```
```
In mm/pagewalk.c (ffffffff812f4c53)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - mm/pagewalk.c:p4d_offset
```
```
In mm/pgtable-generic.c (ffffffff812f5da5)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff812f6263)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - mm/rmap.c:p4d_offset
```
```
In mm/vmalloc.c (ffffffff812fad7d)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
```
```
In mm/swapfile.c (ffffffff81315934)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8131c183)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff8132be73)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
```
```
In mm/migrate.c (ffffffff8133d1e3)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - mm/migrate.c:p4d_offset
```
```
In mm/huge_memory.c (ffffffff813438d3)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - mm/huge_memory.c:p4d_offset
```
```
In mm/memory-failure.c (ffffffff8135e303)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - mm/memory-failure.c:p4d_offset
```
```
In mm/userfaultfd.c (ffffffff81366903)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - mm/userfaultfd.c:p4d_offset
```
```
In mm/ptdump.c (ffffffff8136c045)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pgd_entry
```
```
In fs/userfaultfd.c (ffffffff813d3d03)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - fs/userfaultfd.c:p4d_offset
```
```
In arch/x86/power/hibernate.c (ffffffff81c94183)
Location: arch/x86/include/asm/paravirt.h:409
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:p4d_offset
```
**Symbols:**

```
ffffffff81c94bb1-ffffffff81c94bbe: pgd_val (STB_LOCAL)
ffffffff81c9753f-ffffffff81c9754c: pgd_val (STB_LOCAL)
ffffffff81c9fb42-ffffffff81c9fb4f: pgd_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pgdval_t pgd_val(pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81e43e3f)
Location: arch/x86/include/asm/paravirt.h:415
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81031260)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/xen/trace.c (ffffffff810394de)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81e48595)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81e49a2e)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:p4d_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810956b3)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:p4d_offset
```
```
In arch/x86/mm/init_64.c (ffffffff810a961b)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff810a9f99)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff81e50366)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:p4d_offset
```
```
In arch/x86/mm/pgtable.c (ffffffff810acce5)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810af883)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff81e519d4)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:p4d_offset
```
```
In arch/x86/mm/pti.c (ffffffff810b8ff3)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff83479536)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/events/core.c (ffffffff812cc0a3)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - kernel/events/core.c:p4d_offset
```
```
In mm/percpu.c (ffffffff81e6c568)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/percpu.c:p4d_offset
```
```
In mm/gup.c (ffffffff81336e23)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
```
```
In mm/memory.c (ffffffff8133d0d3)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
```
```
In mm/mprotect.c (ffffffff81353483)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
```
```
In mm/mremap.c (ffffffff813556e3)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81357d23)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:p4d_offset
```
```
In mm/pagewalk.c (ffffffff81358af3)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/pagewalk.c:p4d_offset
```
```
In mm/pgtable-generic.c (ffffffff81359cd5)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff8135a293)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/rmap.c:p4d_offset
```
```
In mm/vmalloc.c (ffffffff81362273)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
```
```
In mm/swapfile.c (ffffffff81380eca)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81388773)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff8139bc53)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
```
```
In mm/migrate_device.c (ffffffff813b6223)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/migrate_device.c:p4d_offset
```
```
In mm/huge_memory.c (ffffffff813b8553)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/huge_memory.c:p4d_offset
```
```
In mm/memory-failure.c (ffffffff813d88b3)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/memory-failure.c:p4d_offset
```
```
In mm/userfaultfd.c (ffffffff813e3c83)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/userfaultfd.c:p4d_offset
```
```
In mm/ptdump.c (ffffffff813ea275)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pgd_entry
```
```
In fs/userfaultfd.c (ffffffff8145d2b3)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - fs/userfaultfd.c:p4d_offset
```
```
In arch/x86/power/hibernate.c (ffffffff81e43193)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:p4d_offset
```
**Symbols:**

```
ffffffff81e43e3f-ffffffff81e43e51: pgd_val (STB_LOCAL)
ffffffff81031260-ffffffff81031272: pgd_val (STB_LOCAL)
ffffffff810a7c70-ffffffff810a7c82: pgd_val (STB_LOCAL)
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83e6486c)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e6f98a)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/xen/trace.c (ffffffff8104177e)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff83e75662)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tboot.c (ffffffff81067b24)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:p4d_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab284)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:p4d_offset
```
```
In arch/x86/mm/init_64.c (ffffffff810c2a21)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/fault.c (ffffffff810c3837)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff810c4f84)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:p4d_offset
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:415
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810c9e54)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff810d48a4)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:p4d_offset
```
```
In arch/x86/mm/pti.c (ffffffff810d4924)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff83ea37be)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/events/core.c (ffffffff81333aa4)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - kernel/events/core.c:p4d_offset
```
```
In mm/percpu.c (ffffffff81399164)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/percpu.c:p4d_offset
```
```
In mm/gup.c (ffffffff813b299f)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff813b4ca9)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
```
```
In mm/mprotect.c (ffffffff813cd764)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
```
```
In mm/mremap.c (ffffffff813cfe34)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff813d24d4)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:p4d_offset
```
```
In mm/pagewalk.c (ffffffff813d3394)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/pagewalk.c:p4d_offset
```
```
In mm/pgtable-generic.c (ffffffff813d46c5)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff813d4d34)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/rmap.c:p4d_offset
```
```
In mm/vmalloc.c (ffffffff813ddc14)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
```
```
In mm/swapfile.c (ffffffff813ff716)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff814069e4)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
```
```
In mm/hugetlb_vmemmap.c (ffffffff814138c4)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse-vmemmap.c (ffffffff8141bc04)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
```
```
In mm/migrate_device.c (ffffffff81437a22)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/migrate_device.c:p4d_alloc
```
```
In mm/memory-failure.c (ffffffff8145e444)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/memory-failure.c:p4d_offset
```
```
In mm/userfaultfd.c (ffffffff8146b684)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/userfaultfd.c:p4d_offset
```
```
In mm/ptdump.c (ffffffff81472335)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pgd_entry
```
```
In fs/userfaultfd.c (ffffffff814ecb94)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - fs/userfaultfd.c:p4d_offset
```
```
In arch/x86/power/hibernate.c (ffffffff8201e1e4)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:p4d_offset
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83684eec)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8369074a)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/xen/trace.c (ffffffff810418be)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff83697132)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tboot.c (ffffffff810693d4)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:p4d_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810aee44)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:p4d_offset
```
```
In arch/x86/mm/init_64.c (ffffffff810c6101)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/fault.c (ffffffff810c7087)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff810c8714)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:p4d_offset
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:410
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cd4a4)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff810d7db4)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:p4d_offset
```
```
In arch/x86/mm/pti.c (ffffffff810d7e34)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff836c7a59)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/events/core.c (ffffffff81364814)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - kernel/events/core.c:p4d_offset
```
```
In mm/percpu.c (ffffffff813cc174)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/percpu.c:p4d_offset
```
```
In mm/gup.c (ffffffff813e748d)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff813e97d4)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
```
```
In mm/mprotect.c (ffffffff814020c4)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
```
```
In mm/mremap.c (ffffffff814048f4)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81407064)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:p4d_offset
```
```
In mm/pagewalk.c (ffffffff81407db4)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/pagewalk.c:p4d_offset
```
```
In mm/pgtable-generic.c (ffffffff81409095)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff81409b74)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/rmap.c:p4d_offset
```
```
In mm/vmalloc.c (ffffffff81412474)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
```
```
In mm/swapfile.c (ffffffff8143278b)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8143a034)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
```
```
In mm/hugetlb_vmemmap.c (ffffffff81446e14)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse-vmemmap.c (ffffffff8144f204)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
```
```
In mm/migrate_device.c (ffffffff8146d6e2)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/migrate_device.c:p4d_alloc
```
```
In mm/memory-failure.c (ffffffff81494124)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/memory-failure.c:p4d_offset
```
```
In mm/userfaultfd.c (ffffffff814a0484)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/userfaultfd.c:p4d_offset
```
```
In mm/ptdump.c (ffffffff814a6a95)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pgd_entry
```
```
In fs/userfaultfd.c (ffffffff81523834)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - fs/userfaultfd.c:p4d_offset
```
```
In arch/x86/power/hibernate.c (ffffffff8209e1e4)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:p4d_offset
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff838b408c)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff838c021a)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/xen/trace.c (ffffffff81047d8e)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105e944)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81070844)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:p4d_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b59c4)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:p4d_offset
```
```
In arch/x86/mm/init_64.c (ffffffff810ce551)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/fault.c (ffffffff810cf557)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff810d0be4)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:p4d_offset
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:410
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d5b84)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff810e0634)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:p4d_offset
```
```
In arch/x86/mm/pti.c (ffffffff810e06b4)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff838f8659)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/events/core.c (ffffffff8138d744)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - kernel/events/core.c:p4d_offset
```
```
In mm/percpu.c (ffffffff813f6ae4)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/percpu.c:p4d_offset
```
```
In mm/gup.c (ffffffff8140cfa4)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
```
```
In mm/memory.c (ffffffff814147f4)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
```
```
In mm/mprotect.c (ffffffff8142e6f4)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
```
```
In mm/mremap.c (ffffffff81430ec4)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81433714)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:p4d_offset
```
```
In mm/pagewalk.c (ffffffff81434494)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/pagewalk.c:p4d_offset
```
```
In mm/pgtable-generic.c (ffffffff81435885)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff814363a4)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/rmap.c:p4d_offset
```
```
In mm/vmalloc.c (ffffffff8143ecd4)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
```
```
In mm/swapfile.c (ffffffff8146bbab)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81473e14)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81488dc4)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
```
```
In mm/migrate_device.c (ffffffff8149ca42)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/migrate_device.c:p4d_alloc
```
```
In mm/memory-failure.c (ffffffff814c3934)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/memory-failure.c:p4d_offset
```
```
In mm/userfaultfd.c (ffffffff814cfb24)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/userfaultfd.c:p4d_offset
```
```
In mm/ptdump.c (ffffffff814d7a95)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pgd_entry
```
```
In fs/userfaultfd.c (ffffffff81557e54)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - fs/userfaultfd.c:p4d_offset
```
```
In arch/x86/power/hibernate.c (ffffffff821761e4)
Location: arch/x86/include/asm/paravirt.h:410
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:p4d_offset
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
In arch/powerpc/mm/pgtable.c (c0000000000879ec)
Location: arch/powerpc/include/asm/pgtable-be-types.h:56
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable.c:__find_linux_pte
```
```
In arch/powerpc/mm/pgtable_64.c (c000000000088f18)
Location: arch/powerpc/include/asm/pgtable-be-types.h:56
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable_64.c:pgd_page
```
```
In arch/powerpc/mm/book3s64/hash_pgtable.c (c00000000008b704)
Location: arch/powerpc/include/asm/pgtable-be-types.h:56
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_pgtable.c:hash__map_kernel_page
```
```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000eebca8)
Location: arch/powerpc/include/asm/pgtable-be-types.h:56
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable
  - arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page
  - arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page
```
```
In arch/powerpc/mm/book3s64/subpage_prot.c (c00000000009f87c)
Location: arch/powerpc/include/asm/pgtable-be-types.h:56
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/subpage_prot.c:hpte_flush_range
```
```
In arch/powerpc/mm/hugetlbpage.c (c0000000000a5c10)
Location: arch/powerpc/include/asm/pgtable-be-types.h:56
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
  - arch/powerpc/mm/hugetlbpage.c:huge_pte_alloc
```
```
In arch/powerpc/xmon/xmon.c (c00000000010d390)
Location: arch/powerpc/include/asm/pgtable-be-types.h:56
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:show_pte
  - arch/powerpc/xmon/xmon.c:show_pte
```
```
In mm/gup.c (c0000000003b7864)
Location: arch/powerpc/include/asm/pgtable-be-types.h:56
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (c0000000003baef4)
Location: arch/powerpc/include/asm/pgtable-be-types.h:56
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (c0000000003d1ea4)
Location: arch/powerpc/include/asm/pgtable-be-types.h:56
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d3bf0)
Location: arch/powerpc/include/asm/pgtable-be-types.h:56
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (c0000000003d5734)
Location: arch/powerpc/include/asm/pgtable-be-types.h:56
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (c0000000003d6660)
Location: arch/powerpc/include/asm/pgtable-be-types.h:56
Inline: True
```
```
In mm/pgtable-generic.c (c0000000003d7478)
Location: arch/powerpc/include/asm/pgtable-be-types.h:56
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (c0000000003d8718)
Location: arch/powerpc/include/asm/pgtable-be-types.h:56
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (c0000000003dba50)
Location: arch/powerpc/include/asm/pgtable-be-types.h:56
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_page_range_noflush
  - mm/vmalloc.c:vunmap_page_range
  - mm/vmalloc.c:vunmap_page_range
  - mm/vmalloc.c:vunmap_page_range
```
```
In mm/swapfile.c (c0000000003fce78)
Location: arch/powerpc/include/asm/pgtable-be-types.h:56
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/sparse-vmemmap.c (c000000000eedd6c)
Location: arch/powerpc/include/asm/pgtable-be-types.h:56
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (c0000000004326f8)
Location: arch/powerpc/include/asm/pgtable-be-types.h:56
Inline: True
```
```
In mm/huge_memory.c (c000000000442330)
Location: arch/powerpc/include/asm/pgtable-be-types.h:56
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (c00000000045e9f8)
Location: arch/powerpc/include/asm/pgtable-be-types.h:56
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (c00000000046a38c)
Location: arch/powerpc/include/asm/pgtable-be-types.h:56
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (c0000000005018d0)
Location: arch/powerpc/include/asm/pgtable-be-types.h:56
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (c000000000ec9f40)
Location: arch/powerpc/include/asm/pgtable-be-types.h:56
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
</details>
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288d60f)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82894c09)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/xen/trace.c (ffffffff81029add)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d
```
```
In arch/x86/kernel/tboot.c (ffffffff8289c7b1)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e837)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e14a)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8107e9e9)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828adb9f)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810840f6)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff8108676f)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810899cc)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/kaslr.c (ffffffff81a6b7eb)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108d923)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81090ea7)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In mm/gup.c (ffffffff81251725)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81255573)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81266acc)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81267c56)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81269b07)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8126a6f9)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff8126acb5)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff8126bd63)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8126de6c)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81283906)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128d332)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81a6e0f9)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812a75da)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b0fda)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812c2ef3)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812ca50d)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81332875)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff818ab364)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a4e8a3)
Location: arch/x86/include/asm/paravirt.h:399
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a060f)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7c00)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/xen/trace.c (ffffffff8102993d)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d
```
```
In arch/x86/kernel/tboot.c (ffffffff828af774)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ece7)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e0fa)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8107e999)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c0a9e)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810840a6)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff8108671f)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108997c)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/kaslr.c (ffffffff81ad7bfb)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108d8d3)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81090e57)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In mm/gup.c (ffffffff8124f4c5)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81253313)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8126486c)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812659f6)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812678a7)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81268499)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff81268a55)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff81269b03)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8126bc0c)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81281716)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128b142)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81ada509)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812a53ea)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
```
```
In mm/huge_memory.c (ffffffff812aedea)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812c0d03)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812c831d)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81330345)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff818fc364)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81abac93)
Location: arch/x86/include/asm/paravirt.h:399
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a0614)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7c06)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/xen/trace.c (ffffffff8102a72d)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_p4d
```
```
In arch/x86/kernel/tboot.c (ffffffff828af7a2)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81070f67)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810801ea)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff81080a89)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c3be9)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810861e6)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff8108885f)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108bc1c)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/kaslr.c (ffffffff81ae40bb)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108fcb3)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81093247)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In mm/gup.c (ffffffff8125ee35)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81262d23)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8127422c)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81275398)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8127723d)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81277e19)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff812783e5)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff81279473)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8127b61c)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81291451)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8129af62)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81ae69bf)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812b4b1a)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
```
```
In mm/huge_memory.c (ffffffff812bf13a)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812d17c3)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812d902d)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81342c9c)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff8191d364)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81ac70e3)
Location: arch/x86/include/asm/paravirt.h:399
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
</ul>
