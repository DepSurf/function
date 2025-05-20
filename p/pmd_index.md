# Function: <code>pmd_index</code>

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
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
```
```
In arch/x86/xen/mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
```
```
In arch/x86/mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
```
```
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
```
```
In mm/pagewalk.c (0)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
```
```
In mm/hugetlb.c (ffffffff811de35c)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (0)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
```
```
In lib/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:540
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
In arch/x86/kernel/head64.c (ffffffff81f815bc)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:early_make_pgtable
```
```
In arch/x86/xen/mmu.c (ffffffff81f8ab2f)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_cleanhighmap
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81f9262c)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bbde)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81069a36)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff81069f1d)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff81fa0512)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c8da)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/gup.c (ffffffff81071c20)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In mm/gup.c (ffffffff811d57e8)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811dab9d)
Location: arch/x86/include/asm/pgtable.h:577
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
In mm/mprotect.c (ffffffff811e481e)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e57e2)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811e778c)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811e9647)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/pagewalk.c (ffffffff811ed061)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
```
```
In mm/swapfile.c (ffffffff811f20da)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811fba05)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81899988)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff812167a4)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8122d056)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81283b3e)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff8143150b)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81760642)
Location: arch/x86/include/asm/pgtable.h:577
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
In arch/x86/kernel/head64.c (ffffffff81fbd5bc)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:early_make_pgtable
```
```
In arch/x86/xen/mmu.c (ffffffff81fc5f1d)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_cleanhighmap
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81fcd8f8)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105eb58)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106d60a)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff8106dabd)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff81fdba83)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8107051a)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/gup.c (ffffffff81075790)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In mm/gup.c (ffffffff811e57e8)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811ea75f)
Location: arch/x86/include/asm/pgtable.h:577
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
In mm/mprotect.c (ffffffff811f483e)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f5a21)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff811f6f09)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff811f7451)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
```
```
In mm/rmap.c (ffffffff811f8b1c)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811fa997)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81202acd)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8120c505)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff818ce03a)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff81228d64)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8123f576)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81297730)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff8144d77b)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178d7a2)
Location: arch/x86/include/asm/pgtable.h:577
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
In arch/x86/kernel/head64.c (ffffffff8209d5b5)
Location: arch/x86/include/asm/pgtable.h:716
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff820a6127)
Location: arch/x86/include/asm/pgtable.h:716
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: arch/x86/include/asm/pgtable.h:716
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff820adf42)
Location: arch/x86/include/asm/pgtable.h:716
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e1f7)
Location: arch/x86/include/asm/pgtable.h:716
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81902884)
Location: arch/x86/include/asm/pgtable.h:716
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff8106d7eb)
Location: arch/x86/include/asm/pgtable.h:716
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:716
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff8106fb98)
Location: arch/x86/include/asm/pgtable.h:716
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In mm/gup.c (ffffffff811f09a1)
Location: arch/x86/include/asm/pgtable.h:716
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811f1ae1)
Location: arch/x86/include/asm/pgtable.h:716
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
In mm/mprotect.c (ffffffff811ff794)
Location: arch/x86/include/asm/pgtable.h:716
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8120080a)
Location: arch/x86/include/asm/pgtable.h:716
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81201e01)
Location: arch/x86/include/asm/pgtable.h:716
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81202668)
Location: arch/x86/include/asm/pgtable.h:716
Inline: True
```
```
In mm/rmap.c (ffffffff81203af3)
Location: arch/x86/include/asm/pgtable.h:716
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81205793)
Location: arch/x86/include/asm/pgtable.h:716
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8120db81)
Location: arch/x86/include/asm/pgtable.h:716
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81217e85)
Location: arch/x86/include/asm/pgtable.h:716
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff819054cf)
Location: arch/x86/include/asm/pgtable.h:716
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff81234a54)
Location: arch/x86/include/asm/pgtable.h:716
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8124aeca)
Location: arch/x86/include/asm/pgtable.h:716
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812a5069)
Location: arch/x86/include/asm/pgtable.h:716
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff817ab93a)
Location: arch/x86/include/asm/pgtable.h:716
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff818ed42c)
Location: arch/x86/include/asm/pgtable.h:716
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
In arch/x86/kernel/head64.c (ffffffff826a348e)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826ac7f1)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff826b4452)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061ece)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8198c7e9)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff81072200)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff8107502a)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pti.c (ffffffff826c5761)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5cfb)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_map_range
  - arch/x86/mm/mem_encrypt.c:sme_populate_pgd
```
```
In mm/gup.c (ffffffff81205507)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff81208837)
Location: arch/x86/include/asm/pgtable.h:725
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
In mm/mprotect.c (ffffffff81217db7)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81218fb9)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8121a953)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8121b2f2)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
```
```
In mm/rmap.c (ffffffff8121c7ef)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8121f751)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81228d7e)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81232c73)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8198f511)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff81249f9b)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
```
```
In mm/huge_memory.c (ffffffff8125442c)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8126b149)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812c847e)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff81822eb2)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff8197355a)
Location: arch/x86/include/asm/pgtable.h:725
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
In arch/x86/kernel/head64.c (ffffffff826cc470)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826d59b7)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff826ddbd9)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81064f77)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff819e90ca)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff8107525a)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff81077acd)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pti.c (ffffffff8108344f)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f0327)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff81226985)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8122987b)
Location: arch/x86/include/asm/pgtable.h:767
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
In mm/mprotect.c (ffffffff81239b6b)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
```
```
In mm/mremap.c (ffffffff8123a988)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8123c660)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8123d070)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
```
```
In mm/rmap.c (ffffffff8123e5cc)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81240ed4)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8124a07e)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81255cbb)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff819ebdcf)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff8126ef0c)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
```
```
In mm/huge_memory.c (ffffffff81278291)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff81288ac7)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff8128fb3a)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812f1801)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d1cb)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff819cf9ff)
Location: arch/x86/include/asm/pgtable.h:767
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
In arch/x86/kernel/head64.c (ffffffff810003ef)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8288ba5d)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8289401e)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106abe7)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81a24a10)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff8107b05a)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff8107e27d)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pti.c (ffffffff8108a000)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a702f)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff81239a65)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8123cd8b)
Location: arch/x86/include/asm/pgtable.h:792
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
In mm/mprotect.c (ffffffff8124d480)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124eb8b)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81250a7d)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81251533)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81252b5c)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81254be4)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8125e6be)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8126a10b)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a2703d)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812835bc)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
```
```
In mm/huge_memory.c (ffffffff8128c8d1)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8129d7ca)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff812a4a5a)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813061c1)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff8188d07b)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff8188f401)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a08ed3)
Location: arch/x86/include/asm/pgtable.h:792
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
In arch/x86/kernel/head64.c (ffffffff81000400)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a2e90)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828ab7cc)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e3a0)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a94de6)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff8107e9c7)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828bc78d)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81081b81)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pti.c (ffffffff8108ddaf)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf6e8)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff8124ac9f)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8124e9ff)
Location: arch/x86/include/asm/pgtable.h:809
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
In mm/mprotect.c (ffffffff8125fc7e)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81260ee0)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81262d5d)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812637fd)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81264edc)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81266f94)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8127b90c)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128523f)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a978dd)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff812a75b4)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812b8a9c)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812c0019)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff812c4de2)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff8132771c)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff818d7aab)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff818d9401)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a787dd)
Location: arch/x86/include/asm/pgtable.h:809
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
In arch/x86/kernel/head64.c (ffffffff810003ab)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a5f43)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828ae7da)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f950)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81acc6c6)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff8107fa57)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c2c34)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81082c41)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pti.c (ffffffff8108ea0f)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c5b6a)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff8125918f)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8125cfa0)
Location: arch/x86/include/asm/pgtable.h:809
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
In mm/mprotect.c (ffffffff8126e53e)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126f679)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8127150d)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81271d13)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
```
```
In mm/rmap.c (ffffffff8127376c)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81275894)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8128b3ec)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81294ddf)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81acf1ab)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812af03e)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b8a54)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812ca97c)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812d1f69)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff812d6792)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff8133a4fc)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff81909deb)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff8190b401)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81aafb8d)
Location: arch/x86/include/asm/pgtable.h:809
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
In arch/x86/kernel/head64.c (ffffffff8100053b)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/pgtable.h:49
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82ccc393)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_pmd_walk
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: include/linux/pgtable.h:49
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81047a4f)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076e5a)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81085cb7)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff81086c42)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (0)
Location: include/linux/pgtable.h:49
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c35f)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff81094d5f)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff810952c0)
Location: include/linux/pgtable.h:49
Inline: True
```
```
In mm/gup.c (ffffffff81289302)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8128d5c4)
Location: include/linux/pgtable.h:49
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
In mm/mprotect.c (ffffffff8129ea56)
Location: include/linux/pgtable.h:49
Inline: True
```
```
In mm/mremap.c (ffffffff8129fb90)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pmd
```
```
In mm/page_vma_mapped.c (ffffffff812a1dc2)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812a260f)
Location: include/linux/pgtable.h:49
Inline: True
```
```
In mm/rmap.c (ffffffff812a493f)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812a72a2)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
```
```
In mm/swapfile.c (ffffffff812bddc8)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812c83e7)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7b4d)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812e50d9)
Location: include/linux/pgtable.h:49
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ed606)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff813007b9)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81307d57)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81372340)
Location: include/linux/pgtable.h:49
Inline: True
```
```
In lib/ioremap.c (ffffffff815e9a7d)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bba6c5)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc426)
Location: include/linux/pgtable.h:49
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
In arch/x86/kernel/head64.c (ffffffff8100062b)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/pgtable.h:49
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82fb81d1)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_pmd_walk
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: include/linux/pgtable.h:49
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81bd4cd5)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107748a)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086d55)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff81088522)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (0)
Location: include/linux/pgtable.h:49
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c5ff)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff8109411f)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81bda32f)
Location: include/linux/pgtable.h:49
Inline: True
```
```
In kernel/events/core.c (ffffffff8123cb15)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff81292fe2)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8129fa75)
Location: include/linux/pgtable.h:49
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
In mm/mprotect.c (ffffffff812a9e16)
Location: include/linux/pgtable.h:49
Inline: True
```
```
In mm/mremap.c (ffffffff812aba2a)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812ad5ee)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812adf4f)
Location: include/linux/pgtable.h:49
Inline: True
```
```
In mm/rmap.c (ffffffff812b00cf)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b2522)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
```
```
In mm/ioremap.c (ffffffff812b8553)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_page_range
```
```
In mm/swapfile.c (ffffffff812c98ec)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812d3fb7)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81c40878)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812f049c)
Location: include/linux/pgtable.h:49
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f8d26)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8130c959)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81313a87)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81380190)
Location: include/linux/pgtable.h:49
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bcedf5)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81bd1406)
Location: include/linux/pgtable.h:49
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
In arch/x86/kernel/head64.c (ffffffff8100061e)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/pgtable.h:49
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff831c2838)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: include/linux/pgtable.h:49
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81bc711e)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077f11)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81087a07)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff810891a1)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (0)
Location: include/linux/pgtable.h:49
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d021)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff81094ac1)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81bcc457)
Location: include/linux/pgtable.h:49
Inline: True
```
```
In kernel/events/core.c (ffffffff81243e2a)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff8129a7a4)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff812a52e4)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812af295)
Location: include/linux/pgtable.h:49
Inline: True
```
```
In mm/mremap.c (ffffffff812b0e25)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812b27e5)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812b333f)
Location: include/linux/pgtable.h:49
Inline: True
```
```
In mm/rmap.c (ffffffff812b56c3)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b8c56)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff812d055a)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff812dae9c)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81c328d6)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812f67b3)
Location: include/linux/pgtable.h:49
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ff272)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff813130c9)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81319c32)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81387512)
Location: include/linux/pgtable.h:49
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bc27ad)
Location: include/linux/pgtable.h:49
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81bc3410)
Location: include/linux/pgtable.h:49
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
In arch/x86/kernel/head64.c (ffffffff81000776)
Location: include/linux/pgtable.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/pgtable.h:68
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff832a3244)
Location: include/linux/pgtable.h:68
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: include/linux/pgtable.h:68
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81c9a763)
Location: include/linux/pgtable.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81085744)
Location: include/linux/pgtable.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81096cbf)
Location: include/linux/pgtable.h:68
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8109861f)
Location: include/linux/pgtable.h:68
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (0)
Location: include/linux/pgtable.h:68
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109c8b2)
Location: include/linux/pgtable.h:68
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810a4a50)
Location: include/linux/pgtable.h:68
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81ca258c)
Location: include/linux/pgtable.h:68
Inline: True
```
```
In kernel/events/core.c (ffffffff8127e7bd)
Location: include/linux/pgtable.h:68
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff812db18a)
Location: include/linux/pgtable.h:68
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff812e6860)
Location: include/linux/pgtable.h:68
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812f0ad9)
Location: include/linux/pgtable.h:68
Inline: True
```
```
In mm/mremap.c (ffffffff812f259f)
Location: include/linux/pgtable.h:68
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812f4428)
Location: include/linux/pgtable.h:68
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812f4ee3)
Location: include/linux/pgtable.h:68
Inline: True
```
```
In mm/rmap.c (ffffffff812f7372)
Location: include/linux/pgtable.h:68
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812fb22c)
Location: include/linux/pgtable.h:68
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81315ac3)
Location: include/linux/pgtable.h:68
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81321eee)
Location: include/linux/pgtable.h:68
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81d51318)
Location: include/linux/pgtable.h:68
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_remap_range
```
```
In mm/migrate.c (ffffffff81340e1e)
Location: include/linux/pgtable.h:68
Inline: True
```
```
In mm/huge_memory.c (ffffffff81348e94)
Location: include/linux/pgtable.h:68
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8135fbc6)
Location: include/linux/pgtable.h:68
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81366a02)
Location: include/linux/pgtable.h:68
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813d4807)
Location: include/linux/pgtable.h:68
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81c92e6d)
Location: include/linux/pgtable.h:68
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81c9444e)
Location: include/linux/pgtable.h:68
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
In arch/x86/kernel/head64.c (ffffffff8100067e)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/pgtable.h:69
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff834524b3)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: include/linux/pgtable.h:69
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81e49bce)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095b0e)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810a976c)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff810ab278)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (0)
Location: include/linux/pgtable.h:69
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b0093)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810b92e4)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81e51ddb)
Location: include/linux/pgtable.h:69
Inline: True
```
```
In kernel/events/core.c (ffffffff812d342b)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/percpu.c (ffffffff8348ba01)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff8133ad4a)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8133d850)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81354af5)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81356444)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8135841a)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81358df6)
Location: include/linux/pgtable.h:69
Inline: True
```
```
In mm/rmap.c (ffffffff8135c98f)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8136272e)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813810bf)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8138f11c)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81f219a5)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_range
```
```
In mm/migrate_device.c (ffffffff813b7cfc)
Location: include/linux/pgtable.h:69
Inline: True
```
```
In mm/huge_memory.c (ffffffff813bf308)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff813da800)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff813e3d90)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8145fcb5)
Location: include/linux/pgtable.h:69
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81e42807)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81e43478)
Location: include/linux/pgtable.h:69
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
In arch/x86/kernel/head64.c (ffffffff810006b3)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/pgtable.h:69
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e6fa22)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: include/linux/pgtable.h:69
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81067f06)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab754)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810c2b78)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff810c3622)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (0)
Location: include/linux/pgtable.h:69
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ca725)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810d4c5a)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea0c61)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In kernel/events/core.c (ffffffff8133b6a8)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff8137f97c)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/percpu.c (ffffffff83ebc90d)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff813b0d1b)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff813b6870)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff813cf056)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813d0a6e)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff813d2a4c)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813d36d6)
Location: include/linux/pgtable.h:69
Inline: True
```
```
In mm/rmap.c (ffffffff813d7070)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff813de0c5)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813ff8ab)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8140dc13)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/hugetlb_vmemmap.c (ffffffff814140f5)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse-vmemmap.c (ffffffff820cb091)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate_device.c (ffffffff814399bf)
Location: include/linux/pgtable.h:69
Inline: True
```
```
In mm/memory-failure.c (ffffffff81460a21)
Location: include/linux/pgtable.h:69
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8146b7b8)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff814ef59f)
Location: include/linux/pgtable.h:69
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff8201d230)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff8201e51d)
Location: include/linux/pgtable.h:69
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
Location: include/linux/pgtable.h:69
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff836907dc)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/head64.c (ffffffff810007d0)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: include/linux/pgtable.h:69
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff810697b4)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af314)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810c6258)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff810c6e6c)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (0)
Location: include/linux/pgtable.h:69
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cdd65)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810d8164)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4d71)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In kernel/events/core.c (ffffffff8136d080)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813b0ea9)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/percpu.c (ffffffff836e4f8d)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff813e75dd)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff813eb287)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:remap_p4d_range
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8140372a)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff81405490)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8140778c)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8140812a)
Location: include/linux/pgtable.h:69
Inline: True
```
```
In mm/rmap.c (ffffffff8140bf73)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8141291f)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff814325a3)
Location: include/linux/pgtable.h:69
Inline: True
```
```
In mm/hugetlb.c (ffffffff81440fc6)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/hugetlb_vmemmap.c (ffffffff81447655)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse-vmemmap.c (ffffffff8214f321)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate_device.c (ffffffff8146e767)
Location: include/linux/pgtable.h:69
Inline: True
```
```
In mm/memory-failure.c (ffffffff814951f4)
Location: include/linux/pgtable.h:69
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814a05bb)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81524d67)
Location: include/linux/pgtable.h:69
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff8209d8c0)
Location: include/linux/pgtable.h:69
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff8209e517)
Location: include/linux/pgtable.h:69
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
Location: include/linux/pgtable.h:71
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff838c02ac)
Location: include/linux/pgtable.h:71
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/head64.c (ffffffff810007e0)
Location: include/linux/pgtable.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: include/linux/pgtable.h:71
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81070cf4)
Location: include/linux/pgtable.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5ea4)
Location: include/linux/pgtable.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810ce6a8)
Location: include/linux/pgtable.h:71
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff810cf330)
Location: include/linux/pgtable.h:71
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (0)
Location: include/linux/pgtable.h:71
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d6445)
Location: include/linux/pgtable.h:71
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810e09e4)
Location: include/linux/pgtable.h:71
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f5971)
Location: include/linux/pgtable.h:71
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In kernel/events/core.c (ffffffff813962c0)
Location: include/linux/pgtable.h:71
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813da420)
Location: include/linux/pgtable.h:71
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/percpu.c (ffffffff8391779e)
Location: include/linux/pgtable.h:71
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff8141225b)
Location: include/linux/pgtable.h:71
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff814152b0)
Location: include/linux/pgtable.h:71
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8142fcaa)
Location: include/linux/pgtable.h:71
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff814319a7)
Location: include/linux/pgtable.h:71
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81433e1a)
Location: include/linux/pgtable.h:71
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8143484a)
Location: include/linux/pgtable.h:71
Inline: True
```
```
In mm/rmap.c (ffffffff81438813)
Location: include/linux/pgtable.h:71
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8143f38f)
Location: include/linux/pgtable.h:71
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff8146b9c3)
Location: include/linux/pgtable.h:71
Inline: True
```
```
In mm/hugetlb.c (ffffffff8147b0f6)
Location: include/linux/pgtable.h:71
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff822321f1)
Location: include/linux/pgtable.h:71
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate_device.c (ffffffff8149d1d8)
Location: include/linux/pgtable.h:71
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/memory-failure.c (ffffffff814c4b5e)
Location: include/linux/pgtable.h:71
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814cfc5b)
Location: include/linux/pgtable.h:71
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff815589f8)
Location: include/linux/pgtable.h:71
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff821750c0)
Location: include/linux/pgtable.h:71
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff82176517)
Location: include/linux/pgtable.h:71
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
In arch/x86/kernel/head64.c (ffffffff810003ab)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82893f4c)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8289c7f9)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e8f0)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a6b536)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff8107ea57)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828adc0a)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81081c41)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pti.c (ffffffff8108d9cf)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b0b02)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff812517df)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812555f0)
Location: arch/x86/include/asm/pgtable.h:809
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
In mm/mprotect.c (ffffffff81266b8e)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81267cc9)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81269b5d)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8126a363)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
```
```
In mm/rmap.c (ffffffff8126bdbc)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8126dee4)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff812839cc)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128d3bf)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a6e01b)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812a761e)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b1034)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812c2f5c)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812ca549)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff812ced72)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff81332adc)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff818a91ab)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff818ab401)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a4e9dd)
Location: arch/x86/include/asm/pgtable.h:809
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
In arch/x86/kernel/head64.c (ffffffff810003ab)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828949c9)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105eed3)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81a27a83)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff8106de03)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828a5e7c)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810708c2)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff8107c452)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8c87)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff812446c1)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff81247d11)
Location: arch/x86/include/asm/pgtable.h:809
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
In mm/mprotect.c (ffffffff81258a45)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8125a009)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8125be32)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8125c817)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff8125de48)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8125ff0e)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8127f190)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a510)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff8129906c)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
```
```
In mm/huge_memory.c (ffffffff812a243a)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812b404a)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff812bb584)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff812bfa07)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff81323487)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff81863e05)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff818653b0)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a0bac6)
Location: arch/x86/include/asm/pgtable.h:809
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
In arch/x86/kernel/head64.c (ffffffff810003ab)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a6f43)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828af7bc)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106eda0)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ad7946)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff8107ea07)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c0b09)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81081bf1)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pti.c (ffffffff8108d97f)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c3a01)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff8124f57f)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81253390)
Location: arch/x86/include/asm/pgtable.h:809
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
In mm/mprotect.c (ffffffff8126492e)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81265a69)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812678fd)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81268103)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
```
```
In mm/rmap.c (ffffffff81269b5c)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8126bc84)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff812817dc)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128b1cf)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81ada42b)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812a542e)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
```
```
In mm/huge_memory.c (ffffffff812aee44)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812c0d6c)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812c8359)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff812ccb82)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff813305ac)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff818fa80b)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff818fc401)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81abadcd)
Location: arch/x86/include/asm/pgtable.h:809
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
In arch/x86/kernel/head64.c (ffffffff810003ab)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a6f17)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828af7ea)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81071020)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ae3e06)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/fault.c (ffffffff81080af7)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c3c54)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81083d11)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pti.c (ffffffff8108fd5f)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c6ba7)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff8125eeef)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81262da0)
Location: arch/x86/include/asm/pgtable.h:809
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
In mm/mprotect.c (ffffffff812742f7)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8127540b)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81277293)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81277a83)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
```
```
In mm/rmap.c (ffffffff812794cc)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8127b694)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81291517)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8129afef)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81ae68e1)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812b4b5e)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
```
```
In mm/huge_memory.c (ffffffff812bf194)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812d182c)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812d9069)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/hmm.c (ffffffff812dd912)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff81342efa)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff8191b96b)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff8191d401)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81ac721d)
Location: arch/x86/include/asm/pgtable.h:809
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
</details>
</li>
</ul>

## Differences
