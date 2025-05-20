# Function: <code>p4d_index</code>

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
In arch/x86/kernel/head64.c (0)
Location: arch/x86/include/asm/pgtable.h:842
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/pgtable.h:842
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:842
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: arch/x86/include/asm/pgtable.h:842
Inline: True
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
In arch/x86/kernel/head64.c (0)
Location: arch/x86/include/asm/pgtable.h:854
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:854
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: arch/x86/include/asm/pgtable.h:854
Inline: True
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
In arch/x86/kernel/head64.c (0)
Location: arch/x86/include/asm/pgtable.h:896
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:896
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: arch/x86/include/asm/pgtable.h:896
Inline: True
```
```
In arch/x86/power/hibernate_64.c (0)
Location: arch/x86/include/asm/pgtable.h:896
Inline: True
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
In arch/x86/kernel/head64.c (0)
Location: arch/x86/include/asm/pgtable.h:921
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:921
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: arch/x86/include/asm/pgtable.h:921
Inline: True
```
```
In arch/x86/power/hibernate_64.c (0)
Location: arch/x86/include/asm/pgtable.h:921
Inline: True
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
In arch/x86/kernel/head64.c (0)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
```
```
In arch/x86/power/hibernate_64.c (0)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
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
In arch/x86/kernel/head64.c (0)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
```
```
In arch/x86/power/hibernate_64.c (0)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
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
In arch/x86/kernel/head64.c (ffffffff82cc23cd)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82cc5ade)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff82cd0723)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tboot.c (ffffffff810479a2)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076cfa)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81085a78)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff81086b98)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff82ce5f96)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff8108aae9)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:sync_current_stack_to_mm
  - arch/x86/mm/tlb.c:sync_current_stack_to_mm
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cd5b)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81bc51be)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81094b6d)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8c20)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81097aaa)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff82cec3ad)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_prolog
```
```
In mm/gup.c (ffffffff8128b288)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff8128d4df)
Location: arch/x86/include/asm/pgtable.h:932
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
In mm/mprotect.c (ffffffff8129edd8)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff8129fab0)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pmd
```
```
In mm/page_vma_mapped.c (ffffffff812a1d29)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812a2c1b)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/rmap.c (ffffffff812a48a9)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812a71ea)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/swapfile.c (ffffffff812bdc3d)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812c8348)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7d3b)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/migrate.c (ffffffff812e203c)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/migrate.c:p4d_alloc
```
```
In mm/huge_memory.c (ffffffff812ed56e)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8130070e)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81307cc2)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813722a6)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
```
```
In lib/ioremap.c (ffffffff815e9d5b)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bba788)
Location: arch/x86/include/asm/pgtable.h:932
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc3a0)
Location: arch/x86/include/asm/pgtable.h:932
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
In arch/x86/kernel/head64.c (ffffffff82fae40c)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82fb13d2)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff82fbc563)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tboot.c (ffffffff81bd4c27)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107732a)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086b3b)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff81088478)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff82fd391c)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cb0d)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81c3e091)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81093f2d)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd66a6)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81096c6e)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In kernel/events/core.c (ffffffff8123ca5d)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff81294f48)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff8129dbf4)
Location: arch/x86/include/asm/pgtable.h:931
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
In mm/mprotect.c (ffffffff812aa198)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812aaf40)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812ad554)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812ae53b)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/rmap.c (ffffffff812b0039)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b246a)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/ioremap.c (ffffffff812b82a4)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_page_range
```
```
In mm/swapfile.c (ffffffff812c975d)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812d3f18)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81c40a66)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/migrate.c (ffffffff812ecfac)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/migrate.c:p4d_alloc
```
```
In mm/huge_memory.c (ffffffff812f8c8e)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8130c8ae)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff813139f2)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813800f6)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bceeb8)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81bd1380)
Location: arch/x86/include/asm/pgtable.h:931
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
In arch/x86/kernel/head64.c (ffffffff831b840c)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff831bb55d)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81bc5ff0)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81bc6fe0)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:p4d_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077b68)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:p4d_offset
```
```
In arch/x86/mm/init_64.c (ffffffff81c2f580)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff81088048)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff81bcb674)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:p4d_offset
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c8d8)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff81bcc2bf)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:p4d_offset
```
```
In arch/x86/mm/pti.c (ffffffff810947f8)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e10fe)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81097560)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In kernel/events/core.c (ffffffff8123e6f8)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - kernel/events/core.c:p4d_offset
```
```
In mm/gup.c (ffffffff81296a28)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
```
```
In mm/memory.c (ffffffff8129c728)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
```
```
In mm/mprotect.c (ffffffff812ae7b8)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/mprotect.c:p4d_offset
```
```
In mm/mremap.c (ffffffff812b02e8)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812b2268)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:p4d_offset
```
```
In mm/pagewalk.c (ffffffff812b30b8)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/pagewalk.c:p4d_offset
```
```
In mm/rmap.c (ffffffff812b4668)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/rmap.c:p4d_offset
```
```
In mm/vmalloc.c (ffffffff812b85e9)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
```
```
In mm/swapfile.c (ffffffff812d03d2)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff812d6358)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81c329c8)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/migrate.c (ffffffff812f2cd8)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/migrate.c:p4d_offset
```
```
In mm/huge_memory.c (ffffffff812f99f8)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/huge_memory.c:p4d_offset
```
```
In mm/memory-failure.c (ffffffff81312878)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/memory-failure.c:p4d_offset
```
```
In mm/userfaultfd.c (ffffffff81319b48)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - mm/userfaultfd.c:p4d_offset
```
```
In fs/userfaultfd.c (ffffffff81386a58)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - fs/userfaultfd.c:p4d_offset
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bc2872)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81bc3168)
Location: arch/x86/include/asm/pgtable.h:931
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:p4d_offset
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
In arch/x86/kernel/head64.c (ffffffff8329844d)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8329ba88)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81c98fc1)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81c9a5c5)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:p4d_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81085368)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:p4d_offset
```
```
In arch/x86/mm/init_64.c (ffffffff81d4dc7e)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff810973c8)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff81ca0dac)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:p4d_offset
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109c138)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff81ca2300)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:p4d_offset
```
```
In arch/x86/mm/pti.c (ffffffff810a4748)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c4989)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810a751a)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In kernel/events/core.c (ffffffff812791d8)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
Inline callers:
  - kernel/events/core.c:p4d_offset
```
```
In mm/gup.c (ffffffff812d7278)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
```
```
In mm/memory.c (ffffffff812dd390)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
```
```
In mm/mprotect.c (ffffffff812eff58)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
Inline callers:
  - mm/mprotect.c:p4d_offset
```
```
In mm/mremap.c (ffffffff812f1b18)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812f3e58)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:p4d_offset
```
```
In mm/pagewalk.c (ffffffff812f4c38)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
Inline callers:
  - mm/pagewalk.c:p4d_offset
```
```
In mm/rmap.c (ffffffff812f6248)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
Inline callers:
  - mm/rmap.c:p4d_offset
```
```
In mm/vmalloc.c (ffffffff812fad62)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
```
```
In mm/swapfile.c (ffffffff8131591d)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8131c168)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff8132be58)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
```
```
In mm/migrate.c (ffffffff8133d1c8)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
Inline callers:
  - mm/migrate.c:p4d_offset
```
```
In mm/huge_memory.c (ffffffff813438b8)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
Inline callers:
  - mm/huge_memory.c:p4d_offset
```
```
In mm/memory-failure.c (ffffffff8135e2e8)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
Inline callers:
  - mm/memory-failure.c:p4d_offset
```
```
In mm/userfaultfd.c (ffffffff813668e8)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
Inline callers:
  - mm/userfaultfd.c:p4d_offset
```
```
In fs/userfaultfd.c (ffffffff813d3ce8)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
Inline callers:
  - fs/userfaultfd.c:p4d_offset
```
```
In arch/x86/power/hibernate_64.c (ffffffff81c92f32)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81c94168)
Location: arch/x86/include/asm/pgtable.h:902
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:p4d_offset
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
In arch/x86/kernel/head64.c (ffffffff83446444)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8344a281)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81e4857b)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81e49a13)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:p4d_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095698)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:p4d_offset
```
```
In arch/x86/mm/init_64.c (ffffffff81f1d9f1)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff810a9eb8)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff81e5034c)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:p4d_offset
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810af868)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff81e519b9)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:p4d_offset
```
```
In arch/x86/mm/pti.c (ffffffff810b8fd8)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff834773b6)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810bc898)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In kernel/events/core.c (ffffffff812cc088)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - kernel/events/core.c:p4d_offset
```
```
In mm/percpu.c (ffffffff81e6c54d)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/percpu.c:p4d_offset
```
```
In mm/gup.c (ffffffff81336e08)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/memory.c (ffffffff8133d0b8)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/mprotect.c (ffffffff81353468)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/mremap.c (ffffffff813556c8)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81357d08)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:p4d_offset
```
```
In mm/pagewalk.c (ffffffff81358ad8)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/pagewalk.c:p4d_offset
```
```
In mm/rmap.c (ffffffff8135a278)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/rmap.c:p4d_offset
```
```
In mm/vmalloc.c (ffffffff81362258)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
```
```
In mm/swapfile.c (ffffffff81380eb3)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81388758)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff8139bc38)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/migrate_device.c (ffffffff813b6208)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/migrate_device.c:p4d_offset
```
```
In mm/huge_memory.c (ffffffff813b8538)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/huge_memory.c:p4d_offset
```
```
In mm/memory-failure.c (ffffffff813d8898)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/memory-failure.c:p4d_offset
```
```
In mm/userfaultfd.c (ffffffff813e3c68)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/userfaultfd.c:p4d_offset
```
```
In fs/userfaultfd.c (ffffffff8145d298)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - fs/userfaultfd.c:p4d_offset
```
```
In arch/x86/power/hibernate_64.c (ffffffff81e428c6)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81e43178)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:p4d_offset
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
In arch/x86/kernel/head64.c (ffffffff83e5f437)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83e64893)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff83e75645)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tboot.c (ffffffff81067b08)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:p4d_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab268)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:p4d_offset
```
```
In arch/x86/mm/init_64.c (ffffffff83e9b171)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff810c3498)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff810c4f68)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:p4d_offset
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810c9e38)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff810d4888)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:p4d_offset
```
```
In arch/x86/mm/pti.c (ffffffff810d4908)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea08a6)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810d7e4a)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In kernel/events/core.c (ffffffff81333a88)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
  - kernel/events/core.c:p4d_offset
```
```
In mm/percpu.c (ffffffff81399148)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
  - mm/percpu.c:p4d_offset
```
```
In mm/gup.c (ffffffff813b2984)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff813b4c90)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
```
```
In mm/mprotect.c (ffffffff813cd748)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
```
```
In mm/mremap.c (ffffffff813cfe18)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff813d24b8)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:p4d_offset
```
```
In mm/pagewalk.c (ffffffff813d3378)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
  - mm/pagewalk.c:p4d_offset
```
```
In mm/rmap.c (ffffffff813d4d18)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
  - mm/rmap.c:p4d_offset
```
```
In mm/vmalloc.c (ffffffff813ddbf8)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
```
```
In mm/swapfile.c (ffffffff813ff6fe)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff814069c8)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
```
```
In mm/hugetlb_vmemmap.c (ffffffff814138a8)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse-vmemmap.c (ffffffff8141bbe8)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
```
```
In mm/migrate_device.c (ffffffff81437a0a)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
  - mm/migrate_device.c:p4d_alloc
```
```
In mm/memory-failure.c (ffffffff8145e428)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
  - mm/memory-failure.c:p4d_offset
```
```
In mm/userfaultfd.c (ffffffff8146b668)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
  - mm/userfaultfd.c:p4d_offset
```
```
In fs/userfaultfd.c (ffffffff814ecb78)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
  - fs/userfaultfd.c:p4d_offset
```
```
In arch/x86/power/hibernate_64.c (ffffffff8201d2f9)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff8201e1c8)
Location: arch/x86/include/asm/pgtable.h:918
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83684f13)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
```
```
In arch/x86/kernel/head64.c (ffffffff83694667)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/kernel/espfix_64.c (ffffffff83697115)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/tboot.c (ffffffff810693b8)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:p4d_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810aee28)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:p4d_offset
```
```
In arch/x86/mm/init_64.c (ffffffff836bec11)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff810c6ce8)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff810c86f8)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:p4d_offset
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cd488)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff810d7d98)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:p4d_offset
```
```
In arch/x86/mm/pti.c (ffffffff810d7e18)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4a12)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810e33db)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In kernel/events/core.c (ffffffff813647f8)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
Inline callers:
  - kernel/events/core.c:p4d_offset
```
```
In mm/percpu.c (ffffffff813cc158)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
Inline callers:
  - mm/percpu.c:p4d_offset
```
```
In mm/gup.c (ffffffff813e7472)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff813e97b8)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
```
```
In mm/mprotect.c (ffffffff814020a8)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
```
```
In mm/mremap.c (ffffffff814048d8)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81407048)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:p4d_offset
```
```
In mm/pagewalk.c (ffffffff81407d98)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
Inline callers:
  - mm/pagewalk.c:p4d_offset
```
```
In mm/rmap.c (ffffffff81409b58)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
Inline callers:
  - mm/rmap.c:p4d_offset
```
```
In mm/vmalloc.c (ffffffff81412458)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
```
```
In mm/swapfile.c (ffffffff81432773)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8143a018)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
```
```
In mm/hugetlb_vmemmap.c (ffffffff81446df8)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse-vmemmap.c (ffffffff8144f1e8)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
```
```
In mm/migrate_device.c (ffffffff8146d6ca)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
Inline callers:
  - mm/migrate_device.c:p4d_alloc
```
```
In mm/memory-failure.c (ffffffff81494108)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
Inline callers:
  - mm/memory-failure.c:p4d_offset
```
```
In mm/userfaultfd.c (ffffffff814a0468)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
Inline callers:
  - mm/userfaultfd.c:p4d_offset
```
```
In fs/userfaultfd.c (ffffffff81523818)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
Inline callers:
  - fs/userfaultfd.c:p4d_offset
```
```
In arch/x86/power/hibernate_64.c (ffffffff8209d989)
Location: arch/x86/include/asm/pgtable.h:919
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff8209e1c8)
Location: arch/x86/include/asm/pgtable.h:919
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff838b40b3)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
```
```
In arch/x86/kernel/head64.c (ffffffff838c4557)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105e928)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81070828)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:p4d_offset
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b59a8)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:p4d_offset
```
```
In arch/x86/mm/init_64.c (ffffffff838ef6b1)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:set_pte_vaddr_p4d
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff810cf1a8)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff810d0bc8)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:p4d_offset
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d5b68)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff810e0618)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:p4d_offset
```
```
In arch/x86/mm/pti.c (ffffffff810e0698)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f5612)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810ebc2b)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In kernel/events/core.c (ffffffff8138d728)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - kernel/events/core.c:p4d_offset
```
```
In mm/percpu.c (ffffffff813f6ac8)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - mm/percpu.c:p4d_offset
```
```
In mm/gup.c (ffffffff8140cf88)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
```
```
In mm/memory.c (ffffffff814147d8)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
```
```
In mm/mprotect.c (ffffffff8142e6d8)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
```
```
In mm/mremap.c (ffffffff81430ea8)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff814336f8)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:p4d_offset
```
```
In mm/pagewalk.c (ffffffff81434478)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - mm/pagewalk.c:p4d_offset
```
```
In mm/rmap.c (ffffffff81436388)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - mm/rmap.c:p4d_offset
```
```
In mm/vmalloc.c (ffffffff8143ecb8)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_small_pages_range_noflush
```
```
In mm/swapfile.c (ffffffff8146bb93)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81473df8)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81488da8)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
```
```
In mm/migrate_device.c (ffffffff8149ca2a)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - mm/migrate_device.c:p4d_alloc
```
```
In mm/memory-failure.c (ffffffff814c3918)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - mm/memory-failure.c:p4d_offset
```
```
In mm/userfaultfd.c (ffffffff814cfb08)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - mm/userfaultfd.c:p4d_offset
```
```
In fs/userfaultfd.c (ffffffff81557e38)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - fs/userfaultfd.c:p4d_offset
```
```
In arch/x86/power/hibernate_64.c (ffffffff82175189)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff821761c8)
Location: arch/x86/include/asm/pgtable.h:1141
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (0)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
```
```
In arch/x86/power/hibernate_64.c (0)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
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
In arch/x86/kernel/head64.c (0)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
```
```
In arch/x86/power/hibernate_64.c (0)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
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
In arch/x86/kernel/head64.c (0)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
```
```
In arch/x86/power/hibernate_64.c (0)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
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
In arch/x86/kernel/head64.c (0)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
```
```
In arch/x86/power/hibernate_64.c (0)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
```
</details>
</li>
</ul>

## Differences
