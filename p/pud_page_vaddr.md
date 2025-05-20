# Function: <code>pud_page_vaddr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_page_vaddr(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101e66d)
Location: arch/x86/include/asm/pgtable.h:591
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810346bc)
Location: arch/x86/include/asm/pgtable.h:591
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81f6a360)
Location: arch/x86/include/asm/pgtable.h:591
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bb02)
Location: arch/x86/include/asm/pgtable.h:591
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81068c50)
Location: arch/x86/include/asm/pgtable.h:591
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
Direct callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:vmemmap_populate
```
```
In arch/x86/mm/fault.c (ffffffff8106a2c4)
Location: arch/x86/include/asm/pgtable.h:591
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff81f77df2)
Location: arch/x86/include/asm/pgtable.h:591
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c5a0)
Location: arch/x86/include/asm/pgtable.h:591
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/gup.c (ffffffff810718a2)
Location: arch/x86/include/asm/pgtable.h:591
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In mm/gup.c (ffffffff811ba878)
Location: arch/x86/include/asm/pgtable.h:591
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811bbe99)
Location: arch/x86/include/asm/pgtable.h:591
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
In mm/mprotect.c (ffffffff811c8589)
Location: arch/x86/include/asm/pgtable.h:591
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811c9407)
Location: arch/x86/include/asm/pgtable.h:591
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811ca8b3)
Location: arch/x86/include/asm/pgtable.h:591
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811cc5f9)
Location: arch/x86/include/asm/pgtable.h:591
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/pagewalk.c (ffffffff811cfe64)
Location: arch/x86/include/asm/pgtable.h:591
Inline: True
```
```
In mm/swapfile.c (ffffffff811d4212)
Location: arch/x86/include/asm/pgtable.h:591
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811dd730)
Location: arch/x86/include/asm/pgtable.h:591
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff8181f2ef)
Location: arch/x86/include/asm/pgtable.h:591
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff811f6f7b)
Location: arch/x86/include/asm/pgtable.h:591
Inline: True
Inline callers:
  - mm/huge_memory.c:page_check_address_pmd
  - mm/huge_memory.c:split_huge_page_address
```
```
In mm/userfaultfd.c (ffffffff81207788)
Location: arch/x86/include/asm/pgtable.h:591
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8125af71)
Location: arch/x86/include/asm/pgtable.h:591
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff813eb124)
Location: arch/x86/include/asm/pgtable.h:591
Inline: True
```
**Symbols:**

```
ffffffff81068c50-ffffffff81068c8b: pud_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_page_vaddr(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81f8ab3c)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:__xen_pgd_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81033887)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81f9263c)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bbeb)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81069a47)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff81069f2e)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff81fa0539)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c8ea)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/gup.c (ffffffff81071bc3)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810740ef)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/gup.c (ffffffff811d57f5)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811daba8)
Location: arch/x86/include/asm/pgtable.h:628
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
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e57ef)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811e7785)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811e9654)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/pagewalk.c (ffffffff811ed05a)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
```
```
In mm/swapfile.c (ffffffff811f20d3)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811fba15)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff818999a3)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff8121679d)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8122d060)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81283b37)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81431518)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff8176085f)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff81068940-ffffffff81068978: pud_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_page_vaddr(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81fc5f2a)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:__xen_pgd_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810334b4)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81fcd908)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105eb65)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106d61b)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff8106dace)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff81fdbaaa)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8107052a)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/gup.c (ffffffff81075733)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81077c67)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/gup.c (ffffffff811e57f5)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811ea76a)
Location: arch/x86/include/asm/pgtable.h:628
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
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f5a2e)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff811f6f17)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff811f744a)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
```
```
In mm/rmap.c (ffffffff811f8b15)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811fa9a4)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81202ac6)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8120c515)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff818ce055)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff81228d5d)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8123f580)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81297729)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff8144d788)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178d9bf)
Location: arch/x86/include/asm/pgtable.h:628
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff8106c590-ffffffff8106c5c8: pud_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_page_vaddr(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff820a6d64)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81031677)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff820adf52)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e204)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106cc5d)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff8106d7fc)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff820bca6c)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8106fbd7)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81076554)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/gup.c (ffffffff811f0926)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811f1ada)
Location: arch/x86/include/asm/pgtable.h:767
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
In mm/mprotect.c (ffffffff811ff78d)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81200803)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81201e0f)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812023f5)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
```
```
In mm/rmap.c (ffffffff81203aec)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8120578c)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8120db7a)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81217e95)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff819054ea)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff81234a4d)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8124aed4)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812a5062)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff817abbac)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff818ed439)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8106b9a0-ffffffff8106b9d8: pud_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_page_vaddr(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826a6469)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826ad4af)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810338ce)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff826b4462)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061edb)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff810718c0)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff81072211)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff826c34d3)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81075069)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81079eed)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107c821)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff8108020f)
Location: arch/x86/include/asm/pgtable.h:776
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/gup.c (ffffffff8120550a)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff81208845)
Location: arch/x86/include/asm/pgtable.h:776
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
In mm/mprotect.c (ffffffff81217dcf)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81218fc6)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8121a961)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8121b2ff)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
```
```
In mm/rmap.c (ffffffff8121c7f9)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8121f75e)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81228d8b)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81232c80)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8198f528)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff81249fa8)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
```
```
In mm/huge_memory.c (ffffffff8125443a)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8126b153)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812c848b)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff8182315b)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff81973567)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff810702a0-ffffffff810702f2: pud_page_vaddr (STB_LOCAL)
ffffffff8108020f-ffffffff81080255: pud_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_page_vaddr(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826cf5fb)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826d67ed)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034c44)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff826ddbe3)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81064f84)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81074587)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff81075268)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff826ed73c)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81077acd)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff8107cb3a)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107f4cb)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff81083459)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f0331)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff81226995)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81229889)
Location: arch/x86/include/asm/pgtable.h:818
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
In mm/mprotect.c (ffffffff81239b6b)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
```
```
In mm/mremap.c (ffffffff8123a995)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8123c66e)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8123d07d)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
```
```
In mm/rmap.c (ffffffff8123e5d6)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81240ee1)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8124a08b)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81255cc6)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff819ebdcf)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff8126ef1c)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
```
```
In mm/huge_memory.c (ffffffff8127829f)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff81288ad2)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff8128fb44)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812f180f)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d43e)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff819cfa0c)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81073240-ffffffff81073286: pud_page_vaddr (STB_LOCAL)
ffffffff81228df0-ffffffff81228e36: pud_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_page_vaddr(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82885628)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8288c736)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81035e24)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8289402b)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106abf4)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8107a477)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff8107b068)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828a42ce)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8107e27d)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff8108357d)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810860bd)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff8108a00b)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a7039)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff81239a75)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8123cd99)
Location: arch/x86/include/asm/pgtable.h:843
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
In mm/mprotect.c (ffffffff8124d48a)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124eb99)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81250a8b)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81251540)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81252b66)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81254bf1)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8125e6cb)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8126a116)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a2703d)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812835cc)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
```
```
In mm/huge_memory.c (ffffffff8128c8df)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8129d7d5)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff812a4a64)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813061cf)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff8188f413)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a08ee1)
Location: arch/x86/include/asm/pgtable.h:843
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff810792e0-ffffffff81079326: pud_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_page_vaddr(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289c6a6)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a3bd7)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81037f84)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828ab7d9)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e3ad)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e1ba)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff8107e9d1)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828bc78d)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81081b87)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff810871ed)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089b06)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108ddb9)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf6f2)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff8124acaf)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8124ea09)
Location: arch/x86/include/asm/pgtable.h:860
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
In mm/mprotect.c (ffffffff8125fc89)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81260eee)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81262d6b)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8126380a)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81264ee6)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81266fa1)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8127b91a)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81285249)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a978dd)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff812a75c2)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812b8aa7)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812c0023)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff812c4def)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff8132772a)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff818d9413)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a787eb)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8107cef0-ffffffff8107cf36: pud_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_page_vaddr(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289f696)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a6c71)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038754)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828ae7e7)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f95d)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107f24a)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff8107fa61)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c2c34)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81082c47)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81087edd)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108a776)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108ea19)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c5b7e)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff8125919f)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8125cfaa)
Location: arch/x86/include/asm/pgtable.h:860
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
In mm/mprotect.c (ffffffff8126e549)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126f687)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8127151b)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81271d13)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
```
```
In mm/rmap.c (ffffffff81273776)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812758a1)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8128b3fa)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81294de9)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81acf1ab)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812af04e)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b8a62)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812ca987)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812d1f73)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff812d679f)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff8133a50a)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff8190b413)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81aafb9b)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8107df80-ffffffff8107dfc6: pud_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_page_vaddr(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82cc5b82)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82cccfca)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b01e)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81047a55)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076e67)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81085cb7)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff81086c48)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff82ce5ff0)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a37d)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c35f)
Location: arch/x86/include/asm/pgtable.h:869
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
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff81094d69)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff810952d1)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
```
```
In mm/gup.c (ffffffff8128930f)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8128d5d1)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8129ea56)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
```
```
In mm/mremap.c (ffffffff8129fb9a)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pmd
```
```
In mm/page_vma_mapped.c (ffffffff812a1dd0)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812a260f)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
```
```
In mm/rmap.c (ffffffff812a4949)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812a72af)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
```
```
In mm/swapfile.c (ffffffff812bddd5)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812c83f1)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7b68)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812e50e6)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ed614)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff813007bf)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81307d61)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8137234e)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
```
```
In lib/ioremap.c (ffffffff815e9a8b)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc430)
Location: arch/x86/include/asm/pgtable.h:869
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810845b0-ffffffff810845f0: pud_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_page_vaddr(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82fb1476)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82fb8e06)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b82e)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81bd4cdb)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077497)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086d55)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff81088528)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff82fd3976)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a5ed)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c5ff)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff81094129)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81bda340)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
```
```
In kernel/events/core.c (ffffffff8123cb22)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff81292fef)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8129fa82)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812a9e16)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
```
```
In mm/mremap.c (ffffffff812aba30)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812ad5fd)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812adf4f)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
```
```
In mm/rmap.c (ffffffff812b00d9)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b252f)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
```
```
In mm/ioremap.c (ffffffff812b8561)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_page_range
```
```
In mm/swapfile.c (ffffffff812c98f9)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812d3fc1)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81c40893)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812f04a9)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f8d34)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8130c95f)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81313a91)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8138019e)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81bd1410)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81085a90-ffffffff81085ad0: pud_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_page_vaddr(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff831bb601)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff831c3362)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103d1cd)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81bc7124)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077f1f)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81087a07)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff810891a7)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff831de570)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff8108b23d)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d021)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff81094acb)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81bcc468)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
```
```
In kernel/events/core.c (ffffffff81243e37)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff8129a7b4)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff812a52f3)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812af295)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
```
```
In mm/mremap.c (ffffffff812b0e2b)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812b27ef)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812b333f)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
```
```
In mm/rmap.c (ffffffff812b56cd)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b8c63)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff812d0567)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff812daea6)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81c328e9)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812f67c0)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ff27f)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff813130cf)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81319c3c)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8138751f)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81bc341a)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810868a0-ffffffff810868e0: pud_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In arch/riscv/mm/fault.c (ffffffe0000b9dfe)
Location: arch/riscv/include/asm/pgtable-64.h:56
Inline: True
Inline callers:
  - arch/riscv/mm/fault.c:do_page_fault
```
```
In mm/gup.c (ffffffe000204a18)
Location: arch/riscv/include/asm/pgtable-64.h:56
Inline: True
```
```
In mm/memory.c (ffffffe000206616)
Location: arch/riscv/include/asm/pgtable-64.h:56
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
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
In mm/mprotect.c (ffffffe0002110e4)
Location: arch/riscv/include/asm/pgtable-64.h:56
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffe000211ac4)
Location: arch/riscv/include/asm/pgtable-64.h:56
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffe0002126f0)
Location: arch/riscv/include/asm/pgtable-64.h:56
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffe0002129e8)
Location: arch/riscv/include/asm/pgtable-64.h:56
Inline: True
```
```
In mm/rmap.c (ffffffe000213760)
Location: arch/riscv/include/asm/pgtable-64.h:56
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffe000215200)
Location: arch/riscv/include/asm/pgtable-64.h:56
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffe000226904)
Location: arch/riscv/include/asm/pgtable-64.h:56
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffe00022fbf0)
Location: arch/riscv/include/asm/pgtable-64.h:56
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffe000048ffe)
Location: arch/riscv/include/asm/pgtable-64.h:56
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/userfaultfd.c (ffffffe00024fa52)
Location: arch/riscv/include/asm/pgtable-64.h:56
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffe0002a8776)
Location: arch/riscv/include/asm/pgtable-64.h:56
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffe0008b3100)
Location: arch/riscv/include/asm/pgtable-64.h:56
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
long unsigned int pud_page_vaddr(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288d696)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82894c7a)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810388b4)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8289c806)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e8fd)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e24a)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff8107ea61)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828adc0a)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81081c47)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81086edd)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089736)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108d9d9)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b0b16)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff812517ef)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812555fa)
Location: arch/x86/include/asm/pgtable.h:860
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
In mm/mprotect.c (ffffffff81266b99)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81267cd7)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81269b6b)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8126a363)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
```
```
In mm/rmap.c (ffffffff8126bdc6)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8126def1)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff812839da)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128d3c9)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a6e01b)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812a762e)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b1042)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812c2f67)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812ca553)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff812ced7f)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff81332aea)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff818ab413)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a4e9eb)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8107cf80-ffffffff8107cfc6: pud_page_vaddr (STB_LOCAL)
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
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8102825f)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828949d3)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105eee0)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106d489)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8106de03)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828a5e99)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810708c2)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pgtable.c (ffffffff81075b26)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107849f)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff8107c470)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8c9b)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff812446de)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff81247d11)
Location: arch/x86/include/asm/pgtable.h:860
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
In mm/mprotect.c (ffffffff81258a54)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8125a019)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8125be32)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8125c824)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff8125de48)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8125ff0e)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81275879)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8127f190)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a532)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff8129908b)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
```
```
In mm/huge_memory.c (ffffffff812a243a)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812b404a)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff812bb598)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff812bfa21)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff81323487)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff818653c0)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a0bad5)
Location: arch/x86/include/asm/pgtable.h:860
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
long unsigned int pud_page_vaddr(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a0696)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7c71)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038714)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828af7c9)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106edad)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e1fa)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff8107ea11)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c0b09)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81081bf7)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81086e8d)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810896e6)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108d989)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c3a15)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff8124f58f)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8125339a)
Location: arch/x86/include/asm/pgtable.h:860
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
In mm/mprotect.c (ffffffff81264939)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81265a77)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8126790b)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81268103)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
```
```
In mm/rmap.c (ffffffff81269b66)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8126bc91)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff812817ea)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128b1d9)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81ada42b)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812a543e)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
```
```
In mm/huge_memory.c (ffffffff812aee52)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812c0d77)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812c8363)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff812ccb8f)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff813305ba)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff818fc413)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81abaddb)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8107cf30-ffffffff8107cf76: pud_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pud_page_vaddr(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a069b)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7c77)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81039714)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828af7f7)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107102d)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810802ea)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff81080b01)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c3c54)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81083d17)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81088fbd)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108b986)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108fd69)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c6bbb)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff8125eeff)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81262daa)
Location: arch/x86/include/asm/pgtable.h:860
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
In mm/mprotect.c (ffffffff81274302)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81275419)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812772a1)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81277a83)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
```
```
In mm/rmap.c (ffffffff812794d6)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8127b6a1)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81291525)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8129aff9)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81ae68e1)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812b4b6e)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
```
```
In mm/huge_memory.c (ffffffff812bf1a2)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812d1837)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812d9073)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff812dd91f)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff81342f08)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff8191d413)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81ac722b)
Location: arch/x86/include/asm/pgtable.h:860
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8107f020-ffffffff8107f066: pud_page_vaddr (STB_LOCAL)
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
