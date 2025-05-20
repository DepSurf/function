# Function: <code>__pte</code>

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
In arch/x86/xen/enlighten.c (ffffffff8101b96a)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:set_aliased_prot
```
```
In arch/x86/xen/mmu.c (ffffffff8101deca)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_alloc_pte
```
```
In arch/x86/xen/grant-table.c (ffffffff81023dba)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
```
```
In arch/x86/xen/p2m.c (ffffffff8102462a)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810348a2)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81f6a3a5)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bbef)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8107d513)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pfn_pte
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff81f77fcd)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c3ae)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/pgtable.c (ffffffff8107115c)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:native_set_fixmap
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/kmmio.c (ffffffff8107304e)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81187879)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811bb81a)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:do_set_pte
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vm_insert_page
```
```
In mm/mprotect.c (ffffffff811c88b3)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffffffff811ce0c4)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
```
```
In mm/swapfile.c (ffffffff811d45d1)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811dafc4)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/sparse-vmemmap.c (ffffffff8181f285)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff811e532b)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff811f0d47)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff811f558a)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/userfaultfd.c (ffffffff812079d4)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mfill_zeropage
```
```
In lib/ioremap.c (ffffffff813eb29d)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
```
```
In drivers/xen/xlate_mmu.c (ffffffff814d702d)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/enlighten.c (ffffffff8101bde6)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:set_aliased_prot
```
```
In arch/x86/xen/mmu.c (ffffffff8101e0e9)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pte
```
```
In arch/x86/xen/grant-table.c (ffffffff8102305a)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
```
```
In arch/x86/xen/p2m.c (ffffffff81023f92)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81033aa9)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81f926e7)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bcfe)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81895c9e)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff81fa072b)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8106db28)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff810711d4)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff81074613)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81199e98)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811db932)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vm_insert_page
  - mm/memory.c:unmap_page_range
```
```
In mm/mprotect.c (ffffffff811e4b88)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffffffff811eac70)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
```
```
In mm/madvise.c (ffffffff811eef3b)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff811f2461)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811fc52e)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse-vmemmap.c (ffffffff8189995f)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81203e9f)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff8120ffb1)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812163a5)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8121a4fc)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff8122d852)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In lib/ioremap.c (ffffffff81431627)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
```
```
In drivers/xen/xlate_mmu.c (ffffffff81527df2)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In arch/x86/power/hibernate_64.c (ffffffff8176097b)
Location: arch/x86/include/asm/paravirt.h:375
Inline: True
Inline callers:
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
In arch/x86/xen/enlighten.c (ffffffff8101c5f6)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:set_aliased_prot
```
```
In arch/x86/xen/mmu.c (ffffffff8101e7d9)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pte
```
```
In arch/x86/xen/grant-table.c (ffffffff810237aa)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
```
```
In arch/x86/xen/p2m.c (ffffffff810246c2)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810336cd)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81fcd9b3)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ec78)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff818ca3be)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff81fdbc9c)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff810717b4)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81074d54)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff81078193)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff811a9602)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811eaeb3)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vm_insert_page
  - mm/memory.c:unmap_page_range
```
```
In mm/mprotect.c (ffffffff811f4bb1)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffffffff811fbedd)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
```
```
In mm/madvise.c (ffffffff811ff89d)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff81202e58)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8120d01e)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse-vmemmap.c (ffffffff818ce011)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81215e75)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812220d9)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81228959)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8122e8fe)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/userfaultfd.c (ffffffff8123fd90)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In lib/ioremap.c (ffffffff8144d897)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
```
In drivers/xen/xlate_mmu.c (ffffffff8155435f)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178daf0)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
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
In arch/x86/xen/grant-table.c (ffffffff8101b470)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
```
```
In arch/x86/xen/p2m.c (ffffffff8101d854)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8101f556)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102078d)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81031873)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff820adffd)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e314)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8190193c)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff820bcc6c)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff81070f9c)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81074302)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff81076a04)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In kernel/events/uprobes.c (ffffffff811b0afe)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff811dcea9)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
```
In mm/memory.c (ffffffff811f5fc7)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mprotect.c (ffffffff811ffa70)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffffffff81206bd7)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
```
```
In mm/madvise.c (ffffffff8120a52a)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8120dee2)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81218f1f)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse-vmemmap.c (ffffffff819054a6)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81221585)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8122df4f)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81231fd1)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff812385ad)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff8124bc6f)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In drivers/xen/xlate_mmu.c (ffffffff81568ec9)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In arch/x86/power/hibernate_64.c (ffffffff817abc9e)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff818ed54d)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/xen/grant-table.c (ffffffff8101c0fb)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
```
```
In arch/x86/xen/p2m.c (ffffffff8101e4cf)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff810200a3)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81021bc4)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
```
```
In arch/x86/kernel/ldt.c (ffffffff81031de9)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81033b07)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff826b4558)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81062009)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8198b96c)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff826c3848)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff810766e4)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81079d92)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8107af88)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff8107cdb5)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5fb0)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff811c465e)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff811eedc6)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8120d8f3)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mprotect.c (ffffffff812181a2)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffffffff8121fc2b)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
```
```
In mm/madvise.c (ffffffff81223781)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff81229154)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81233eb5)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse-vmemmap.c (ffffffff8198f4e8)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8123c895)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81249c85)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81252d52)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff81259a98)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/userfaultfd.c (ffffffff8126bfec)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In drivers/xen/xlate_mmu.c (ffffffff815cd079)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In arch/x86/power/hibernate_64.c (ffffffff8182325e)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff81973682)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/xen/grant-table.c (ffffffff8101cb0b)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
```
```
In arch/x86/xen/p2m.c (ffffffff8101f028)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81020b76)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810226fc)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
```
```
In arch/x86/kernel/ldt.c (ffffffff81033082)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034e1f)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff826ddca6)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810650c6)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff819e827e)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff826edaca)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8107907b)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8107ca0d)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8107ddac)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/kmmio.c (ffffffff8107fd69)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efd79)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff811e4bb8)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff8120f905)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8122e6a5)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mprotect.c (ffffffff812392dd)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff81240cc8)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
```
```
In mm/madvise.c (ffffffff8124658c)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8124a466)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81256e44)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse-vmemmap.c (ffffffff819ebd82)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812601aa)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8126d4cc)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812771af)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff8127c419)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff81290a3a)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In drivers/xen/xlate_mmu.c (ffffffff816057be)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d511)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff819cfb1f)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/xen/grant-table.c (ffffffff8101c39b)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
```
```
In arch/x86/xen/p2m.c (ffffffff8101e8ca)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81020476)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102497c)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
```
```
In arch/x86/kernel/ldt.c (ffffffff81034844)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81035fff)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828940ef)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ad36)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81a23840)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff828a465c)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8107f992)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8108343d)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8108492c)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/kmmio.c (ffffffff810868a9)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff828a6601)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6a36)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff811f524d)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff812226c6)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff812425bb)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mprotect.c (ffffffff8124d879)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffffffff81255577)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
```
```
In mm/madvise.c (ffffffff8125a9af)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8125eaca)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8126b40c)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse-vmemmap.c (ffffffff81a26ff0)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812748dd)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81281bbc)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812889f9)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff81290abc)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff812a5a1e)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In drivers/xen/xlate_mmu.c (ffffffff8162089e)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In arch/x86/power/hibernate.c (ffffffff8188f4e6)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a09114)
Location: arch/x86/include/asm/paravirt.h:374
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
In arch/x86/xen/grant-table.c (ffffffff8101def7)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
```
```
In arch/x86/xen/p2m.c (ffffffff81020429)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81021fb6)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025982)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
```
```
In arch/x86/kernel/ldt.c (ffffffff810366ec)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103815f)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff81039852)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff828ab8a0)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e4f2)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a93ba1)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff828bcb25)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8108338d)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/pgtable.c (ffffffff810870a3)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff810885be)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a4b9)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff828bed14)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bf0e0)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff8120cf45)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff81231ccf)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81251389)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mprotect.c (ffffffff8125f87e)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff812678c9)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
```
```
In mm/madvise.c (ffffffff81275af9)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff812797f6)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
```
```
In mm/hugetlb.c (ffffffff812866e6)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse-vmemmap.c (ffffffff81a9788d)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8128f9f8)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff8129dcc8)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a363c)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812a9df1)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812c110f)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In drivers/xen/xlate_mmu.c (ffffffff81654066)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In arch/x86/power/hibernate.c (ffffffff818d94e6)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a78995)
Location: arch/x86/include/asm/paravirt.h:374
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
In arch/x86/xen/grant-table.c (ffffffff8101e877)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
```
```
In arch/x86/xen/p2m.c (ffffffff81020d89)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff810228f6)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025f62)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
```
```
In arch/x86/kernel/ldt.c (ffffffff81036f1c)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103892f)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103a023)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff828ae8ae)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106faa2)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81acb481)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff828c2fc0)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8108445d)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/pgtable.c (ffffffff81087d93)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8108922e)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/kmmio.c (ffffffff8108b129)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff828c50de)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c5562)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff8121a236)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8123fd8f)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8125f939)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mprotect.c (ffffffff8126e08e)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff81276229)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
```
```
In mm/madvise.c (ffffffff81284ac9)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff812892d6)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
```
```
In mm/hugetlb.c (ffffffff812962cb)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse-vmemmap.c (ffffffff81acf162)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8129f788)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812ad578)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b4b3c)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812bb361)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812d305f)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In drivers/xen/xlate_mmu.c (ffffffff81676606)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In arch/x86/power/hibernate.c (ffffffff8190b4e6)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81aafd45)
Location: arch/x86/include/asm/paravirt.h:362
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
pte_t __pte(pteval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81020df7)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
```
```
In arch/x86/xen/p2m.c (ffffffff810235f5)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81024d76)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810271b0)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
```
```
In arch/x86/kernel/ldt.c (ffffffff81038b1a)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:unmap_ldt_struct
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b117)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103cc91)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81047b5b)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076fbf)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81085e1c)
Location: arch/x86/include/asm/paravirt.h:376
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff81088ea0)
Location: arch/x86/include/asm/paravirt.h:376
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a232)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8108bb8c)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e1f9)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:unmap_pte_range
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff8109258d)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/pti.c (ffffffff82ce81aa)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82ce8772)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81246baf)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8126e5ae)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8128fdf0)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pte_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mprotect.c (ffffffff8129e69c)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff812a79e1)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pte_range
```
```
In mm/madvise.c (ffffffff812b6cb8)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff812bbcd5)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812c9854)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7b22)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812d3df8)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812e28d8)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ea0e5)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff812f05c5)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_copy
  - mm/khugepaged.c:__collapse_huge_page_copy
```
```
In mm/userfaultfd.c (ffffffff81307e63)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage_pte
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In lib/ioremap.c (ffffffff815e988e)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pte_range
```
```
In drivers/xen/xlate_mmu.c (ffffffff817270ca)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc4db)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81085e1c-ffffffff81085e29: __pte (STB_LOCAL)
ffffffff81088ea0-ffffffff81088ead: __pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t __pte(pteval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81021671)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
```
```
In arch/x86/xen/p2m.c (ffffffff81023bc5)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff810254e6)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810282c0)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
```
```
In arch/x86/kernel/ldt.c (ffffffff810392aa)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b927)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103d151)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81bd4dd8)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810775ef)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81bd87ce)
Location: arch/x86/include/asm/paravirt.h:372
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff82fd3d38)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a4b4)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8108bbac)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e0c9)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff81091c77)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/pti.c (ffffffff82fd5bc9)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82fd6185)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81251212)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff81278fad)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8129a870)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pte_range
  - mm/memory.c:insert_pfn
```
```
In mm/mprotect.c (ffffffff812a9a5c)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff812b228b)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pte_range
```
```
In mm/ioremap.c (ffffffff812b8134)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_pte_range
```
```
In mm/swapfile.c (ffffffff812c7785)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812d55be)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/sparse-vmemmap.c (ffffffff81c40859)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812df7e8)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812edd0a)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812f52bb)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff81313e58)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In drivers/xen/xlate_mmu.c (ffffffff81743618)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In arch/x86/power/hibernate.c (ffffffff81bd14bb)
Location: arch/x86/include/asm/paravirt.h:372
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81bd87ce-ffffffff81bd87db: __pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t __pte(pteval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff810239f1)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
```
```
In arch/x86/xen/p2m.c (ffffffff81025de8)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff810279aa)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102acb5)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
```
```
In arch/x86/kernel/ldt.c (ffffffff8103addb)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103d2c2)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103e98e)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81bc7227)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107806d)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81bca675)
Location: arch/x86/include/asm/paravirt.h:389
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff831de879)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pgtable.c (ffffffff8108b114)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8108c7ae)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ec8c)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff8109252c)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In arch/x86/mm/pti.c (ffffffff831e0806)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff831e0be0)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff8125530c)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8127df5d)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8129fc8b)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:remap_pfn_range_notrack
```
```
In mm/mprotect.c (ffffffff812aeee7)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff812b795c)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff812ce0fd)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812dc239)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/sparse-vmemmap.c (ffffffff81c328b7)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812e8108)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812f3eb9)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812fb804)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff8131a015)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In drivers/xen/xlate_mmu.c (ffffffff81727004)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In arch/x86/power/hibernate.c (ffffffff81bc34c5)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81bca675-ffffffff81bca682: __pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t __pte(pteval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81027c91)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
```
```
In arch/x86/xen/p2m.c (ffffffff8102a306)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102c02a)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102f2e5)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
```
```
In arch/x86/kernel/ldt.c (ffffffff81040805)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81042dff)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff810446fe)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81c9a820)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81085887)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81c9fb1b)
Location: arch/x86/include/asm/paravirt.h:389
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff832c1bef)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a6b4)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8109bfee)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109e740)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810a231c)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In arch/x86/mm/pti.c (ffffffff832c3ee4)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff832c42b8)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81290d4e)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff812e3281)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:remap_pfn_range_notrack
```
```
In mm/mprotect.c (ffffffff812f06d7)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff812fa08c)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff8131357d)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff813233cf)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/sparse-vmemmap.c (ffffffff8132c597)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_restore_pte
  - mm/sparse-vmemmap.c:vmemmap_remap_pte
  - mm/sparse-vmemmap.c:vmemmap_remap_range
```
```
In mm/ksm.c (ffffffff81330038)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/kfence/core.c (ffffffff8133be28)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_unprotect
  - mm/kfence/core.c:kfence_protect
```
```
In mm/migrate.c (ffffffff8133e8ea)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8134563e)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff81366d4a)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In drivers/xen/xlate_mmu.c (ffffffff817a6084)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In arch/x86/power/hibernate.c (ffffffff81c944d5)
Location: arch/x86/include/asm/paravirt.h:389
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81c9fb1b-ffffffff81c9fb28: __pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t __pte(pteval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8102c111)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
```
```
In arch/x86/xen/p2m.c (ffffffff8102edfc)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81030c5e)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810342ed)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
```
```
In arch/x86/kernel/ldt.c (ffffffff810481b5)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8104ad3b)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/alternative.c (ffffffff8104ccfc)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81e49c8d)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095c31)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81e4f38e)
Location: arch/x86/include/asm/paravirt.h:395
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff834742fd)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pgtable.c (ffffffff810ad925)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff810af5a5)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b2126)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810b68d4)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In arch/x86/mm/pti.c (ffffffff834767fb)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83476c1b)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff812e6051)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff813445f5)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:remap_pfn_range_notrack
```
```
In mm/mprotect.c (ffffffff81353ce6)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff813603e8)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff8137ea61)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81390cb9)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/sparse-vmemmap.c (ffffffff8139c625)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_restore_pte
  - mm/sparse-vmemmap.c:vmemmap_remap_pte
  - mm/sparse-vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/ksm.c (ffffffff813a0a18)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/kfence/core.c (ffffffff813aea70)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_protect_page
  - mm/kfence/core.c:kfence_protect_page
```
```
In mm/migrate.c (ffffffff813b19cf)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff813b7e53)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
```
```
In mm/huge_memory.c (ffffffff813bb61d)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff813e4199)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In drivers/xen/xlate_mmu.c (ffffffff818e0041)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In arch/x86/power/hibernate.c (ffffffff81e43505)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81e4f38e-ffffffff81e4f3a0: __pte (STB_LOCAL)
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
In arch/x86/xen/grant-table.c (ffffffff81033053)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
```
```
In arch/x86/xen/p2m.c (ffffffff81036162)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83e6ebf3)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103bdbe)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff81052f02)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81056c12)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/alternative.c (ffffffff8105910d)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81067f88)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab86a)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff820c73af)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff83e9c0a8)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7ad5)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff810c9a28)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cc9b0)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810d1b20)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In arch/x86/mm/pti.c (ffffffff83e9f54c)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83e9fe07)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff8134fcb0)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff813bc728)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:remap_pfn_range_notrack
```
```
In mm/mprotect.c (ffffffff813ce1ca)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff813dc3c4)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813fd40d)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff814125b0)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/hugetlb_vmemmap.c (ffffffff8141436e)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_restore_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_pte
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff820cb4fd)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8142028e)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/kfence/core.c (ffffffff8142efa4)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_protect_page
  - mm/kfence/core.c:kfence_protect_page
```
```
In mm/migrate.c (ffffffff81432429)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff81439b2a)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
```
```
In mm/huge_memory.c (ffffffff8143dbc8)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff8146bc29)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In drivers/xen/xlate_mmu.c (ffffffff81a344e5)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In arch/x86/power/hibernate.c (ffffffff8201e5ac)
Location: arch/x86/include/asm/paravirt.h:395
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t __pte(pteval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81032ff3)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
```
```
In arch/x86/xen/p2m.c (ffffffff810360e2)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8368fb13)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103a54e)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff81053ee5)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81057beb)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/alternative.c (ffffffff8105a6bb)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81069810)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af42b)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8214b44e)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff836bfb48)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pgtable.c (ffffffff810cb21b)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff810cd0ba)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cffd0)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810d4fd0)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In arch/x86/mm/pti.c (ffffffff836c36d9)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff836c3fae)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81380e49)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff813f1116)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_set_pte
  - mm/memory.c:remap_p4d_range
  - mm/memory.c:restore_exclusive_pte
Direct callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mprotect.c (ffffffff81402a7e)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8140e763)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81410ca4)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81433905)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/swapfile.c:generic_max_swapfile_size
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81445f6f)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/hugetlb_vmemmap.c (ffffffff814478c7)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_restore_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_pte
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff8214f78f)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81454e9e)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/kfence/core.c (ffffffff814647dc)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
```
```
In mm/migrate.c (ffffffff81467ba3)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8146f77b)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81473049)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff814a08a2)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_pte_zeropage
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In drivers/xen/xlate_mmu.c (ffffffff81a7df04)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In arch/x86/power/hibernate.c (ffffffff8209e5a6)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff813e9350-ffffffff813e9368: __pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t __pte(pteval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81039321)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
```
```
In arch/x86/xen/p2m.c (ffffffff8103c2e2)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff838befe3)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81040a0e)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff8105b105)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105ee8b)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/alternative.c (ffffffff81061938)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81070d50)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5fbb)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff8222defe)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff838f0668)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pgtable.c (ffffffff810d376b)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff810d578a)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d86b0)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810dd770)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In arch/x86/mm/pti.c (ffffffff838f4379)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff838f4c2e)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff813aa201)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (0)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
```
```
In mm/memory.c (ffffffff8141b2fe)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - mm/memory.c:set_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:restore_exclusive_pte
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mprotect.c (ffffffff8142f089)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
```
```
In mm/rmap.c (ffffffff8143af6a)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8143eecd)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
```
```
In mm/swapfile.c (ffffffff8146ccf5)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - mm/swapfile.c:generic_max_swapfile_size
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8147f970)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/hugetlb_vmemmap.c (ffffffff81481294)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_restore_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_pte
  - mm/hugetlb_vmemmap.c:vmemmap_split_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff82232658)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8149015e)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/kfence/core.c (ffffffff81493904)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
```
```
In mm/migrate.c (ffffffff8149787b)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8149d620)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a17b1)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff814d205b)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/proc/task_mmu.c (ffffffff8159cd58)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:make_uffd_wp_pte
```
```
In drivers/xen/xlate_mmu.c (ffffffff81ad01e0)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In arch/x86/power/hibernate.c (ffffffff821765a6)
Location: arch/x86/include/asm/paravirt.h:392
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81414000-ffffffff81414018: __pte (STB_LOCAL)
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
In arch/x86/xen/grant-table.c (ffffffff8101e887)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
```
```
In arch/x86/xen/p2m.c (ffffffff81020ee9)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81022a56)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810260c2)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
```
```
In arch/x86/kernel/ldt.c (ffffffff8103707c)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038a8f)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103a183)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff8289c8cd)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ea42)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a6a2f1)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff828adf96)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8108345d)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/pgtable.c (ffffffff81086d93)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff810881ee)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a0e9)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff828b0076)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b04fa)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81212886)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff812383df)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81257f89)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mprotect.c (ffffffff812666de)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff8126e879)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
```
```
In mm/madvise.c (ffffffff8127d119)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff812818b6)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128e8ab)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse-vmemmap.c (ffffffff81a6dfd2)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81297d68)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a5b58)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ad11c)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b3941)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812cb63f)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In drivers/xen/xlate_mmu.c (ffffffff8163c2f6)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In arch/x86/power/hibernate.c (ffffffff818ab4e6)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a4eb95)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
In arch/x86/xen/grant-table.c (ffffffff8101e837)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
```
```
In arch/x86/xen/p2m.c (ffffffff81020d49)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff810228b6)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025f22)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
```
```
In arch/x86/kernel/ldt.c (ffffffff81036edc)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810388ef)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff81039fe3)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff828af890)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106eef2)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ad6701)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff828c0e95)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8108340d)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/pgtable.c (ffffffff81086d43)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8108819e)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a099)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff828c2f75)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c33f9)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81210626)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8123617f)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81255d29)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mprotect.c (ffffffff8126447e)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff8126c619)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
```
```
In mm/madvise.c (ffffffff8127aeb9)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8127f6c6)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128c6bb)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse-vmemmap.c (ffffffff81ada3e2)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81295b78)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a3968)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812aaf2c)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b1751)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812c944f)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In drivers/xen/xlate_mmu.c (ffffffff8166a446)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In arch/x86/power/hibernate.c (ffffffff818fc4e6)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81abaf85)
Location: arch/x86/include/asm/paravirt.h:362
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
In arch/x86/xen/grant-table.c (ffffffff8101ea87)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
```
```
In arch/x86/xen/p2m.c (ffffffff81020f99)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81022c26)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810250a2)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
```
```
In arch/x86/kernel/ldt.c (ffffffff81037edc)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810398ef)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103afe3)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff828af8be)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81071172)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ae2bc1)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff828c3fe0)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8108565f)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/pgtable.c (ffffffff81088e73)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8108a43e)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/kmmio.c (ffffffff8108c339)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff828c60fe)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c659f)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff8121f569)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8124645f)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff812657b9)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mprotect.c (ffffffff81273e3e)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff8127c159)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
```
```
In mm/madvise.c (ffffffff8128aa85)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8128f399)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
```
```
In mm/hugetlb.c (ffffffff8129c4a3)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/sparse-vmemmap.c (ffffffff81ae6898)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812a5988)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812b4178)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812bb27c)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812c1abb)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812da12f)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In drivers/xen/xlate_mmu.c (ffffffff81684a06)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In arch/x86/power/hibernate.c (ffffffff8191d4e6)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81ac73d5)
Location: arch/x86/include/asm/paravirt.h:362
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
