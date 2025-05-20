# Function: <code>__pmd</code>

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
In arch/x86/xen/mmu.c (ffffffff81f6227f)
Location: arch/x86/include/asm/paravirt.h:525
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_cleanhighmap
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
```
In arch/x86/xen/p2m.c (ffffffff81024b7f)
Location: arch/x86/include/asm/paravirt.h:525
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034793)
Location: arch/x86/include/asm/paravirt.h:525
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bb99)
Location: arch/x86/include/asm/paravirt.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8107d4e3)
Location: arch/x86/include/asm/paravirt.h:525
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
In arch/x86/mm/ioremap.c (ffffffff81f77ed4)
Location: arch/x86/include/asm/paravirt.h:525
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c286)
Location: arch/x86/include/asm/paravirt.h:525
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810713d5)
Location: arch/x86/include/asm/paravirt.h:525
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/kmmio.c (ffffffff81072fe8)
Location: arch/x86/include/asm/paravirt.h:525
Inline: True
```
```
In mm/memory.c (ffffffff811bce48)
Location: arch/x86/include/asm/paravirt.h:525
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:__pte_alloc
  - mm/memory.c:__pte_alloc_kernel
```
```
In mm/pgtable-generic.c (ffffffff811d0425)
Location: arch/x86/include/asm/paravirt.h:525
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/sparse-vmemmap.c (ffffffff8181f387)
Location: arch/x86/include/asm/paravirt.h:525
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff811f33d9)
Location: arch/x86/include/asm/paravirt.h:525
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff811f38f6)
Location: arch/x86/include/asm/paravirt.h:525
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In fs/proc/task_mmu.c (ffffffff81278f7c)
Location: arch/x86/include/asm/paravirt.h:525
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/x86/xen/mmu.c (ffffffff81f8abb8)
Location: arch/x86/include/asm/paravirt.h:498
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_cleanhighmap
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/xen/p2m.c (ffffffff81023ecf)
Location: arch/x86/include/asm/paravirt.h:498
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103396d)
Location: arch/x86/include/asm/paravirt.h:498
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bc86)
Location: arch/x86/include/asm/paravirt.h:498
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81896c27)
Location: arch/x86/include/asm/paravirt.h:498
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
In arch/x86/mm/ioremap.c (ffffffff81fa0636)
Location: arch/x86/include/asm/paravirt.h:498
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c7d6)
Location: arch/x86/include/asm/paravirt.h:498
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff810712c1)
Location: arch/x86/include/asm/paravirt.h:498
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/kmmio.c (ffffffff810745b1)
Location: arch/x86/include/asm/paravirt.h:498
Inline: True
```
```
In mm/memory.c (ffffffff811da309)
Location: arch/x86/include/asm/paravirt.h:498
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff811ed7fc)
Location: arch/x86/include/asm/paravirt.h:498
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81899a56)
Location: arch/x86/include/asm/paravirt.h:498
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812131ba)
Location: arch/x86/include/asm/paravirt.h:498
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81216201)
Location: arch/x86/include/asm/paravirt.h:498
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8121a721)
Location: arch/x86/include/asm/paravirt.h:498
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff812a582c)
Location: arch/x86/include/asm/paravirt.h:498
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff8176063b)
Location: arch/x86/include/asm/paravirt.h:498
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
In arch/x86/xen/mmu.c (ffffffff81fc5fa6)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_cleanhighmap
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/xen/p2m.c (ffffffff810245ff)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81033597)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ec00)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff818cb312)
Location: arch/x86/include/asm/paravirt.h:489
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
In arch/x86/mm/ioremap.c (ffffffff81fdbba7)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81070416)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81074e41)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/kmmio.c (ffffffff81078131)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
```
```
In mm/memory.c (ffffffff811e9e31)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff811f7bcc)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff818ce108)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff81225522)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812287aa)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8122eb2b)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/dax.c (ffffffff8129cf11)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff812bb176)
Location: arch/x86/include/asm/paravirt.h:489
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178d79b)
Location: arch/x86/include/asm/paravirt.h:489
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
In arch/x86/xen/p2m.c (ffffffff8101d7c6)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/xen/mmu_pv.c (ffffffff820a6ea4)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81031749)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e29f)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81902904)
Location: arch/x86/include/asm/paravirt.h:508
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
In arch/x86/mm/ioremap.c (ffffffff820bcb81)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff8106fb42)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff810743f2)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/kmmio.c (ffffffff810769b5)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In mm/memory.c (ffffffff811f4f2a)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff81202dbc)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/rmap.c (ffffffff8120327b)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/sparse-vmemmap.c (ffffffff8190559d)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff81230bf3)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81231e57)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812387f9)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff812abd0e)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff812c6894)
Location: arch/x86/include/asm/paravirt.h:508
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff817ab933)
Location: arch/x86/include/asm/paravirt.h:508
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826a64b8)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff8101e751)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826ad614)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810339c6)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061f8c)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8198c870)
Location: arch/x86/include/asm/paravirt.h:472
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
In arch/x86/mm/ioremap.c (ffffffff826c375d)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81074f78)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81079e95)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/kmmio.c (ffffffff8107cd59)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff826c58a2)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In mm/memory.c (ffffffff8120d024)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff8121b8c5)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff8198f5f4)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff8124e972)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81255c4f)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81259300)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/dax.c (ffffffff812cf5b9)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
```
In arch/x86/power/hibernate_64.c (ffffffff81822eab)
Location: arch/x86/include/asm/paravirt.h:472
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826cf63e)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff8101f165)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826d6910)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034d00)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81065019)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff819e917b)
Location: arch/x86/include/asm/paravirt.h:472
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
In arch/x86/mm/ioremap.c (ffffffff826ed9ae)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff810779c5)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8107cd10)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/kmmio.c (ffffffff8107fdcf)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff826ef97f)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In mm/memory.c (ffffffff8122dbeb)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff8123d940)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff819ebe76)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff81272796)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81279af4)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8127c5cf)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff812f9787)
Location: arch/x86/include/asm/paravirt.h:472
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d1a9)
Location: arch/x86/include/asm/paravirt.h:472
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288566b)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff8101ea06)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8288c859)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81035ee0)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ac89)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81a24ac1)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:pmd_clear
```
```
In arch/x86/mm/ioremap.c (ffffffff828a4540)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff8107e175)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81083721)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/kmmio.c (ffffffff8108690f)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff8108a3a2)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/memory.c (ffffffff8124136e)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/mremap.c (ffffffff8124f47d)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff81251ef0)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81a270e4)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff81286d79)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff8128e0d1)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81290c92)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8130e228)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff8188d059)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff8188f47a)
Location: arch/x86/include/asm/paravirt.h:475
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289c6e9)
Location: arch/x86/include/asm/paravirt.h:476
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff81020563)
Location: arch/x86/include/asm/paravirt.h:476
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a3cf7)
Location: arch/x86/include/asm/paravirt.h:476
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038040)
Location: arch/x86/include/asm/paravirt.h:476
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e441)
Location: arch/x86/include/asm/paravirt.h:476
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a94e95)
Location: arch/x86/include/asm/paravirt.h:476
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
In arch/x86/mm/ioremap.c (ffffffff828bca12)
Location: arch/x86/include/asm/paravirt.h:476
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81081a62)
Location: arch/x86/include/asm/paravirt.h:476
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81087392)
Location: arch/x86/include/asm/paravirt.h:476
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a4eb)
Location: arch/x86/include/asm/paravirt.h:476
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff8108e0f7)
Location: arch/x86/include/asm/paravirt.h:476
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/memory.c (ffffffff81253644)
Location: arch/x86/include/asm/paravirt.h:476
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff812617cb)
Location: arch/x86/include/asm/paravirt.h:476
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff812641d9)
Location: arch/x86/include/asm/paravirt.h:476
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81a97988)
Location: arch/x86/include/asm/paravirt.h:476
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812a1306)
Location: arch/x86/include/asm/paravirt.h:476
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812a8a53)
Location: arch/x86/include/asm/paravirt.h:476
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812aba82)
Location: arch/x86/include/asm/paravirt.h:476
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81334727)
Location: arch/x86/include/asm/paravirt.h:476
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff818d7a89)
Location: arch/x86/include/asm/paravirt.h:476
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff818d947a)
Location: arch/x86/include/asm/paravirt.h:476
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289f6d9)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff81020ec3)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a6d91)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038810)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f9f1)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81acc775)
Location: arch/x86/include/asm/paravirt.h:464
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
In arch/x86/mm/ioremap.c (ffffffff828c2eb9)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81082b22)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81088082)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/kmmio.c (ffffffff8108b15b)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff8108ed94)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/memory.c (ffffffff81261ba4)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff8126ff89)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff81272a49)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81acf256)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812b2726)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812b9fd3)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812bd27c)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813482f7)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81909dc9)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff8190b47a)
Location: arch/x86/include/asm/paravirt.h:464
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
pmd_t __pmd(pmdval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82cc5bc2)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff81022f1d)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102a46f)
Location: arch/x86/include/asm/paravirt.h:478
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b2d3)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076efa)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81bc47a5)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:ident_pmd_init
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:pmd_clear
```
```
In arch/x86/mm/ioremap.c (ffffffff82ce62b1)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a51f)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c241)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pte_range
```
```
In arch/x86/mm/kmmio.c (ffffffff810924e1)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In arch/x86/mm/pti.c (ffffffff8109513d)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/memory.c (ffffffff8128c827)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff8129fe6e)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - mm/mremap.c:move_normal_pmd
```
```
In mm/pgtable-generic.c (ffffffff812a3808)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7c13)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812e7cc6)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812eebb0)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812f29b4)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8138ed77)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bba6a2)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc517)
Location: arch/x86/include/asm/paravirt.h:478
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81022d30-ffffffff81022d3d: __pmd (STB_LOCAL)
ffffffff8102a46f-ffffffff8102a47c: __pmd (STB_LOCAL)
ffffffff81085e6a-ffffffff81085e77: __pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pmd_t __pmd(pmdval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82fb14b6)
Location: arch/x86/include/asm/paravirt.h:420
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff810234ed)
Location: arch/x86/include/asm/paravirt.h:420
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81bd2bcb)
Location: arch/x86/include/asm/paravirt.h:420
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103bae3)
Location: arch/x86/include/asm/paravirt.h:420
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107752a)
Location: arch/x86/include/asm/paravirt.h:420
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81c3d69e)
Location: arch/x86/include/asm/paravirt.h:420
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:ident_pmd_init
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/ioremap.c (ffffffff82fd3c37)
Location: arch/x86/include/asm/paravirt.h:420
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c4e1)
Location: arch/x86/include/asm/paravirt.h:420
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
```
```
In arch/x86/mm/kmmio.c (ffffffff81091b82)
Location: arch/x86/include/asm/paravirt.h:420
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In arch/x86/mm/pti.c (ffffffff81bda261)
Location: arch/x86/include/asm/paravirt.h:420
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/memory.c (ffffffff81297ab9)
Location: arch/x86/include/asm/paravirt.h:420
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/pgtable-generic.c (ffffffff812af0e8)
Location: arch/x86/include/asm/paravirt.h:420
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/sparse-vmemmap.c (ffffffff81c4093e)
Location: arch/x86/include/asm/paravirt.h:420
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812f30b2)
Location: arch/x86/include/asm/paravirt.h:420
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812fa210)
Location: arch/x86/include/asm/paravirt.h:420
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812fcfcb)
Location: arch/x86/include/asm/paravirt.h:420
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813a0469)
Location: arch/x86/include/asm/paravirt.h:420
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bcedd2)
Location: arch/x86/include/asm/paravirt.h:420
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81bd14f7)
Location: arch/x86/include/asm/paravirt.h:420
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81023300-ffffffff8102330d: __pmd (STB_LOCAL)
ffffffff81bd2bcb-ffffffff81bd2bd8: __pmd (STB_LOCAL)
ffffffff81bd881c-ffffffff81bd8829: __pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pmd_t __pmd(pmdval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff831bb641)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff810259a0)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81bc4d7d)
Location: arch/x86/include/asm/paravirt.h:443
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103d484)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077fb1)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086fbe)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:ident_pmd_init
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/ioremap.c (ffffffff81bcb794)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cf20)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810926c1)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In arch/x86/mm/pti.c (ffffffff81bcc385)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/filemap.c (ffffffff8125c372)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/filemap.c:pmd_populate
```
```
In mm/memory.c (ffffffff812a186b)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
Direct callers:
  - mm/memory.c:finish_fault
```
```
In mm/pgtable-generic.c (ffffffff812b4198)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_mkinvalid
```
```
In mm/sparse-vmemmap.c (ffffffff81bdad64)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In mm/migrate.c (ffffffff812f944b)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81300fd3)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81303d40)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813a6b2e)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bc278a)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81bc3501)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81025600-ffffffff8102560d: __pmd (STB_LOCAL)
ffffffff81bc4d7d-ffffffff81bc4d8a: __pmd (STB_LOCAL)
ffffffff81bca6c3-ffffffff81bca6d0: __pmd (STB_LOCAL)
ffffffff8129c250-ffffffff8129c25d: __pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pmd_t __pmd(pmdval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8329bb7a)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff81029eb0)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81c97559)
Location: arch/x86/include/asm/paravirt.h:443
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81042ee1)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810857c2)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810962ce)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:ident_pmd_init
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/ioremap.c (ffffffff81ca0f02)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109c7ac)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810a23e1)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In arch/x86/mm/pti.c (ffffffff81ca2417)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/filemap.c (ffffffff81298222)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/filemap.c:pmd_populate
```
```
In mm/memory.c (ffffffff812df8bc)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
Direct callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:do_set_pmd
```
```
In mm/mremap.c (ffffffff812f206e)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812f5d78)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_mkinvalid
```
```
In mm/sparse-vmemmap.c (ffffffff8132be17)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In mm/huge_memory.c (ffffffff8134ac43)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8134da9b)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813f65be)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81c92e4a)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81c94510)
Location: arch/x86/include/asm/paravirt.h:443
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81029b10-ffffffff81029b1d: __pmd (STB_LOCAL)
ffffffff81c97559-ffffffff81c97566: __pmd (STB_LOCAL)
ffffffff81c9fb69-ffffffff81c9fb76: __pmd (STB_LOCAL)
ffffffff812dcd50-ffffffff812dcd5d: __pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pmd_t __pmd(pmdval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8344a36b)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff8102e98c)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81e469bf)
Location: arch/x86/include/asm/paravirt.h:449
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8104ae1b)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095b8c)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810a8b74)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:ident_pmd_init
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/ioremap.c (ffffffff81e504ae)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff810ad5dd)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810aff58)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810b69c3)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/pti.c (ffffffff81e51af8)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/percpu.c (ffffffff81e6c891)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
```
```
In mm/memory.c (ffffffff8134303f)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:pmd_install
```
```
In mm/mremap.c (ffffffff81355dda)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81359ca2)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_mkinvalid
```
```
In mm/sparse-vmemmap.c (ffffffff8139bbe6)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
```
```
In mm/huge_memory.c (ffffffff813c1dd7)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813c6cd8)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81468cbf)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81e427e2)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81e43555)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff8102e420-ffffffff8102e432: __pmd (STB_LOCAL)
ffffffff81e469bf-ffffffff81e469d1: __pmd (STB_LOCAL)
ffffffff810a7cf0-ffffffff810a7d02: __pmd (STB_LOCAL)
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83e6497e)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff81035986)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e70638)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81056ae2)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab7d3)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff820c73be)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
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
In arch/x86/mm/ioremap.c (ffffffff810c5867)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7720)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ca5db)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810d1cfc)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/pti.c (ffffffff810d4d72)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/percpu.c (ffffffff8139af96)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
```
```
In mm/memory.c (ffffffff813bafe2)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:pmd_install
```
```
In mm/mremap.c (ffffffff813d03fb)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff813d4675)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_mkinvalid
```
```
In mm/hugetlb_vmemmap.c (ffffffff81413496)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff8141bb86)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
```
```
In mm/huge_memory.c (ffffffff81443fb8)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81449132)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:pmd_populate
```
```
In fs/dax.c (ffffffff814f985c)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
```
```
In arch/x86/power/hibernate_64.c (ffffffff8201d215)
Location: arch/x86/include/asm/paravirt.h:449
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff8201e5fc)
Location: arch/x86/include/asm/paravirt.h:449
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83684ffe)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff81035906)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff836914b2)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81057ab1)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af393)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8214b45d)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
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
In arch/x86/mm/ioremap.c (ffffffff810c8f57)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff810cae88)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cdc0c)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810d51ac)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/pti.c (ffffffff810d8272)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/percpu.c (ffffffff813ce056)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In mm/memory.c (ffffffff813efae8)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:pmd_install
```
```
In mm/mremap.c (ffffffff8140516b)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81409662)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/hugetlb_vmemmap.c (ffffffff814469f6)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff8144f186)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In mm/huge_memory.c (ffffffff81479549)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8147e916)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81530ce0)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
```
```
In arch/x86/power/hibernate_64.c (ffffffff8209d8a5)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff8209e5f6)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pmd_t __pmd(pmdval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff838b419e)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff8103be66)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff838c0fc2)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105ed51)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5f23)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8222df0d)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
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
In arch/x86/mm/ioremap.c (ffffffff838f04fd)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pgtable.c (ffffffff810d33d8)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d62ec)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810dd8b5)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In arch/x86/mm/pti.c (ffffffff810e0af2)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/percpu.c (ffffffff813f89c6)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In mm/memory.c (ffffffff8141b13f)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:pmd_install
```
```
In mm/mremap.c (ffffffff8143164b)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81435e52)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/hugetlb_vmemmap.c (ffffffff81480526)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81488d46)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
```
```
In mm/huge_memory.c (ffffffff814a8ac9)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:pmd_modify
Direct callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814af5aa)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:pmd_populate
```
```
In fs/dax.c (ffffffff81565bc0)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
```
```
In arch/x86/power/hibernate_64.c (ffffffff821750a5)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff821765f6)
Location: arch/x86/include/asm/paravirt.h:444
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff8149f230-ffffffff8149f248: __pmd (STB_LOCAL)
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288d6d9)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff81021023)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82894d9a)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038970)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e991)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a6b5e5)
Location: arch/x86/include/asm/paravirt.h:464
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
In arch/x86/mm/ioremap.c (ffffffff828ade8f)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81081b22)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81087082)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a11b)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff8108dd54)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/memory.c (ffffffff8125a1f4)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff812685d9)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff8126b099)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81a6e0c6)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812aad06)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812b25b3)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b585c)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813408d7)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff818a9189)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff818ab47a)
Location: arch/x86/include/asm/paravirt.h:464
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a06d9)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff81020e83)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7d91)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810387d0)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ee41)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ad79f5)
Location: arch/x86/include/asm/paravirt.h:464
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
In arch/x86/mm/ioremap.c (ffffffff828c0d8e)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81081ad2)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81087032)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a0cb)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff8108dd04)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/memory.c (ffffffff81257f94)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff81266379)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff81268e39)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81ada4d6)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812a8b16)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812b03c3)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b366c)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8133e3a7)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff818fa7e9)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff818fc47a)
Location: arch/x86/include/asm/paravirt.h:464
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a06de)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/p2m.c (ffffffff810210d3)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7d97)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810397d0)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810710c1)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ae3eb5)
Location: arch/x86/include/asm/paravirt.h:464
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
In arch/x86/mm/ioremap.c (ffffffff828c3ed9)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81083bf2)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81089162)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/kmmio.c (ffffffff8108c36b)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff810900e4)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In mm/memory.c (ffffffff81267980)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff81275d0a)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff812787c9)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pmd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81ae698c)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812b8e36)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812c0703)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812c3ad3)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8135270c)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff8191b949)
Location: arch/x86/include/asm/paravirt.h:464
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (ffffffff8191d47a)
Location: arch/x86/include/asm/paravirt.h:464
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
