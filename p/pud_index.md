# Function: <code>pud_index</code>

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
In arch/x86/kernel/head64.c (0)
Location: arch/x86/include/asm/pgtable.h:644
Inline: True
```
```
In arch/x86/xen/mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:644
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: arch/x86/include/asm/pgtable.h:644
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/include/asm/pgtable.h:644
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/include/asm/pgtable.h:644
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:644
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable.h:644
Inline: True
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:644
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:644
Inline: True
```
```
In arch/x86/mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:644
Inline: True
```
```
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:644
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:644
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:644
Inline: True
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/pgtable.h:644
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:644
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:644
Inline: True
```
```
In mm/pagewalk.c (0)
Location: arch/x86/include/asm/pgtable.h:644
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:644
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/pgtable.h:644
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: arch/x86/include/asm/pgtable.h:644
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:644
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:644
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:644
Inline: True
```
```
In lib/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:644
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
In arch/x86/kernel/head64.c (ffffffff81f814a3)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:early_make_pgtable
```
```
In arch/x86/xen/mmu.c (ffffffff81f8aad5)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103376b)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81f925e0)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bb2b)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106999d)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff81069eab)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff81fa0515)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8106ec23)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/gup.c (ffffffff81071b9f)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In arch/x86/mm/kaslr.c (ffffffff81896ea0)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
```
```
In mm/gup.c (ffffffff811d57b4)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811dab60)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811e4706)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e577d)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811e7732)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811e9613)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/pagewalk.c (ffffffff811ecfa4)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
```
```
In mm/swapfile.c (ffffffff811f1ff5)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811fb9a3)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81899a90)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff81216732)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8122d01a)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81283ae0)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff8143147b)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff8176068c)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
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
In arch/x86/kernel/head64.c (ffffffff81fbd4a3)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:early_make_pgtable
```
```
In arch/x86/xen/mmu.c (ffffffff81fc5ec3)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103339b)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81fcd8ac)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105eaa5)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106d577)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8106da4b)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff81fdba86)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81072893)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/gup.c (ffffffff8107570f)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In arch/x86/mm/kaslr.c (ffffffff818cb589)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
```
```
In mm/gup.c (ffffffff811e57b4)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811ea722)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811f4726)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f59bc)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff811f6ebe)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff811f7394)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
```
```
In mm/rmap.c (ffffffff811f8ac2)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811fa963)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff812029e5)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8120c4a3)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff818ce142)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff81228cf2)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8123f53a)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812976d2)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff8144d6eb)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178d7ec)
Location: arch/x86/include/asm/pgtable.h:681
Inline: True
Inline callers:
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
In arch/x86/kernel/head64.c (ffffffff8209d49c)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810201d5)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81031568)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff820adef6)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e147)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106cbb0)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8106d77b)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff81071e51)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/kaslr.c (ffffffff81902b76)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107dded)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
```
```
In mm/gup.c (ffffffff811f0919)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811f1a54)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811ff699)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81200786)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81201d76)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812023da)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
```
```
In mm/rmap.c (ffffffff81203a98)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81205717)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8120da9a)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81217e23)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff819055d7)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff812349e3)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8124ae95)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812a500b)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff817ab984)
Location: arch/x86/include/asm/pgtable.h:802
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff818ed3a0)
Location: arch/x86/include/asm/pgtable.h:802
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
In arch/x86/kernel/head64.c (ffffffff826a3351)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81020e54)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103379b)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff826b4401)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061e20)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81071810)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff81072194)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff81077690)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/kaslr.c (ffffffff8198cab7)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff826c5747)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5ad9)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff826c7fba)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff81205472)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812087de)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81217ccd)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81218f4e)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8121a87f)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8121b000)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
```
```
In mm/rmap.c (ffffffff8121c7ad)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8121f6f8)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81228c9b)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81232be3)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff8198f635)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff81249f58)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
```
```
In mm/huge_memory.c (ffffffff812543d5)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8126b10e)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812c8432)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff81822f06)
Location: arch/x86/include/asm/pgtable.h:810
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff819734c8)
Location: arch/x86/include/asm/pgtable.h:810
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
In arch/x86/kernel/head64.c (ffffffff826cc3f8)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826d6295)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034b1f)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff826ddb8d)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81064ebe)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff810744b7)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810751d4)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff8107a0d6)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/kaslr.c (ffffffff819e93bb)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff810833a3)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f016a)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff826f25b0)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff812268ff)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81229808)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81239a9f)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
```
```
In mm/mremap.c (ffffffff8123a915)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8123c60a)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8123ce4c)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
```
```
In mm/rmap.c (ffffffff8123e573)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81240e5c)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81249fa3)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81255c2c)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff819ebea9)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff8126eec8)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
```
```
In mm/huge_memory.c (ffffffff81278237)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812889e9)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff8128fafe)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812f1562)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d212)
Location: arch/x86/include/asm/pgtable.h:852
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff819cf963)
Location: arch/x86/include/asm/pgtable.h:852
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
In arch/x86/kernel/head64.c (ffffffff82882403)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8288c1e0)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81035cff)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff82893fd5)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ab2e)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8107a3a7)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8107afd4)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff810808b6)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff81a24d01)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff81089f54)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a6e72)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828a8ea2)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff812399b5)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8123cd18)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff8124d3bd)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124eb18)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81250a27)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812512ff)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81252b03)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81254b6c)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8125e5e3)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8126a07c)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81a27117)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff81283578)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
```
```
In mm/huge_memory.c (ffffffff8128c877)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8129d6e9)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff812a4a1e)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81305f22)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff8188d0c2)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff8188f346)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a08dcf)
Location: arch/x86/include/asm/pgtable.h:877
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
In arch/x86/kernel/head64.c (ffffffff82899393)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a367f)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81037e5f)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828ab784)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e2e7)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e0e7)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8107e959)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828bc722)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810843b6)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff81a9509b)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108dd03)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf52a)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c175c)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff8124abe5)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8124e986)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8125fbbc)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81260e6d)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81262d07)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812635df)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81264e83)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81266f1c)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8127b846)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff812851b2)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81a979bb)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff812a755a)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812b8a33)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812bffdd)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813274b5)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff818d7af2)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff818d9346)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a786a3)
Location: arch/x86/include/asm/pgtable.h:894
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
In arch/x86/kernel/head64.c (ffffffff8289c393)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a6725)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103862f)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828ae792)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f897)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107f177)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8107f9e9)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c2bc9)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810850f6)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff81acc97b)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108e963)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c59a5)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c7bd7)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff812590d5)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8125cf23)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8126e47c)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126f606)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812714b7)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812720a9)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81273713)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8127581c)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8128b326)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81294d52)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81acf289)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812aeffa)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b89fa)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812ca913)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812d1f2d)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8133a295)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff81909e32)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff8190b346)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81aafa53)
Location: arch/x86/include/asm/pgtable.h:894
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
In arch/x86/kernel/head64.c (ffffffff82cc244e)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/pgtable.h:57
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82ccc30f)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103afec)
Location: include/linux/pgtable.h:57
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff810479ee)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076d99)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81085af1)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:fill_pud
```
```
In arch/x86/mm/fault.c (ffffffff81086bd6)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (0)
Location: include/linux/pgtable.h:57
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/pgtable.h:57
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c682)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81bc51f5)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81094cb3)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8c85)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/linux/pgtable.h:57
Inline: True
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff82cec3c4)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_prolog
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_prolog
```
```
In mm/gup.c (ffffffff812892c7)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8128d551)
Location: include/linux/pgtable.h:57
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
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8129ee9b)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff8129fb23)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pmd
```
```
In mm/page_vma_mapped.c (ffffffff812a1d68)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812a296c)
Location: include/linux/pgtable.h:57
Inline: True
```
```
In mm/rmap.c (ffffffff812a48eb)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812a722f)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
```
```
In mm/swapfile.c (ffffffff812bdd1c)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812c838a)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7c46)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812e5094)
Location: include/linux/pgtable.h:57
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ed5ac)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8130074c)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81307d19)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813722e4)
Location: include/linux/pgtable.h:57
Inline: True
```
```
In lib/ioremap.c (ffffffff815e9957)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bba70c)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc3dc)
Location: include/linux/pgtable.h:57
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
In arch/x86/kernel/head64.c (ffffffff82fae48d)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/pgtable.h:57
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82fb814d)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b7fc)
Location: include/linux/pgtable.h:57
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81bd4c74)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810773c9)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086bb6)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810884b6)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (0)
Location: include/linux/pgtable.h:57
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/pgtable.h:57
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cc38)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81c3e0c8)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81094073)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd670b)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/linux/pgtable.h:57
Inline: True
```
```
In kernel/events/core.c (ffffffff8123ca9b)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff81292fa7)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8129fa02)
Location: include/linux/pgtable.h:57
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
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812aa25b)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812aafaf)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812ad593)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812ae2ac)
Location: include/linux/pgtable.h:57
Inline: True
```
```
In mm/rmap.c (ffffffff812b007b)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b24af)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
```
```
In mm/ioremap.c (ffffffff812b8428)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_page_range
```
```
In mm/swapfile.c (ffffffff812c9840)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812d3f5a)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81c40971)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812f0457)
Location: include/linux/pgtable.h:57
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f8ccc)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8130c8ec)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81313a49)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81380134)
Location: include/linux/pgtable.h:57
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bcee3c)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81bd13bc)
Location: include/linux/pgtable.h:57
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
In arch/x86/kernel/head64.c (ffffffff831b848d)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/pgtable.h:57
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff831c27b0)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103d19b)
Location: include/linux/pgtable.h:57
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81bc70cb)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077e57)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81087868)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8108913a)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (0)
Location: include/linux/pgtable.h:57
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/pgtable.h:57
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d82a)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81c303dd)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81094a14)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e115f)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/linux/pgtable.h:57
Inline: True
```
```
In kernel/events/core.c (ffffffff81243db0)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff8129a701)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff812a527d)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812af6a8)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812b03ed)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812b2763)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812b369f)
Location: include/linux/pgtable.h:57
Inline: True
```
```
In mm/rmap.c (ffffffff812b566f)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b8bbf)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff812d04ab)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff812dae3f)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81c3294f)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812f676f)
Location: include/linux/pgtable.h:57
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ff21e)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8131305c)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81319bf6)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813874bd)
Location: include/linux/pgtable.h:57
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bc27f5)
Location: include/linux/pgtable.h:57
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81bc33bf)
Location: include/linux/pgtable.h:57
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
In arch/x86/kernel/head64.c (ffffffff832984ed)
Location: include/linux/pgtable.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/pgtable.h:76
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff832a31bc)
Location: include/linux/pgtable.h:76
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81042cc2)
Location: include/linux/pgtable.h:76
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81c9a6df)
Location: include/linux/pgtable.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81085694)
Location: include/linux/pgtable.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81096be4)
Location: include/linux/pgtable.h:76
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810985c1)
Location: include/linux/pgtable.h:76
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (0)
Location: include/linux/pgtable.h:76
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/pgtable.h:76
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109d0c4)
Location: include/linux/pgtable.h:76
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81d4eba5)
Location: include/linux/pgtable.h:76
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810a4995)
Location: include/linux/pgtable.h:76
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c49e8)
Location: include/linux/pgtable.h:76
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/linux/pgtable.h:76
Inline: True
```
```
In kernel/events/core.c (ffffffff8127e74f)
Location: include/linux/pgtable.h:76
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff812db0d0)
Location: include/linux/pgtable.h:76
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff812e67ff)
Location: include/linux/pgtable.h:76
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812f0ee9)
Location: include/linux/pgtable.h:76
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812f1c51)
Location: include/linux/pgtable.h:76
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812f43b8)
Location: include/linux/pgtable.h:76
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812f524a)
Location: include/linux/pgtable.h:76
Inline: True
```
```
In mm/rmap.c (ffffffff812f7320)
Location: include/linux/pgtable.h:76
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812fb182)
Location: include/linux/pgtable.h:76
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813159fd)
Location: include/linux/pgtable.h:76
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81321e9a)
Location: include/linux/pgtable.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81d51374)
Location: include/linux/pgtable.h:76
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_remap_range
```
```
In mm/migrate.c (ffffffff81340dc0)
Location: include/linux/pgtable.h:76
Inline: True
```
```
In mm/huge_memory.c (ffffffff81348e42)
Location: include/linux/pgtable.h:76
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8135fb5e)
Location: include/linux/pgtable.h:76
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff813669aa)
Location: include/linux/pgtable.h:76
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813d47b2)
Location: include/linux/pgtable.h:76
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81c92eb5)
Location: include/linux/pgtable.h:76
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81c943e7)
Location: include/linux/pgtable.h:76
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
In arch/x86/kernel/head64.c (ffffffff834464e5)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/pgtable.h:77
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8345242b)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8104abfc)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/tboot.c (ffffffff81e49b49)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095a61)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810a96a0)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810ab21c)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (0)
Location: include/linux/pgtable.h:77
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/pgtable.h:77
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b094c)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81f1e9fb)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810b9230)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83477411)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/linux/pgtable.h:77
Inline: True
```
```
In kernel/events/core.c (ffffffff812d33bf)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/percpu.c (ffffffff8348b985)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff8133ac80)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8133d7ec)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff813549e4)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81355815)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff813583a9)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81359102)
Location: include/linux/pgtable.h:77
Inline: True
```
```
In mm/rmap.c (ffffffff8135c93a)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81362686)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81380f9f)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8138f0c5)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81f2198d)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_range
```
```
In mm/migrate_device.c (ffffffff813b7c9f)
Location: include/linux/pgtable.h:77
Inline: True
```
```
In mm/huge_memory.c (ffffffff813bf2b3)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff813da79a)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff813e3d39)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8145fc5d)
Location: include/linux/pgtable.h:77
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81e4284d)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81e43413)
Location: include/linux/pgtable.h:77
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
In arch/x86/kernel/head64.c (ffffffff83e5f469)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/pgtable.h:77
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e6f993)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810568f3)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/tboot.c (ffffffff81067ea3)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab6a6)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810c2a9c)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810c35bd)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (0)
Location: include/linux/pgtable.h:77
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cb012)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff820c7828)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810d4b98)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea08de)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/linux/pgtable.h:77
Inline: True
```
```
In kernel/events/core.c (ffffffff8133b635)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff8137fdfb)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/percpu.c (ffffffff83ebc883)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff813b2a17)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_p4d_mask
```
```
In mm/memory.c (ffffffff813b680c)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff813cef42)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813cff85)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff813d29dc)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813d39dc)
Location: include/linux/pgtable.h:77
Inline: True
```
```
In mm/rmap.c (ffffffff813d701a)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff813de012)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813ff7d4)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8140dbbb)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/hugetlb_vmemmap.c (ffffffff814140a3)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse-vmemmap.c (ffffffff820cb048)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate_device.c (ffffffff8143995e)
Location: include/linux/pgtable.h:77
Inline: True
```
```
In mm/memory-failure.c (ffffffff814609ba)
Location: include/linux/pgtable.h:77
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8146b759)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff814ef546)
Location: include/linux/pgtable.h:77
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff8201d276)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff8201e4ac)
Location: include/linux/pgtable.h:77
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
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/pgtable.h:77
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83690753)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/head64.c (ffffffff83694699)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810578c3)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/tboot.c (ffffffff81069753)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af266)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810c617c)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810c6e0d)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (0)
Location: include/linux/pgtable.h:77
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce642)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff8214b8b8)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810d80a8)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4aa0)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/linux/pgtable.h:77
Inline: True
```
```
In kernel/events/core.c (ffffffff8136d013)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813b130b)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/percpu.c (ffffffff836e4f03)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff813e74fe)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_p4d_mask
```
```
In mm/memory.c (ffffffff813eb22a)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_p4d_range
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81403642)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff81404a48)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff8140771c)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff814083ac)
Location: include/linux/pgtable.h:77
Inline: True
```
```
In mm/rmap.c (ffffffff8140bf1d)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81412872)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff814324ab)
Location: include/linux/pgtable.h:77
Inline: True
```
```
In mm/hugetlb.c (ffffffff81440f6e)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/hugetlb_vmemmap.c (ffffffff81447603)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse-vmemmap.c (ffffffff8214f2d8)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate_device.c (ffffffff8146e706)
Location: include/linux/pgtable.h:77
Inline: True
```
```
In mm/memory-failure.c (ffffffff8149518d)
Location: include/linux/pgtable.h:77
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814a055c)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81524d0d)
Location: include/linux/pgtable.h:77
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff8209d906)
Location: include/linux/pgtable.h:77
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff8209e4ac)
Location: include/linux/pgtable.h:77
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
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/pgtable.h:79
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff838c0223)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/head64.c (ffffffff838c4589)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105eb63)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/tboot.c (ffffffff81070c93)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5df6)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810ce5cc)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810cf2cd)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (0)
Location: include/linux/pgtable.h:79
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d6d22)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff8222e368)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810e0928)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f56a0)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/linux/pgtable.h:79
Inline: True
```
```
In kernel/events/core.c (ffffffff81396253)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813da88b)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/percpu.c (ffffffff83917714)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff81412183)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff81415253)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8142fbc2)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff81431018)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff81433daa)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81434acc)
Location: include/linux/pgtable.h:79
Inline: True
```
```
In mm/rmap.c (ffffffff814387bd)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8143f2e2)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff8146b8cb)
Location: include/linux/pgtable.h:79
Inline: True
```
```
In mm/hugetlb.c (ffffffff8147b09e)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff822321a8)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate_device.c (ffffffff8149d17a)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/memory-failure.c (ffffffff814c4af5)
Location: include/linux/pgtable.h:79
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814cfbfc)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8155899e)
Location: include/linux/pgtable.h:79
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff82175106)
Location: include/linux/pgtable.h:79
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff821764ac)
Location: include/linux/pgtable.h:79
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
In arch/x86/kernel/head64.c (ffffffff8288a393)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8289472e)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103878f)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8289c7b1)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e837)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e177)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8107e9e9)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828adb9f)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810840f6)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff81a6b7eb)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108d923)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b093d)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828b2b6f)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff81251725)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81255573)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81266acc)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81267c56)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81269b07)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8126a6f9)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff8126bd63)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8126de6c)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81283906)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128d332)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81a6e0f9)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812a75da)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b0fda)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812c2ef3)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812ca50d)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81332875)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff818a91f2)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff818ab346)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a4e8a3)
Location: arch/x86/include/asm/pgtable.h:894
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
In arch/x86/kernel/head64.c (ffffffff82888337)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8102816d)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8289498b)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ee9e)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106d3d7)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8106dd9c)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828a5e3f)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81070c20)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pgd
  - arch/x86/mm/pageattr.c:populate_pgd
  - arch/x86/mm/pageattr.c:populate_pgd
  - arch/x86/mm/pageattr.c:populate_pgd
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff81a27d30)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8107c400)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8ac2)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828aacdb)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff81244615)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81247cbf)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff8125898b)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81259fb8)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8125bdf1)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8125c5ef)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff8125de1e)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8125fe99)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff812757c2)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8127f125)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a5a5)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff8129902a)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
```
```
In mm/huge_memory.c (ffffffff812a23f6)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812b3ffc)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff812bb54a)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8132344f)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff81863e4a)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff81865353)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a0b98e)
Location: arch/x86/include/asm/pgtable.h:894
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
In arch/x86/kernel/head64.c (ffffffff8289d393)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7725)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810385ef)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828af774)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ece7)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e127)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8107e999)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c0a9e)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810840a6)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff81ad7bfb)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108d8d3)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c383c)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c5a6e)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff8124f4c5)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81253313)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8126486c)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812659f6)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812678a7)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81268499)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81269b03)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8126bc0c)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81281716)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128b142)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81ada509)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812a53ea)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
```
```
In mm/huge_memory.c (ffffffff812aedea)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812c0d03)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812c831d)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81330345)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff818fa852)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff818fc346)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81abac93)
Location: arch/x86/include/asm/pgtable.h:894
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
In arch/x86/kernel/head64.c (ffffffff8289d393)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a772b)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810395ef)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828af7a2)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81070f67)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81080217)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:set_pte_vaddr_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff81080a89)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c3be9)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810861e6)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff81ae40bb)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108fcb3)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c69e2)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c8c14)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff8125ee35)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81262d23)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8127422c)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81275398)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8127723d)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81277e19)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81279473)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8127b61c)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81291451)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8129af62)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81ae69bf)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812b4b1a)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
```
```
In mm/huge_memory.c (ffffffff812bf13a)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812d17c3)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812d902d)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81342c9c)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff8191b9b2)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff8191d346)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81ac70e3)
Location: arch/x86/include/asm/pgtable.h:894
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
</details>
</li>
</ul>

## Differences
