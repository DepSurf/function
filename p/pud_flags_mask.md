# Function: <code>pud_flags_mask</code>

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
In arch/x86/xen/mmu.c (ffffffff81f629d5)
Location: arch/x86/include/asm/pgtable_types.h:287
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034584)
Location: arch/x86/include/asm/pgtable_types.h:287
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ba65)
Location: arch/x86/include/asm/pgtable_types.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81068fdb)
Location: arch/x86/include/asm/pgtable_types.h:287
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/fault.c (ffffffff8106a280)
Location: arch/x86/include/asm/pgtable_types.h:287
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8106d204)
Location: arch/x86/include/asm/pgtable_types.h:287
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/gup.c (ffffffff810715e8)
Location: arch/x86/include/asm/pgtable_types.h:287
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pud
```
```
In mm/gup.c (ffffffff811ba837)
Location: arch/x86/include/asm/pgtable_types.h:287
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811bc236)
Location: arch/x86/include/asm/pgtable_types.h:287
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff811c85e9)
Location: arch/x86/include/asm/pgtable_types.h:287
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811c93c9)
Location: arch/x86/include/asm/pgtable_types.h:287
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811ca865)
Location: arch/x86/include/asm/pgtable_types.h:287
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811ce397)
Location: arch/x86/include/asm/pgtable_types.h:287
Inline: True
```
```
In mm/pagewalk.c (ffffffff811cfeb9)
Location: arch/x86/include/asm/pgtable_types.h:287
Inline: True
```
```
In mm/swapfile.c (ffffffff811d428e)
Location: arch/x86/include/asm/pgtable_types.h:287
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811dd6d3)
Location: arch/x86/include/asm/pgtable_types.h:287
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff811f6f44)
Location: arch/x86/include/asm/pgtable_types.h:287
Inline: True
Inline callers:
  - mm/huge_memory.c:page_check_address_pmd
  - mm/huge_memory.c:split_huge_page_address
```
```
In fs/userfaultfd.c (ffffffff8125af40)
Location: arch/x86/include/asm/pgtable_types.h:287
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In arch/x86/xen/mmu.c (ffffffff81f8a5bc)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103374e)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bb53)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8189633c)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff81069eb8)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8106dc0a)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810740ca)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/gup.c (ffffffff811d4f0a)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811da95d)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811e47c0)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e57b1)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811e773f)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811eaf3d)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
```
```
In mm/pagewalk.c (ffffffff811ed008)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
```
```
In mm/swapfile.c (ffffffff811f208b)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811fb9c8)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff8121673f)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In fs/userfaultfd.c (ffffffff81283b07)
Location: arch/x86/include/asm/pgtable_types.h:325
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
In arch/x86/xen/mmu.c (ffffffff81fc59b6)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103337e)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105eacd)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff818caa59)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8106da58)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81071896)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81077c42)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/gup.c (ffffffff811e4f2a)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811ea4ca)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811f47e0)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f59f0)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff811f6ed9)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff811f73f8)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
```
```
In mm/rmap.c (ffffffff811f8acf)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811fc19d)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
```
```
In mm/swapfile.c (ffffffff81202a7e)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8120c4c8)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff81228cff)
Location: arch/x86/include/asm/pgtable_types.h:325
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In fs/userfaultfd.c (ffffffff812976f9)
Location: arch/x86/include/asm/pgtable_types.h:325
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
In arch/x86/xen/mmu_pv.c (ffffffff820a6893)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103155a)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e16f)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81901f5a)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8106d788)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff810708d8)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81074088)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107652f)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/gup.c (ffffffff811ef547)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
```
```
In mm/memory.c (ffffffff811f1a88)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811ff739)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812007ba)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81201d7a)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81203abf)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81205724)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8120daa7)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81217e48)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812349f0)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
```
```
In fs/userfaultfd.c (ffffffff812a5032)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In arch/x86/xen/mmu_pv.c (ffffffff826acf74)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810337b7)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061e4d)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8198bfb7)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810721b7)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff810760d5)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81079adf)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107c732)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5ee9)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff81206cf0)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
```
```
In mm/memory.c (ffffffff81208811)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81217cd0)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81218f8b)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8121a8a0)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8121c7d0)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8121f71e)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81228d3d)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81232c36)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812543f8)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In fs/userfaultfd.c (ffffffff812c8455)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In arch/x86/xen/mmu_pv.c (ffffffff826d62bc)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034b34)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81064efa)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff819e8945)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8107521a)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81078bc0)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff8107c869)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107f3d3)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efcb8)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff812274ee)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
```
```
In mm/memory.c (ffffffff8122984a)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81239b11)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
```
```
In mm/mremap.c (ffffffff8123a957)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8123c644)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8123e5b3)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81240e9c)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8124a03d)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81255c82)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff81278278)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff81288a25)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/userfaultfd.c (ffffffff812f159e)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In arch/x86/xen/mmu_pv.c (ffffffff8288c207)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81035d14)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ab6a)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81a241ce)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8107b01a)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8107f528)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81083299)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81085fbd)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6975)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff8123ac91)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
```
```
In mm/memory.c (ffffffff8123cd5a)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff8124d434)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124eb5a)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81250a61)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81252b43)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81254bac)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8125e67d)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8126a0d2)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff8128c8b8)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff8129d725)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/userfaultfd.c (ffffffff81305f5e)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81a08e81)
Location: arch/x86/include/asm/pgtable_types.h:410
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
In arch/x86/xen/mmu_pv.c (ffffffff828a36a6)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81037e74)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e324)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a94886)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8107e996)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81082fcc)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81086f09)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089a15)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bf026)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff8124c70e)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
```
```
In mm/memory.c (ffffffff8124e9c8)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8125fc2e)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81260eaf)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81262d41)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81264ec3)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81266f5c)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8127b8ca)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81285206)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812a759a)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff812b8a6f)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812c4e75)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff813274f1)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81a7875f)
Location: arch/x86/include/asm/pgtable_types.h:409
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
In arch/x86/xen/mmu_pv.c (ffffffff828a674c)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038644)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f8d4)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81acc166)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8107fa26)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8108409c)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81087bf9)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108a685)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c549f)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff8125ac3e)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
```
```
In mm/memory.c (ffffffff8125cf65)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8126e4ee)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126f648)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812714f1)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81273753)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8127585c)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8128b3aa)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81294da6)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812b8a3a)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff812ca94f)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812d6825)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff8133a2d1)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81aafb0f)
Location: arch/x86/include/asm/pgtable_types.h:409
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
In arch/x86/xen/mmu_pv.c (ffffffff82ccc336)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103afec)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076ddb)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81085fcd)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff81086c17)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a099)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d881)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82ce86b0)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff81288fa1)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
```
```
In mm/memory.c (ffffffff8128d593)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8129eee5)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff8129fb62)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pmd
```
```
In mm/page_vma_mapped.c (ffffffff812a1da5)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812a2b55)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
```
```
In mm/rmap.c (ffffffff812a4927)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812a7272)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff812bdd86)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812c83c8)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812ed5e8)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff81300788)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff8130b933)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130ca22)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
```
In fs/userfaultfd.c (ffffffff81372320)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
```
```
In lib/ioremap.c (ffffffff815e99ce)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
In arch/x86/xen/mmu_pv.c (ffffffff82fb8174)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b7fc)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107740b)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81085b9d)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810884f7)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a319)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d751)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82fd60ce)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/core.c (ffffffff8123cad7)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff81292c81)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
```
```
In mm/memory.c (ffffffff8129fa44)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812aa2a9)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812aafea)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812ad5d1)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812ae4b3)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
```
```
In mm/rmap.c (ffffffff812b00b7)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b24f2)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/ioremap.c (ffffffff812b84b8)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_page_range
```
```
In mm/swapfile.c (ffffffff812c98aa)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812d3f98)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812f8d08)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff8130c928)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff81317823)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff81318962)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
```
In fs/userfaultfd.c (ffffffff81380170)
Location: arch/x86/include/asm/pgtable_types.h:434
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
In arch/x86/xen/mmu_pv.c (ffffffff831c27de)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103d19b)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077e94)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8108695d)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff81089176)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff8108af79)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e314)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff831e0b34)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/core.c (ffffffff81243dec)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff8129a767)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff812a52bd)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812af6e9)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812b042c)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812b27a1)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812b3877)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
```
```
In mm/rmap.c (ffffffff812b56ab)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b8c15)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff812d0518)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff812dae7d)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812ff25a)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff81313098)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff8131da23)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131eb52)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
```
In fs/userfaultfd.c (ffffffff813874f9)
Location: arch/x86/include/asm/pgtable_types.h:432
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
In arch/x86/xen/mmu_pv.c (ffffffff832a31ea)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81042cd9)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810856a5)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81096861)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810985d1)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a519)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109ddbd)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff832c4212)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/core.c (ffffffff8127e75f)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff812db128)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff812e681a)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812f0f1b)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812f1c6e)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812f43c8)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812f540a)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
```
```
In mm/rmap.c (ffffffff812f7340)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812fb1ca)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81315a63)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81321eb3)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff81348e62)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff8135fb6e)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff8136adc3)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136bf32)
Location: arch/x86/include/asm/pgtable_types.h:430
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
```
In fs/userfaultfd.c (ffffffff813d47d2)
Location: arch/x86/include/asm/pgtable_types.h:430
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
In arch/x86/xen/mmu_pv.c (ffffffff83452459)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8104ac13)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095a72)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810a9189)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810ab22c)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff810ad77d)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b1709)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810b9862)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In kernel/events/core.c (ffffffff812d33cf)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff8133ace8)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pud
```
```
In mm/memory.c (ffffffff8133d807)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81354b21)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81355832)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff813583b9)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813592c6)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
```
```
In mm/rmap.c (ffffffff8135c95a)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff813626cd)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81381060)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8138f0de)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff813bf2d3)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff813da7aa)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff813e883c)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff813ea15f)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
```
In fs/userfaultfd.c (ffffffff8145fc7d)
Location: arch/x86/include/asm/pgtable_types.h:432
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
In arch/x86/xen/mmu_pv.c (ffffffff83e6f9ca)
Location: arch/x86/include/asm/pgtable_types.h:411
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81056903)
Location: arch/x86/include/asm/pgtable_types.h:411
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab6b7)
Location: arch/x86/include/asm/pgtable_types.h:411
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff820c5bac)
Location: arch/x86/include/asm/pgtable_types.h:411
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810c35ce)
Location: arch/x86/include/asm/pgtable_types.h:411
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff810c791d)
Location: arch/x86/include/asm/pgtable_types.h:411
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cbe47)
Location: arch/x86/include/asm/pgtable_types.h:411
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810d54f9)
Location: arch/x86/include/asm/pgtable_types.h:411
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In kernel/events/core.c (ffffffff8133b645)
Location: arch/x86/include/asm/pgtable_types.h:411
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff8137feb0)
Location: arch/x86/include/asm/pgtable_types.h:411
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/gup.c (ffffffff813b2ad1)
Location: arch/x86/include/asm/pgtable_types.h:411
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:follow_p4d_mask
```
```
In mm/memory.c (ffffffff813b6827)
Location: arch/x86/include/asm/pgtable_types.h:411
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff813cf083)
Location: arch/x86/include/asm/pgtable_types.h:411
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813cffa2)
Location: arch/x86/include/asm/pgtable_types.h:411
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff813d29ec)
Location: arch/x86/include/asm/pgtable_types.h:411
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813d3b92)
Location: arch/x86/include/asm/pgtable_types.h:411
Inline: True
```
```
In mm/rmap.c (ffffffff813d703a)
Location: arch/x86/include/asm/pgtable_types.h:411
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff813de063)
Location: arch/x86/include/asm/pgtable_types.h:411
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813ff84c)
Location: arch/x86/include/asm/pgtable_types.h:411
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8140dbd4)
Location: arch/x86/include/asm/pgtable_types.h:411
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff8143ecd1)
Location: arch/x86/include/asm/pgtable_types.h:411
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff814609cb)
Location: arch/x86/include/asm/pgtable_types.h:411
Inline: True
```
```
In mm/hmm.c (ffffffff814707bf)
Location: arch/x86/include/asm/pgtable_types.h:411
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff8147221c)
Location: arch/x86/include/asm/pgtable_types.h:411
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
```
In fs/userfaultfd.c (ffffffff814ef566)
Location: arch/x86/include/asm/pgtable_types.h:411
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
In arch/x86/xen/mmu_pv.c (ffffffff8369078a)
Location: arch/x86/include/asm/pgtable_types.h:412
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810578d3)
Location: arch/x86/include/asm/pgtable_types.h:412
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af277)
Location: arch/x86/include/asm/pgtable_types.h:412
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff82149c1c)
Location: arch/x86/include/asm/pgtable_types.h:412
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810c6e1e)
Location: arch/x86/include/asm/pgtable_types.h:412
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff810cb066)
Location: arch/x86/include/asm/pgtable_types.h:412
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cf487)
Location: arch/x86/include/asm/pgtable_types.h:412
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810d8a0f)
Location: arch/x86/include/asm/pgtable_types.h:412
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In kernel/events/core.c (ffffffff8136d023)
Location: arch/x86/include/asm/pgtable_types.h:412
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813b139c)
Location: arch/x86/include/asm/pgtable_types.h:412
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/gup.c (ffffffff813e7567)
Location: arch/x86/include/asm/pgtable_types.h:412
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:follow_p4d_mask
```
```
In mm/memory.c (ffffffff813eb245)
Location: arch/x86/include/asm/pgtable_types.h:412
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81403757)
Location: arch/x86/include/asm/pgtable_types.h:412
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff81404a65)
Location: arch/x86/include/asm/pgtable_types.h:412
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff8140772c)
Location: arch/x86/include/asm/pgtable_types.h:412
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8140855c)
Location: arch/x86/include/asm/pgtable_types.h:412
Inline: True
```
```
In mm/rmap.c (ffffffff8140bf3d)
Location: arch/x86/include/asm/pgtable_types.h:412
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff814128bd)
Location: arch/x86/include/asm/pgtable_types.h:412
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81432544)
Location: arch/x86/include/asm/pgtable_types.h:412
Inline: True
```
```
In mm/hugetlb.c (ffffffff81440f87)
Location: arch/x86/include/asm/pgtable_types.h:412
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff8147455e)
Location: arch/x86/include/asm/pgtable_types.h:412
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff8149519e)
Location: arch/x86/include/asm/pgtable_types.h:412
Inline: True
```
```
In mm/hmm.c (ffffffff814a54ef)
Location: arch/x86/include/asm/pgtable_types.h:412
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a69ed)
Location: arch/x86/include/asm/pgtable_types.h:412
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
```
In fs/userfaultfd.c (ffffffff81524d2d)
Location: arch/x86/include/asm/pgtable_types.h:412
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
In arch/x86/xen/mmu_pv.c (ffffffff838c025a)
Location: arch/x86/include/asm/pgtable_types.h:440
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105eb73)
Location: arch/x86/include/asm/pgtable_types.h:440
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5e07)
Location: arch/x86/include/asm/pgtable_types.h:440
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8222c6cc)
Location: arch/x86/include/asm/pgtable_types.h:440
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810cf2de)
Location: arch/x86/include/asm/pgtable_types.h:440
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff810d35b6)
Location: arch/x86/include/asm/pgtable_types.h:440
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d7b67)
Location: arch/x86/include/asm/pgtable_types.h:440
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810e128f)
Location: arch/x86/include/asm/pgtable_types.h:440
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In kernel/events/core.c (ffffffff81396263)
Location: arch/x86/include/asm/pgtable_types.h:440
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813da91c)
Location: arch/x86/include/asm/pgtable_types.h:440
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/gup.c (ffffffff814121e5)
Location: arch/x86/include/asm/pgtable_types.h:440
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pud
```
```
In mm/memory.c (ffffffff8141526e)
Location: arch/x86/include/asm/pgtable_types.h:440
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8142fcd7)
Location: arch/x86/include/asm/pgtable_types.h:440
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff81431035)
Location: arch/x86/include/asm/pgtable_types.h:440
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff81433dba)
Location: arch/x86/include/asm/pgtable_types.h:440
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81434c7c)
Location: arch/x86/include/asm/pgtable_types.h:440
Inline: True
```
```
In mm/rmap.c (ffffffff814387dd)
Location: arch/x86/include/asm/pgtable_types.h:440
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8143f32d)
Location: arch/x86/include/asm/pgtable_types.h:440
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff8146b964)
Location: arch/x86/include/asm/pgtable_types.h:440
Inline: True
```
```
In mm/hugetlb.c (ffffffff8147b0b7)
Location: arch/x86/include/asm/pgtable_types.h:440
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff814a3b0a)
Location: arch/x86/include/asm/pgtable_types.h:440
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff814c4b06)
Location: arch/x86/include/asm/pgtable_types.h:440
Inline: True
```
```
In mm/hmm.c (ffffffff814d64af)
Location: arch/x86/include/asm/pgtable_types.h:440
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d78ed)
Location: arch/x86/include/asm/pgtable_types.h:440
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pud_entry
```
```
In fs/userfaultfd.c (ffffffff815589be)
Location: arch/x86/include/asm/pgtable_types.h:440
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
In arch/x86/xen/mmu_pv.c (ffffffff82894755)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810387a4)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e874)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a6afd6)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8107ea26)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8108309c)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81086bf9)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089645)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b0437)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff8125328e)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
```
```
In mm/memory.c (ffffffff812555b5)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81266b3e)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81267c98)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81269b41)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8126bda3)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8126deac)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8128398a)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128d386)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812b101a)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff812c2f2f)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812cee05)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff813328b1)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81a4e95f)
Location: arch/x86/include/asm/pgtable_types.h:409
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
In arch/x86/kernel/espfix_64.c (ffffffff81028184)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105eeb7)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81a274e0)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8106ddc6)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81071d21)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pgtable.c (ffffffff8107587a)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810783ce)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a85e7)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff81245f80)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
```
```
In mm/memory.c (ffffffff81247cee)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff812589f4)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81259fe6)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8125be0f)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8125de3c)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8125fece)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81275833)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8127f16c)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812a241a)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812b401a)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/hmm.c (ffffffff812bfa93)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff8132346d)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81a0ba31)
Location: arch/x86/include/asm/pgtable_types.h:409
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
In arch/x86/xen/mmu_pv.c (ffffffff828a774c)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038604)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ed24)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ad73e6)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8107e9d6)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8108304c)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81086ba9)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810895f5)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c3336)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff8125102e)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
```
```
In mm/memory.c (ffffffff81253355)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812648de)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81265a38)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812678e1)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81269b43)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8126bc4c)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8128179a)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128b196)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812aee2a)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff812c0d3f)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812ccc15)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff81330381)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81abad4f)
Location: arch/x86/include/asm/pgtable_types.h:409
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
In arch/x86/xen/mmu_pv.c (ffffffff828a7752)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81039604)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81070fa4)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ae38a6)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff81080ac6)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81085413)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81088cd9)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pudp_test_and_clear_young
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108b895)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c64dc)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff812609a7)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
```
```
In mm/memory.c (ffffffff81262d65)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812742a7)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812753da)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81277277)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812794b3)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8127b65c)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff812914d5)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8129afb6)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812bf17a)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff812d17ff)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812dd9a5)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff81342cd8)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81ac719f)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
</details>
</li>
</ul>

## Differences
