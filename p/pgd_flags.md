# Function: <code>pgd_flags</code>

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
In arch/x86/xen/mmu.c (0)
Location: arch/x86/include/asm/pgtable_types.h:232
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/include/asm/pgtable_types.h:232
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable_types.h:232
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable_types.h:232
Inline: True
```
```
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable_types.h:232
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable_types.h:232
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable_types.h:232
Inline: True
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/pgtable_types.h:232
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable_types.h:232
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable_types.h:232
Inline: True
```
```
In mm/pagewalk.c (0)
Location: arch/x86/include/asm/pgtable_types.h:232
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable_types.h:232
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/pgtable_types.h:232
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable_types.h:232
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable_types.h:232
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
In arch/x86/xen/mmu.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff81069e83)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81073fb6)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
```
```
In mm/rmap.c (ffffffff811e770a)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
```
```
In mm/pagewalk.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
```
```
In fs/userfaultfd.c (ffffffff812839ae)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In arch/x86/xen/mmu.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff8106da23)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81077b26)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff811f6e62)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
```
```
In mm/rmap.c (ffffffff811f8a9a)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
```
```
In fs/userfaultfd.c (ffffffff812974d1)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/include/asm/pgtable_types.h:270
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
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable_types.h:280
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/include/asm/pgtable_types.h:280
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
In arch/x86/mm/fault.c (ffffffff810759f5)
Location: arch/x86/include/asm/pgtable_types.h:279
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107f354)
Location: arch/x86/include/asm/pgtable_types.h:279
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
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
In arch/x86/mm/fault.c (ffffffff8107b7c0)
Location: arch/x86/include/asm/pgtable_types.h:303
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81085f1e)
Location: arch/x86/include/asm/pgtable_types.h:303
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
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
In arch/x86/mm/fault.c (ffffffff8107f2df)
Location: arch/x86/include/asm/pgtable_types.h:302
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089e34)
Location: arch/x86/include/asm/pgtable_types.h:302
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
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
In arch/x86/mm/fault.c (ffffffff8108036f)
Location: arch/x86/include/asm/pgtable_types.h:302
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108aaa4)
Location: arch/x86/include/asm/pgtable_types.h:302
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
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
In arch/x86/xen/mmu_pv.c (ffffffff82ccc2fd)
Location: arch/x86/include/asm/pgtable_types.h:326
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076c8e)
Location: arch/x86/include/asm/pgtable_types.h:326
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8108523d)
Location: arch/x86/include/asm/pgtable_types.h:326
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff81086b8d)
Location: arch/x86/include/asm/pgtable_types.h:326
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff82cec1eb)
Location: arch/x86/include/asm/pgtable_types.h:326
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_epilog
```
```
In mm/gup.c (ffffffff81289114)
Location: arch/x86/include/asm/pgtable_types.h:326
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff8128d4a6)
Location: arch/x86/include/asm/pgtable_types.h:326
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff8129f0b5)
Location: arch/x86/include/asm/pgtable_types.h:326
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8129fa77)
Location: arch/x86/include/asm/pgtable_types.h:326
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pmd
```
```
In mm/page_vma_mapped.c (ffffffff812a1cd6)
Location: arch/x86/include/asm/pgtable_types.h:326
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812a2e28)
Location: arch/x86/include/asm/pgtable_types.h:326
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff812a4893)
Location: arch/x86/include/asm/pgtable_types.h:326
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812a8309)
Location: arch/x86/include/asm/pgtable_types.h:326
Inline: True
Inline callers:
  - mm/vmalloc.c:map_kernel_range_noflush
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:unmap_kernel_range_noflush
```
```
In mm/swapfile.c (ffffffff812bdff3)
Location: arch/x86/include/asm/pgtable_types.h:326
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff812c8336)
Location: arch/x86/include/asm/pgtable_types.h:326
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812ed55d)
Location: arch/x86/include/asm/pgtable_types.h:326
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff813006fc)
Location: arch/x86/include/asm/pgtable_types.h:326
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/userfaultfd.c (ffffffff81372291)
Location: arch/x86/include/asm/pgtable_types.h:326
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff82fb813b)
Location: arch/x86/include/asm/pgtable_types.h:327
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810772be)
Location: arch/x86/include/asm/pgtable_types.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8108631d)
Location: arch/x86/include/asm/pgtable_types.h:327
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8108846d)
Location: arch/x86/include/asm/pgtable_types.h:327
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In mm/gup.c (ffffffff81292df4)
Location: arch/x86/include/asm/pgtable_types.h:327
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff8129f989)
Location: arch/x86/include/asm/pgtable_types.h:327
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff812aa475)
Location: arch/x86/include/asm/pgtable_types.h:327
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812aaf07)
Location: arch/x86/include/asm/pgtable_types.h:327
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812ad501)
Location: arch/x86/include/asm/pgtable_types.h:327
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812ae748)
Location: arch/x86/include/asm/pgtable_types.h:327
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff812b0023)
Location: arch/x86/include/asm/pgtable_types.h:327
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b33d3)
Location: arch/x86/include/asm/pgtable_types.h:327
Inline: True
Inline callers:
  - mm/vmalloc.c:map_kernel_range_noflush
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:unmap_kernel_range_noflush
```
```
In mm/swapfile.c (ffffffff812c9b13)
Location: arch/x86/include/asm/pgtable_types.h:327
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff812d3f06)
Location: arch/x86/include/asm/pgtable_types.h:327
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812f8c7d)
Location: arch/x86/include/asm/pgtable_types.h:327
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8130c89c)
Location: arch/x86/include/asm/pgtable_types.h:327
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/userfaultfd.c (ffffffff813800e1)
Location: arch/x86/include/asm/pgtable_types.h:327
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
In arch/x86/xen/mmu_pv.c (ffffffff831c279e)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077d77)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810870ca)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff81089125)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In mm/gup.c (ffffffff8129882b)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff812a5201)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff812af8b5)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812b0377)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812b26ed)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812b3b08)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff812b564e)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b8b4a)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff812d0388)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff812dae23)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812ff200)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8131300e)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/userfaultfd.c (ffffffff8138749e)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff832a31aa)
Location: arch/x86/include/asm/pgtable_types.h:323
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81085585)
Location: arch/x86/include/asm/pgtable_types.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810963ea)
Location: arch/x86/include/asm/pgtable_types.h:323
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8109857e)
Location: arch/x86/include/asm/pgtable_types.h:323
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In mm/gup.c (ffffffff812d928c)
Location: arch/x86/include/asm/pgtable_types.h:323
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff812e37b4)
Location: arch/x86/include/asm/pgtable_types.h:323
Inline: True
Inline callers:
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff812f10fd)
Location: arch/x86/include/asm/pgtable_types.h:323
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812f1bb9)
Location: arch/x86/include/asm/pgtable_types.h:323
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812f4302)
Location: arch/x86/include/asm/pgtable_types.h:323
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812f56a7)
Location: arch/x86/include/asm/pgtable_types.h:323
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff812f72dd)
Location: arch/x86/include/asm/pgtable_types.h:323
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812fb0fc)
Location: arch/x86/include/asm/pgtable_types.h:323
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813158d3)
Location: arch/x86/include/asm/pgtable_types.h:323
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81321e53)
Location: arch/x86/include/asm/pgtable_types.h:323
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff81348dff)
Location: arch/x86/include/asm/pgtable_types.h:323
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8135fade)
Location: arch/x86/include/asm/pgtable_types.h:323
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/userfaultfd.c (ffffffff813d476e)
Location: arch/x86/include/asm/pgtable_types.h:323
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff83452419)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8109595e)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810a8c7d)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff810ab1da)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In mm/gup.c (ffffffff81339265)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff8133d74c)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff8135491a)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8135577e)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff813582ff)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8135956d)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff8135c8ed)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81362601)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81380e7a)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8138f073)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff813bf260)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff813da66d)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/userfaultfd.c (ffffffff8145fc0e)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff83e6f961)
Location: arch/x86/include/asm/pgtable_types.h:306
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab5a3)
Location: arch/x86/include/asm/pgtable_types.h:306
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff820c5fff)
Location: arch/x86/include/asm/pgtable_types.h:306
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff810c357d)
Location: arch/x86/include/asm/pgtable_types.h:306
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In mm/gup.c (ffffffff813b0b5f)
Location: arch/x86/include/asm/pgtable_types.h:306
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff813b676c)
Location: arch/x86/include/asm/pgtable_types.h:306
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff813cee6e)
Location: arch/x86/include/asm/pgtable_types.h:306
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813cfeee)
Location: arch/x86/include/asm/pgtable_types.h:306
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff813d2931)
Location: arch/x86/include/asm/pgtable_types.h:306
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813d3e4d)
Location: arch/x86/include/asm/pgtable_types.h:306
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff813d6fcd)
Location: arch/x86/include/asm/pgtable_types.h:306
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff813ddf97)
Location: arch/x86/include/asm/pgtable_types.h:306
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:__vunmap_range_noflush
  - mm/vmalloc.c:__vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813ff6c5)
Location: arch/x86/include/asm/pgtable_types.h:306
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8140db63)
Location: arch/x86/include/asm/pgtable_types.h:306
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/memory-failure.c (ffffffff8146095d)
Location: arch/x86/include/asm/pgtable_types.h:306
Inline: True
```
```
In fs/userfaultfd.c (ffffffff814ef4ee)
Location: arch/x86/include/asm/pgtable_types.h:306
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
In arch/x86/xen/mmu_pv.c (ffffffff83690721)
Location: arch/x86/include/asm/pgtable_types.h:307
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af163)
Location: arch/x86/include/asm/pgtable_types.h:307
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8214a05f)
Location: arch/x86/include/asm/pgtable_types.h:307
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff810c6dcd)
Location: arch/x86/include/asm/pgtable_types.h:307
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In mm/gup.c (ffffffff813e4f92)
Location: arch/x86/include/asm/pgtable_types.h:307
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff813eb18d)
Location: arch/x86/include/asm/pgtable_types.h:307
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81403a97)
Location: arch/x86/include/asm/pgtable_types.h:307
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff814049b1)
Location: arch/x86/include/asm/pgtable_types.h:307
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff81407671)
Location: arch/x86/include/asm/pgtable_types.h:307
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8140881d)
Location: arch/x86/include/asm/pgtable_types.h:307
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff8140bed0)
Location: arch/x86/include/asm/pgtable_types.h:307
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff814127f7)
Location: arch/x86/include/asm/pgtable_types.h:307
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:__vunmap_range_noflush
  - mm/vmalloc.c:__vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff8143273a)
Location: arch/x86/include/asm/pgtable_types.h:307
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81440f16)
Location: arch/x86/include/asm/pgtable_types.h:307
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/memory-failure.c (ffffffff81495130)
Location: arch/x86/include/asm/pgtable_types.h:307
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81524cb4)
Location: arch/x86/include/asm/pgtable_types.h:307
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
In arch/x86/xen/mmu_pv.c (ffffffff838c01f1)
Location: arch/x86/include/asm/pgtable_types.h:335
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5cf3)
Location: arch/x86/include/asm/pgtable_types.h:335
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8222cb0f)
Location: arch/x86/include/asm/pgtable_types.h:335
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff810cf28d)
Location: arch/x86/include/asm/pgtable_types.h:335
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In mm/gup.c (ffffffff8140f7c5)
Location: arch/x86/include/asm/pgtable_types.h:335
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff814151b3)
Location: arch/x86/include/asm/pgtable_types.h:335
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81430017)
Location: arch/x86/include/asm/pgtable_types.h:335
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81430f81)
Location: arch/x86/include/asm/pgtable_types.h:335
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff81433cff)
Location: arch/x86/include/asm/pgtable_types.h:335
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81434f3d)
Location: arch/x86/include/asm/pgtable_types.h:335
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81438770)
Location: arch/x86/include/asm/pgtable_types.h:335
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8143f267)
Location: arch/x86/include/asm/pgtable_types.h:335
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:__vunmap_range_noflush
  - mm/vmalloc.c:__vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff8146bb5a)
Location: arch/x86/include/asm/pgtable_types.h:335
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8147b046)
Location: arch/x86/include/asm/pgtable_types.h:335
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/memory-failure.c (ffffffff814c4a92)
Location: arch/x86/include/asm/pgtable_types.h:335
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81558945)
Location: arch/x86/include/asm/pgtable_types.h:335
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107f36f)
Location: arch/x86/include/asm/pgtable_types.h:302
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089a64)
Location: arch/x86/include/asm/pgtable_types.h:302
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
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
In arch/x86/mm/fault.c (ffffffff8106e349)
Location: arch/x86/include/asm/pgtable_types.h:302
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81078357)
Location: arch/x86/include/asm/pgtable_types.h:302
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
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
In arch/x86/mm/fault.c (ffffffff8107f31f)
Location: arch/x86/include/asm/pgtable_types.h:302
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089a14)
Location: arch/x86/include/asm/pgtable_types.h:302
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
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
In arch/x86/mm/fault.c (ffffffff8108140f)
Location: arch/x86/include/asm/pgtable_types.h:302
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108bcaf)
Location: arch/x86/include/asm/pgtable_types.h:302
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
</details>
</li>
</ul>

## Differences
