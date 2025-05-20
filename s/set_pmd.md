# Function: <code>set_pmd</code>

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
In arch/x86/xen/mmu.c (ffffffff81f622b8)
Location: arch/x86/include/asm/paravirt.h:514
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_cleanhighmap
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
```
In arch/x86/xen/p2m.c (ffffffff81024b93)
Location: arch/x86/include/asm/paravirt.h:514
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810347fc)
Location: arch/x86/include/asm/paravirt.h:514
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bbad)
Location: arch/x86/include/asm/paravirt.h:514
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8107d4f2)
Location: arch/x86/include/asm/paravirt.h:514
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pmd_clear
  - arch/x86/mm/init_64.c:ident_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:vmemmap_populate
```
```
In arch/x86/mm/ioremap.c (ffffffff81f77ee5)
Location: arch/x86/include/asm/paravirt.h:514
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c297)
Location: arch/x86/include/asm/paravirt.h:514
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810713e1)
Location: arch/x86/include/asm/paravirt.h:514
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/kmmio.c (ffffffff81072ff2)
Location: arch/x86/include/asm/paravirt.h:514
Inline: True
```
```
In mm/memory.c (ffffffff811bce54)
Location: arch/x86/include/asm/paravirt.h:514
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:__pte_alloc
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/pgtable-generic.c (ffffffff811d0431)
Location: arch/x86/include/asm/paravirt.h:514
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff8181f398)
Location: arch/x86/include/asm/paravirt.h:514
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff811f390b)
Location: arch/x86/include/asm/paravirt.h:514
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
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
In arch/x86/xen/mmu.c (ffffffff81f8abc7)
Location: arch/x86/include/asm/paravirt.h:487
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_cleanhighmap
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/xen/p2m.c (ffffffff81023edc)
Location: arch/x86/include/asm/paravirt.h:487
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810339bf)
Location: arch/x86/include/asm/paravirt.h:487
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bc93)
Location: arch/x86/include/asm/paravirt.h:487
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81896c34)
Location: arch/x86/include/asm/paravirt.h:487
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:pmd_clear
```
```
In arch/x86/mm/ioremap.c (ffffffff81fa0640)
Location: arch/x86/include/asm/paravirt.h:487
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c7e0)
Location: arch/x86/include/asm/paravirt.h:487
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff810712d0)
Location: arch/x86/include/asm/paravirt.h:487
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/kmmio.c (ffffffff810745bb)
Location: arch/x86/include/asm/paravirt.h:487
Inline: True
```
```
In mm/memory.c (ffffffff811da464)
Location: arch/x86/include/asm/paravirt.h:487
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff811ed5e1)
Location: arch/x86/include/asm/paravirt.h:487
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81899a60)
Location: arch/x86/include/asm/paravirt.h:487
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff8121620e)
Location: arch/x86/include/asm/paravirt.h:487
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8121a981)
Location: arch/x86/include/asm/paravirt.h:487
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In arch/x86/power/hibernate_64.c (ffffffff8176065b)
Location: arch/x86/include/asm/paravirt.h:487
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
In arch/x86/xen/mmu.c (ffffffff81fc5fb5)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_cleanhighmap
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/xen/p2m.c (ffffffff8102460c)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810335e9)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ec0d)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff818cb31f)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:pmd_clear
```
```
In arch/x86/mm/ioremap.c (ffffffff81fdbbb1)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81070420)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81074e50)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/kmmio.c (ffffffff8107813b)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
```
```
In mm/memory.c (ffffffff811e9f84)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff811f79d1)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff818ce112)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff812287b4)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8122ecd4)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178d7bb)
Location: arch/x86/include/asm/paravirt.h:478
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
In arch/x86/xen/p2m.c (ffffffff8101d7d3)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/xen/mmu_pv.c (ffffffff820a6eb0)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103179f)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e2a9)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81902911)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:pmd_clear
```
```
In arch/x86/mm/ioremap.c (ffffffff820bcb8b)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff8106fb4c)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81074401)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/kmmio.c (ffffffff810769bf)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In mm/memory.c (ffffffff811f51d0)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff81202b61)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff819055a7)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff81231e61)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff81238a0b)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In arch/x86/power/hibernate_64.c (ffffffff817ab953)
Location: arch/x86/include/asm/paravirt.h:497
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826a64c2)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff8101e75b)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826ad620)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81033a1c)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061f96)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8198c87d)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:pmd_clear
```
```
In arch/x86/mm/ioremap.c (ffffffff826c3767)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81074f82)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81079ea4)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/kmmio.c (ffffffff8107cd63)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff826c58ac)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In mm/memory.c (ffffffff8120d2bd)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff8121b8d1)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff8198f5fe)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff81252be7)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8125930d)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In arch/x86/power/hibernate_64.c (ffffffff81822ecb)
Location: arch/x86/include/asm/paravirt.h:461
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826cf64c)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff8101f181)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826d691a)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034d6d)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81065031)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff819e9188)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:pmd_clear
```
```
In arch/x86/mm/ioremap.c (ffffffff826ed9c6)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff810779d2)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8107cd1a)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/kmmio.c (ffffffff8107fddd)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff826ef998)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In mm/memory.c (ffffffff8122de8c)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff8123d6b1)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff819ebe8e)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff81277023)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff8127ca7e)
Location: arch/x86/include/asm/paravirt.h:461
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d1cb)
Location: arch/x86/include/asm/paravirt.h:461
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82885679)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff8101ea22)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8288c863)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81035f4d)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106aca1)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81a24ace)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:pmd_clear
```
```
In arch/x86/mm/ioremap.c (ffffffff828a4558)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff8107e182)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8108372b)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In arch/x86/mm/kmmio.c (ffffffff8108691d)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff8108a3bb)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/memory.c (ffffffff812413c8)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/mremap.c (ffffffff8124f490)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff81251c01)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/rmap.c (ffffffff8125223b)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/sparse-vmemmap.c (ffffffff81a270fc)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff81286db5)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff8128e165)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81290d22)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8130c43f)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81330a25)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff8188d07b)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff8188f489)
Location: arch/x86/include/asm/paravirt.h:464
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289c6f7)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff81020582)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a3d01)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810380ad)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e459)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a94ea2)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:pmd_clear
```
```
In arch/x86/mm/ioremap.c (ffffffff828bca2a)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81081a6f)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8108739c)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a4f9)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff8108e110)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/memory.c (ffffffff81253660)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff812617e2)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff81263ed2)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/rmap.c (ffffffff81264a9f)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/sparse-vmemmap.c (ffffffff81a979a0)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812a1341)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812a8ad8)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812abb3c)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81333981)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8135884c)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff818d7aab)
Location: arch/x86/include/asm/paravirt.h:465
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff818d9489)
Location: arch/x86/include/asm/paravirt.h:465
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289f6e7)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff81020ee2)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a6d9b)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103887d)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106fa09)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81acc782)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:pmd_clear
```
```
In arch/x86/mm/ioremap.c (ffffffff828c2ed1)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81082b2f)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8108808c)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In arch/x86/mm/kmmio.c (ffffffff8108b169)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff8108edad)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/memory.c (ffffffff81261bc0)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff8126ffa0)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff81272742)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/rmap.c (ffffffff81273326)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff81285360)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81acf26e)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812b2761)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812ba058)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812bd336)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81347546)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81370a9c)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff81909deb)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff8190b489)
Location: arch/x86/include/asm/paravirt.h:453
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
void set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82cc5bd3)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff81022f36)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102a462)
Location: arch/x86/include/asm/paravirt.h:467
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b33f)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076f12)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81bc47bd)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:ident_pmd_init
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:pmd_clear
```
```
In arch/x86/mm/ioremap.c (ffffffff82ce62c9)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a529)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c24e)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pte_range
```
```
In arch/x86/mm/kmmio.c (ffffffff810924fd)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In arch/x86/mm/pti.c (ffffffff81095156)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/memory.c (ffffffff8128c898)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff8129fe81)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - mm/mremap.c:move_normal_pmd
  - mm/mremap.c:move_normal_pmd
```
```
In mm/pgtable-generic.c (ffffffff812a34f2)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/rmap.c (ffffffff812a3f01)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812b7957)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7c2b)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812e7d00)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812eec36)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812f2a30)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8138d929)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813b8f52)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bba6c5)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc529)
Location: arch/x86/include/asm/paravirt.h:467
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81022d20-ffffffff81022d2d: set_pmd (STB_LOCAL)
ffffffff8102a462-ffffffff8102a46f: set_pmd (STB_LOCAL)
ffffffff81085e5d-ffffffff81085e6a: set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82fb14c7)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff81023506)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81bd2bbe)
Location: arch/x86/include/asm/paravirt.h:415
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103bb4f)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077542)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81c3d6b6)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:ident_pmd_init
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/ioremap.c (ffffffff82fd3c4f)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a7ef)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c4ee)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In arch/x86/mm/kmmio.c (ffffffff81091b9e)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In arch/x86/mm/pti.c (ffffffff81bda27a)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/memory.c (ffffffff81297b23)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff812ab2e9)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812aedd6)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/rmap.c (ffffffff812afc0b)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812c2892)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81c40956)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812f30ec)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812fa292)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812fd044)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8139f3a9)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813ca989)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bcedf5)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81bd1509)
Location: arch/x86/include/asm/paravirt.h:415
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810232f0-ffffffff810232fd: set_pmd (STB_LOCAL)
ffffffff81bd2bbe-ffffffff81bd2bcb: set_pmd (STB_LOCAL)
ffffffff81bd880f-ffffffff81bd881c: set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff831bb652)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff810259b9)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81bc4d70)
Location: arch/x86/include/asm/paravirt.h:438
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103d4f0)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077fca)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086fd8)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:ident_pmd_init
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/ioremap.c (ffffffff81bcb7ad)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff8108b41f)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cf2a)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In arch/x86/mm/kmmio.c (ffffffff810926dd)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In arch/x86/mm/pti.c (ffffffff81bcc39e)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/filemap.c (ffffffff8125c38e)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - mm/filemap.c:pmd_populate
```
```
In mm/memory.c (ffffffff812a1c1c)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff812b06e8)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812b4306)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/rmap.c (ffffffff812b51ac)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812c9718)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81bdad7d)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
```
```
In mm/migrate.c (ffffffff812f9485)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff8130106d)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
Direct callers:
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81303db9)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813a6116)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813d19ed)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bc27ad)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81bc3513)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810255f0-ffffffff810255fd: set_pmd (STB_LOCAL)
ffffffff81bc4d70-ffffffff81bc4d7d: set_pmd (STB_LOCAL)
ffffffff81bca6b6-ffffffff81bca6c3: set_pmd (STB_LOCAL)
ffffffff812f99d0-ffffffff812f99dd: set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8329bb8b)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff81029ec9)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81c9754c)
Location: arch/x86/include/asm/paravirt.h:438
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81042f5c)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810857db)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810962e8)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:ident_pmd_init
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/ioremap.c (ffffffff81ca0f1b)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a9bf)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109c7b6)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In arch/x86/mm/kmmio.c (ffffffff810a23fd)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In arch/x86/mm/pti.c (ffffffff81ca2430)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/filemap.c (ffffffff8129823e)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - mm/filemap.c:pmd_populate
```
```
In mm/memory.c (ffffffff812e2bec)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff812f2006)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812f5ee6)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/rmap.c (ffffffff812f6d48)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8130e73a)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff8132be30)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
```
```
In mm/huge_memory.c (ffffffff8134acdd)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8134db1b)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813f5b86)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81422eed)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff81c92e6d)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81c94522)
Location: arch/x86/include/asm/paravirt.h:438
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81029b00-ffffffff81029b0d: set_pmd (STB_LOCAL)
ffffffff81c9754c-ffffffff81c97559: set_pmd (STB_LOCAL)
ffffffff81c9fb5c-ffffffff81c9fb69: set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8344a37b)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff8102e9a3)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81e46999)
Location: arch/x86/include/asm/paravirt.h:444
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8104ae93)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095ba4)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810a8b8d)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:ident_pmd_init
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/ioremap.c (ffffffff81e504c6)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff810adcad)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810aff5e)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In arch/x86/mm/kmmio.c (ffffffff810b69d0)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/pti.c (ffffffff81e51b10)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/percpu.c (ffffffff81e6c8a9)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In mm/memory.c (ffffffff813430a3)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:pmd_install
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff81355d75)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81359e64)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/rmap.c (ffffffff8135b245)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In mm/madvise.c (ffffffff81377b41)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff8139bbfe)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In mm/huge_memory.c (ffffffff813c1e78)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
Direct callers:
  - mm/huge_memory.c:set_pmd_migration_entry
```
```
In mm/khugepaged.c (ffffffff813c6d48)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81468cc8)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8149ad7c)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff81e42807)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81e43566)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff8102e3f0-ffffffff8102e416: set_pmd (STB_LOCAL)
ffffffff81e46999-ffffffff81e469bf: set_pmd (STB_LOCAL)
ffffffff810a7cc0-ffffffff810a7ce6: set_pmd (STB_LOCAL)
ffffffff813b84e0-ffffffff813b8506: set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83e6498b)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff8103599a)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e70640)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81056b5a)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab7e8)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff820c73c7)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:ident_pmd_init
```
```
In arch/x86/mm/ioremap.c (ffffffff810c587c)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7ed3)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ca5e1)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In arch/x86/mm/kmmio.c (ffffffff810d1cde)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/pti.c (ffffffff810d4d87)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/percpu.c (ffffffff8139afab)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In mm/memory.c (ffffffff813bb055)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:pmd_install
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff813d039b)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff813d4884)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/rmap.c (ffffffff813d6143)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In mm/madvise.c (ffffffff813f52e3)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb_vmemmap.c (ffffffff814134ab)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff8141bb9b)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In mm/huge_memory.c (ffffffff81444096)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
Direct callers:
  - mm/huge_memory.c:set_pmd_migration_entry
```
```
In mm/khugepaged.c (ffffffff814491aa)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:pmd_populate
```
```
In fs/dax.c (ffffffff814f9862)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
```
```
In fs/proc/task_mmu.c (ffffffff8152f2b9)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff8201d230)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff8201e60a)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff8143a630-ffffffff8143a656: set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8368500b)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff8103591a)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff836914ba)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81057b26)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af3a8)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8214b466)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:ident_pmd_init
```
```
In arch/x86/mm/ioremap.c (ffffffff810c8f6c)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff810cb613)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cdc12)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In arch/x86/mm/kmmio.c (ffffffff810d5195)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/pti.c (ffffffff810d8287)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/percpu.c (ffffffff813ce06b)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
```
```
In mm/memory.c (ffffffff813efb56)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:pmd_install
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff8140510b)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81409254)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/rmap.c (ffffffff8140b247)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
```
```
In mm/madvise.c (ffffffff81428496)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb_vmemmap.c (ffffffff81446a0b)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff8144f19b)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
```
```
In mm/huge_memory.c (ffffffff8147962b)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
Direct callers:
  - mm/huge_memory.c:set_pmd_migration_entry
```
```
In mm/khugepaged.c (ffffffff8147e99b)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81530ce6)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
```
```
In fs/proc/task_mmu.c (ffffffff8156757d)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff8209d8c0)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff8209e604)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff8146ff70-ffffffff8146ff96: set_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_pmd(pmd_t *pmdp, pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff838b41ab)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff8103be7a)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff838c0fca)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105edc6)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5f38)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8222df16)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:ident_pmd_init
```
```
In arch/x86/mm/ioremap.c (ffffffff838f0512)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pgtable.c (ffffffff810d3b73)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d62f2)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In arch/x86/mm/kmmio.c (ffffffff810dd876)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In arch/x86/mm/pti.c (ffffffff810e0b07)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/percpu.c (ffffffff813f89db)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
```
```
In mm/memory.c (ffffffff8141b1b3)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:pmd_install
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff814315eb)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81435a44)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/rmap.c (ffffffff81437b9a)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
```
```
In mm/madvise.c (ffffffff81461d91)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb_vmemmap.c (ffffffff8148053b)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81488d5b)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
```
```
In mm/huge_memory.c (ffffffff814a8bc1)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
Direct callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814af64e)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:pmd_populate
```
```
In fs/dax.c (ffffffff81565bc6)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
```
```
In fs/proc/task_mmu.c (ffffffff8159db23)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff821750c0)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff82176604)
Location: arch/x86/include/asm/paravirt.h:439
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff8149f1f0-ffffffff8149f216: set_pmd (STB_LOCAL)
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
In arch/arm64/mm/mmu.c (ffff8000100af428)
Location: arch/arm64/include/asm/pgtable.h:469
Inline: True
Inline callers:
  - arch/arm64/mm/mmu.c:pmd_clear_huge
  - arch/arm64/mm/mmu.c:pmd_set_huge
  - arch/arm64/mm/mmu.c:init_pmd
  - arch/arm64/mm/mmu.c:early_fixmap_init
```
```
In virt/kvm/arm/mmu.c (ffff8000100cb35c)
Location: arch/arm64/include/asm/pgtable.h:469
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
```
```
In mm/memory.c (ffff8000102f8fd0)
Location: arch/arm64/include/asm/pgtable.h:469
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffff800010307f9c)
Location: arch/arm64/include/asm/pgtable.h:469
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffff800010da0e94)
Location: arch/arm64/include/asm/pgtable.h:469
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffff800010355e80)
Location: arch/arm64/include/asm/pgtable.h:469
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffff80001035e940)
Location: arch/arm64/include/asm/pgtable.h:469
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
Location: arch/riscv/include/asm/pgtable.h:138
Inline: True
```
```
In mm/memory.c (ffffffe0002090ae)
Location: arch/riscv/include/asm/pgtable.h:138
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffe000212e66)
Location: arch/riscv/include/asm/pgtable.h:138
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffe00004904c)
Location: arch/riscv/include/asm/pgtable.h:138
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288d6e7)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff81021042)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82894da4)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810389dd)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e9a9)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a6b5f2)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:pmd_clear
```
```
In arch/x86/mm/ioremap.c (ffffffff828adea7)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81081b2f)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8108708c)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a129)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff8108dd6d)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/memory.c (ffffffff8125a210)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff812685f0)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff8126ad92)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/rmap.c (ffffffff8126b976)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8127d9b0)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81a6e0de)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812aad41)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812b2638)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b5916)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8133fb26)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8136907c)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff818a91ab)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff818ab489)
Location: arch/x86/include/asm/paravirt.h:453
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a06e7)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff81020ea2)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7d9b)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103883d)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ee59)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ad7a02)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:pmd_clear
```
```
In arch/x86/mm/ioremap.c (ffffffff828c0da6)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81081adf)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8108703c)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a0d9)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff8108dd1d)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/memory.c (ffffffff81257fb0)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff81266390)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff81268b32)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/rmap.c (ffffffff81269716)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8127b750)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81ada4ee)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812a8b51)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812b0448)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b3726)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8133d5f6)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81366b4c)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff818fa80b)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff818fc489)
Location: arch/x86/include/asm/paravirt.h:453
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a06ec)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff810210f2)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7da1)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103983d)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810710d9)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ae3ec2)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:pmd_clear
```
```
In arch/x86/mm/ioremap.c (ffffffff828c3ef1)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81083bff)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8108916c)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmdp_set_access_flags
```
```
In arch/x86/mm/kmmio.c (ffffffff8108c379)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff810900fd)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/memory.c (ffffffff8126799c)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff81275d21)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff812784c2)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/rmap.c (ffffffff8127922f)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8128b722)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81ae69a4)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812b8e71)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812c0788)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812c3b8d)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8135050c)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8137a1a2)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff8191b96b)
Location: arch/x86/include/asm/paravirt.h:453
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff8191d489)
Location: arch/x86/include/asm/paravirt.h:453
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
