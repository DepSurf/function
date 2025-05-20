# Function: <code>pgd_page_vaddr</code>

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
In arch/x86/xen/mmu.c (ffffffff8101e558)
Location: arch/x86/include/asm/pgtable.h:632
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
```
In arch/x86/kernel/tboot.c (ffffffff81f6a326)
Location: arch/x86/include/asm/pgtable.h:632
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ba39)
Location: arch/x86/include/asm/pgtable.h:632
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81068c91)
Location: arch/x86/include/asm/pgtable.h:632
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
```
```
In arch/x86/mm/fault.c (ffffffff8106a24f)
Location: arch/x86/include/asm/pgtable.h:632
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff81f77dbb)
Location: arch/x86/include/asm/pgtable.h:632
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c85d)
Location: arch/x86/include/asm/pgtable.h:632
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pgd_range
  - arch/x86/mm/pageattr.c:unmap_pgd_range
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:632
Inline: True
```
```
In arch/x86/mm/gup.c (ffffffff81071887)
Location: arch/x86/include/asm/pgtable.h:632
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In mm/gup.c (ffffffff811ba7da)
Location: arch/x86/include/asm/pgtable.h:632
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811bbe63)
Location: arch/x86/include/asm/pgtable.h:632
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
Location: arch/x86/include/asm/pgtable.h:632
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811c938c)
Location: arch/x86/include/asm/pgtable.h:632
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811ca851)
Location: arch/x86/include/asm/pgtable.h:632
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811cc5ac)
Location: arch/x86/include/asm/pgtable.h:632
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/pagewalk.c (ffffffff811cfe3f)
Location: arch/x86/include/asm/pgtable.h:632
Inline: True
```
```
In mm/swapfile.c (ffffffff811d41d4)
Location: arch/x86/include/asm/pgtable.h:632
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811dd54c)
Location: arch/x86/include/asm/pgtable.h:632
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff8181f3b9)
Location: arch/x86/include/asm/pgtable.h:632
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff811f6f0d)
Location: arch/x86/include/asm/pgtable.h:632
Inline: True
Inline callers:
  - mm/huge_memory.c:page_check_address_pmd
  - mm/huge_memory.c:split_huge_page_address
```
```
In mm/userfaultfd.c (ffffffff81207743)
Location: arch/x86/include/asm/pgtable.h:632
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8125af0e)
Location: arch/x86/include/asm/pgtable.h:632
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff813eb0ff)
Location: arch/x86/include/asm/pgtable.h:632
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
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81f9259b)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bb24)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81069921)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
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
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff81fa04ee)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8106ec1c)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
```
```
In arch/x86/mm/gup.c (ffffffff81071b98)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107405a)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kaslr.c (ffffffff81896e60)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107a530)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
```
```
In mm/gup.c (ffffffff811d57ad)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811dab59)
Location: arch/x86/include/asm/pgtable.h:669
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
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e5776)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811e772b)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811e960c)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/pagewalk.c (ffffffff811ecf9d)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
```
```
In mm/swapfile.c (ffffffff811f1f29)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811fb99c)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81899a86)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff8121672b)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8122d013)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81283ad9)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81431474)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff817607fa)
Location: arch/x86/include/asm/pgtable.h:669
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
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81fcd867)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ea9e)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106d501)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
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
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff81fdba5f)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8107288c)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
```
```
In arch/x86/mm/gup.c (ffffffff81075708)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81077bd2)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kaslr.c (ffffffff818cb549)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107e320)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
```
```
In mm/gup.c (ffffffff811e57ad)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811ea71b)
Location: arch/x86/include/asm/pgtable.h:669
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
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f59b5)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff811f6ead)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff811f738d)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
```
```
In mm/rmap.c (ffffffff811f8abb)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811fa95c)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81202919)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8120c49c)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff818ce138)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff81228ceb)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8123f533)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812976cb)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff8144d6e4)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178d95a)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
</details>
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pgd_page_vaddr(pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82cc5ae8)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82ccd195)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff82cd073e)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tboot.c (ffffffff810479bd)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076d11)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81085a92)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff81086baf)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff82ce5fac)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810898b5)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff8108ab00)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:sync_current_stack_to_mm
  - arch/x86/mm/tlb.c:sync_current_stack_to_mm
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cd72)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81bc51d7)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81094b86)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8c20)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81097a5a)
Location: arch/x86/include/asm/pgtable.h:945
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
Location: arch/x86/include/asm/pgtable.h:945
Inline: False
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_epilog
```
```
In mm/gup.c (ffffffff8128b29f)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff8128d4f6)
Location: arch/x86/include/asm/pgtable.h:945
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
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff8129fac8)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pmd
```
```
In mm/page_vma_mapped.c (ffffffff812a1d3d)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812a2c1b)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/rmap.c (ffffffff812a48c0)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812a7201)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/swapfile.c (ffffffff812bdc58)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812c835f)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7d53)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/migrate.c (ffffffff812e2053)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - mm/migrate.c:p4d_alloc
```
```
In mm/huge_memory.c (ffffffff812ed585)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff81300725)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81307cdd)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813722bd)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
```
```
In lib/ioremap.c (ffffffff815e9d77)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc3b7)
Location: arch/x86/include/asm/pgtable.h:945
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff8109db0f-ffffffff8109db30: pgd_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pgd_page_vaddr(pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82fb13dc)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82fb8fd1)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff82fbc57e)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tboot.c (ffffffff81bd4c43)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077341)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086b56)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/fault.c (ffffffff8108848f)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff82fd3932)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff81089a85)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cb24)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81c3e0aa)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81093f46)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd66a6)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81096c1e)
Location: arch/x86/include/asm/pgtable.h:944
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
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff81294f5f)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff8129dc12)
Location: arch/x86/include/asm/pgtable.h:944
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
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812aaf58)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812ad568)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812ae53b)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/rmap.c (ffffffff812b0050)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b2481)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/ioremap.c (ffffffff812b82c6)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_page_range
```
```
In mm/swapfile.c (ffffffff812c9778)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812d3f2f)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81c40a7e)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/migrate.c (ffffffff812ecfc3)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/migrate.c:p4d_alloc
```
```
In mm/huge_memory.c (ffffffff812f8ca5)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8130c8c5)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81313a0d)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8138010d)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81bd1397)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81bd8c9d-ffffffff81bd8cbe: pgd_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pgd_page_vaddr(pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff831bb567)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810285b5)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81bc600a)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81bc6ffb)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:p4d_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077b83)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:p4d_offset
```
```
In arch/x86/mm/init_64.c (ffffffff81bcac97)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/fault.c (ffffffff81088063)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff81bcb68e)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:p4d_offset
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a755)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c8f3)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff81bcc2da)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:p4d_offset
```
```
In arch/x86/mm/pti.c (ffffffff81094813)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e10fe)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff831e2ec3)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/events/core.c (ffffffff8123e713)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - kernel/events/core.c:p4d_offset
```
```
In mm/gup.c (ffffffff81296a43)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
```
```
In mm/memory.c (ffffffff8129c743)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
```
```
In mm/mprotect.c (ffffffff812ae7d3)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/mprotect.c:p4d_offset
```
```
In mm/mremap.c (ffffffff812b0303)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812b2283)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:p4d_offset
```
```
In mm/pagewalk.c (ffffffff812b30d3)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/pagewalk.c:p4d_offset
```
```
In mm/rmap.c (ffffffff812b4683)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/rmap.c:p4d_offset
```
```
In mm/vmalloc.c (ffffffff812b8604)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
```
```
In mm/swapfile.c (ffffffff812d03e9)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff812d6373)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81c329e0)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/migrate.c (ffffffff812f2cf3)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/migrate.c:p4d_offset
```
```
In mm/huge_memory.c (ffffffff812f9a13)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/huge_memory.c:p4d_offset
```
```
In mm/memory-failure.c (ffffffff81312893)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/memory-failure.c:p4d_offset
```
```
In mm/userfaultfd.c (ffffffff81319b63)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - mm/userfaultfd.c:p4d_offset
```
```
In fs/userfaultfd.c (ffffffff81386a73)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - fs/userfaultfd.c:p4d_offset
```
```
In arch/x86/power/hibernate.c (ffffffff81bc3183)
Location: arch/x86/include/asm/pgtable.h:944
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:p4d_offset
```
**Symbols:**

```
ffffffff81bcac97-ffffffff81bcacb8: pgd_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pgd_page_vaddr(pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8329ba92)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102ccc5)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81c98fdb)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81c9a5e0)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:p4d_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81085383)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:p4d_offset
```
```
In arch/x86/mm/init_64.c (ffffffff81ca017f)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/fault.c (ffffffff810973e3)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff81ca0dc6)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:p4d_offset
```
```
In arch/x86/mm/pgtable.c (ffffffff81099cd5)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109c153)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff81ca231b)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:p4d_offset
```
```
In arch/x86/mm/pti.c (ffffffff810a4763)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c4989)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff832c6866)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/events/core.c (ffffffff812791f3)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
Inline callers:
  - kernel/events/core.c:p4d_offset
```
```
In mm/gup.c (ffffffff812d7293)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
```
```
In mm/memory.c (ffffffff812dd3ac)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
```
```
In mm/mprotect.c (ffffffff812eff73)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
Inline callers:
  - mm/mprotect.c:p4d_offset
```
```
In mm/mremap.c (ffffffff812f1b33)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812f3e73)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:p4d_offset
```
```
In mm/pagewalk.c (ffffffff812f4c53)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
Inline callers:
  - mm/pagewalk.c:p4d_offset
```
```
In mm/rmap.c (ffffffff812f6263)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
Inline callers:
  - mm/rmap.c:p4d_offset
```
```
In mm/vmalloc.c (ffffffff812fad7d)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
```
```
In mm/swapfile.c (ffffffff81315934)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8131c183)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff8132be73)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
```
```
In mm/migrate.c (ffffffff8133d1e3)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
Inline callers:
  - mm/migrate.c:p4d_offset
```
```
In mm/huge_memory.c (ffffffff813438d3)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
Inline callers:
  - mm/huge_memory.c:p4d_offset
```
```
In mm/memory-failure.c (ffffffff8135e303)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
Inline callers:
  - mm/memory-failure.c:p4d_offset
```
```
In mm/userfaultfd.c (ffffffff81366903)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
Inline callers:
  - mm/userfaultfd.c:p4d_offset
```
```
In fs/userfaultfd.c (ffffffff813d3d03)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
Inline callers:
  - fs/userfaultfd.c:p4d_offset
```
```
In arch/x86/power/hibernate.c (ffffffff81c94183)
Location: arch/x86/include/asm/pgtable.h:915
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:p4d_offset
```
**Symbols:**

```
ffffffff81ca017f-ffffffff81ca01a0: pgd_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pgd_page_vaddr(pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8344a28a)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81031c05)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81e48595)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81e49a2e)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:p4d_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810956b3)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:p4d_offset
```
```
In arch/x86/mm/init_64.c (ffffffff810a80c0)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/fault.c (ffffffff810a9ed3)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff81e50366)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:p4d_offset
```
```
In arch/x86/mm/pgtable.c (ffffffff810acce5)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810af883)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff81e519d4)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:p4d_offset
```
```
In arch/x86/mm/pti.c (ffffffff810b8ff3)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff834773b6)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff83479536)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/events/core.c (ffffffff812cc0a3)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
Inline callers:
  - kernel/events/core.c:p4d_offset
```
```
In mm/percpu.c (ffffffff81e6c568)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
Inline callers:
  - mm/percpu.c:p4d_offset
```
```
In mm/gup.c (ffffffff81336e23)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
```
```
In mm/memory.c (ffffffff8133d0d3)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
```
```
In mm/mprotect.c (ffffffff81353483)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
```
```
In mm/mremap.c (ffffffff813556e3)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81357d23)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:p4d_offset
```
```
In mm/pagewalk.c (ffffffff81358af3)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
Inline callers:
  - mm/pagewalk.c:p4d_offset
```
```
In mm/rmap.c (ffffffff8135a293)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
Inline callers:
  - mm/rmap.c:p4d_offset
```
```
In mm/vmalloc.c (ffffffff81362273)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
```
```
In mm/swapfile.c (ffffffff81380eca)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81388773)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff8139bc53)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
```
```
In mm/migrate_device.c (ffffffff813b6223)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
Inline callers:
  - mm/migrate_device.c:p4d_offset
```
```
In mm/huge_memory.c (ffffffff813b8553)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
Inline callers:
  - mm/huge_memory.c:p4d_offset
```
```
In mm/memory-failure.c (ffffffff813d88b3)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
Inline callers:
  - mm/memory-failure.c:p4d_offset
```
```
In mm/userfaultfd.c (ffffffff813e3c83)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
Inline callers:
  - mm/userfaultfd.c:p4d_offset
```
```
In fs/userfaultfd.c (ffffffff8145d2b3)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
Inline callers:
  - fs/userfaultfd.c:p4d_offset
```
```
In arch/x86/power/hibernate.c (ffffffff81e43193)
Location: arch/x86/include/asm/pgtable.h:913
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:p4d_offset
```
**Symbols:**

```
ffffffff810a80c0-ffffffff810a80e6: pgd_page_vaddr (STB_LOCAL)
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83e648ab)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810394b8)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff83e75662)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tboot.c (ffffffff81067b24)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:p4d_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab284)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:p4d_offset
```
```
In arch/x86/mm/init_64.c (ffffffff83e9b18d)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/fault.c (ffffffff810c34b4)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff810c4f84)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:p4d_offset
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:931
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810c9e54)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff810d48a4)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:p4d_offset
```
```
In arch/x86/mm/pti.c (ffffffff810d4924)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea08a6)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff83ea37be)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/events/core.c (ffffffff81333aa4)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - kernel/events/core.c:p4d_offset
```
```
In mm/percpu.c (ffffffff81399164)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/percpu.c:p4d_offset
```
```
In mm/gup.c (ffffffff813b299f)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff813b4ca9)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
```
```
In mm/mprotect.c (ffffffff813cd764)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
```
```
In mm/mremap.c (ffffffff813cfe34)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff813d24d4)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:p4d_offset
```
```
In mm/pagewalk.c (ffffffff813d3394)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/pagewalk.c:p4d_offset
```
```
In mm/rmap.c (ffffffff813d4d34)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/rmap.c:p4d_offset
```
```
In mm/vmalloc.c (ffffffff813ddc14)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
```
```
In mm/swapfile.c (ffffffff813ff716)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff814069e4)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
```
```
In mm/hugetlb_vmemmap.c (ffffffff814138c4)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse-vmemmap.c (ffffffff8141bc04)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
```
```
In mm/migrate_device.c (ffffffff81437a22)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/migrate_device.c:p4d_alloc
```
```
In mm/memory-failure.c (ffffffff8145e444)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/memory-failure.c:p4d_offset
```
```
In mm/userfaultfd.c (ffffffff8146b684)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/userfaultfd.c:p4d_offset
```
```
In fs/userfaultfd.c (ffffffff814ecb94)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - fs/userfaultfd.c:p4d_offset
```
```
In arch/x86/power/hibernate.c (ffffffff8201e1e4)
Location: arch/x86/include/asm/pgtable.h:931
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83684f2b)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810393f8)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff83697132)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tboot.c (ffffffff810693d4)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:p4d_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810aee44)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:p4d_offset
```
```
In arch/x86/mm/init_64.c (ffffffff836bec2d)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/fault.c (ffffffff810c6d04)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff810c8714)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:p4d_offset
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:932
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cd4a4)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff810d7db4)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:p4d_offset
```
```
In arch/x86/mm/pti.c (ffffffff810d7e34)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4a12)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff836c7a59)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/events/core.c (ffffffff81364814)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - kernel/events/core.c:p4d_offset
```
```
In mm/percpu.c (ffffffff813cc174)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/percpu.c:p4d_offset
```
```
In mm/gup.c (ffffffff813e748d)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff813e97d4)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
```
```
In mm/mprotect.c (ffffffff814020c4)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
```
```
In mm/mremap.c (ffffffff814048f4)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81407064)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:p4d_offset
```
```
In mm/pagewalk.c (ffffffff81407db4)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/pagewalk.c:p4d_offset
```
```
In mm/rmap.c (ffffffff81409b74)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/rmap.c:p4d_offset
```
```
In mm/vmalloc.c (ffffffff81412474)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
```
```
In mm/swapfile.c (ffffffff8143278b)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8143a034)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
```
```
In mm/hugetlb_vmemmap.c (ffffffff81446e14)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse-vmemmap.c (ffffffff8144f204)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
```
```
In mm/migrate_device.c (ffffffff8146d6e2)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/migrate_device.c:p4d_alloc
```
```
In mm/memory-failure.c (ffffffff81494124)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/memory-failure.c:p4d_offset
```
```
In mm/userfaultfd.c (ffffffff814a0484)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/userfaultfd.c:p4d_offset
```
```
In fs/userfaultfd.c (ffffffff81523834)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - fs/userfaultfd.c:p4d_offset
```
```
In arch/x86/power/hibernate.c (ffffffff8209e1e4)
Location: arch/x86/include/asm/pgtable.h:932
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff838b40cb)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103f8a8)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105e944)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81070844)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:p4d_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b59c4)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:p4d_offset
```
```
In arch/x86/mm/init_64.c (ffffffff838ef6cd)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/fault.c (ffffffff810cf1c4)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff810d0be4)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:p4d_offset
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d5b84)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff810e0634)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:p4d_offset
```
```
In arch/x86/mm/pti.c (ffffffff810e06b4)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f5612)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff838f8659)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/events/core.c (ffffffff8138d744)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
Inline callers:
  - kernel/events/core.c:p4d_offset
```
```
In mm/percpu.c (ffffffff813f6ae4)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
Inline callers:
  - mm/percpu.c:p4d_offset
```
```
In mm/gup.c (ffffffff8140cfa4)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
```
```
In mm/memory.c (ffffffff814147f4)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
```
```
In mm/mprotect.c (ffffffff8142e6f4)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
```
```
In mm/mremap.c (ffffffff81430ec4)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81433714)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:p4d_offset
```
```
In mm/pagewalk.c (ffffffff81434494)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
Inline callers:
  - mm/pagewalk.c:p4d_offset
```
```
In mm/rmap.c (ffffffff814363a4)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
Inline callers:
  - mm/rmap.c:p4d_offset
```
```
In mm/vmalloc.c (ffffffff8143ecd4)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
```
```
In mm/swapfile.c (ffffffff8146bbab)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81473e14)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81488dc4)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
```
```
In mm/migrate_device.c (ffffffff8149ca42)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
Inline callers:
  - mm/migrate_device.c:p4d_alloc
```
```
In mm/memory-failure.c (ffffffff814c3934)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
Inline callers:
  - mm/memory-failure.c:p4d_offset
```
```
In mm/userfaultfd.c (ffffffff814cfb24)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
Inline callers:
  - mm/userfaultfd.c:p4d_offset
```
```
In fs/userfaultfd.c (ffffffff81557e54)
Location: arch/x86/include/asm/pgtable.h:1154
Inline: True
Inline callers:
  - fs/userfaultfd.c:p4d_offset
```
```
In arch/x86/power/hibernate.c (ffffffff821761e4)
Location: arch/x86/include/asm/pgtable.h:1154
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
