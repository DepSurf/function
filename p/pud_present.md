# Function: <code>pud_present</code>

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
Location: arch/x86/include/asm/pgtable.h:586
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034584)
Location: arch/x86/include/asm/pgtable.h:586
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ba65)
Location: arch/x86/include/asm/pgtable.h:586
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81068fdb)
Location: arch/x86/include/asm/pgtable.h:586
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/fault.c (ffffffff8106a280)
Location: arch/x86/include/asm/pgtable.h:586
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8106d204)
Location: arch/x86/include/asm/pgtable.h:586
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In mm/memory.c (ffffffff811beb14)
Location: arch/x86/include/asm/pgtable.h:586
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/rmap.c (ffffffff811ca865)
Location: arch/x86/include/asm/pgtable.h:586
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff811dd6d3)
Location: arch/x86/include/asm/pgtable.h:586
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff811f6f44)
Location: arch/x86/include/asm/pgtable.h:586
Inline: True
Inline callers:
  - mm/huge_memory.c:page_check_address_pmd
  - mm/huge_memory.c:split_huge_page_address
```
```
In fs/userfaultfd.c (ffffffff8125af40)
Location: arch/x86/include/asm/pgtable.h:586
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
Location: arch/x86/include/asm/pgtable.h:623
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103374e)
Location: arch/x86/include/asm/pgtable.h:623
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bb53)
Location: arch/x86/include/asm/pgtable.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8189633c)
Location: arch/x86/include/asm/pgtable.h:623
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff81069eb8)
Location: arch/x86/include/asm/pgtable.h:623
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8106ec6b)
Location: arch/x86/include/asm/pgtable.h:623
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810740ca)
Location: arch/x86/include/asm/pgtable.h:623
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/memory.c (ffffffff811da95d)
Location: arch/x86/include/asm/pgtable.h:623
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/rmap.c (ffffffff811e773f)
Location: arch/x86/include/asm/pgtable.h:623
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff811fb9c8)
Location: arch/x86/include/asm/pgtable.h:623
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff8121673f)
Location: arch/x86/include/asm/pgtable.h:623
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In fs/userfaultfd.c (ffffffff81283b07)
Location: arch/x86/include/asm/pgtable.h:623
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
Location: arch/x86/include/asm/pgtable.h:623
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103337e)
Location: arch/x86/include/asm/pgtable.h:623
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105eacd)
Location: arch/x86/include/asm/pgtable.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff818caa59)
Location: arch/x86/include/asm/pgtable.h:623
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8106da58)
Location: arch/x86/include/asm/pgtable.h:623
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff810728db)
Location: arch/x86/include/asm/pgtable.h:623
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81077c42)
Location: arch/x86/include/asm/pgtable.h:623
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/memory.c (ffffffff811ea4ca)
Location: arch/x86/include/asm/pgtable.h:623
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/page_vma_mapped.c (ffffffff811f6ed9)
Location: arch/x86/include/asm/pgtable.h:623
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff811f8acf)
Location: arch/x86/include/asm/pgtable.h:623
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff8120c4c8)
Location: arch/x86/include/asm/pgtable.h:623
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff81228cff)
Location: arch/x86/include/asm/pgtable.h:623
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In fs/userfaultfd.c (ffffffff812976f9)
Location: arch/x86/include/asm/pgtable.h:623
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
Location: arch/x86/include/asm/pgtable.h:762
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103155a)
Location: arch/x86/include/asm/pgtable.h:762
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e16f)
Location: arch/x86/include/asm/pgtable.h:762
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81901f5a)
Location: arch/x86/include/asm/pgtable.h:762
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8106d788)
Location: arch/x86/include/asm/pgtable.h:762
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81071e98)
Location: arch/x86/include/asm/pgtable.h:762
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107652f)
Location: arch/x86/include/asm/pgtable.h:762
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/memory.c (ffffffff811f554a)
Location: arch/x86/include/asm/pgtable.h:762
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/page_vma_mapped.c (ffffffff81201d7a)
Location: arch/x86/include/asm/pgtable.h:762
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81203abf)
Location: arch/x86/include/asm/pgtable.h:762
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff81217e48)
Location: arch/x86/include/asm/pgtable.h:762
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812349f0)
Location: arch/x86/include/asm/pgtable.h:762
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
```
```
In fs/userfaultfd.c (ffffffff812a5032)
Location: arch/x86/include/asm/pgtable.h:762
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
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810337b7)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061e4d)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8198bfb7)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810721b7)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff810776e0)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107c732)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/memory.c (ffffffff8120e41b)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/page_vma_mapped.c (ffffffff8121a8a0)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8121c7d0)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff81232c36)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812543f8)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
```
```
In fs/userfaultfd.c (ffffffff812c8455)
Location: arch/x86/include/asm/pgtable.h:771
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
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034b34)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81064efa)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff819e8945)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff8107521a)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8107a128)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff8107c869)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107f434)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/memory.c (ffffffff8122ee1a)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/page_vma_mapped.c (ffffffff8123c644)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8123e5b3)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff81255c82)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff81278278)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff81288a25)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/userfaultfd.c (ffffffff812f159e)
Location: arch/x86/include/asm/pgtable.h:813
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
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81035d14)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ab6a)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81a241ce)
Location: arch/x86/include/asm/pgtable.h:838
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
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81080908)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81083299)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81086021)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/memory.c (ffffffff812418aa)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/page_vma_mapped.c (ffffffff81250a61)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81252b43)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff8126a0d2)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff8128c8b8)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff8129d725)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/userfaultfd.c (ffffffff81305f5e)
Location: arch/x86/include/asm/pgtable.h:838
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81a08e81)
Location: arch/x86/include/asm/pgtable.h:838
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
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81037e74)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e324)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a94886)
Location: arch/x86/include/asm/pgtable.h:855
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
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81084408)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81086f09)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089a74)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In mm/memory.c (ffffffff81254229)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/page_vma_mapped.c (ffffffff81262d41)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81264ec3)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff81285206)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812a759a)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff812b8a6f)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812c4e75)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff813274f1)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81a7875f)
Location: arch/x86/include/asm/pgtable.h:855
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
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038644)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f8d4)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81acc166)
Location: arch/x86/include/asm/pgtable.h:855
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
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81085148)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81087bf9)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108a6e4)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In mm/memory.c (ffffffff81262789)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/page_vma_mapped.c (ffffffff812714f1)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81273753)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff81294da6)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812b8a3a)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff812ca94f)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812d6825)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff8133a2d1)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81aafb0f)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pud_present(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82ccc336)
Location: arch/x86/include/asm/pgtable.h:864
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103afec)
Location: arch/x86/include/asm/pgtable.h:864
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076ddb)
Location: arch/x86/include/asm/pgtable.h:864
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81085fcd)
Location: arch/x86/include/asm/pgtable.h:864
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff81086c17)
Location: arch/x86/include/asm/pgtable.h:864
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a099)
Location: arch/x86/include/asm/pgtable.h:864
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108eefe)
Location: arch/x86/include/asm/pgtable.h:864
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In mm/gup.c (ffffffff8128b165)
Location: arch/x86/include/asm/pgtable.h:864
Inline: True
```
```
In mm/memory.c (ffffffff81292689)
Location: arch/x86/include/asm/pgtable.h:864
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/page_vma_mapped.c (ffffffff812a1da5)
Location: arch/x86/include/asm/pgtable.h:864
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812a2b55)
Location: arch/x86/include/asm/pgtable.h:864
Inline: True
```
```
In mm/rmap.c (ffffffff812a4927)
Location: arch/x86/include/asm/pgtable.h:864
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff812c83c8)
Location: arch/x86/include/asm/pgtable.h:864
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812ed5e8)
Location: arch/x86/include/asm/pgtable.h:864
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff81300788)
Location: arch/x86/include/asm/pgtable.h:864
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff8130b933)
Location: arch/x86/include/asm/pgtable.h:864
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff81372320)
Location: arch/x86/include/asm/pgtable.h:864
Inline: True
```
```
In lib/ioremap.c (ffffffff815e99ce)
Location: arch/x86/include/asm/pgtable.h:864
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81085fcd-ffffffff81085ff6: pud_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pud_present(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82fb8174)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b7fc)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107740b)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81085b9d)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810884f7)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a319)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ecee)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In kernel/events/core.c (ffffffff8123cad7)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff81294e25)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
```
```
In mm/memory.c (ffffffff8129cf70)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/page_vma_mapped.c (ffffffff812ad5d1)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812ae4b3)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
```
```
In mm/rmap.c (ffffffff812b00b7)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/ioremap.c (ffffffff812b84b8)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_page_range
```
```
In mm/hugetlb.c (ffffffff812d3f98)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812f8d08)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff8130c928)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff81317823)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff81380170)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
```
**Symbols:**

```
ffffffff81bd8941-ffffffff81bd896a: pud_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pud_present(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff831c27de)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103d19b)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077e94)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8108695d)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff81089176)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff8108af6f)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f876)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In kernel/events/core.c (ffffffff81243dec)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff8129a767)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff812a2653)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/page_vma_mapped.c (ffffffff812b27a1)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812b386d)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
```
```
In mm/rmap.c (ffffffff812b56ab)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b8337)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/hugetlb.c (ffffffff812dae7d)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812ff25a)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff81313098)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff8131da23)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff813874f9)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
```
**Symbols:**

```
ffffffff81bca7ed-ffffffff81bca81a: pud_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pud_present(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff832a31ea)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81042cd9)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810856a5)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81096861)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810985d1)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a50f)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109f34b)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In kernel/events/core.c (ffffffff8127e75f)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff812db128)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff812e39c3)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/page_vma_mapped.c (ffffffff812f43c8)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812f53ff)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
```
```
In mm/rmap.c (ffffffff812f7340)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812faa89)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/hugetlb.c (ffffffff81321eb3)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff81348e62)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff8135fb6e)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff8136adc3)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff813d47d2)
Location: arch/x86/include/asm/pgtable.h:834
Inline: True
```
**Symbols:**

```
ffffffff81c9fc93-ffffffff81c9fcc0: pud_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pud_present(pud_t pud);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff83452459)
Location: arch/x86/include/asm/pgtable.h:832
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8104ac13)
Location: arch/x86/include/asm/pgtable.h:832
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095a72)
Location: arch/x86/include/asm/pgtable.h:832
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810a9189)
Location: arch/x86/include/asm/pgtable.h:832
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/fault.c (ffffffff810ab22c)
Location: arch/x86/include/asm/pgtable.h:832
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff810ad773)
Location: arch/x86/include/asm/pgtable.h:832
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b2f45)
Location: arch/x86/include/asm/pgtable.h:832
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In kernel/events/core.c (ffffffff812d33cf)
Location: arch/x86/include/asm/pgtable.h:832
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff8133ace8)
Location: arch/x86/include/asm/pgtable.h:832
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff81344d4f)
Location: arch/x86/include/asm/pgtable.h:832
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/page_vma_mapped.c (ffffffff813583b9)
Location: arch/x86/include/asm/pgtable.h:832
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813592bb)
Location: arch/x86/include/asm/pgtable.h:832
Inline: True
```
```
In mm/rmap.c (ffffffff8135c95a)
Location: arch/x86/include/asm/pgtable.h:832
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81361ed5)
Location: arch/x86/include/asm/pgtable.h:832
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/hugetlb.c (ffffffff8138f0de)
Location: arch/x86/include/asm/pgtable.h:832
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff813bf2d3)
Location: arch/x86/include/asm/pgtable.h:832
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff813da7aa)
Location: arch/x86/include/asm/pgtable.h:832
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff813e883c)
Location: arch/x86/include/asm/pgtable.h:832
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff8145fc7d)
Location: arch/x86/include/asm/pgtable.h:832
Inline: True
```
**Symbols:**

```
ffffffff810a7ec0-ffffffff810a7ef1: pud_present (STB_LOCAL)
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
Location: arch/x86/include/asm/pgtable.h:850
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81056903)
Location: arch/x86/include/asm/pgtable.h:850
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab6b7)
Location: arch/x86/include/asm/pgtable.h:850
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff820c5bac)
Location: arch/x86/include/asm/pgtable.h:850
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
Location: arch/x86/include/asm/pgtable.h:850
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7913)
Location: arch/x86/include/asm/pgtable.h:850
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cd94f)
Location: arch/x86/include/asm/pgtable.h:850
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In kernel/events/core.c (ffffffff8133b645)
Location: arch/x86/include/asm/pgtable.h:850
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff8137feb0)
Location: arch/x86/include/asm/pgtable.h:850
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/gup.c (ffffffff813b2ad1)
Location: arch/x86/include/asm/pgtable.h:850
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff813bcf7f)
Location: arch/x86/include/asm/pgtable.h:850
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/page_vma_mapped.c (ffffffff813d29ec)
Location: arch/x86/include/asm/pgtable.h:850
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813d3b87)
Location: arch/x86/include/asm/pgtable.h:850
Inline: True
```
```
In mm/rmap.c (ffffffff813d703a)
Location: arch/x86/include/asm/pgtable.h:850
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff813dd889)
Location: arch/x86/include/asm/pgtable.h:850
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/hugetlb.c (ffffffff8140dbd4)
Location: arch/x86/include/asm/pgtable.h:850
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff8143ecd1)
Location: arch/x86/include/asm/pgtable.h:850
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff814609cb)
Location: arch/x86/include/asm/pgtable.h:850
Inline: True
```
```
In mm/hmm.c (ffffffff814707bf)
Location: arch/x86/include/asm/pgtable.h:850
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff814ef566)
Location: arch/x86/include/asm/pgtable.h:850
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
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810578d3)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af277)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff82149c1c)
Location: arch/x86/include/asm/pgtable.h:851
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
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff810cb05b)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d0f15)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In kernel/events/core.c (ffffffff8136d023)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813b139c)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/gup.c (ffffffff813e7567)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff813f1cc2)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/page_vma_mapped.c (ffffffff8140772c)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81408551)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
```
```
In mm/rmap.c (ffffffff8140bf3d)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff814120ed)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/hugetlb.c (ffffffff81440f87)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff81474493)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff8149519e)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
```
```
In mm/hmm.c (ffffffff814a54ef)
Location: arch/x86/include/asm/pgtable.h:851
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff81524d2d)
Location: arch/x86/include/asm/pgtable.h:851
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
Location: arch/x86/include/asm/pgtable.h:1073
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105eb73)
Location: arch/x86/include/asm/pgtable.h:1073
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5e07)
Location: arch/x86/include/asm/pgtable.h:1073
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8222c6cc)
Location: arch/x86/include/asm/pgtable.h:1073
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
Location: arch/x86/include/asm/pgtable.h:1073
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff810d35ab)
Location: arch/x86/include/asm/pgtable.h:1073
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d95f5)
Location: arch/x86/include/asm/pgtable.h:1073
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In kernel/events/core.c (ffffffff81396263)
Location: arch/x86/include/asm/pgtable.h:1073
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813da91c)
Location: arch/x86/include/asm/pgtable.h:1073
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/gup.c (ffffffff814121e5)
Location: arch/x86/include/asm/pgtable.h:1073
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff8141c9ba)
Location: arch/x86/include/asm/pgtable.h:1073
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/page_vma_mapped.c (ffffffff81433dba)
Location: arch/x86/include/asm/pgtable.h:1073
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81434c71)
Location: arch/x86/include/asm/pgtable.h:1073
Inline: True
```
```
In mm/rmap.c (ffffffff814387dd)
Location: arch/x86/include/asm/pgtable.h:1073
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8143e956)
Location: arch/x86/include/asm/pgtable.h:1073
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/hugetlb.c (ffffffff8147b0b7)
Location: arch/x86/include/asm/pgtable.h:1073
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff814a3a42)
Location: arch/x86/include/asm/pgtable.h:1073
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff814c4b06)
Location: arch/x86/include/asm/pgtable.h:1073
Inline: True
```
```
In mm/hmm.c (ffffffff814d64af)
Location: arch/x86/include/asm/pgtable.h:1073
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff815589be)
Location: arch/x86/include/asm/pgtable.h:1073
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000eebd40)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:921
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable
```
```
In mm/memory.c (c0000000003c3934)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:921
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/page_vma_mapped.c (c0000000003d5788)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:921
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (c0000000003d876c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:921
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/huge_memory.c (c000000000442388)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:921
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (c00000000045ea4c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:921
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/userfaultfd.c (c000000000501924)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:921
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (c000000000eca038)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:921
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/mm/fault.c (ffffffe0000b9df8)
Location: arch/riscv/include/asm/pgtable-64.h:31
Inline: True
Inline callers:
  - arch/riscv/mm/fault.c:do_page_fault
```
```
In arch/riscv/mm/hugetlbpage.c (ffffffe0000ba5de)
Location: arch/riscv/include/asm/pgtable-64.h:31
Inline: True
Inline callers:
  - arch/riscv/mm/hugetlbpage.c:pud_huge
```
```
In mm/gup.c (ffffffe000204a12)
Location: arch/riscv/include/asm/pgtable-64.h:31
Inline: True
```
```
In mm/memory.c (ffffffe00020660e)
Location: arch/riscv/include/asm/pgtable-64.h:31
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffe000211124)
Location: arch/riscv/include/asm/pgtable-64.h:31
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffe000211b18)
Location: arch/riscv/include/asm/pgtable-64.h:31
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffe0002126ea)
Location: arch/riscv/include/asm/pgtable-64.h:31
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffe00021375a)
Location: arch/riscv/include/asm/pgtable-64.h:31
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffe0002151f6)
Location: arch/riscv/include/asm/pgtable-64.h:31
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffe0002268fc)
Location: arch/riscv/include/asm/pgtable-64.h:31
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffe00022fbea)
Location: arch/riscv/include/asm/pgtable-64.h:31
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In fs/userfaultfd.c (ffffffe0002a8770)
Location: arch/riscv/include/asm/pgtable-64.h:31
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (0)
Location: arch/riscv/include/asm/pgtable-64.h:31
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
In arch/x86/xen/mmu_pv.c (ffffffff82894755)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810387a4)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e874)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a6afd6)
Location: arch/x86/include/asm/pgtable.h:855
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
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81084148)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81086bf9)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810896a4)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In mm/memory.c (ffffffff8125add9)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/page_vma_mapped.c (ffffffff81269b41)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8126bda3)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff8128d386)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812b101a)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff812c2f2f)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812cee05)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff813328b1)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81a4e95f)
Location: arch/x86/include/asm/pgtable.h:855
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
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105eeb7)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81a274e0)
Location: arch/x86/include/asm/pgtable.h:855
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
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81072d96)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pgtable.c (ffffffff8107587a)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81078430)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/memory.c (ffffffff8124d167)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/page_vma_mapped.c (ffffffff8125be0f)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8125de3c)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff8127f16c)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812a241a)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff812b401a)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/hmm.c (ffffffff812bfa93)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff8132346d)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81a0ba31)
Location: arch/x86/include/asm/pgtable.h:855
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
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038604)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ed24)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ad73e6)
Location: arch/x86/include/asm/pgtable.h:855
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
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff810840f8)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81086ba9)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089654)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In mm/memory.c (ffffffff81258b79)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/page_vma_mapped.c (ffffffff812678e1)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81269b43)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff8128b196)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812aee2a)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff812c0d3f)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812ccc15)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff81330381)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81abad4f)
Location: arch/x86/include/asm/pgtable.h:855
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
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81039604)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81070fa4)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ae38a6)
Location: arch/x86/include/asm/pgtable.h:855
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
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81086238)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (ffffffff81088cd9)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108b8f4)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In mm/memory.c (ffffffff81268579)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/page_vma_mapped.c (ffffffff81277277)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812794b3)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff8129afb6)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812bf17a)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:follow_devmap_pud
```
```
In mm/memory-failure.c (ffffffff812d17ff)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812dd9a5)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
```
```
In fs/userfaultfd.c (ffffffff81342cd8)
Location: arch/x86/include/asm/pgtable.h:855
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81ac719f)
Location: arch/x86/include/asm/pgtable.h:855
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
