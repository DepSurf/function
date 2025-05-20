# Function: <code>pud_pgtable</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pmd_t *pud_pgtable(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8329bb3a)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff832a3d9c)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81042d0b)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81c9a724)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81085723)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81096c9e)
Location: arch/x86/include/asm/pgtable.h:839
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
In arch/x86/mm/fault.c (ffffffff810985ff)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff832c1846)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a7dd)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109c891)
Location: arch/x86/include/asm/pgtable.h:839
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
In arch/x86/mm/pti.c (ffffffff810a4a33)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81ca256d)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
```
```
In kernel/events/core.c (ffffffff8127e79c)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff812db166)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff812e683e)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812f0ab8)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
```
```
In mm/mremap.c (ffffffff812f257e)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812f440a)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812f4ec2)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
```
```
In mm/rmap.c (ffffffff812f7358)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812fb20b)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81315aa5)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81321ed2)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81d512f4)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_remap_range
```
```
In mm/migrate.c (ffffffff81340dfd)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
```
```
In mm/huge_memory.c (ffffffff81348e7a)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8135fba2)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff813669e3)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813d47ea)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81c9442a)
Location: arch/x86/include/asm/pgtable.h:839
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81095b90-ffffffff81095bd0: pud_pgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pmd_t *pud_pgtable(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8344a32c)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83453025)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8104ac45)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/tboot.c (ffffffff81e49b90)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095aee)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810a9750)
Location: arch/x86/include/asm/pgtable.h:837
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
In arch/x86/mm/fault.c (ffffffff810ab259)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff83473ef4)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810adaad)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b0073)
Location: arch/x86/include/asm/pgtable.h:837
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
In arch/x86/mm/pti.c (ffffffff810b92c8)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81e51dbc)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
```
```
In kernel/events/core.c (ffffffff812d340b)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/percpu.c (ffffffff8348b9db)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff8133ad27)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8133d82b)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81354ad3)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81356424)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff813583fb)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81358dd6)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
```
```
In mm/rmap.c (ffffffff8135c976)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8136270e)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813810a2)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8138f101)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8139bfb8)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_range
Direct callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate_device.c (ffffffff813b7cdc)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
```
```
In mm/huge_memory.c (ffffffff813bf2ef)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff813da7dd)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff813e3d72)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8145fc99)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81e43455)
Location: arch/x86/include/asm/pgtable.h:837
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810a81b0-ffffffff810a81ff: pud_pgtable (STB_LOCAL)
ffffffff8139bac0-ffffffff8139bb0f: pud_pgtable (STB_LOCAL)
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83e64940)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e7050f)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81056a26)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/tboot.c (ffffffff81067ee0)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab734)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810c2b5b)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810c35ff)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff83e9bb4f)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7cb9)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ca704)
Location: arch/x86/include/asm/pgtable.h:855
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
In arch/x86/mm/pti.c (ffffffff810d4c3a)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea0c47)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In kernel/events/core.c (ffffffff8133b685)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff8137f92e)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/percpu.c (ffffffff83ebc8e8)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff813b0cf4)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff813b684b)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff813cf032)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813d0a4a)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff813d2a2f)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813d36b5)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
```
```
In mm/rmap.c (ffffffff813d7057)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff813de0a5)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813ff88e)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8140dbf8)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/hugetlb_vmemmap.c (ffffffff814140cc)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse-vmemmap.c (ffffffff820cb071)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate_device.c (ffffffff8143999b)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
```
```
In mm/memory-failure.c (ffffffff814609fa)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8146b796)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff814ef583)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff8201e4f6)
Location: arch/x86/include/asm/pgtable.h:855
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83684fc0)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83691389)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810579f5)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/tboot.c (ffffffff81069790)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af2f4)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810c623b)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810c6e49)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff836bf5ef)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810cb3f9)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cdd44)
Location: arch/x86/include/asm/pgtable.h:856
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
In arch/x86/mm/pti.c (ffffffff810d8144)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4d57)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In kernel/events/core.c (ffffffff8136d061)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813b0e5e)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/percpu.c (ffffffff836e4f68)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff813e75ba)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff813eb265)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:remap_p4d_range
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81403706)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff8140546c)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8140776f)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81408109)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
```
```
In mm/rmap.c (ffffffff8140bf5a)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff814128ff)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81432586)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
```
```
In mm/hugetlb.c (ffffffff81440fab)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/hugetlb_vmemmap.c (ffffffff8144762c)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse-vmemmap.c (ffffffff8214f301)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate_device.c (ffffffff8146e743)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
```
```
In mm/memory-failure.c (ffffffff814951cd)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814a0599)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81524d4a)
Location: arch/x86/include/asm/pgtable.h:856
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff8209e4f0)
Location: arch/x86/include/asm/pgtable.h:856
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff838b4160)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff838c0e99)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105ec95)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/tboot.c (ffffffff81070cd0)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5e84)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810ce68b)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810cf309)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff838f008f)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810d3949)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d6424)
Location: arch/x86/include/asm/pgtable.h:1078
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
In arch/x86/mm/pti.c (ffffffff810e09c4)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f5957)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In kernel/events/core.c (ffffffff813962a1)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813da3d5)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/percpu.c (ffffffff83917779)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff81412238)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8141528e)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8142fc86)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff81431983)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81433dfd)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81434829)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
```
```
In mm/rmap.c (ffffffff814387fa)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8143f36f)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff8146b9a6)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
```
```
In mm/hugetlb.c (ffffffff8147b0db)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff822321d1)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate_device.c (ffffffff8149d1b4)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/memory-failure.c (ffffffff814c4b37)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814cfc39)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff815589db)
Location: arch/x86/include/asm/pgtable.h:1078
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff821764f0)
Location: arch/x86/include/asm/pgtable.h:1078
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
