# Function: <code>p4d_page_vaddr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
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
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff820adea8)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e140)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106cba6)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
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
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff820bca3a)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81071e4a)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81076485)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kaslr.c (ffffffff81902b44)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff820bfeac)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/gup.c (ffffffff811f0912)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811f1a4d)
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
In mm/mprotect.c (ffffffff811ff692)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8120077f)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81201d65)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812023d3)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
```
```
In mm/rmap.c (ffffffff81203a91)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81205710)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8120da93)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81217e1c)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff819055cd)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff812349dc)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8124ae8e)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812a5004)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff817abafa)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff818ed399)
Location: arch/x86/include/asm/pgtable.h:818
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826a640a)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826ad497)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff826b43a6)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061e12)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff810717ff)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
```
```
In arch/x86/mm/fault.c (ffffffff81072186)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff826c3494)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81077682)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:826
Inline: False
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107c627)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kaslr.c (ffffffff8198ca78)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff81080255)
Location: arch/x86/include/asm/pgtable.h:826
Inline: False
Direct callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81082cc0)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff81205464)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812087d0)
Location: arch/x86/include/asm/pgtable.h:826
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
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81218f40)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8121a871)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8121aff2)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
```
```
In mm/rmap.c (ffffffff8121c79f)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8121f6e0)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81228c8d)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81232bd5)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff8198f624)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff81249f4a)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
```
```
In mm/huge_memory.c (ffffffff812543c7)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8126b100)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812c8424)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff8182309e)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff81973445)
Location: arch/x86/include/asm/pgtable.h:826
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81070260-ffffffff81070291: p4d_page_vaddr (STB_LOCAL)
ffffffff81080255-ffffffff81080286: p4d_page_vaddr (STB_LOCAL)
ffffffff81082cc0-ffffffff81082cf1: p4d_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826cf5a9)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826d6770)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff826ddb8d)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81064ebe)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff810744b7)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
```
```
In arch/x86/mm/fault.c (ffffffff810751d4)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff826ed6f0)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8107a0d6)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:868
Inline: False
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107f38d)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kaslr.c (ffffffff819e9381)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff810833a3)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f016a)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81086469)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff812268ff)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81229808)
Location: arch/x86/include/asm/pgtable.h:868
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
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
```
```
In mm/mremap.c (ffffffff8123a915)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8123c60a)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8123ce4c)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
```
```
In mm/rmap.c (ffffffff8123e573)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81240e5c)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81249fa3)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81255c2c)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff819ebea9)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff8126eec8)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
```
```
In mm/huge_memory.c (ffffffff81278237)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812889e9)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff8128fafe)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812f1562)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d38b)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff819cf963)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff810732b0-ffffffff810732d1: p4d_page_vaddr (STB_LOCAL)
ffffffff81086370-ffffffff81086391: p4d_page_vaddr (STB_LOCAL)
ffffffff81228e40-ffffffff81228e61: p4d_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828855d6)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8288c6b9)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff82893fd5)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ab2e)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8107a3a7)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
```
```
In arch/x86/mm/fault.c (ffffffff8107afd4)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828a4282)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810808b6)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81082e43)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81085f57)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kaslr.c (ffffffff81a24cc7)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff81089f54)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a6e72)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8108d2f9)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff812399b5)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8123cd18)
Location: arch/x86/include/asm/pgtable.h:893
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
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124eb18)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81250a27)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812512ff)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81252b03)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81254b6c)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8125e5e3)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8126a07c)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81a27117)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff81283578)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
```
```
In mm/huge_memory.c (ffffffff8128c877)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8129d6e9)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff812a4a1e)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81305f22)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff8188f364)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a08dcf)
Location: arch/x86/include/asm/pgtable.h:893
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81079350-ffffffff81079371: p4d_page_vaddr (STB_LOCAL)
ffffffff8108d200-ffffffff8108d221: p4d_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289c654)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a3b66)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff828ab784)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e2e7)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e0e7)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
```
```
In arch/x86/mm/fault.c (ffffffff8107e959)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828bc722)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810843b6)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81086a7f)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810899c5)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/kaslr.c (ffffffff81a9509b)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108dd03)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf52a)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810911a7)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff8124abe5)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8124e986)
Location: arch/x86/include/asm/pgtable.h:910
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
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81260e6d)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81262d07)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812635df)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81264e83)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81266f1c)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8127b846)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff812851b2)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81a979bb)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff812a755a)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812b8a33)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812bffdd)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813274b5)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff818d9364)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a786a3)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8107cf60-ffffffff8107cf81: p4d_page_vaddr (STB_LOCAL)
ffffffff810910b0-ffffffff810910d1: p4d_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289f644)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a6c00)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff828ae792)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f897)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107f177)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
```
```
In arch/x86/mm/fault.c (ffffffff8107f9e9)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c2bc9)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810850f6)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff8108776f)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108a635)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/kaslr.c (ffffffff81acc97b)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108e963)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c59a5)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81091ee7)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff812590d5)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8125cf23)
Location: arch/x86/include/asm/pgtable.h:910
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
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126f606)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812714b7)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812720a9)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81273713)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8127581c)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8128b326)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81294d52)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81acf289)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812aeffa)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b89fa)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812ca913)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812d1f2d)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8133a295)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff8190b364)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81aafa53)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8107dff0-ffffffff8107e011: p4d_page_vaddr (STB_LOCAL)
ffffffff81091df0-ffffffff81091e11: p4d_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82cc5b3b)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102646f)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/kernel/tboot.c (ffffffff810479ee)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076d99)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81085af1)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
```
```
In arch/x86/mm/fault.c (ffffffff81086bd6)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff82ce5fca)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810898d7)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c682)
Location: arch/x86/include/asm/pgtable.h:910
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
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81094cb3)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8c85)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81097b3a)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff8109daee)
Location: arch/x86/include/asm/pgtable.h:910
Inline: False
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_epilog
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_prolog
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_prolog
```
```
In mm/gup.c (ffffffff812892c7)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8128d551)
Location: arch/x86/include/asm/pgtable.h:910
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
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff8129fb23)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pmd
```
```
In mm/page_vma_mapped.c (ffffffff812a1d76)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812a296c)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
```
```
In mm/rmap.c (ffffffff812a48eb)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812a722f)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
```
```
In mm/swapfile.c (ffffffff812bdd1c)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812c838a)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7c46)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812e5094)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ed5ac)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8130074c)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81307d19)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813722e4)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
```
```
In lib/ioremap.c (ffffffff815e9957)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc3dc)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81025920-ffffffff81025941: p4d_page_vaddr (STB_LOCAL)
ffffffff81084580-ffffffff810845a1: p4d_page_vaddr (STB_LOCAL)
ffffffff81097840-ffffffff81097861: p4d_page_vaddr (STB_LOCAL)
ffffffff8109daee-ffffffff8109db0f: p4d_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82fb142f)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81026b78)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/kernel/tboot.c (ffffffff81bd4c74)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810773c9)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086bb6)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
Direct callers:
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/fault.c (ffffffff810884b6)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff82fd3950)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff81089aa7)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cc38)
Location: arch/x86/include/asm/pgtable.h:909
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
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81094073)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd670b)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81096cfe)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/events/core.c (ffffffff8123ca9b)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff81292fa7)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8129fa02)
Location: arch/x86/include/asm/pgtable.h:909
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
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812aafaf)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812ad5a2)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812ae2ac)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
```
```
In mm/rmap.c (ffffffff812b007b)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b24af)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
```
```
In mm/ioremap.c (ffffffff812b8428)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_page_range
```
```
In mm/swapfile.c (ffffffff812c9840)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812d3f5a)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81c40971)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812f0457)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f8ccc)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8130c8ec)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81313a49)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81380134)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81bd13bc)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81026040-ffffffff81026061: p4d_page_vaddr (STB_LOCAL)
ffffffff81085a60-ffffffff81085a81: p4d_page_vaddr (STB_LOCAL)
ffffffff81096a40-ffffffff81096a61: p4d_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff831bb5ba)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff831c34af)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81bc70cb)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077e57)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81087868)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
Direct callers:
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/fault.c (ffffffff8108913a)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff831de54a)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff8108aa8e)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d82a)
Location: arch/x86/include/asm/pgtable.h:909
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
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81094a14)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e115f)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81097597)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/events/core.c (ffffffff81243db0)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff8129a701)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff812a527d)
Location: arch/x86/include/asm/pgtable.h:909
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
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812b03ed)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812b2772)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812b369f)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
```
```
In mm/rmap.c (ffffffff812b566f)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b8bbf)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff812d04ab)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff812dae3f)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81c3294f)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812f676f)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ff21e)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8131305c)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81319bf6)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813874bd)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81bc33d3)
Location: arch/x86/include/asm/pgtable.h:909
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810867d0-ffffffff810867f1: p4d_page_vaddr (STB_LOCAL)
ffffffff81097360-ffffffff81097381: p4d_page_vaddr (STB_LOCAL)
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
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288d644)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82894c09)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff8289c7b1)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e837)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e177)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
```
```
In arch/x86/mm/fault.c (ffffffff8107e9e9)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828adb9f)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810840f6)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff8108676f)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810895f5)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/kaslr.c (ffffffff81a6b7eb)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108d923)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b093d)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81090ea7)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff81251725)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81255573)
Location: arch/x86/include/asm/pgtable.h:910
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
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81267c56)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81269b07)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8126a6f9)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff8126bd63)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8126de6c)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81283906)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128d332)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81a6e0f9)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812a75da)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b0fda)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812c2ef3)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812ca50d)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81332875)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff818ab364)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a4e8a3)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8107cff0-ffffffff8107d011: p4d_page_vaddr (STB_LOCAL)
ffffffff81090db0-ffffffff81090dd1: p4d_page_vaddr (STB_LOCAL)
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
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/kernel/tboot.c (ffffffff8289498b)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ee9e)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106d3d7)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8106dd9c)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff828a5e3f)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81070c20)
Location: arch/x86/include/asm/pgtable.h:910
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
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810783a1)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kaslr.c (ffffffff81a27d30)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8107c400)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8ac2)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107f993)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff81244615)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81247cbf)
Location: arch/x86/include/asm/pgtable.h:910
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
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81259fb8)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8125bdf1)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8125c5ef)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff8125de1e)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8125fe99)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff812757c2)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8127f125)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a5a5)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff8129902a)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
```
```
In mm/huge_memory.c (ffffffff812a23f6)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812b3ffc)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff812bb54a)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8132344f)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff81865353)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a0b98e)
Location: arch/x86/include/asm/pgtable.h:910
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
long unsigned int p4d_page_vaddr(p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a0644)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7c00)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff828af774)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ece7)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e127)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
```
```
In arch/x86/mm/fault.c (ffffffff8107e999)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c0a9e)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810840a6)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff8108671f)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810895a5)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/kaslr.c (ffffffff81ad7bfb)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108d8d3)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c383c)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81090e57)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff8124f4c5)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81253313)
Location: arch/x86/include/asm/pgtable.h:910
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
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812659f6)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812678a7)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81268499)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81269b03)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8126bc0c)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81281716)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128b142)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81ada509)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812a53ea)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
```
```
In mm/huge_memory.c (ffffffff812aedea)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812c0d03)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812c831d)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81330345)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff818fc364)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81abac93)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8107cfa0-ffffffff8107cfc1: p4d_page_vaddr (STB_LOCAL)
ffffffff81090d60-ffffffff81090d81: p4d_page_vaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int p4d_page_vaddr(p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a0649)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7c06)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff828af7a2)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81070f67)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81080217)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
```
```
In arch/x86/mm/fault.c (ffffffff81080a89)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c3be9)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810861e6)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff8108885f)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108b845)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/kaslr.c (ffffffff81ae40bb)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108fcb3)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c69e2)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81093247)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff8125ee35)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81262d23)
Location: arch/x86/include/asm/pgtable.h:910
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
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81275398)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8127723d)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81277e19)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81279473)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8127b61c)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81291451)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8129af62)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81ae69bf)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812b4b1a)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
```
```
In mm/huge_memory.c (ffffffff812bf13a)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812d17c3)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812d902d)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81342c9c)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff8191d364)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81ac70e3)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8107f090-ffffffff8107f0b1: p4d_page_vaddr (STB_LOCAL)
ffffffff81093150-ffffffff81093171: p4d_page_vaddr (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
