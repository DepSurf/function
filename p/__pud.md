# Function: <code>__pud</code>

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
In arch/x86/xen/mmu.c (ffffffff81f628aa)
Location: arch/x86/include/asm/paravirt.h:565
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034645)
Location: arch/x86/include/asm/paravirt.h:565
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bacb)
Location: arch/x86/include/asm/paravirt.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8107d4c4)
Location: arch/x86/include/asm/paravirt.h:565
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pud_clear
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c226)
Location: arch/x86/include/asm/paravirt.h:565
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pgd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8107137b)
Location: arch/x86/include/asm/paravirt.h:565
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In mm/memory.c (ffffffff811bcf0f)
Location: arch/x86/include/asm/paravirt.h:565
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:__pmd_alloc
```
```
In mm/pgtable-generic.c (ffffffff811d03d5)
Location: arch/x86/include/asm/paravirt.h:565
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff811dd5ea)
Location: arch/x86/include/asm/paravirt.h:565
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8181f450)
Location: arch/x86/include/asm/paravirt.h:565
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
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
In arch/x86/xen/mmu.c (ffffffff81f8ac31)
Location: arch/x86/include/asm/paravirt.h:538
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81033821)
Location: arch/x86/include/asm/paravirt.h:538
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bbbb)
Location: arch/x86/include/asm/paravirt.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff818960eb)
Location: arch/x86/include/asm/paravirt.h:538
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:pud_clear
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c09b)
Location: arch/x86/include/asm/paravirt.h:538
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8107126c)
Location: arch/x86/include/asm/paravirt.h:538
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In mm/memory.c (ffffffff811da9fd)
Location: arch/x86/include/asm/paravirt.h:538
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff811ed585)
Location: arch/x86/include/asm/paravirt.h:538
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff811fb89a)
Location: arch/x86/include/asm/paravirt.h:538
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81899b37)
Location: arch/x86/include/asm/paravirt.h:538
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff81760685)
Location: arch/x86/include/asm/paravirt.h:538
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/xen/mmu.c (ffffffff81fc601f)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103344e)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105eb35)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff818ca808)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:pud_clear
```
```
In arch/x86/mm/pageattr.c (ffffffff8106fcbb)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81074dec)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In mm/memory.c (ffffffff811ea56a)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff811f7975)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff8120c392)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff818ce1e9)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178d7e5)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/xen/mmu_pv.c (ffffffff820a6ed4)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81031610)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e1d7)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81901d81)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:pud_clear
```
```
In arch/x86/mm/pageattr.c (ffffffff8106f3eb)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8107439c)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In mm/memory.c (ffffffff811f55c2)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff81202b05)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff81217d32)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8190567e)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff8123353e)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In arch/x86/power/hibernate_64.c (ffffffff817ab97d)
Location: arch/x86/include/asm/paravirt.h:548
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826a6452)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826ad644)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81033867)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061eae)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8198bdb9)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:pud_clear
```
```
In arch/x86/mm/pageattr.c (ffffffff81074795)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81079f52)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pti.c (ffffffff826c5550)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff8120e4aa)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff8121b875)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff81232a99)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8198f6e8)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff8124f70b)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In arch/x86/power/hibernate_64.c (ffffffff81822eff)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826cf5e0)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826d693e)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034bb8)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81064f49)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff819e86cc)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:pud_clear
```
```
In arch/x86/mm/pageattr.c (ffffffff810771f4)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8107cbf1)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pti.c (ffffffff81083429)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff8122ee91)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff8123d655)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff81255b09)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff819ebf52)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff8127375a)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d1fb)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288560d)
Location: arch/x86/include/asm/paravirt.h:510
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8288c887)
Location: arch/x86/include/asm/paravirt.h:510
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81035d98)
Location: arch/x86/include/asm/paravirt.h:510
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106abb9)
Location: arch/x86/include/asm/paravirt.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81a23e30)
Location: arch/x86/include/asm/paravirt.h:510
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:pud_clear
```
```
In arch/x86/mm/pageattr.c (ffffffff8107d924)
Location: arch/x86/include/asm/paravirt.h:510
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8108361f)
Location: arch/x86/include/asm/paravirt.h:510
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pti.c (ffffffff81089fda)
Location: arch/x86/include/asm/paravirt.h:510
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff81241921)
Location: arch/x86/include/asm/paravirt.h:510
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff81251ba5)
Location: arch/x86/include/asm/paravirt.h:510
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff81269f59)
Location: arch/x86/include/asm/paravirt.h:510
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a271c0)
Location: arch/x86/include/asm/paravirt.h:510
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff81287ae7)
Location: arch/x86/include/asm/paravirt.h:510
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In arch/x86/power/hibernate_64.c (ffffffff8188d0ab)
Location: arch/x86/include/asm/paravirt.h:510
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff8188f3c4)
Location: arch/x86/include/asm/paravirt.h:510
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289c68b)
Location: arch/x86/include/asm/paravirt.h:511
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a3d24)
Location: arch/x86/include/asm/paravirt.h:511
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81037ef8)
Location: arch/x86/include/asm/paravirt.h:511
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e372)
Location: arch/x86/include/asm/paravirt.h:511
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a94150)
Location: arch/x86/include/asm/paravirt.h:511
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:pud_clear
```
```
In arch/x86/mm/pageattr.c (ffffffff81081224)
Location: arch/x86/include/asm/paravirt.h:511
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8108728f)
Location: arch/x86/include/asm/paravirt.h:511
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pti.c (ffffffff8108dd89)
Location: arch/x86/include/asm/paravirt.h:511
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff812542a0)
Location: arch/x86/include/asm/paravirt.h:511
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff81263e76)
Location: arch/x86/include/asm/paravirt.h:511
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff8128508c)
Location: arch/x86/include/asm/paravirt.h:511
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a97a6b)
Location: arch/x86/include/asm/paravirt.h:511
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff812a2260)
Location: arch/x86/include/asm/paravirt.h:511
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In arch/x86/power/hibernate_64.c (ffffffff818d7adb)
Location: arch/x86/include/asm/paravirt.h:511
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff818d93c4)
Location: arch/x86/include/asm/paravirt.h:511
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289f67b)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a6dbe)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810386c8)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f922)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81acba30)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:pud_clear
```
```
In arch/x86/mm/pageattr.c (ffffffff810822e4)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81087f7f)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pti.c (ffffffff8108e9e9)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff81262800)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff812726e6)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff81294c2c)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81acf339)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff812b3610)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In arch/x86/power/hibernate_64.c (ffffffff81909e1b)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff8190b3c4)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pud_t __pud(pudval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82cc5b64)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102a47c)
Location: arch/x86/include/asm/paravirt.h:513
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b1e5)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076e2a)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81bc4b5c)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:pud_clear
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a41f)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c5b5)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In arch/x86/mm/pti.c (ffffffff81094d39)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff81292700)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff812a3486)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff812c8222)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7cf4)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff812e8f38)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - mm/huge_memory.c:insert_pfn_pud
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bba6f5)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc548)
Location: arch/x86/include/asm/paravirt.h:513
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff8102a47c-ffffffff8102a489: __pud (STB_LOCAL)
ffffffff81085e91-ffffffff81085e9e: __pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pud_t __pud(pudval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82fb1458)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81bd2bd8)
Location: arch/x86/include/asm/paravirt.h:435
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b9f5)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107745a)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81c3da55)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:435
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c855)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
```
```
In arch/x86/mm/pti.c (ffffffff810940f9)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff8129cfe6)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff812d5a4e)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81c40a1f)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff812f43a8)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - mm/huge_memory.c:insert_pfn_pud
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bcee25)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81bd1528)
Location: arch/x86/include/asm/paravirt.h:435
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81bd2bd8-ffffffff81bd2be5: __pud (STB_LOCAL)
ffffffff81bd8843-ffffffff81bd8850: __pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pud_t __pud(pudval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff831bb5e3)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81bc4d97)
Location: arch/x86/include/asm/paravirt.h:461
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103d396)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077ee2)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086e5e)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:461
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d275)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
```
```
In arch/x86/mm/pti.c (ffffffff81094a9a)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff812a26c9)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff812dc751)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81bdacd3)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
```
```
In mm/huge_memory.c (ffffffff812fa5fc)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - mm/huge_memory.c:insert_pfn_pud
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bc27dd)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81bc3532)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81bc4d97-ffffffff81bc4da4: __pud (STB_LOCAL)
ffffffff81bca6ea-ffffffff81bca6f7: __pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pud_t __pud(pudval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8329bb17)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81c97573)
Location: arch/x86/include/asm/paravirt.h:461
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81042fdd)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810856f3)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8109616e)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:461
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109caf8)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
```
```
In arch/x86/mm/pti.c (ffffffff810a4a0c)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff812e3a39)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/mremap.c (ffffffff812f1e99)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
```
```
In mm/hugetlb.c (ffffffff81323909)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81cc076e)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
```
```
In mm/huge_memory.c (ffffffff8134445c)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - mm/huge_memory.c:insert_pfn_pud
```
```
In arch/x86/power/hibernate_64.c (ffffffff81c92e9d)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81c94541)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81c97573-ffffffff81c97580: __pud (STB_LOCAL)
ffffffff81c9fb90-ffffffff81c9fb9d: __pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pud_t __pud(pudval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8344a30c)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81e469d1)
Location: arch/x86/include/asm/paravirt.h:467
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8104af10)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095ac0)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810a8a04)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:467
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b0301)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
```
```
In arch/x86/mm/pti.c (ffffffff810b92a4)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/percpu.c (ffffffff81e6c7e9)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
```
```
In mm/memory.c (ffffffff81344dc6)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/mremap.c (ffffffff81355bd7)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
```
```
In mm/hugetlb.c (ffffffff81391481)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81e72b93)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
```
```
In mm/huge_memory.c (ffffffff813b9960)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - mm/huge_memory.c:insert_pfn_pud
```
```
In arch/x86/power/hibernate_64.c (ffffffff81e42836)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81e43586)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81e469d1-ffffffff81e469e3: __pud (STB_LOCAL)
ffffffff810a7d60-ffffffff810a7d72: __pud (STB_LOCAL)
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83e6491c)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e7066c)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81056989)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab705)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff820c693a)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ca98b)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
```
```
In arch/x86/mm/pti.c (ffffffff810d4c16)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/percpu.c (ffffffff8139aed6)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
```
```
In mm/memory.c (ffffffff813bcff6)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/mremap.c (ffffffff813d01ec)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
```
```
In mm/hugetlb.c (ffffffff8140e4a9)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8141bac6)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
```
```
In mm/huge_memory.c (ffffffff8143be47)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - mm/huge_memory.c:insert_pfn_pud
```
```
In arch/x86/power/hibernate_64.c (ffffffff8201d269)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff8201e62d)
Location: arch/x86/include/asm/paravirt.h:467
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83684f9c)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff836914e6)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81057959)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af2c5)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8214a7a6)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cdfb7)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
```
```
In arch/x86/mm/pti.c (ffffffff810d8120)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/percpu.c (ffffffff813cdf96)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
```
```
In mm/memory.c (ffffffff813f1d3c)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/mremap.c (ffffffff81404f4f)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
```
```
In mm/hugetlb.c (ffffffff8144188a)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8144f0c6)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
```
```
In mm/huge_memory.c (ffffffff81471958)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - mm/huge_memory.c:insert_pfn_pud
```
```
In arch/x86/power/hibernate_64.c (ffffffff8209d8f9)
Location: arch/x86/include/asm/paravirt.h:462
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff8209e627)
Location: arch/x86/include/asm/paravirt.h:462
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff838b413c)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff838c0ff6)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105ebf9)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5e55)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8222d256)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d6697)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
```
```
In arch/x86/mm/pti.c (ffffffff810e09a0)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/percpu.c (ffffffff813f8906)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
```
```
In mm/memory.c (ffffffff81414c5f)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - mm/memory.c:pud_populate
```
```
In mm/mremap.c (ffffffff814314cf)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - mm/mremap.c:pud_populate
```
```
In mm/hugetlb.c (ffffffff8147436f)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - mm/hugetlb.c:pud_populate
```
```
In mm/sparse-vmemmap.c (ffffffff81488c86)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
```
```
In mm/huge_memory.c (ffffffff814a110c)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - mm/huge_memory.c:insert_pfn_pud
```
```
In arch/x86/power/hibernate_64.c (ffffffff821750f9)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff82176627)
Location: arch/x86/include/asm/paravirt.h:461
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288d67b)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82894dc7)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038828)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e8c2)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a6a8a0)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:pud_clear
```
```
In arch/x86/mm/pageattr.c (ffffffff810812e4)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81086f7f)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pti.c (ffffffff8108d9a9)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff8125ae50)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff8126ad36)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff8128d20c)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a6e1a9)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff812abbf0)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In arch/x86/power/hibernate_64.c (ffffffff818a91db)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff818ab3c4)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a067b)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7dbe)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038688)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ed72)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ad6cb0)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:pud_clear
```
```
In arch/x86/mm/pageattr.c (ffffffff81081294)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81086f2f)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pti.c (ffffffff8108d959)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff81258bf0)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff81268ad6)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff8128b01c)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81ada5b9)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff812a9a00)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In arch/x86/power/hibernate_64.c (ffffffff818fa83b)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff818fc3c4)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a0680)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7dc4)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81039688)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81070ff2)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ae3170)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:pud_clear
```
```
In arch/x86/mm/pageattr.c (ffffffff810833b4)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8108905f)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_clear_huge
```
```
In arch/x86/mm/pti.c (ffffffff8108fd39)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff812685f0)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff81278466)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pud_clear_bad
```
```
In mm/hugetlb.c (ffffffff8129ae3c)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81ae6a6f)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff812b9852)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
```
In arch/x86/power/hibernate_64.c (ffffffff8191b99b)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff8191d3c4)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
