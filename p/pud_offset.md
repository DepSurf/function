# Function: <code>pud_offset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pud_t *pud_offset(pgd_t *pgd, long unsigned int address);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101e558)
Location: arch/x86/include/asm/pgtable.h:649
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
```
In arch/x86/kernel/tboot.c (ffffffff81f6a326)
Location: arch/x86/include/asm/pgtable.h:649
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ba39)
Location: arch/x86/include/asm/pgtable.h:649
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81068c90)
Location: arch/x86/include/asm/pgtable.h:649
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
Direct callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:populate_extra_pmd
```
```
In arch/x86/mm/fault.c (ffffffff8106a24f)
Location: arch/x86/include/asm/pgtable.h:649
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff81f77dbb)
Location: arch/x86/include/asm/pgtable.h:649
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c85d)
Location: arch/x86/include/asm/pgtable.h:649
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pgd_range
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/gup.c (ffffffff81071887)
Location: arch/x86/include/asm/pgtable.h:649
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In mm/gup.c (ffffffff811ba7da)
Location: arch/x86/include/asm/pgtable.h:649
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811bbe63)
Location: arch/x86/include/asm/pgtable.h:649
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
Location: arch/x86/include/asm/pgtable.h:649
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811c938c)
Location: arch/x86/include/asm/pgtable.h:649
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811ca851)
Location: arch/x86/include/asm/pgtable.h:649
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811cc5ac)
Location: arch/x86/include/asm/pgtable.h:649
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/pagewalk.c (ffffffff811cfe3f)
Location: arch/x86/include/asm/pgtable.h:649
Inline: True
```
```
In mm/swapfile.c (ffffffff811d41d4)
Location: arch/x86/include/asm/pgtable.h:649
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811dd54c)
Location: arch/x86/include/asm/pgtable.h:649
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff8181f3b9)
Location: arch/x86/include/asm/pgtable.h:649
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff811f6f0d)
Location: arch/x86/include/asm/pgtable.h:649
Inline: True
Inline callers:
  - mm/huge_memory.c:page_check_address_pmd
  - mm/huge_memory.c:split_huge_page_address
```
```
In mm/userfaultfd.c (ffffffff81207743)
Location: arch/x86/include/asm/pgtable.h:649
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8125af0e)
Location: arch/x86/include/asm/pgtable.h:649
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff813eb0ff)
Location: arch/x86/include/asm/pgtable.h:649
Inline: True
```
**Symbols:**

```
ffffffff81068c90-ffffffff81068cc7: pud_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pud_t *pud_offset(pgd_t *pgd, long unsigned int address);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81f8aa84)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81f9259b)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bb24)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81069921)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:populate_extra_pmd
```
```
In arch/x86/mm/fault.c (ffffffff81069ea4)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff81fa04ee)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8106ec1c)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/gup.c (ffffffff81071b98)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107a530)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
```
```
In mm/gup.c (ffffffff811d57ad)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811dab59)
Location: arch/x86/include/asm/pgtable.h:686
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
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e5776)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811e772b)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811e960c)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/pagewalk.c (ffffffff811ecf9d)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
```
```
In mm/swapfile.c (ffffffff811f1f29)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811fb99c)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81899a86)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff8121672b)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8122d013)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81283ad9)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81431474)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff817607f3)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff81068980-ffffffff810689b1: pud_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pud_t *pud_offset(pgd_t *pgd, long unsigned int address);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81fc5e72)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81fcd867)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ea9e)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106d501)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:populate_extra_pmd
```
```
In arch/x86/mm/fault.c (ffffffff8106da44)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff81fdba5f)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8107288c)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/gup.c (ffffffff81075708)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107e320)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
```
```
In mm/gup.c (ffffffff811e57ad)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811ea71b)
Location: arch/x86/include/asm/pgtable.h:686
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
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f59b5)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff811f6ead)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff811f738d)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
```
```
In mm/rmap.c (ffffffff811f8abb)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811fa95c)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81202919)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8120c49c)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff818ce138)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff81228ceb)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8123f533)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812976cb)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff8144d6e4)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178d953)
Location: arch/x86/include/asm/pgtable.h:686
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff8106c5d0-ffffffff8106c601: pud_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pud_t *pud_offset(p4d_t *p4d, long unsigned int address);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff820a6d53)
Location: arch/x86/include/asm/pgtable.h:831
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff820adea8)
Location: arch/x86/include/asm/pgtable.h:831
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e140)
Location: arch/x86/include/asm/pgtable.h:831
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106cba6)
Location: arch/x86/include/asm/pgtable.h:831
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/fault.c (ffffffff8106d774)
Location: arch/x86/include/asm/pgtable.h:831
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff820bca3a)
Location: arch/x86/include/asm/pgtable.h:831
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81071e4a)
Location: arch/x86/include/asm/pgtable.h:831
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107dddf)
Location: arch/x86/include/asm/pgtable.h:831
Inline: True
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff811f0912)
Location: arch/x86/include/asm/pgtable.h:831
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811f1a4d)
Location: arch/x86/include/asm/pgtable.h:831
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
Location: arch/x86/include/asm/pgtable.h:831
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8120077f)
Location: arch/x86/include/asm/pgtable.h:831
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81201d65)
Location: arch/x86/include/asm/pgtable.h:831
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812023d3)
Location: arch/x86/include/asm/pgtable.h:831
Inline: True
```
```
In mm/rmap.c (ffffffff81203a91)
Location: arch/x86/include/asm/pgtable.h:831
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81205710)
Location: arch/x86/include/asm/pgtable.h:831
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8120da93)
Location: arch/x86/include/asm/pgtable.h:831
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81217e1c)
Location: arch/x86/include/asm/pgtable.h:831
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff819055cd)
Location: arch/x86/include/asm/pgtable.h:831
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff812349dc)
Location: arch/x86/include/asm/pgtable.h:831
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8124ae8e)
Location: arch/x86/include/asm/pgtable.h:831
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812a5004)
Location: arch/x86/include/asm/pgtable.h:831
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff817abaf0)
Location: arch/x86/include/asm/pgtable.h:831
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff818ed399)
Location: arch/x86/include/asm/pgtable.h:831
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8106b9e0-ffffffff8106ba11: pud_offset (STB_LOCAL)
ffffffff8107dddf-ffffffff8107de10: pud_offset (STB_LOCAL)
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826a640a)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826ad497)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff826b43a6)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061e12)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff810717ff)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff81072186)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff826c3494)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81077682)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pti.c (ffffffff826c5742)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff826c7fb1)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff81205464)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812087d0)
Location: arch/x86/include/asm/pgtable.h:838
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
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81218f40)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8121a871)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8121aff2)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
```
```
In mm/rmap.c (ffffffff8121c79f)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8121f6e0)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81228c8d)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81232bd5)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff8198f624)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff81249f4a)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
```
```
In mm/huge_memory.c (ffffffff812543c7)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8126b100)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812c8424)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff81823083)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff81973445)
Location: arch/x86/include/asm/pgtable.h:838
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826cf5a9)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826d6770)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff826ddb8d)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81064ebe)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff810744b7)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff810751d4)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff826ed6f0)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8107a0d6)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pti.c (ffffffff810833a3)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f016a)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81086469)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff812268ff)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81229808)
Location: arch/x86/include/asm/pgtable.h:880
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
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
```
```
In mm/mremap.c (ffffffff8123a915)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8123c60a)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8123ce4c)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
```
```
In mm/rmap.c (ffffffff8123e573)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81240e5c)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81249fa3)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81255c2c)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff819ebea9)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff8126eec8)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
```
```
In mm/huge_memory.c (ffffffff81278237)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812889e9)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff8128fafe)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812f1562)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d36d)
Location: arch/x86/include/asm/pgtable.h:880
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff819cf963)
Location: arch/x86/include/asm/pgtable.h:880
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828855d6)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8288c6b9)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff82893fd5)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ab2e)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8107a3a7)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8107afd4)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828a4282)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810808b6)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81082e43)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/pti.c (ffffffff81089f54)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a6e72)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8108d2f9)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff812399b5)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8123cd18)
Location: arch/x86/include/asm/pgtable.h:905
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
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124eb18)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81250a27)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812512ff)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81252b03)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81254b6c)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8125e5e3)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8126a07c)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81a27117)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff81283578)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
```
```
In mm/huge_memory.c (ffffffff8128c877)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8129d6e9)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff812a4a1e)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81305f22)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff8188f346)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a08dcf)
Location: arch/x86/include/asm/pgtable.h:905
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289c654)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a3b66)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff828ab784)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e2e7)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e0e7)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8107e959)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828bc722)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810843b6)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81086a7f)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/kaslr.c (ffffffff81a9509b)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108dd03)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf52a)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810911a7)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff8124abe5)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8124e986)
Location: arch/x86/include/asm/pgtable.h:922
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
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81260e6d)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81262d07)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812635df)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81264e83)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81266f1c)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8127b846)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff812851b2)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81a979bb)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff812a755a)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812b8a33)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812bffdd)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813274b5)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff818d9346)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a786a3)
Location: arch/x86/include/asm/pgtable.h:922
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289f644)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a6c00)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff828ae792)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f897)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107f177)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8107f9e9)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c2bc9)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810850f6)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff8108776f)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/kaslr.c (ffffffff81acc97b)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108e963)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c59a5)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81091ee7)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff812590d5)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8125cf23)
Location: arch/x86/include/asm/pgtable.h:922
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
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126f606)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812714b7)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812720a9)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81273713)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8127581c)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8128b326)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81294d52)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81acf289)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812aeffa)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b89fa)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812ca913)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812d1f2d)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8133a295)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff8190b346)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81aafa53)
Location: arch/x86/include/asm/pgtable.h:922
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82cc5b37)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82ccd04e)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff810479ee)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076d99)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81085af1)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff81086bd6)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff82ce5fca)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810898d7)
Location: include/linux/pgtable.h:97
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c682)
Location: include/linux/pgtable.h:97
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
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81094cb3)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8c85)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81097b3a)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff82cec3c4)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_prolog
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_prolog
```
```
In mm/gup.c (ffffffff812892c7)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8128d551)
Location: include/linux/pgtable.h:97
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
In mm/mprotect.c (ffffffff8129ee9b)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff8129fb23)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pmd
```
```
In mm/page_vma_mapped.c (ffffffff812a1d68)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812a296c)
Location: include/linux/pgtable.h:97
Inline: True
```
```
In mm/rmap.c (ffffffff812a48eb)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812a722f)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
```
```
In mm/swapfile.c (ffffffff812bdd1c)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812c838a)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7c46)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812e5094)
Location: include/linux/pgtable.h:97
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ed5ac)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8130074c)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81307d19)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813722e4)
Location: include/linux/pgtable.h:97
Inline: True
```
```
In lib/ioremap.c (ffffffff815e9957)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc3dc)
Location: include/linux/pgtable.h:97
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82fb142b)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82fb8e8a)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81bd4c74)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810773c9)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086bb6)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff810884b6)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff82fd3950)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff81089aa7)
Location: include/linux/pgtable.h:97
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cc38)
Location: include/linux/pgtable.h:97
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
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81094073)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd670b)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81096cfe)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/events/core.c (ffffffff8123ca9b)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff81292fa7)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8129fa02)
Location: include/linux/pgtable.h:97
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
In mm/mprotect.c (ffffffff812aa25b)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812aafaf)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812ad593)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812ae2ac)
Location: include/linux/pgtable.h:97
Inline: True
```
```
In mm/rmap.c (ffffffff812b007b)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b24af)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
```
```
In mm/ioremap.c (ffffffff812b8428)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_page_range
```
```
In mm/swapfile.c (ffffffff812c9840)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812d3f5a)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81c40971)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812f0457)
Location: include/linux/pgtable.h:97
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f8ccc)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8130c8ec)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81313a49)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81380134)
Location: include/linux/pgtable.h:97
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81bd13bc)
Location: include/linux/pgtable.h:97
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff831bb5b6)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff831c34af)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81bc70cb)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077e57)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81087868)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff8108913a)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff831de54a)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff8108aa8e)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d82a)
Location: include/linux/pgtable.h:97
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
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81094a14)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e115f)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81097597)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/events/core.c (ffffffff81243db0)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff8129a701)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff812a527d)
Location: include/linux/pgtable.h:97
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
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812af6a8)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812b03ed)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812b2763)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812b369f)
Location: include/linux/pgtable.h:97
Inline: True
```
```
In mm/rmap.c (ffffffff812b566f)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b8bbf)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff812d04ab)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff812dae3f)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81c3294f)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812f676f)
Location: include/linux/pgtable.h:97
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ff21e)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8131305c)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81319bf6)
Location: include/linux/pgtable.h:97
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813874bd)
Location: include/linux/pgtable.h:97
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81bc33bf)
Location: include/linux/pgtable.h:97
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8329bae1)
Location: include/linux/pgtable.h:116
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff832a3ee9)
Location: include/linux/pgtable.h:116
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81c9a6cb)
Location: include/linux/pgtable.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81085666)
Location: include/linux/pgtable.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81096bd0)
Location: include/linux/pgtable.h:116
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff81098593)
Location: include/linux/pgtable.h:116
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff832c1820)
Location: include/linux/pgtable.h:116
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a01b)
Location: include/linux/pgtable.h:116
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109d0b3)
Location: include/linux/pgtable.h:116
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
In arch/x86/mm/kaslr.c (ffffffff81d4eb9b)
Location: include/linux/pgtable.h:116
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810a4984)
Location: include/linux/pgtable.h:116
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c49e8)
Location: include/linux/pgtable.h:116
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810a7551)
Location: include/linux/pgtable.h:116
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/events/core.c (ffffffff8127e723)
Location: include/linux/pgtable.h:116
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff812db0c2)
Location: include/linux/pgtable.h:116
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff812e67da)
Location: include/linux/pgtable.h:116
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
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812f0ed8)
Location: include/linux/pgtable.h:116
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812f1c2f)
Location: include/linux/pgtable.h:116
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812f438f)
Location: include/linux/pgtable.h:116
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812f522c)
Location: include/linux/pgtable.h:116
Inline: True
```
```
In mm/rmap.c (ffffffff812f7301)
Location: include/linux/pgtable.h:116
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812fb171)
Location: include/linux/pgtable.h:116
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813159f6)
Location: include/linux/pgtable.h:116
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81321e75)
Location: include/linux/pgtable.h:116
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81d5135d)
Location: include/linux/pgtable.h:116
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_remap_range
```
```
In mm/migrate.c (ffffffff81340db9)
Location: include/linux/pgtable.h:116
Inline: True
```
```
In mm/huge_memory.c (ffffffff81348e23)
Location: include/linux/pgtable.h:116
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8135fb30)
Location: include/linux/pgtable.h:116
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff813669a3)
Location: include/linux/pgtable.h:116
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813d4793)
Location: include/linux/pgtable.h:116
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81c943d6)
Location: include/linux/pgtable.h:116
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8344a2d9)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83453187)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81e49b35)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095a34)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810a968d)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff810ab1ef)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff83473ecf)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810ad0c5)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b093c)
Location: include/linux/pgtable.h:117
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
In arch/x86/mm/kaslr.c (ffffffff81f1e9f2)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810b9220)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83477411)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810bc8cf)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/events/core.c (ffffffff812d3394)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/percpu.c (ffffffff8348b971)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff8133ac70)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8133d7c8)
Location: include/linux/pgtable.h:117
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
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff813549db)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813557f4)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff81358381)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813590f2)
Location: include/linux/pgtable.h:117
Inline: True
```
```
In mm/rmap.c (ffffffff8135c91c)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81362676)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81380f83)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8138f0a1)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81f21985)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_range
```
```
In mm/migrate_device.c (ffffffff813b7c99)
Location: include/linux/pgtable.h:117
Inline: True
```
```
In mm/huge_memory.c (ffffffff813bf295)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff813da76d)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff813e3d33)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8145fc3f)
Location: include/linux/pgtable.h:117
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81e43403)
Location: include/linux/pgtable.h:117
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83e648ee)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e70499)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81067e9d)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab679)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810c2a93)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff810c3592)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff83e9bb2a)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cb00c)
Location: include/linux/pgtable.h:117
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
In arch/x86/mm/kaslr.c (ffffffff820c781f)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810d4b92)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea08de)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810d7e81)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/events/core.c (ffffffff8133b60a)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff8137fdc9)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/percpu.c (ffffffff83ebc87d)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff813b2a0a)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_p4d_mask
```
```
In mm/memory.c (ffffffff813b67e8)
Location: include/linux/pgtable.h:117
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
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff813cef39)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813cff64)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff813d29b3)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813d39d6)
Location: include/linux/pgtable.h:117
Inline: True
```
```
In mm/rmap.c (ffffffff813d6ffc)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff813de00c)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813ff7ce)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8140db97)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/hugetlb_vmemmap.c (ffffffff8141409a)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse-vmemmap.c (ffffffff820cb03f)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate_device.c (ffffffff81439958)
Location: include/linux/pgtable.h:117
Inline: True
```
```
In mm/memory-failure.c (ffffffff8146098f)
Location: include/linux/pgtable.h:117
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8146b753)
Location: include/linux/pgtable.h:117
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff814ef528)
Location: include/linux/pgtable.h:117
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff8201e4a3)
Location: include/linux/pgtable.h:117
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83684f6e)
Location: include/linux/pgtable.h:125
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83691319)
Location: include/linux/pgtable.h:125
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff8106974d)
Location: include/linux/pgtable.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af239)
Location: include/linux/pgtable.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810c6173)
Location: include/linux/pgtable.h:125
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff810c6de2)
Location: include/linux/pgtable.h:125
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff836bf5ca)
Location: include/linux/pgtable.h:125
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce63c)
Location: include/linux/pgtable.h:125
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
In arch/x86/mm/kaslr.c (ffffffff8214b8af)
Location: include/linux/pgtable.h:125
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810d80a2)
Location: include/linux/pgtable.h:125
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4aa0)
Location: include/linux/pgtable.h:125
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810e3412)
Location: include/linux/pgtable.h:125
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/events/core.c (ffffffff8136cfe8)
Location: include/linux/pgtable.h:125
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813b12dd)
Location: include/linux/pgtable.h:125
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/percpu.c (ffffffff836e4efd)
Location: include/linux/pgtable.h:125
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff813e74f1)
Location: include/linux/pgtable.h:125
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_p4d_mask
```
```
In mm/memory.c (ffffffff813eb206)
Location: include/linux/pgtable.h:125
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
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8140363c)
Location: include/linux/pgtable.h:125
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff81404a27)
Location: include/linux/pgtable.h:125
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff814076f3)
Location: include/linux/pgtable.h:125
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff814083a6)
Location: include/linux/pgtable.h:125
Inline: True
```
```
In mm/rmap.c (ffffffff8140beff)
Location: include/linux/pgtable.h:125
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8141286c)
Location: include/linux/pgtable.h:125
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81432491)
Location: include/linux/pgtable.h:125
Inline: True
```
```
In mm/hugetlb.c (ffffffff81440f4a)
Location: include/linux/pgtable.h:125
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/hugetlb_vmemmap.c (ffffffff814475fa)
Location: include/linux/pgtable.h:125
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse-vmemmap.c (ffffffff8214f2cf)
Location: include/linux/pgtable.h:125
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate_device.c (ffffffff8146e700)
Location: include/linux/pgtable.h:125
Inline: True
```
```
In mm/memory-failure.c (ffffffff81495162)
Location: include/linux/pgtable.h:125
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814a0556)
Location: include/linux/pgtable.h:125
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81524cef)
Location: include/linux/pgtable.h:125
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff8209e4a3)
Location: include/linux/pgtable.h:125
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff838b410e)
Location: include/linux/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff838c0e29)
Location: include/linux/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81070c8d)
Location: include/linux/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5dc9)
Location: include/linux/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810ce5c3)
Location: include/linux/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff810cf2a2)
Location: include/linux/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff838f006a)
Location: include/linux/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d6d1c)
Location: include/linux/pgtable.h:129
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
In arch/x86/mm/kaslr.c (ffffffff8222e35f)
Location: include/linux/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810e0922)
Location: include/linux/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f56a0)
Location: include/linux/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810ebc62)
Location: include/linux/pgtable.h:129
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/events/core.c (ffffffff81396228)
Location: include/linux/pgtable.h:129
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813da85d)
Location: include/linux/pgtable.h:129
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/percpu.c (ffffffff8391770e)
Location: include/linux/pgtable.h:129
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff81412176)
Location: include/linux/pgtable.h:129
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8141522f)
Location: include/linux/pgtable.h:129
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
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8142fbbc)
Location: include/linux/pgtable.h:129
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff81430ff7)
Location: include/linux/pgtable.h:129
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff81433d81)
Location: include/linux/pgtable.h:129
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81434ac6)
Location: include/linux/pgtable.h:129
Inline: True
```
```
In mm/rmap.c (ffffffff8143879f)
Location: include/linux/pgtable.h:129
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8143f2dc)
Location: include/linux/pgtable.h:129
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff8146b8b1)
Location: include/linux/pgtable.h:129
Inline: True
```
```
In mm/hugetlb.c (ffffffff8147b07a)
Location: include/linux/pgtable.h:129
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff8223219f)
Location: include/linux/pgtable.h:129
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate_device.c (ffffffff8149d174)
Location: include/linux/pgtable.h:129
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/memory-failure.c (ffffffff814c4aca)
Location: include/linux/pgtable.h:129
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814cfbf6)
Location: include/linux/pgtable.h:129
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81558980)
Location: include/linux/pgtable.h:129
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff821764a3)
Location: include/linux/pgtable.h:129
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
In arch/arm/mm/fault.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:41
Inline: True
```
```
In arch/arm/mm/init.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:41
Inline: True
```
```
In arch/arm/mm/dma-mapping.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:41
Inline: True
```
```
In arch/arm/mm/idmap.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:41
Inline: True
```
```
In arch/arm/mm/pgd.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:41
Inline: True
```
```
In arch/arm/mm/mmu.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:41
Inline: True
```
```
In arch/arm/mm/dump.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:41
Inline: True
```
```
In arch/arm/mm/highmem.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:41
Inline: True
```
```
In mm/gup.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:41
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:41
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:41
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:41
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:41
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:41
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:41
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:41
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:41
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:41
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:41
Inline: True
```
```
In lib/ioremap.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:41
Inline: True
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
In arch/riscv/mm/fault.c (0)
Location: include/asm-generic/pgtable-nopud.h:45
Inline: True
```
```
In mm/gup.c (0)
Location: include/asm-generic/pgtable-nopud.h:45
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nopud.h:45
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable-nopud.h:45
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable-nopud.h:45
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/asm-generic/pgtable-nopud.h:45
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable-nopud.h:45
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/pgtable-nopud.h:45
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable-nopud.h:45
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable-nopud.h:45
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/pgtable-nopud.h:45
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: include/asm-generic/pgtable-nopud.h:45
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/pgtable-nopud.h:45
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/pgtable-nopud.h:45
Inline: True
```
```
In lib/ioremap.c (0)
Location: include/asm-generic/pgtable-nopud.h:45
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288d644)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82894c09)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff8289c7b1)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e837)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e177)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8107e9e9)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828adb9f)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810840f6)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff8108676f)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/kaslr.c (ffffffff81a6b7eb)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108d923)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b093d)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81090ea7)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff81251725)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81255573)
Location: arch/x86/include/asm/pgtable.h:922
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
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81267c56)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81269b07)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8126a6f9)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff8126bd63)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8126de6c)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81283906)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128d332)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81a6e0f9)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812a75da)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b0fda)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812c2ef3)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812ca50d)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81332875)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff818ab346)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a4e8a3)
Location: arch/x86/include/asm/pgtable.h:922
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288b5ba)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/kernel/tboot.c (ffffffff8289498b)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ee9e)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106d3d7)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8106dd9c)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828a5e3f)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81070c20)
Location: arch/x86/include/asm/pgtable.h:922
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
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff81a27d30)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8107c400)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8ac2)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107f993)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff81244615)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81247cbf)
Location: arch/x86/include/asm/pgtable.h:922
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
In mm/mprotect.c (ffffffff8125898b)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81259fb8)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8125bdf1)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8125c5ef)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff8125de1e)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8125fe99)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff812757c2)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8127f125)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a5a5)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff8129902a)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
```
```
In mm/huge_memory.c (ffffffff812a23f6)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812b3ffc)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff812bb54a)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8132344f)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff81865353)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a0b98e)
Location: arch/x86/include/asm/pgtable.h:922
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a0644)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7c00)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff828af774)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ece7)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e127)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8107e999)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c0a9e)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810840a6)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff8108671f)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/kaslr.c (ffffffff81ad7bfb)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108d8d3)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c383c)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81090e57)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff8124f4c5)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81253313)
Location: arch/x86/include/asm/pgtable.h:922
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
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812659f6)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812678a7)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81268499)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81269b03)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8126bc0c)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81281716)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128b142)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81ada509)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812a53ea)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
```
```
In mm/huge_memory.c (ffffffff812aedea)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812c0d03)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812c831d)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81330345)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff818fc346)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81abac93)
Location: arch/x86/include/asm/pgtable.h:922
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a0649)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7c06)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff828af7a2)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81070f67)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81080217)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff81080a89)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c3be9)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810861e6)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff8108885f)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/kaslr.c (ffffffff81ae40bb)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108fcb3)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c69e2)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81093247)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff8125ee35)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81262d23)
Location: arch/x86/include/asm/pgtable.h:922
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
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81275398)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8127723d)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81277e19)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81279473)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8127b61c)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81291451)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8129af62)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81ae69bf)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812b4b1a)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
```
```
In mm/huge_memory.c (ffffffff812bf13a)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812d17c3)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812d902d)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81342c9c)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff8191d346)
Location: arch/x86/include/asm/pgtable.h:922
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81ac70e3)
Location: arch/x86/include/asm/pgtable.h:922
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>p4d_t *p4d</code>
</li>
<li>
<b>Param removed. </b>
<code>pgd_t *pgd</code>
</li>
</ul>
</details>
</li>
</ul>
