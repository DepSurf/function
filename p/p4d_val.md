# Function: <code>p4d_val</code>

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
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
p4dval_t p4d_val(p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810064dd)
Location: arch/x86/include/asm/paravirt.h:548
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102646f)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/xen/trace.c (ffffffff8102d159)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d
```
```
In arch/x86/kernel/tboot.c (ffffffff810479ee)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076d99)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81085ac4)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:free_pud_table
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
Direct callers:
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff81086bd6)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff82ce5fca)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810898d7)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c682)
Location: arch/x86/include/asm/paravirt.h:548
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
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81094cb3)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81097b3a)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff8109daee)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:p4d_page_vaddr
```
```
In mm/gup.c (ffffffff812892c7)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8128d551)
Location: arch/x86/include/asm/paravirt.h:548
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
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff8129fb23)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pmd
```
```
In mm/page_vma_mapped.c (ffffffff812a1d76)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812a296c)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812a33f5)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/rmap.c (ffffffff812a48eb)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812a722f)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
```
```
In mm/swapfile.c (ffffffff812bdd1c)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812c838a)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7c46)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812e5094)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ed5ac)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8130074c)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81307d19)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/ptdump.c (ffffffff8130cb75)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_p4d_entry
```
```
In fs/userfaultfd.c (ffffffff813722e4)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
```
```
In lib/ioremap.c (ffffffff815e9957)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc3dc)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810064dd-ffffffff810064ea: p4d_val (STB_LOCAL)
ffffffff81085ee4-ffffffff81085ef1: p4d_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
p4dval_t p4d_val(p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81bd1ae6)
Location: arch/x86/include/asm/paravirt.h:470
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81026b78)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/xen/trace.c (ffffffff8102e0f9)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d
```
```
In arch/x86/kernel/tboot.c (ffffffff81bd4c74)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810773c9)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086b89)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:free_pud_table
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
Direct callers:
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff810884b6)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff82fd3950)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff81089aa7)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cc38)
Location: arch/x86/include/asm/paravirt.h:470
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
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81094073)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81096cfe)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In kernel/events/core.c (ffffffff8123ca9b)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff81292fa7)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8129fa02)
Location: arch/x86/include/asm/paravirt.h:470
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
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812aafaf)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812ad5a2)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812ae2ac)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812aed05)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/rmap.c (ffffffff812b007b)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b24af)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
```
```
In mm/ioremap.c (ffffffff812b8428)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_page_range
```
```
In mm/swapfile.c (ffffffff812c9840)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812d3f5a)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81c40971)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812f0457)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f8ccc)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8130c8ec)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81313a49)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/ptdump.c (ffffffff81318ab5)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_p4d_entry
```
```
In fs/userfaultfd.c (ffffffff81380134)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81bd13bc)
Location: arch/x86/include/asm/paravirt.h:470
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81bd1ae6-ffffffff81bd1af3: p4d_val (STB_LOCAL)
ffffffff81bd8877-ffffffff81bd8884: p4d_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
p4dval_t p4d_val(p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81bc3b87)
Location: arch/x86/include/asm/paravirt.h:500
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff831c34af)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/xen/trace.c (ffffffff8102eb69)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d
```
```
In arch/x86/kernel/tboot.c (ffffffff81bc70cb)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077e57)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8108783b)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
Direct callers:
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff8108913a)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff831de54a)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff8108aa8e)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d82a)
Location: arch/x86/include/asm/paravirt.h:500
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
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81094a14)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81097597)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In kernel/events/core.c (ffffffff81243db0)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff8129a701)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff812a527d)
Location: arch/x86/include/asm/paravirt.h:500
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
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812b03ed)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812b2772)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812b369f)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812b4235)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/rmap.c (ffffffff812b566f)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b8bbf)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff812d04ab)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff812dae3f)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81c3294f)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812f676f)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ff21e)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8131305c)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81319bf6)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/ptdump.c (ffffffff8131eca5)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_p4d_entry
```
```
In fs/userfaultfd.c (ffffffff813874bd)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81bc33d3)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81bc3b87-ffffffff81bc3b94: p4d_val (STB_LOCAL)
ffffffff81bca71e-ffffffff81bca72b: p4d_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
p4dval_t p4d_val(p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81c94bd8)
Location: arch/x86/include/asm/paravirt.h:500
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff832a3ee9)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/xen/trace.c (ffffffff81033559)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d
```
```
In arch/x86/kernel/tboot.c (ffffffff81c9a6cb)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81085666)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81096ba3)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
Direct callers:
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff81098593)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff832c1820)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a01b)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109d0b3)
Location: arch/x86/include/asm/paravirt.h:500
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
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810a4984)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810a7551)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In kernel/events/core.c (ffffffff8127e723)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff812db0c2)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff812e67da)
Location: arch/x86/include/asm/paravirt.h:500
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
```
```
In mm/mprotect.c (ffffffff812f0ed8)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812f1c2f)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812f438f)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812f522c)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812f5e15)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/rmap.c (ffffffff812f7301)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812fb171)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813159f6)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81321e75)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81d5135d)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_remap_range
```
```
In mm/migrate.c (ffffffff81340db9)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
```
```
In mm/huge_memory.c (ffffffff81348e23)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8135fb30)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff813669a3)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/ptdump.c (ffffffff8136c085)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_p4d_entry
```
```
In fs/userfaultfd.c (ffffffff813d4793)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81c943d6)
Location: arch/x86/include/asm/paravirt.h:500
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81c94bd8-ffffffff81c94be5: p4d_val (STB_LOCAL)
ffffffff81c9fbc4-ffffffff81c9fbd1: p4d_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
p4dval_t p4d_val(p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81e43e89)
Location: arch/x86/include/asm/paravirt.h:506
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83453187)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/xen/trace.c (ffffffff810374e8)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d
```
```
In arch/x86/kernel/tboot.c (ffffffff81e49b35)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095a34)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810a9661)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
Direct callers:
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff810ab1ef)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff83473ecf)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810ad0c5)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b093c)
Location: arch/x86/include/asm/paravirt.h:506
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
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810b9220)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810bc8cf)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In kernel/events/core.c (ffffffff812d3394)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/percpu.c (ffffffff8348b971)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff8133ac70)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8133d7c8)
Location: arch/x86/include/asm/paravirt.h:506
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
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813557f4)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff81358381)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813590f2)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81359d75)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/rmap.c (ffffffff8135c91c)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81362676)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81380f83)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8138f0a1)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff8139bf52)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_range
```
```
In mm/migrate_device.c (ffffffff813b7c99)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
```
```
In mm/huge_memory.c (ffffffff813bf295)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff813da76d)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff813e3d33)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/ptdump.c (ffffffff813ea2d5)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_p4d_entry
```
```
In fs/userfaultfd.c (ffffffff8145fc3f)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81e43403)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81e43e89-ffffffff81e43e9b: p4d_val (STB_LOCAL)
ffffffff810a7df0-ffffffff810a7e02: p4d_val (STB_LOCAL)
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83e648cc)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e70499)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/xen/trace.c (ffffffff8103f4e5)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d
```
```
In arch/x86/kernel/tboot.c (ffffffff81067e9d)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab679)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810c2a67)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff810c3592)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff83e9bb2a)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cb00c)
Location: arch/x86/include/asm/paravirt.h:506
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
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810d4b92)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810d7e81)
Location: arch/x86/include/asm/paravirt.h:506
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
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff8137fdc9)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/percpu.c (ffffffff83ebc87d)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff813b2a0a)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_p4d_mask
```
```
In mm/memory.c (ffffffff813b67e8)
Location: arch/x86/include/asm/paravirt.h:506
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
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813cff64)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff813d29b3)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813d39d6)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff813d4775)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/rmap.c (ffffffff813d6ffc)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff813de00c)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813ff7ce)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8140db97)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/hugetlb_vmemmap.c (ffffffff8141409a)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse-vmemmap.c (ffffffff820cb03f)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate_device.c (ffffffff81439958)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
```
```
In mm/memory-failure.c (ffffffff8146098f)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8146b753)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/ptdump.c (ffffffff814723a5)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_p4d_entry
```
```
In fs/userfaultfd.c (ffffffff814ef528)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff8201e4a3)
Location: arch/x86/include/asm/paravirt.h:506
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83684f4c)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83691319)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/xen/trace.c (ffffffff8103f625)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d
```
```
In arch/x86/kernel/tboot.c (ffffffff8106974d)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af239)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810c6147)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff810c6de2)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff836bf5ca)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce63c)
Location: arch/x86/include/asm/paravirt.h:501
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
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810d80a2)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810e3412)
Location: arch/x86/include/asm/paravirt.h:501
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
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813b12dd)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/percpu.c (ffffffff836e4efd)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff813e74f1)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_p4d_mask
```
```
In mm/memory.c (ffffffff813eb206)
Location: arch/x86/include/asm/paravirt.h:501
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
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff81404a27)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff814076f3)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff814083a6)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81409145)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/rmap.c (ffffffff8140beff)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8141286c)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81432491)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
```
```
In mm/hugetlb.c (ffffffff81440f4a)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/hugetlb_vmemmap.c (ffffffff814475fa)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse-vmemmap.c (ffffffff8214f2cf)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate_device.c (ffffffff8146e700)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
```
```
In mm/memory-failure.c (ffffffff81495162)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814a0556)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/ptdump.c (ffffffff814a6b05)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_p4d_entry
```
```
In fs/userfaultfd.c (ffffffff81524cef)
Location: arch/x86/include/asm/paravirt.h:501
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff8209e4a3)
Location: arch/x86/include/asm/paravirt.h:501
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff838b40ec)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff838c0e29)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/xen/trace.c (ffffffff81045af5)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_set_p4d
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_set_p4d
```
```
In arch/x86/kernel/tboot.c (ffffffff81070c8d)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5dc9)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810ce597)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff810cf2a2)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff838f006a)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d6d1c)
Location: arch/x86/include/asm/paravirt.h:499
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
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810e0922)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810ebc62)
Location: arch/x86/include/asm/paravirt.h:499
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
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813da85d)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/percpu.c (ffffffff8391770e)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff81412176)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8141522f)
Location: arch/x86/include/asm/paravirt.h:499
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
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff81430ff7)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff81433d81)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81434ac6)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81435935)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/rmap.c (ffffffff8143879f)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8143f2dc)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff8146b8b1)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
```
```
In mm/hugetlb.c (ffffffff8147b07a)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff8223219f)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate_device.c (ffffffff8149d174)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/memory-failure.c (ffffffff814c4aca)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814cfbf6)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/ptdump.c (ffffffff814d7b05)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_p4d_entry
```
```
In fs/userfaultfd.c (ffffffff81558980)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff821764a3)
Location: arch/x86/include/asm/paravirt.h:499
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
