# Function: <code>pgd_present</code>

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
Location: arch/x86/include/asm/pgtable.h:627
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/include/asm/pgtable.h:627
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:627
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable.h:627
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:627
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:627
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/pgtable.h:627
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:627
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:627
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
Location: arch/x86/include/asm/pgtable.h:664
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/include/asm/pgtable.h:664
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:664
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff81069e83)
Location: arch/x86/include/asm/pgtable.h:664
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81073fb6)
Location: arch/x86/include/asm/pgtable.h:664
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:664
Inline: True
```
```
In mm/rmap.c (ffffffff811e770a)
Location: arch/x86/include/asm/pgtable.h:664
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/pgtable.h:664
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:664
Inline: True
```
```
In fs/userfaultfd.c (ffffffff812839ae)
Location: arch/x86/include/asm/pgtable.h:664
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
Location: arch/x86/include/asm/pgtable.h:664
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/include/asm/pgtable.h:664
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:664
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff8106da23)
Location: arch/x86/include/asm/pgtable.h:664
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81077b26)
Location: arch/x86/include/asm/pgtable.h:664
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:664
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff811f6e62)
Location: arch/x86/include/asm/pgtable.h:664
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff811f8a9a)
Location: arch/x86/include/asm/pgtable.h:664
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/pgtable.h:664
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:664
Inline: True
```
```
In fs/userfaultfd.c (ffffffff812974d1)
Location: arch/x86/include/asm/pgtable.h:664
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
In arch/x86/xen/mmu_pv.c (0)
Location: include/asm-generic/pgtable-nop4d.h:22
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:22
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:22
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/asm-generic/pgtable-nop4d.h:22
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: include/asm-generic/pgtable-nop4d.h:22
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/asm-generic/pgtable-nop4d.h:22
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/pgtable-nop4d.h:22
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/pgtable-nop4d.h:22
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:22
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/pgtable-nop4d.h:22
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
In arch/x86/xen/mmu_pv.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/pgtable-nop4d.h:23
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
In arch/x86/xen/mmu_pv.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
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
In arch/x86/xen/mmu_pv.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
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
In arch/x86/xen/mmu_pv.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
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
In arch/x86/xen/mmu_pv.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pgd_present(pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82ccc2f8)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076c89)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81085238)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/fault.c (ffffffff81086b88)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff82cec1e6)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_epilog
```
```
In mm/memory.c (ffffffff812924a5)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
Inline callers:
  - mm/memory.c:__p4d_alloc
```
```
In mm/page_vma_mapped.c (ffffffff812a1cd1)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812a488e)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff812c8331)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812ed558)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff813006f7)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/userfaultfd.c (ffffffff8137228c)
Location: arch/x86/include/asm/pgtable.h:938
Inline: True
```
**Symbols:**

```
ffffffff81085ff6-ffffffff81086008: pgd_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pgd_present(pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82fb8136)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810772b9)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086318)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/fault.c (ffffffff81088468)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In mm/memory.c (ffffffff8129cd55)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - mm/memory.c:__p4d_alloc
```
```
In mm/page_vma_mapped.c (ffffffff812ad4fc)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812b001e)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff812d3f01)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812f8c78)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8130c897)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/userfaultfd.c (ffffffff813800dc)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
```
**Symbols:**

```
ffffffff81bd896a-ffffffff81bd897c: pgd_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pgd_present(pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff831c2799)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077d68)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810870c5)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/fault.c (ffffffff81089120)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In mm/memory.c (ffffffff812a2438)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - mm/memory.c:__p4d_alloc
```
```
In mm/page_vma_mapped.c (ffffffff812b26e8)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812b5649)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff812dae1e)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812ff1fb)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff81313009)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/userfaultfd.c (ffffffff81387499)
Location: arch/x86/include/asm/pgtable.h:937
Inline: True
```
**Symbols:**

```
ffffffff81bca81a-ffffffff81bca82c: pgd_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pgd_present(pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff832a31a5)
Location: arch/x86/include/asm/pgtable.h:908
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81085580)
Location: arch/x86/include/asm/pgtable.h:908
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810963e5)
Location: arch/x86/include/asm/pgtable.h:908
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/fault.c (ffffffff81098579)
Location: arch/x86/include/asm/pgtable.h:908
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In mm/memory.c (ffffffff812e37a8)
Location: arch/x86/include/asm/pgtable.h:908
Inline: True
Inline callers:
  - mm/memory.c:__p4d_alloc
```
```
In mm/page_vma_mapped.c (ffffffff812f42fd)
Location: arch/x86/include/asm/pgtable.h:908
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812f72d8)
Location: arch/x86/include/asm/pgtable.h:908
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff81321e4e)
Location: arch/x86/include/asm/pgtable.h:908
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff81348dfa)
Location: arch/x86/include/asm/pgtable.h:908
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8135fad9)
Location: arch/x86/include/asm/pgtable.h:908
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/userfaultfd.c (ffffffff813d4769)
Location: arch/x86/include/asm/pgtable.h:908
Inline: True
```
**Symbols:**

```
ffffffff81c9fcc0-ffffffff81c9fcd2: pgd_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pgd_present(pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff83452414)
Location: arch/x86/include/asm/pgtable.h:906
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095959)
Location: arch/x86/include/asm/pgtable.h:906
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810a8c78)
Location: arch/x86/include/asm/pgtable.h:906
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/fault.c (ffffffff810ab1d5)
Location: arch/x86/include/asm/pgtable.h:906
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In mm/memory.c (ffffffff81344b47)
Location: arch/x86/include/asm/pgtable.h:906
Inline: True
Inline callers:
  - mm/memory.c:__p4d_alloc
```
```
In mm/page_vma_mapped.c (ffffffff813582fa)
Location: arch/x86/include/asm/pgtable.h:906
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8135c8e8)
Location: arch/x86/include/asm/pgtable.h:906
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff8138f06e)
Location: arch/x86/include/asm/pgtable.h:906
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff813bf25b)
Location: arch/x86/include/asm/pgtable.h:906
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff813da668)
Location: arch/x86/include/asm/pgtable.h:906
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/userfaultfd.c (ffffffff8145fc09)
Location: arch/x86/include/asm/pgtable.h:906
Inline: True
```
**Symbols:**

```
ffffffff810a7f00-ffffffff810a7f1d: pgd_present (STB_LOCAL)
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
In arch/x86/xen/mmu_pv.c (ffffffff83e6f95c)
Location: arch/x86/include/asm/pgtable.h:924
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab59e)
Location: arch/x86/include/asm/pgtable.h:924
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff820c5ffa)
Location: arch/x86/include/asm/pgtable.h:924
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff810c3578)
Location: arch/x86/include/asm/pgtable.h:924
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In mm/memory.c (ffffffff813bcd57)
Location: arch/x86/include/asm/pgtable.h:924
Inline: True
Inline callers:
  - mm/memory.c:__p4d_alloc
```
```
In mm/page_vma_mapped.c (ffffffff813d292c)
Location: arch/x86/include/asm/pgtable.h:924
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff813d6fc8)
Location: arch/x86/include/asm/pgtable.h:924
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff8140db5e)
Location: arch/x86/include/asm/pgtable.h:924
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/memory-failure.c (ffffffff81460958)
Location: arch/x86/include/asm/pgtable.h:924
Inline: True
```
```
In fs/userfaultfd.c (ffffffff814ef4e9)
Location: arch/x86/include/asm/pgtable.h:924
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
In arch/x86/xen/mmu_pv.c (ffffffff8369071c)
Location: arch/x86/include/asm/pgtable.h:925
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af15e)
Location: arch/x86/include/asm/pgtable.h:925
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8214a05a)
Location: arch/x86/include/asm/pgtable.h:925
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff810c6dc8)
Location: arch/x86/include/asm/pgtable.h:925
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In mm/memory.c (ffffffff813f1a7a)
Location: arch/x86/include/asm/pgtable.h:925
Inline: True
Inline callers:
  - mm/memory.c:__p4d_alloc
```
```
In mm/page_vma_mapped.c (ffffffff8140766c)
Location: arch/x86/include/asm/pgtable.h:925
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8140becb)
Location: arch/x86/include/asm/pgtable.h:925
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff81440f11)
Location: arch/x86/include/asm/pgtable.h:925
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/memory-failure.c (ffffffff8149512b)
Location: arch/x86/include/asm/pgtable.h:925
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81524caf)
Location: arch/x86/include/asm/pgtable.h:925
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
In arch/x86/xen/mmu_pv.c (ffffffff838c01ec)
Location: arch/x86/include/asm/pgtable.h:1147
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5cee)
Location: arch/x86/include/asm/pgtable.h:1147
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8222cb0a)
Location: arch/x86/include/asm/pgtable.h:1147
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff810cf288)
Location: arch/x86/include/asm/pgtable.h:1147
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In mm/memory.c (ffffffff8141c72a)
Location: arch/x86/include/asm/pgtable.h:1147
Inline: True
Inline callers:
  - mm/memory.c:__p4d_alloc
```
```
In mm/page_vma_mapped.c (ffffffff81433cfa)
Location: arch/x86/include/asm/pgtable.h:1147
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8143876b)
Location: arch/x86/include/asm/pgtable.h:1147
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff8147b041)
Location: arch/x86/include/asm/pgtable.h:1147
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/memory-failure.c (ffffffff814c4a8d)
Location: arch/x86/include/asm/pgtable.h:1147
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81558940)
Location: arch/x86/include/asm/pgtable.h:1147
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
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/mm/fault.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:29
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:29
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:29
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/pgtable-nop4d-hack.h:29
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000eebc8c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:964
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable
```
```
In mm/memory.c (c0000000003c37ec)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:964
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/page_vma_mapped.c (c0000000003d572c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:964
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (c0000000003d8710)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:964
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/huge_memory.c (c000000000442328)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:964
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (c00000000045e9f0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:964
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/userfaultfd.c (c0000000005018c8)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:964
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In arch/riscv/mm/fault.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
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
In arch/x86/xen/mmu_pv.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
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
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
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
In arch/x86/xen/mmu_pv.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
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
In arch/x86/xen/mmu_pv.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/pgtable-nop4d.h:24
Inline: True
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
