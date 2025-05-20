# Function: <code>pud_val</code>

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
In arch/x86/xen/mmu.c (ffffffff8101e66d)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
```
In arch/x86/xen/trace.c (ffffffff81026fa0)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810346bc)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81f6a360)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bb02)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81068c54)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
```
```
In arch/x86/mm/fault.c (ffffffff8106a29f)
Location: arch/x86/include/asm/paravirt.h:579
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
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff81f77df2)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c5a0)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pgd_range
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81071359)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/gup.c (ffffffff81071633)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pud
  - arch/x86/mm/gup.c:gup_pud_range
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81072ba9)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pud_huge
```
```
In mm/gup.c (ffffffff811ba878)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811bbe99)
Location: arch/x86/include/asm/paravirt.h:579
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
In mm/mprotect.c (ffffffff811c8629)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811c9407)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811ca8b3)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811cc5f9)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/pagewalk.c (ffffffff811cff01)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff811d03ad)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/swapfile.c (ffffffff811d42bf)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811dd730)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff8181f2ef)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff811f6f7b)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - mm/huge_memory.c:page_check_address_pmd
  - mm/huge_memory.c:split_huge_page_address
```
```
In mm/userfaultfd.c (ffffffff81207788)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8125af71)
Location: arch/x86/include/asm/paravirt.h:579
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff813eb1a6)
Location: arch/x86/include/asm/paravirt.h:579
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
In arch/x86/xen/mmu.c (ffffffff81f8aaf4)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/xen/trace.c (ffffffff81028060)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81033887)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81f9263c)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bbeb)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff810699c9)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff81069eed)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
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
In arch/x86/mm/ioremap.c (ffffffff81fa0539)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8106dc50)
Location: arch/x86/include/asm/paravirt.h:552
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
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pgtable.c (ffffffff81071249)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/gup.c (ffffffff81071c2d)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
  - arch/x86/mm/gup.c:gup_pud_range
  - arch/x86/mm/gup.c:gup_huge_pud
  - arch/x86/mm/gup.c:gup_huge_pud
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81073439)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pud_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810740af)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/gup.c (ffffffff811d57f5)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811daba8)
Location: arch/x86/include/asm/paravirt.h:552
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
In mm/mprotect.c (ffffffff811e4817)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e57ef)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811e7785)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811e9654)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/pagewalk.c (ffffffff811ed05a)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff811ed55d)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/swapfile.c (ffffffff811f20d3)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811fba15)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff818999a3)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff8121679d)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8122d060)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81283b37)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81431518)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81760830)
Location: arch/x86/include/asm/paravirt.h:552
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/xen/mmu.c (ffffffff81fc5ee2)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/xen/trace.c (ffffffff810287b0)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810334b4)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81fcd908)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105eb65)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106d5a3)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8106da8d)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
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
In arch/x86/mm/ioremap.c (ffffffff81fdbaaa)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810718dc)
Location: arch/x86/include/asm/paravirt.h:543
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
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pgtable.c (ffffffff81074dc9)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/gup.c (ffffffff8107579d)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
  - arch/x86/mm/gup.c:gup_pud_range
  - arch/x86/mm/gup.c:gup_huge_pud
  - arch/x86/mm/gup.c:gup_huge_pud
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81076fe9)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pud_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81077c27)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/gup.c (ffffffff811e57f5)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811ea76a)
Location: arch/x86/include/asm/paravirt.h:543
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
In mm/mprotect.c (ffffffff811f4837)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f5a2e)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff811f6f17)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff811f744a)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff811f794d)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/rmap.c (ffffffff811f8b15)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811fa9a4)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81202ac6)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8120c515)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff818ce055)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff81228d5d)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8123f580)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81297729)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff8144d788)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178d990)
Location: arch/x86/include/asm/paravirt.h:543
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/xen/mmu_pv.c (ffffffff820a6dcf)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/xen/trace.c (ffffffff81026c43)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81031677)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff820adf52)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e204)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106cbe4)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8106d7bd)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
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
In arch/x86/mm/ioremap.c (ffffffff820bca6c)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8107091e)
Location: arch/x86/include/asm/paravirt.h:562
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
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81074379)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81075809)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pud_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810764ea)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/gup.c (ffffffff811f09a4)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811f1ada)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811ff78d)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81200803)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81201e0f)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81202675)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81202add)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/rmap.c (ffffffff81203aec)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8120578c)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8120db7a)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81217e95)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff819054ea)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff81234a4d)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/userfaultfd.c (ffffffff8124aed4)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812a5062)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff817abb30)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff818ed439)
Location: arch/x86/include/asm/paravirt.h:562
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826a6441)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826ad51b)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:pud_large
```
```
In arch/x86/xen/trace.c (ffffffff81027233)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810338ce)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff826b4462)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061edb)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81071841)
Location: arch/x86/include/asm/paravirt.h:526
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
```
```
In arch/x86/mm/fault.c (ffffffff810721df)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff826c34d3)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81076107)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
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
In arch/x86/mm/pgtable.c (ffffffff81079eed)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff8107ba49)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pud_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107c710)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff826c54e5)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pud_page_vaddr
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5ea9)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff8120550a)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff81208845)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81217dcf)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81218fc6)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8121a961)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8121b2ff)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff8121b84d)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/rmap.c (ffffffff8121c7f9)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8121f75e)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81228d8b)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81232c80)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8198f528)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff81249fa8)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
```
```
In mm/huge_memory.c (ffffffff8125443a)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/userfaultfd.c (ffffffff8126b153)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812c848b)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff818230d9)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff81973567)
Location: arch/x86/include/asm/paravirt.h:526
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826cf5d3)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826d67c6)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:pud_large
```
```
In arch/x86/xen/trace.c (ffffffff81027d03)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034c44)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff826ddbe3)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81064f84)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff810744f5)
Location: arch/x86/include/asm/paravirt.h:526
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
```
```
In arch/x86/mm/fault.c (ffffffff81075236)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff826ed73c)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81078bee)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
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
In arch/x86/mm/pgtable.c (ffffffff8107cb3a)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff8107e835)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pud_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107f4cb)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff810833cf)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efc67)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff81226995)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81229889)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81239b6b)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
```
```
In mm/mremap.c (ffffffff8123a995)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8123c66e)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8123d07d)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff8123d625)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/rmap.c (ffffffff8123e5d6)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81240ee1)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8124a08b)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81255cc6)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff819ebdcf)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff8126ef1c)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
```
```
In mm/huge_memory.c (ffffffff8127829f)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff81288aaf)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff8128fb44)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812f180f)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d3c7)
Location: arch/x86/include/asm/paravirt.h:526
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff819cfa0c)
Location: arch/x86/include/asm/paravirt.h:526
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82885600)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8288c70f)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:pud_large
```
```
In arch/x86/xen/trace.c (ffffffff810282e3)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81035e24)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8289402b)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106abf4)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8107a3e5)
Location: arch/x86/include/asm/paravirt.h:519
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
  - arch/x86/mm/init_64.c:pud_same
  - arch/x86/mm/init_64.c:pud_same
```
```
In arch/x86/mm/fault.c (ffffffff8107b036)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828a42ce)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8107f552)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
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
In arch/x86/mm/pgtable.c (ffffffff8108357d)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810853b5)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pud_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810860bd)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff81089f80)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6924)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff81239a75)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8123cd99)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff8124d48a)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124eb99)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81250a8b)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81251540)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff81251b75)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/rmap.c (ffffffff81252b66)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81254bf1)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8125e6cb)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8126a116)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a2703d)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812835cc)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
```
```
In mm/huge_memory.c (ffffffff8128c8df)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff8129d7b2)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff812a4a64)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813061cf)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff8188f3a0)
Location: arch/x86/include/asm/paravirt.h:519
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a08ee1)
Location: arch/x86/include/asm/paravirt.h:519
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289c67e)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a3bb0)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:pud_large
```
```
In arch/x86/xen/trace.c (ffffffff81029f64)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81037f84)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828ab7d9)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e3ad)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e128)
Location: arch/x86/include/asm/paravirt.h:520
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
  - arch/x86/mm/init_64.c:pud_same
  - arch/x86/mm/init_64.c:pud_same
```
```
In arch/x86/mm/fault.c (ffffffff8107e9a9)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828bc78d)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81082ff6)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff810871ed)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81088fb5)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pud_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089a5d)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108dd2f)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828befd5)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff8124acaf)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8124ea09)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8125fc89)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81260eee)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81262d6b)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812637a3)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff81263e45)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/rmap.c (ffffffff81264ee6)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81266fa1)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8127b91a)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81285249)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a978dd)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff812a75c2)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff812b8a82)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812c0023)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff812c4f38)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff8132772a)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff818d93a0)
Location: arch/x86/include/asm/paravirt.h:520
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a787eb)
Location: arch/x86/include/asm/paravirt.h:520
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289f66e)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a6c4a)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:pud_large
```
```
In arch/x86/xen/trace.c (ffffffff8102a864)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038754)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828ae7e7)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f95d)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107f1b8)
Location: arch/x86/include/asm/paravirt.h:508
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
  - arch/x86/mm/init_64.c:pud_same
  - arch/x86/mm/init_64.c:pud_same
```
```
In arch/x86/mm/fault.c (ffffffff8107fa39)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c2c34)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810840c6)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81087edd)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81089c25)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pud_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108a6cd)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108e98f)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c544e)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff8125919f)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8125cfaa)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8126e549)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126f687)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8127151b)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812722ad)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff812726b5)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/rmap.c (ffffffff81273776)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812758a1)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8128b3fa)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81294de9)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81acf1ab)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812af04e)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b8a62)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff812ca962)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812d1f73)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff812d68e8)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff8133a50a)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff8190b3a0)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81aafb9b)
Location: arch/x86/include/asm/paravirt.h:508
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
pudval_t pud_val(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810064c3)
Location: arch/x86/include/asm/paravirt.h:522
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82cccfca)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/xen/trace.c (ffffffff8102c674)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b01e)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81047a55)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076e67)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81085b30)
Location: arch/x86/include/asm/paravirt.h:522
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
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff81086c2e)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff82ce5ff0)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a37d)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c35f)
Location: arch/x86/include/asm/paravirt.h:522
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
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81091505)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pud_huge
```
```
In arch/x86/mm/pti.c (ffffffff81094cdf)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82ce865f)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff8128a96e)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8128d5d1)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8129ea56)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
```
```
In mm/mremap.c (ffffffff8129fb9a)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pmd
```
```
In mm/page_vma_mapped.c (ffffffff812a1dd0)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812a260f)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812a3455)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/rmap.c (ffffffff812a4949)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812a72af)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
```
```
In mm/swapfile.c (ffffffff812bddd5)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812c83f1)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7b68)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812e50e6)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ed614)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff8130079f)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81307d61)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff8130ba07)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130ca4c)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
```
In mm/ptdump.c (ffffffff8130ccf2)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pud_entry
  - mm/ptdump.c:ptdump_pud_entry
  - mm/ptdump.c:ptdump_pud_entry
```
```
In fs/userfaultfd.c (ffffffff8137234e)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
```
```
In lib/ioremap.c (ffffffff815e9a8b)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc40b)
Location: arch/x86/include/asm/paravirt.h:522
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810064c3-ffffffff810064d0: pud_val (STB_LOCAL)
ffffffff810258c0-ffffffff810258cd: pud_val (STB_LOCAL)
ffffffff81085e9e-ffffffff81085eab: pud_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pudval_t pud_val(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81bd1acc)
Location: arch/x86/include/asm/paravirt.h:444
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82fb8e06)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/xen/trace.c (ffffffff8102d624)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b82e)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81bd4cdb)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077497)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086bf7)
Location: arch/x86/include/asm/paravirt.h:444
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
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8108850e)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff82fd3976)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a5ed)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ccb1)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81090e35)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pud_huge
```
```
In arch/x86/mm/pti.c (ffffffff8109409f)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82fd607d)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/core.c (ffffffff8123caf4)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff8129462e)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8129fa82)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812a9e16)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In mm/mremap.c (ffffffff812aba30)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812ad5fd)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812adf4f)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812aed55)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/rmap.c (ffffffff812b00d9)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b252f)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
```
```
In mm/ioremap.c (ffffffff812b8561)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_page_range
```
```
In mm/swapfile.c (ffffffff812c98f9)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812d3fc1)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81c40893)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812f04a9)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f8d34)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff8130c93f)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81313a91)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff813178f7)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131898c)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
```
In mm/ptdump.c (ffffffff81318c32)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pud_entry
  - mm/ptdump.c:ptdump_pud_entry
  - mm/ptdump.c:ptdump_pud_entry
```
```
In fs/userfaultfd.c (ffffffff8138019e)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81bd13eb)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81bd1acc-ffffffff81bd1ad9: pud_val (STB_LOCAL)
ffffffff81025fe0-ffffffff81025fed: pud_val (STB_LOCAL)
ffffffff81bd8850-ffffffff81bd885d: pud_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pudval_t pud_val(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81bc3b6d)
Location: arch/x86/include/asm/paravirt.h:471
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff831c3362)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/xen/trace.c (ffffffff8102e1cc)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103d1cd)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81bc7124)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077f1f)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810878a9)
Location: arch/x86/include/asm/paravirt.h:471
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
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8108918d)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff831de570)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff8108b23d)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d8a3)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81091805)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pud_huge
```
```
In arch/x86/mm/pti.c (ffffffff81094a40)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff831e0ae6)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/core.c (ffffffff81243e09)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff8129a7b4)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff812a3439)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
Direct callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812af295)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
```
```
In mm/mremap.c (ffffffff812b0e2b)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812b27ef)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812b333f)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812b4285)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/rmap.c (ffffffff812b56cd)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b8bfa)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff812d0567)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff812daea6)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81c328e9)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812f67c0)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ff27f)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff813130af)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81319c3c)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff8131daec)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131eb7c)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
```
In mm/ptdump.c (ffffffff8131ee22)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pud_entry
  - mm/ptdump.c:ptdump_pud_entry
  - mm/ptdump.c:ptdump_pud_entry
```
```
In fs/userfaultfd.c (ffffffff8138751f)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81bc33f5)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81bc3b6d-ffffffff81bc3b7a: pud_val (STB_LOCAL)
ffffffff81bc4da4-ffffffff81bc4db1: pud_val (STB_LOCAL)
ffffffff81bca6f7-ffffffff81bca704: pud_val (STB_LOCAL)
ffffffff8129c270-ffffffff8129c27d: pud_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pudval_t pud_val(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81c94bbe)
Location: arch/x86/include/asm/paravirt.h:471
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff832a3d9c)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/xen/trace.c (ffffffff81032b6c)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81042d0b)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81c9a724)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81085723)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81096c12)
Location: arch/x86/include/asm/paravirt.h:471
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
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810985e8)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff832c1846)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a7dd)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109d12e)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810a1385)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pud_huge
```
```
In arch/x86/mm/pti.c (ffffffff810a49b2)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff832c41c4)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/core.c (ffffffff8127e77b)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff812db166)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff812e4ddc)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
Direct callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812f0ab8)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
```
```
In mm/mremap.c (ffffffff812f2506)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812f440a)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812f4ec2)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812f5e65)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/rmap.c (ffffffff812f7358)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812fb1af)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81315aa5)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81321ed2)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81d512f4)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_remap_range
```
```
In mm/migrate.c (ffffffff81340dfd)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
```
```
In mm/huge_memory.c (ffffffff81348e7a)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff8135fb85)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff813669e3)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff8136ae8c)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136bf5c)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
```
In mm/ptdump.c (ffffffff8136c202)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pud_entry
  - mm/ptdump.c:ptdump_pud_entry
  - mm/ptdump.c:ptdump_pud_entry
```
```
In fs/userfaultfd.c (ffffffff813d47ea)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81c94405)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81c94bbe-ffffffff81c94bcb: pud_val (STB_LOCAL)
ffffffff81c97580-ffffffff81c9758d: pud_val (STB_LOCAL)
ffffffff81c9fb9d-ffffffff81c9fbaa: pud_val (STB_LOCAL)
ffffffff812dcd70-ffffffff812dcd7d: pud_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pudval_t pud_val(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81e43e51)
Location: arch/x86/include/asm/paravirt.h:477
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83453025)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/xen/trace.c (ffffffff8103944e)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8104ac45)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/tboot.c (ffffffff81e49b90)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095aee)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810a9750)
Location: arch/x86/include/asm/paravirt.h:477
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
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810ab243)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff83473ef4)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810adaad)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b09ba)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810b54a5)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pud_huge
```
```
In arch/x86/mm/pti.c (ffffffff810b924d)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810b9828)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In kernel/events/core.c (ffffffff812d33eb)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/percpu.c (ffffffff8348b9db)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff8133ad27)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff81346010)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
Direct callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81354ad3)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81356385)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff813583fb)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81358dd6)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81359dd5)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/rmap.c (ffffffff8135c976)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff813626b3)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813810a2)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8138f101)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8139bfb8)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_range
```
```
In mm/migrate_device.c (ffffffff813b7cdc)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
```
```
In mm/huge_memory.c (ffffffff813bf2ef)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff813da7c1)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff813e3d72)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff813e8939)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff813ea189)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
```
In mm/ptdump.c (ffffffff813ea4c6)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pud_entry
  - mm/ptdump.c:ptdump_pud_entry
  - mm/ptdump.c:ptdump_pud_entry
```
```
In fs/userfaultfd.c (ffffffff8145fc99)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81e43431)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81e43e51-ffffffff81e43e63: pud_val (STB_LOCAL)
ffffffff810312a0-ffffffff810312b2: pud_val (STB_LOCAL)
ffffffff810a7d80-ffffffff810a7d92: pud_val (STB_LOCAL)
ffffffff8133ca00-ffffffff8133ca12: pud_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pudval_t pud_val(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83e6490f)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e6f9ef)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/xen/trace.c (ffffffff810416ce)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81056a26)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/tboot.c (ffffffff81067ee0)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab734)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810c2b5b)
Location: arch/x86/include/asm/paravirt.h:477
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
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810c35e5)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff83e9bb4f)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7cb9)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cb088)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810d045d)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pud_huge
```
```
In arch/x86/mm/pti.c (ffffffff810d4bbf)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810d54bb)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In kernel/events/core.c (ffffffff8133b662)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff8137fed2)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/percpu.c (ffffffff83ebc8e8)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff813b2a5c)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_p4d_mask
```
```
In mm/memory.c (ffffffff813be3e0)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
Direct callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff813cf032)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813d09a9)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff813d2a2f)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813d36b5)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff813d47e5)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/rmap.c (ffffffff813d7057)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff813de049)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813ff88e)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8140dbf8)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/hugetlb_vmemmap.c (ffffffff814140cc)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse-vmemmap.c (ffffffff820cb071)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate_device.c (ffffffff8143999b)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
```
```
In mm/huge_memory.c (ffffffff81440ad1)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff814609de)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8146b796)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff81470888)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff81472246)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
```
In mm/ptdump.c (ffffffff814725d6)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pud_entry
  - mm/ptdump.c:ptdump_pud_entry
  - mm/ptdump.c:ptdump_pud_entry
```
```
In fs/userfaultfd.c (ffffffff814ef583)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff8201e4d2)
Location: arch/x86/include/asm/paravirt.h:477
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff813b4770-ffffffff813b4788: pud_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pudval_t pud_val(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83684f8f)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff836907af)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/xen/trace.c (ffffffff8104180e)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810579f5)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/tboot.c (ffffffff81069790)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af2f4)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810c623b)
Location: arch/x86/include/asm/paravirt.h:472
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
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810c6e35)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff836bf5ef)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810cb3f9)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce6b8)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810d3a7d)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pud_huge
```
```
In arch/x86/mm/pti.c (ffffffff810d80cf)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810d89cd)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In kernel/events/core.c (ffffffff8136d040)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813b13be)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/percpu.c (ffffffff836e4f68)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff813e759e)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_p4d_mask
```
```
In mm/memory.c (ffffffff813f4792)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_p4d_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
Direct callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81403706)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff814053c9)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8140776f)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81408109)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff814091b5)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/rmap.c (ffffffff8140bf5a)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff814128a9)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81432586)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
```
```
In mm/hugetlb.c (ffffffff81440fab)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/hugetlb_vmemmap.c (ffffffff8144762c)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse-vmemmap.c (ffffffff8214f301)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate_device.c (ffffffff8146e743)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
```
```
In mm/huge_memory.c (ffffffff8147638a)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff814951b1)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814a0599)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff814a55ec)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a69c9)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
```
In mm/ptdump.c (ffffffff814a6d36)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pud_entry
  - mm/ptdump.c:ptdump_pud_entry
  - mm/ptdump.c:ptdump_pud_entry
```
```
In fs/userfaultfd.c (ffffffff81524d4a)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff8209e4d2)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff813e93f0-ffffffff813e9408: pud_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pudval_t pud_val(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff838b412f)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff838c027f)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/xen/trace.c (ffffffff81047cde)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105ec95)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/tboot.c (ffffffff81070cd0)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5e84)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810ce68b)
Location: arch/x86/include/asm/paravirt.h:471
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
In arch/x86/mm/fault.c (ffffffff810cf2f5)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff838f008f)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810d3949)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d6d98)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810dc20d)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pud_huge
```
```
In arch/x86/mm/pti.c (ffffffff810e094f)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810e124d)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In kernel/events/core.c (ffffffff81396280)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813da93e)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/percpu.c (ffffffff83917779)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff81412238)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff81420e95)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
Direct callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8142fc86)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff814318dc)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81433dfd)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81434829)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff814359a5)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/rmap.c (ffffffff814387fa)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8143f319)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff8146b9a6)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
```
```
In mm/hugetlb.c (ffffffff8147b0db)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff822321d1)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate_device.c (ffffffff8149d1b4)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/huge_memory.c (ffffffff814a5c36)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff814c4b1d)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814cfc39)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff814d65ac)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d78c9)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
```
In mm/ptdump.c (ffffffff814d7d36)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pud_entry
  - mm/ptdump.c:ptdump_pud_entry
  - mm/ptdump.c:ptdump_pud_entry
```
```
In fs/userfaultfd.c (ffffffff815589db)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff821764d2)
Location: arch/x86/include/asm/paravirt.h:471
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff814140d0-ffffffff814140e8: pud_val (STB_LOCAL)
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
In arch/powerpc/mm/pgtable.c (c000000000087a70)
Location: arch/powerpc/include/asm/pgtable-be-types.h:40
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable.c:__find_linux_pte
```
```
In arch/powerpc/mm/pgtable_64.c (c000000000088f88)
Location: arch/powerpc/include/asm/pgtable-be-types.h:40
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable_64.c:pud_page
```
```
In arch/powerpc/mm/book3s64/hash_pgtable.c (c00000000008b768)
Location: arch/powerpc/include/asm/pgtable-be-types.h:40
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_pgtable.c:hash__map_kernel_page
```
```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c00000000009592c)
Location: arch/powerpc/include/asm/pgtable-be-types.h:40
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:pud_free_pmd_page
  - arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable
  - arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page
  - arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page
```
```
In arch/powerpc/mm/book3s64/subpage_prot.c (c00000000009f8d8)
Location: arch/powerpc/include/asm/pgtable-be-types.h:40
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/subpage_prot.c:hpte_flush_range
```
```
In arch/powerpc/mm/hugetlbpage.c (c0000000000a5cc0)
Location: arch/powerpc/include/asm/pgtable-be-types.h:40
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
  - arch/powerpc/mm/hugetlbpage.c:huge_pte_alloc
```
```
In arch/powerpc/xmon/xmon.c (c00000000010d454)
Location: arch/powerpc/include/asm/pgtable-be-types.h:40
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:show_pte
```
```
In mm/gup.c (c0000000003b6868)
Location: arch/powerpc/include/asm/pgtable-be-types.h:40
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (c0000000003baf7c)
Location: arch/powerpc/include/asm/pgtable-be-types.h:40
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
In mm/mprotect.c (c0000000003d1fb8)
Location: arch/powerpc/include/asm/pgtable-be-types.h:40
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d3c6c)
Location: arch/powerpc/include/asm/pgtable-be-types.h:40
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (c0000000003d5790)
Location: arch/powerpc/include/asm/pgtable-be-types.h:40
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (c0000000003d6774)
Location: arch/powerpc/include/asm/pgtable-be-types.h:40
Inline: True
```
```
In mm/pgtable-generic.c (c0000000003d74d8)
Location: arch/powerpc/include/asm/pgtable-be-types.h:40
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/rmap.c (c0000000003d8774)
Location: arch/powerpc/include/asm/pgtable-be-types.h:40
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (c0000000003dbaa8)
Location: arch/powerpc/include/asm/pgtable-be-types.h:40
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_page_range_noflush
  - mm/vmalloc.c:vunmap_page_range
  - mm/vmalloc.c:vunmap_page_range
  - mm/vmalloc.c:vunmap_page_range
```
```
In mm/swapfile.c (c0000000003fcf58)
Location: arch/powerpc/include/asm/pgtable-be-types.h:40
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/sparse-vmemmap.c (c000000000eedca0)
Location: arch/powerpc/include/asm/pgtable-be-types.h:40
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (c00000000043275c)
Location: arch/powerpc/include/asm/pgtable-be-types.h:40
Inline: True
```
```
In mm/huge_memory.c (c0000000004423a0)
Location: arch/powerpc/include/asm/pgtable-be-types.h:40
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (c00000000045ea54)
Location: arch/powerpc/include/asm/pgtable-be-types.h:40
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (c00000000046a3f0)
Location: arch/powerpc/include/asm/pgtable-be-types.h:40
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (c00000000050192c)
Location: arch/powerpc/include/asm/pgtable-be-types.h:40
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (c000000000eca0d4)
Location: arch/powerpc/include/asm/pgtable-be-types.h:40
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288d66e)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82894c53)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:pud_large
```
```
In arch/x86/xen/trace.c (ffffffff8102a9c4)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810388b4)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8289c806)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e8fd)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e1b8)
Location: arch/x86/include/asm/paravirt.h:508
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
  - arch/x86/mm/init_64.c:pud_same
  - arch/x86/mm/init_64.c:pud_same
```
```
In arch/x86/mm/fault.c (ffffffff8107ea39)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828adc0a)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810830c6)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81086edd)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81088be5)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pud_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108968d)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108d94f)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b03e6)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff812517ef)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812555fa)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81266b99)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81267cd7)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81269b6b)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8126a8fd)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff8126ad05)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/rmap.c (ffffffff8126bdc6)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8126def1)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff812839da)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128d3c9)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a6e01b)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812a762e)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b1042)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff812c2f42)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812ca553)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff812ceec8)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff81332aea)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff818ab3a0)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a4e9eb)
Location: arch/x86/include/asm/paravirt.h:508
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a066e)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7c4a)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:pud_large
```
```
In arch/x86/xen/trace.c (ffffffff8102a824)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038714)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828af7c9)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106edad)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e168)
Location: arch/x86/include/asm/paravirt.h:508
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
  - arch/x86/mm/init_64.c:pud_same
  - arch/x86/mm/init_64.c:pud_same
```
```
In arch/x86/mm/fault.c (ffffffff8107e9e9)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c0b09)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81083076)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81086e8d)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81088b95)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pud_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108963d)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108d8ff)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c32e5)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff8124f58f)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8125339a)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81264939)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81265a77)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8126790b)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8126869d)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff81268aa5)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/rmap.c (ffffffff81269b66)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8126bc91)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff812817ea)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128b1d9)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81ada42b)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812a543e)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
```
```
In mm/huge_memory.c (ffffffff812aee52)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff812c0d52)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812c8363)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff812cccd8)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff813305ba)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff818fc3a0)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81abaddb)
Location: arch/x86/include/asm/paravirt.h:508
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a0673)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7c50)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:pud_large
```
```
In arch/x86/xen/trace.c (ffffffff8102b614)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pud
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81039714)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828af7f7)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107102d)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81080258)
Location: arch/x86/include/asm/paravirt.h:508
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
  - arch/x86/mm/init_64.c:pud_same
  - arch/x86/mm/init_64.c:pud_same
```
```
In arch/x86/mm/fault.c (ffffffff81080ad9)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c3c54)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8108543d)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81088fbd)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff8108ae35)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pud_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108b8dd)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108fcdf)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c648b)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff8125eeff)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81262daa)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81274302)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81275419)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812772a1)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81278024)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff81278435)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/rmap.c (ffffffff812794d6)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8127b6a1)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81291525)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8129aff9)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81ae68e1)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812b4b6e)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
```
```
In mm/huge_memory.c (ffffffff812bf1a2)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In mm/memory-failure.c (ffffffff812d1812)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812d9073)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff812dda68)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff81342f08)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff8191d3a0)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81ac722b)
Location: arch/x86/include/asm/paravirt.h:508
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
