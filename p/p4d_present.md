# Function: <code>p4d_present</code>

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
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff8106d753)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81070364)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81201d55)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
```
```
In fs/userfaultfd.c (ffffffff812a4d05)
Location: arch/x86/include/asm/pgtable.h:813
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
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/include/asm/pgtable.h:821
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff8198c51e)
Location: arch/x86/include/asm/pgtable.h:821
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff81072151)
Location: arch/x86/include/asm/pgtable.h:821
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8107765c)
Location: arch/x86/include/asm/pgtable.h:821
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:821
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff8121a841)
Location: arch/x86/include/asm/pgtable.h:821
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8121c779)
Location: arch/x86/include/asm/pgtable.h:821
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff81232b99)
Location: arch/x86/include/asm/pgtable.h:821
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff8125438f)
Location: arch/x86/include/asm/pgtable.h:821
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In fs/userfaultfd.c (ffffffff812c819d)
Location: arch/x86/include/asm/pgtable.h:821
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff81064e5c)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff819e88ce)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff810751ce)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8107a0cc)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff826f266e)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff8122ecd9)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/page_vma_mapped.c (ffffffff8123c522)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8123e569)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff81255c22)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff81278230)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812889e3)
Location: arch/x86/include/asm/pgtable.h:863
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/userfaultfd.c (ffffffff812f155c)
Location: arch/x86/include/asm/pgtable.h:863
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106aacc)
Location: arch/x86/include/asm/pgtable.h:888
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81a24157)
Location: arch/x86/include/asm/pgtable.h:888
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8107afce)
Location: arch/x86/include/asm/pgtable.h:888
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff810808ac)
Location: arch/x86/include/asm/pgtable.h:888
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828a8f7a)
Location: arch/x86/include/asm/pgtable.h:888
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff81241769)
Location: arch/x86/include/asm/pgtable.h:888
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/page_vma_mapped.c (ffffffff81250938)
Location: arch/x86/include/asm/pgtable.h:888
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81252af9)
Location: arch/x86/include/asm/pgtable.h:888
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff8126a072)
Location: arch/x86/include/asm/pgtable.h:888
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff8128c870)
Location: arch/x86/include/asm/pgtable.h:888
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8129d6e3)
Location: arch/x86/include/asm/pgtable.h:888
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/userfaultfd.c (ffffffff81305f1c)
Location: arch/x86/include/asm/pgtable.h:888
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81a08db8)
Location: arch/x86/include/asm/pgtable.h:888
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e286)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a9482e)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8107e953)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff810843ac)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c15a4)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff812540e9)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/page_vma_mapped.c (ffffffff81262c18)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81264e79)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff812851a5)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812a7553)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812b8a22)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/userfaultfd.c (ffffffff813274af)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81a78b5d)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f836)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81acc10e)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8107f9e3)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff810850ec)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c7a23)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff81262649)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/page_vma_mapped.c (ffffffff812713c8)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81273709)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff81294d45)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812b89f3)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812ca902)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/userfaultfd.c (ffffffff8133a28f)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81aaff0d)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076d37)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81bc4348)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff81086bd0)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ee9f)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff82cec21a)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_epilog
```
```
In mm/memory.c (ffffffff81292549)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/page_vma_mapped.c (ffffffff812a1d5e)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812a48e1)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff812c8380)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812ed5a6)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff81300746)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/userfaultfd.c (ffffffff813722de)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
```
```
In lib/ioremap.c (ffffffff815e9deb)
Location: arch/x86/include/asm/pgtable.h:905
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077367)
Location: arch/x86/include/asm/pgtable.h:904
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81c3d241)
Location: arch/x86/include/asm/pgtable.h:904
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff810884b0)
Location: arch/x86/include/asm/pgtable.h:904
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ec8f)
Location: arch/x86/include/asm/pgtable.h:904
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In kernel/events/core.c (ffffffff8123ca95)
Location: arch/x86/include/asm/pgtable.h:904
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/memory.c (ffffffff8129cdf9)
Location: arch/x86/include/asm/pgtable.h:904
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/page_vma_mapped.c (ffffffff812ad589)
Location: arch/x86/include/asm/pgtable.h:904
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812b0071)
Location: arch/x86/include/asm/pgtable.h:904
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/ioremap.c (ffffffff812b8362)
Location: arch/x86/include/asm/pgtable.h:904
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_page_range
```
```
In mm/hugetlb.c (ffffffff812d3f50)
Location: arch/x86/include/asm/pgtable.h:904
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812f8cc6)
Location: arch/x86/include/asm/pgtable.h:904
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8130c8e6)
Location: arch/x86/include/asm/pgtable.h:904
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/userfaultfd.c (ffffffff8138012e)
Location: arch/x86/include/asm/pgtable.h:904
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077df5)
Location: arch/x86/include/asm/pgtable.h:904
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81c2f5eb)
Location: arch/x86/include/asm/pgtable.h:904
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff81089134)
Location: arch/x86/include/asm/pgtable.h:904
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f822)
Location: arch/x86/include/asm/pgtable.h:904
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In kernel/events/core.c (ffffffff81243daa)
Location: arch/x86/include/asm/pgtable.h:904
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/memory.c (ffffffff812a24d9)
Location: arch/x86/include/asm/pgtable.h:904
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/page_vma_mapped.c (ffffffff812b272f)
Location: arch/x86/include/asm/pgtable.h:904
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812b5669)
Location: arch/x86/include/asm/pgtable.h:904
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:904
Inline: True
```
```
In mm/hugetlb.c (ffffffff812dae39)
Location: arch/x86/include/asm/pgtable.h:904
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812ff218)
Location: arch/x86/include/asm/pgtable.h:904
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff81313056)
Location: arch/x86/include/asm/pgtable.h:904
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/userfaultfd.c (ffffffff813874b7)
Location: arch/x86/include/asm/pgtable.h:904
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff81085603)
Location: arch/x86/include/asm/pgtable.h:875
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8109681f)
Location: arch/x86/include/asm/pgtable.h:875
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff8109858d)
Location: arch/x86/include/asm/pgtable.h:875
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109f2f4)
Location: arch/x86/include/asm/pgtable.h:875
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In kernel/events/core.c (ffffffff8127e71d)
Location: arch/x86/include/asm/pgtable.h:875
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/memory.c (ffffffff812e3849)
Location: arch/x86/include/asm/pgtable.h:875
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/page_vma_mapped.c (ffffffff812f4359)
Location: arch/x86/include/asm/pgtable.h:875
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812f72fb)
Location: arch/x86/include/asm/pgtable.h:875
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:875
Inline: True
```
```
In mm/hugetlb.c (ffffffff81321e6f)
Location: arch/x86/include/asm/pgtable.h:875
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff81348e1d)
Location: arch/x86/include/asm/pgtable.h:875
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8135fb2a)
Location: arch/x86/include/asm/pgtable.h:875
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/userfaultfd.c (ffffffff813d478d)
Location: arch/x86/include/asm/pgtable.h:875
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff810959d3)
Location: arch/x86/include/asm/pgtable.h:873
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810a9148)
Location: arch/x86/include/asm/pgtable.h:873
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff810ab1e9)
Location: arch/x86/include/asm/pgtable.h:873
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b2ef0)
Location: arch/x86/include/asm/pgtable.h:873
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In kernel/events/core.c (ffffffff812d338e)
Location: arch/x86/include/asm/pgtable.h:873
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/memory.c (ffffffff81344be9)
Location: arch/x86/include/asm/pgtable.h:873
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/page_vma_mapped.c (ffffffff81358346)
Location: arch/x86/include/asm/pgtable.h:873
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8135c916)
Location: arch/x86/include/asm/pgtable.h:873
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:873
Inline: True
```
```
In mm/hugetlb.c (ffffffff8138f09b)
Location: arch/x86/include/asm/pgtable.h:873
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff813bf28f)
Location: arch/x86/include/asm/pgtable.h:873
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff813da763)
Location: arch/x86/include/asm/pgtable.h:873
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/userfaultfd.c (ffffffff8145fc39)
Location: arch/x86/include/asm/pgtable.h:873
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab618)
Location: arch/x86/include/asm/pgtable.h:891
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff820c5e39)
Location: arch/x86/include/asm/pgtable.h:891
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff810c358c)
Location: arch/x86/include/asm/pgtable.h:891
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cd8f6)
Location: arch/x86/include/asm/pgtable.h:891
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In kernel/events/core.c (ffffffff8133b604)
Location: arch/x86/include/asm/pgtable.h:891
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/memory.c (ffffffff813bce09)
Location: arch/x86/include/asm/pgtable.h:891
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/page_vma_mapped.c (ffffffff813d2978)
Location: arch/x86/include/asm/pgtable.h:891
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff813d6ff6)
Location: arch/x86/include/asm/pgtable.h:891
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:891
Inline: True
```
```
In mm/hugetlb.c (ffffffff8140db91)
Location: arch/x86/include/asm/pgtable.h:891
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/memory-failure.c (ffffffff81460989)
Location: arch/x86/include/asm/pgtable.h:891
Inline: True
```
```
In fs/userfaultfd.c (ffffffff814ef522)
Location: arch/x86/include/asm/pgtable.h:891
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af1d8)
Location: arch/x86/include/asm/pgtable.h:892
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff82149e99)
Location: arch/x86/include/asm/pgtable.h:892
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff810c6ddc)
Location: arch/x86/include/asm/pgtable.h:892
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d0ec6)
Location: arch/x86/include/asm/pgtable.h:892
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In kernel/events/core.c (ffffffff8136cfe2)
Location: arch/x86/include/asm/pgtable.h:892
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/memory.c (ffffffff813f1b3c)
Location: arch/x86/include/asm/pgtable.h:892
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/page_vma_mapped.c (ffffffff814076b8)
Location: arch/x86/include/asm/pgtable.h:892
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8140bef9)
Location: arch/x86/include/asm/pgtable.h:892
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:892
Inline: True
```
```
In mm/hugetlb.c (ffffffff81440f44)
Location: arch/x86/include/asm/pgtable.h:892
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/memory-failure.c (ffffffff8149515c)
Location: arch/x86/include/asm/pgtable.h:892
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81524ce9)
Location: arch/x86/include/asm/pgtable.h:892
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5d68)
Location: arch/x86/include/asm/pgtable.h:1114
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8222c949)
Location: arch/x86/include/asm/pgtable.h:1114
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff810cf29c)
Location: arch/x86/include/asm/pgtable.h:1114
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d95a6)
Location: arch/x86/include/asm/pgtable.h:1114
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In kernel/events/core.c (ffffffff81396222)
Location: arch/x86/include/asm/pgtable.h:1114
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/memory.c (ffffffff8141c827)
Location: arch/x86/include/asm/pgtable.h:1114
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/page_vma_mapped.c (ffffffff81433d46)
Location: arch/x86/include/asm/pgtable.h:1114
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81438799)
Location: arch/x86/include/asm/pgtable.h:1114
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:1114
Inline: True
```
```
In mm/hugetlb.c (ffffffff8147b074)
Location: arch/x86/include/asm/pgtable.h:1114
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/memory-failure.c (ffffffff814c4ac4)
Location: arch/x86/include/asm/pgtable.h:1114
Inline: True
```
```
In fs/userfaultfd.c (ffffffff8155897a)
Location: arch/x86/include/asm/pgtable.h:1114
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (0)
Location: include/asm-generic/5level-fixup.h:34
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/5level-fixup.h:34
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/5level-fixup.h:34
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/asm-generic/5level-fixup.h:34
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/5level-fixup.h:34
Inline: True
```
```
In lib/ioremap.c (0)
Location: include/asm-generic/5level-fixup.h:34
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_vma_mapped.c (0)
Location: include/asm-generic/5level-fixup.h:34
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/5level-fixup.h:34
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/5level-fixup.h:34
Inline: True
```
```
In lib/ioremap.c (0)
Location: include/asm-generic/5level-fixup.h:34
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
In mm/page_vma_mapped.c (0)
Location: include/asm-generic/5level-fixup.h:34
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/5level-fixup.h:34
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/5level-fixup.h:34
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/asm-generic/5level-fixup.h:34
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/5level-fixup.h:34
Inline: True
```
```
In lib/ioremap.c (0)
Location: include/asm-generic/5level-fixup.h:34
Inline: True
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
Location: include/asm-generic/pgtable-nopud.h:33
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/asm-generic/pgtable-nopud.h:33
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/pgtable-nopud.h:33
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/pgtable-nopud.h:33
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/pgtable-nopud.h:33
Inline: True
```
```
In lib/ioremap.c (0)
Location: include/asm-generic/pgtable-nopud.h:33
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e7d6)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a6af7e)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8107e9e3)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff810840ec)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828b29bb)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff8125ac99)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/page_vma_mapped.c (ffffffff81269a18)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8126bd59)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff8128d325)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812b0fd3)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812c2ee2)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/userfaultfd.c (ffffffff8133286f)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81a4ed5d)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ee95)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81a27485)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8106dd85)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81072d3d)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828aab49)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff8124d067)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/page_vma_mapped.c (ffffffff8125bde0)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8125de04)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff8127f105)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812a23d3)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812b3fed)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/userfaultfd.c (ffffffff8132343a)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81a0be5d)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ec86)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ad738e)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8107e993)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8108409c)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c58ba)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff81258a39)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/page_vma_mapped.c (ffffffff812677b8)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81269af9)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff8128b135)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812aede3)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812c0cf2)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/userfaultfd.c (ffffffff8133033f)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81abb14d)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff81070f06)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ae384e)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff81080a83)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff810861dc)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c8a60)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff81268439)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/page_vma_mapped.c (ffffffff81277152)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81279469)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff8129af55)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/huge_memory.c (ffffffff812bf133)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812d17b2)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/userfaultfd.c (ffffffff81342c96)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffffffff81ac758b)
Location: arch/x86/include/asm/pgtable.h:905
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
</details>
</li>
</ul>

## Differences
