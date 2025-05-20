# Function: <code>pgd_offset_pgd</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82cc5a6e)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82ccd17c)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free
```
```
In arch/x86/kernel/ldt.c (ffffffff81038525)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/kernel/tboot.c (ffffffff81047942)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff810859f8)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/fault.c (ffffffff81087d59)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/tlb.c (ffffffff8108ab2d)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:sync_current_stack_to_mm
  - arch/x86/mm/tlb.c:sync_current_stack_to_mm
  - arch/x86/mm/tlb.c:sync_current_stack_to_mm
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f5b2)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_mm
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
```
In arch/x86/mm/kaslr.c (ffffffff81bc51a3)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff82ce80ae)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81097a22)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff82cec1ac)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_epilog
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_prolog
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_prolog
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_prolog
```
```
In mm/gup.c (ffffffff8128b211)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff8128d455)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff8129f032)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8129fa45)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pmd
```
```
In mm/page_vma_mapped.c (ffffffff812a1cb4)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812a2ed4)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff812a4875)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812a71b5)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:map_kernel_range_noflush
  - mm/vmalloc.c:unmap_kernel_range_noflush
```
```
In mm/swapfile.c (ffffffff812bdf82)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff812c8315)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7e17)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
```
In mm/migrate.c (ffffffff812e504a)
Location: include/linux/pgtable.h:104
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ed535)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff813006e4)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81307c85)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81372270)
Location: include/linux/pgtable.h:104
Inline: True
```
```
In lib/ioremap.c (ffffffff815e9cce)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82fb1362)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82fb8fb8)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free
```
```
In arch/x86/kernel/ldt.c (ffffffff81038ed5)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/kernel/tboot.c (ffffffff81bd4bc6)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff81086abc)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f372)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_mm
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
```
In arch/x86/mm/kaslr.c (ffffffff81c3e076)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff82fd5acd)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81096be6)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In kernel/events/core.c (ffffffff8123ca21)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff81294ed1)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff8129f935)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff812aa3f2)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812aaed5)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812ad4df)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812ae7f4)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff812b0005)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b2435)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:map_kernel_range_noflush
  - mm/vmalloc.c:unmap_kernel_range_noflush
```
```
In mm/ioremap.c (ffffffff812b820c)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_page_range
```
```
In mm/swapfile.c (ffffffff812c9aa2)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff812d3ee5)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81c40b42)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
```
In mm/migrate.c (ffffffff812f040a)
Location: include/linux/pgtable.h:104
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f8c55)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8130c884)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff813139b5)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813800c0)
Location: include/linux/pgtable.h:104
Inline: True
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff831bb4ed)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff831c3684)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/ldt.c (ffffffff8103a9c5)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/kernel/tboot.c (ffffffff81bc7050)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff810877a1)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ff02)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_mm
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
```
In arch/x86/mm/kaslr.c (ffffffff81c303bf)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff831e0567)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8109750f)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In kernel/events/core.c (ffffffff81243d64)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff8129a612)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff812a51a5)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff812af832)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812b0335)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812b26cc)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812b3bb4)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff812b5625)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b8b05)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff812d030a)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff812dadf5)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81c32aa5)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
```
In mm/migrate.c (ffffffff812f671c)
Location: include/linux/pgtable.h:104
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ff1c5)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff81312fe9)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81319b95)
Location: include/linux/pgtable.h:104
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81387470)
Location: include/linux/pgtable.h:104
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
pgd_t *pgd_offset_pgd(pgd_t *pgd, long unsigned int address);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8329ba06)
Location: include/linux/pgtable.h:123
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff832a40f4)
Location: include/linux/pgtable.h:123
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/ldt.c (ffffffff810403d0)
Location: include/linux/pgtable.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/kernel/tboot.c (ffffffff81c9a659)
Location: include/linux/pgtable.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff81096b15)
Location: include/linux/pgtable.h:123
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:set_pte_vaddr
Direct callers:
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109f9e3)
Location: include/linux/pgtable.h:123
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:_lookup_address_cpa
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_mm
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
```
In arch/x86/mm/kaslr.c (ffffffff81d4eb69)
Location: include/linux/pgtable.h:123
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810a47b2)
Location: include/linux/pgtable.h:123
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
Direct callers:
  - arch/x86/mm/pti.c:pti_clone_p4d
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810a7495)
Location: include/linux/pgtable.h:123
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In kernel/events/core.c (ffffffff8127e6c7)
Location: include/linux/pgtable.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff812dafa6)
Location: include/linux/pgtable.h:123
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff812e6751)
Location: include/linux/pgtable.h:123
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff812f1066)
Location: include/linux/pgtable.h:123
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812f1b7d)
Location: include/linux/pgtable.h:123
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812f42e5)
Location: include/linux/pgtable.h:123
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812f576c)
Location: include/linux/pgtable.h:123
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff812f72bd)
Location: include/linux/pgtable.h:123
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812fb0c0)
Location: include/linux/pgtable.h:123
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81315820)
Location: include/linux/pgtable.h:123
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81321e32)
Location: include/linux/pgtable.h:123
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff8132bee5)
Location: include/linux/pgtable.h:123
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_range
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
```
In mm/migrate.c (ffffffff81340d63)
Location: include/linux/pgtable.h:123
Inline: True
```
```
In mm/huge_memory.c (ffffffff81348ddf)
Location: include/linux/pgtable.h:123
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8135fabe)
Location: include/linux/pgtable.h:123
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81366952)
Location: include/linux/pgtable.h:123
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813d474d)
Location: include/linux/pgtable.h:123
Inline: True
```
**Symbols:**

```
ffffffff81c9fce3-ffffffff81c9fd25: pgd_offset_pgd (STB_LOCAL)
ffffffff810a4710-ffffffff810a473e: pgd_offset_pgd (STB_LOCAL)
ffffffff81ca2353-ffffffff81ca2374: pgd_offset_pgd.cold (STB_LOCAL)
ffffffff8132bd80-ffffffff8132bdae: pgd_offset_pgd (STB_LOCAL)
ffffffff81cc060f-ffffffff81cc0630: pgd_offset_pgd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
pgd_t *pgd_offset_pgd(pgd_t *pgd, long unsigned int address);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8344a202)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83453399)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/ldt.c (ffffffff810480cf)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/kernel/tboot.c (ffffffff81e49ac4)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff810a95c6)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:set_pte_vaddr
Direct callers:
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b3813)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:_lookup_address_cpa
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
```
In arch/x86/mm/kaslr.c (ffffffff81f1e9c0)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810b9050)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
Direct callers:
  - arch/x86/mm/pti.c:pti_clone_p4d
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810bc815)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In kernel/events/core.c (ffffffff812d332c)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/percpu.c (ffffffff8348b857)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff8133ab84)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff8133d719)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff813547d3)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8135573d)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff813582e2)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8135962d)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff8135c8cd)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff813625c0)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81380de7)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8138f052)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff8139c20e)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_range
Direct callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
```
In mm/migrate_device.c (ffffffff813b7c3f)
Location: include/linux/pgtable.h:124
Inline: True
```
```
In mm/huge_memory.c (ffffffff813bf240)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff813da64d)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff813e3ce2)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8145fbed)
Location: include/linux/pgtable.h:124
Inline: True
```
**Symbols:**

```
ffffffff810a7f40-ffffffff810a7f7a: pgd_offset_pgd (STB_LOCAL)
ffffffff81e4f3f8-ffffffff81e4f419: pgd_offset_pgd.cold (STB_LOCAL)
ffffffff810b8f90-ffffffff810b8fca: pgd_offset_pgd (STB_LOCAL)
ffffffff81e51a3c-ffffffff81e51a5d: pgd_offset_pgd.cold (STB_LOCAL)
ffffffff8139bb40-ffffffff8139bb7a: pgd_offset_pgd (STB_LOCAL)
ffffffff81e72a1d-ffffffff81e72a3e: pgd_offset_pgd.cold (STB_LOCAL)
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83e64841)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e70911)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/ldt.c (ffffffff81052e0f)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/kernel/tboot.c (ffffffff81067e4c)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff810c29c6)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce413)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:_lookup_address_cpa
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
```
In arch/x86/mm/kaslr.c (ffffffff820c77fe)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff83e9f49f)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810d7dc5)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In kernel/events/core.c (ffffffff8133b59c)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/percpu.c (ffffffff83ebc774)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff813b2900)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff813b6739)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff813ced02)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813cfead)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff813d2912)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813d3f0d)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff813d6fad)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff813ddf50)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:__vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813ff633)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8140db42)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/hugetlb_vmemmap.c (ffffffff8141407a)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse-vmemmap.c (ffffffff820cb01f)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
```
In mm/migrate_device.c (ffffffff8143990c)
Location: include/linux/pgtable.h:124
Inline: True
```
```
In mm/memory-failure.c (ffffffff8146093d)
Location: include/linux/pgtable.h:124
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8146b702)
Location: include/linux/pgtable.h:124
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff814ef4cd)
Location: include/linux/pgtable.h:124
Inline: True
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83684ec1)
Location: include/linux/pgtable.h:132
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83691791)
Location: include/linux/pgtable.h:132
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/ldt.c (ffffffff81053df2)
Location: include/linux/pgtable.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/kernel/tboot.c (ffffffff810696fc)
Location: include/linux/pgtable.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff810c60a6)
Location: include/linux/pgtable.h:132
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d19d3)
Location: include/linux/pgtable.h:132
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:_lookup_address_cpa
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
```
In arch/x86/mm/kaslr.c (ffffffff8214b88e)
Location: include/linux/pgtable.h:132
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff836c361f)
Location: include/linux/pgtable.h:132
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810e3357)
Location: include/linux/pgtable.h:132
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In kernel/events/core.c (ffffffff8136cf77)
Location: include/linux/pgtable.h:132
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/percpu.c (ffffffff836e4df4)
Location: include/linux/pgtable.h:132
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff813e73d7)
Location: include/linux/pgtable.h:132
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff813eb15f)
Location: include/linux/pgtable.h:132
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81403963)
Location: include/linux/pgtable.h:132
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81404970)
Location: include/linux/pgtable.h:132
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff81407652)
Location: include/linux/pgtable.h:132
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff814088e0)
Location: include/linux/pgtable.h:132
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff8140beb0)
Location: include/linux/pgtable.h:132
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff814127b0)
Location: include/linux/pgtable.h:132
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:__vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff814326a4)
Location: include/linux/pgtable.h:132
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81440ef5)
Location: include/linux/pgtable.h:132
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/hugetlb_vmemmap.c (ffffffff814475da)
Location: include/linux/pgtable.h:132
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse-vmemmap.c (ffffffff8214f2af)
Location: include/linux/pgtable.h:132
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
```
In mm/migrate_device.c (ffffffff8146e6b9)
Location: include/linux/pgtable.h:132
Inline: True
```
```
In mm/memory-failure.c (ffffffff81495110)
Location: include/linux/pgtable.h:132
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814a0505)
Location: include/linux/pgtable.h:132
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81524c94)
Location: include/linux/pgtable.h:132
Inline: True
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff838b4061)
Location: include/linux/pgtable.h:136
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff838c12a1)
Location: include/linux/pgtable.h:136
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/kernel/ldt.c (ffffffff8105b012)
Location: include/linux/pgtable.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/kernel/tboot.c (ffffffff81070c3c)
Location: include/linux/pgtable.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff810ce4f6)
Location: include/linux/pgtable.h:136
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810da103)
Location: include/linux/pgtable.h:136
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:_lookup_address_cpa
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
```
In arch/x86/mm/kaslr.c (ffffffff8222e33e)
Location: include/linux/pgtable.h:136
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff838f42bf)
Location: include/linux/pgtable.h:136
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810ebba7)
Location: include/linux/pgtable.h:136
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In kernel/events/core.c (ffffffff813961b7)
Location: include/linux/pgtable.h:136
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/percpu.c (ffffffff83917670)
Location: include/linux/pgtable.h:136
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff81412074)
Location: include/linux/pgtable.h:136
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff81415180)
Location: include/linux/pgtable.h:136
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff8142fee3)
Location: include/linux/pgtable.h:136
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81430f40)
Location: include/linux/pgtable.h:136
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff81433ce0)
Location: include/linux/pgtable.h:136
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81435000)
Location: include/linux/pgtable.h:136
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81438750)
Location: include/linux/pgtable.h:136
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8143f220)
Location: include/linux/pgtable.h:136
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:__vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff8146bac4)
Location: include/linux/pgtable.h:136
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8147b025)
Location: include/linux/pgtable.h:136
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff8223217f)
Location: include/linux/pgtable.h:136
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
```
In mm/migrate_device.c (ffffffff8149d130)
Location: include/linux/pgtable.h:136
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/memory-failure.c (ffffffff814c4a72)
Location: include/linux/pgtable.h:136
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814cfba5)
Location: include/linux/pgtable.h:136
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81558925)
Location: include/linux/pgtable.h:136
Inline: True
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
