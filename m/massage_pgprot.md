# Function: <code>massage_pgprot</code>

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
In arch/x86/xen/enlighten.c (ffffffff8101b950)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:set_aliased_prot
```
```
In arch/x86/xen/setup.c (0)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
```
```
In arch/x86/xen/mmu.c (ffffffff8101deb0)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:set_pte_mfn
```
```
In arch/x86/xen/grant-table.c (0)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
```
```
In arch/x86/xen/p2m.c (ffffffff81024610)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff8107d503)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff81f77fc1)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c36a)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
```
In arch/x86/mm/pgtable.c (ffffffff81071145)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:native_set_fixmap
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In kernel/events/uprobes.c (ffffffff81187867)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811bb800)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vm_insert_page
```
```
In mm/mprotect.c (ffffffff811c84df)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffffffff811cdecd)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
```
```
In mm/swapfile.c (ffffffff811d45bd)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811dafaa)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/sparse-vmemmap.c (0)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
```
```
In mm/ksm.c (ffffffff811e5855)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff811f0d33)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff811f43b7)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/userfaultfd.c (ffffffff812079bf)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mfill_zeropage
```
```
In lib/ioremap.c (ffffffff813eb0b1)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: arch/x86/include/asm/pgtable.h:344
Inline: True
```
```
In drivers/xen/xlate_mmu.c (ffffffff814d7015)
Location: arch/x86/include/asm/pgtable.h:344
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
In arch/x86/xen/enlighten.c (ffffffff8101bdc4)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:set_aliased_prot
```
```
In arch/x86/xen/setup.c (ffffffff81f88e8f)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu.c (ffffffff8101dd6c)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:set_pte_mfn
```
```
In arch/x86/xen/grant-table.c (ffffffff81022fbb)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/p2m.c (ffffffff81023f72)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/kernel/tboot.c (ffffffff81f926d3)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bcd6)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8107efe0)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff81fa071c)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8106dfa5)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810711bf)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In kernel/events/uprobes.c (ffffffff81199e7f)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811db924)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vm_insert_page
```
```
In mm/mprotect.c (ffffffff811e474e)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffffffff811eab0e)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
```
```
In mm/swapfile.c (ffffffff811f2445)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811fc42b)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/sparse-vmemmap.c (ffffffff81899944)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8120441f)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff812131a7)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81216390)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8121a70e)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff8122d83b)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In lib/ioremap.c (ffffffff81431404)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff8151749d)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xlate_mmu.c (ffffffff81527dd5)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/enlighten.c (ffffffff8101c5d4)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:set_aliased_prot
```
```
In arch/x86/xen/setup.c (ffffffff81fc4283)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu.c (ffffffff8101e45c)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:set_pte_mfn
```
```
In arch/x86/xen/grant-table.c (ffffffff8102370b)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/p2m.c (ffffffff810246a2)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/kernel/tboot.c (ffffffff81fcd99f)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ec50)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81083690)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff81fdbc8d)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff81071c15)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff81074d3f)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In kernel/events/uprobes.c (ffffffff811a95ee)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811eae92)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vm_insert_page
```
```
In mm/mprotect.c (ffffffff811f476e)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffffffff811fbd03)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
```
```
In mm/swapfile.c (ffffffff81202e3c)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8120cf1b)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/sparse-vmemmap.c (ffffffff818cdff6)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81216331)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8122550b)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8122893d)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8122eb18)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/userfaultfd.c (ffffffff8123fd79)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff8129cf03)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In lib/ioremap.c (ffffffff8144d674)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
```
In drivers/xen/balloon.c (ffffffff815438ce)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xlate_mmu.c (ffffffff81554342)
Location: arch/x86/include/asm/pgtable.h:373
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/mmu.c (ffffffff8101a981)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
```
```
In arch/x86/xen/grant-table.c (ffffffff8101b3ed)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff820a4105)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/p2m.c (ffffffff8101d835)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8101f544)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81021b18)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In arch/x86/kernel/tboot.c (ffffffff820adfe9)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e2ec)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106ce81)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff820bcc5d)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8107132b)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810742f2)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In kernel/events/uprobes.c (ffffffff811b0aef)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff811dce99)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
```
In mm/memory.c (ffffffff811f5fab)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mprotect.c (ffffffff811ffa4d)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffffffff81206b89)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
```
```
In mm/swapfile.c (ffffffff8120ded3)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81218f00)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/sparse-vmemmap.c (ffffffff8190548b)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81221b87)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81230be5)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81231fc1)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812387eb)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff8124bc61)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff812abd00)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
```
In drivers/xen/balloon.c (ffffffff8155777d)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xlate_mmu.c (ffffffff81568eba)
Location: arch/x86/include/asm/pgtable.h:504
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff818ed522)
Location: arch/x86/include/asm/pgtable.h:504
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
In arch/x86/xen/mmu.c (ffffffff8101b281)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
```
```
In arch/x86/xen/grant-table.c (ffffffff8101c074)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff826aa7ef)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/p2m.c (ffffffff8101e4ba)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81020091)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102261c)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In arch/x86/kernel/ldt.c (ffffffff81031dce)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff826b4545)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061fe5)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81071ba0)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff826c3839)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff81076aa7)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff81079d82)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8107af75)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5fa0)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff811c464e)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff811eedb6)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8120d8e3)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mprotect.c (ffffffff812180cc)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffffffff8121fbdd)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
```
```
In mm/swapfile.c (ffffffff81229145)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81233ea0)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/sparse-vmemmap.c (ffffffff8198f4cd)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8123ce75)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8124e964)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81255c41)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81259c54)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/userfaultfd.c (ffffffff8126bfde)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff812cf5ab)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
```
In drivers/xen/balloon.c (ffffffff815bb8c1)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xlate_mmu.c (ffffffff815cd06a)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff81973657)
Location: arch/x86/include/asm/pgtable.h:519
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
In arch/x86/xen/mmu.c (ffffffff8101bc41)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_pfn_pte_fn
```
```
In arch/x86/xen/grant-table.c (ffffffff8101ca68)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff826d3cc9)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/p2m.c (ffffffff8101f01b)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81020be6)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81024e4a)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff826ddc99)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810650bb)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81074899)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff826edabd)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff810795ae)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff8107ca07)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8107dda0)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efd59)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff811e4bac)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff8120f8f9)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8122e66d)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mmap.c (ffffffff81236a74)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
```
```
In mm/mprotect.c (ffffffff812392a5)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/pgtable-generic.c (0)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
```
```
In mm/vmalloc.c (ffffffff81240cb3)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
```
```
In mm/swapfile.c (ffffffff8124a466)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81256e06)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/sparse-vmemmap.c (ffffffff819ebd59)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81260590)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81272796)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81279af4)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8127c5cf)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff81290a3a)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff812f977b)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff815f3e23)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xlate_mmu.c (ffffffff816057b2)
Location: arch/x86/include/asm/pgtable.h:519
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff819cfb11)
Location: arch/x86/include/asm/pgtable.h:519
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
In arch/x86/xen/grant-table.c (ffffffff8101c2f8)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff82889d5c)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/p2m.c (ffffffff8101e8c3)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff810204e6)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81021621)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828940e2)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ad2b)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8107a789)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (ffffffff828a464f)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8107ff17)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff81083437)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff81084920)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff828a65de)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6a16)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff811f5345)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff812226c6)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8124257c)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mmap.c (ffffffff8124a324)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
```
```
In mm/mprotect.c (ffffffff8124d83a)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/pgtable-generic.c (0)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
```
```
In mm/vmalloc.c (ffffffff81255575)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
```
```
In mm/swapfile.c (ffffffff8125eabe)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8126b3c6)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/sparse-vmemmap.c (ffffffff81a26fc7)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81274ce4)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81286d79)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8128e0d1)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81290c87)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff812a5a13)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff8130e228)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
```
```
In drivers/xen/mem-reservation.c (ffffffff8160fec1)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
```
In drivers/xen/xlate_mmu.c (ffffffff81620892)
Location: arch/x86/include/asm/pgtable.h:521
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff81a09112)
Location: arch/x86/include/asm/pgtable.h:521
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
In arch/x86/xen/grant-table.c (ffffffff8101de68)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff828a1115)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/p2m.c (ffffffff81020422)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81022024)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102323c)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff81039846)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff828ab893)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e4f2)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e4e0)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff810839b2)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/pgtable.c (ffffffff8108709c)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff810885b2)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a5ce)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff828becf2)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bf0bf)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff8120d021)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff81231ccf)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81251336)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
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
In mm/mmap.c (ffffffff8125c670)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
```
```
In mm/mprotect.c (ffffffff8125f839)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/pgtable-generic.c (ffffffff812641d9)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/vmalloc.c (ffffffff812678c7)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In mm/swapfile.c (ffffffff812797f6)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128669a)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/sparse-vmemmap.c (ffffffff81a97864)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8128f7c4)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a1306)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a8a53)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812aba76)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff812c110f)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff81334727)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In drivers/xen/mem-reservation.c (ffffffff81643cf6)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
```
In drivers/xen/xlate_mmu.c (ffffffff8165405a)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff81a78987)
Location: arch/x86/include/asm/pgtable.h:538
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
In arch/x86/xen/grant-table.c (ffffffff8101e7e8)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff828a41d5)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/p2m.c (ffffffff81020d82)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81022964)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023b7c)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103a017)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff828ae8a1)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106faa2)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107f570)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff81084a82)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/pgtable.c (ffffffff81087d8c)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff81089222)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/kmmio.c (ffffffff8108b23e)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff828c50d3)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c5555)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff8121a3b4)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8123fd8f)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8125f8e6)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
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
In mm/mmap.c (ffffffff8126add0)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
```
```
In mm/mprotect.c (ffffffff8126e049)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/pgtable-generic.c (ffffffff81272a49)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/vmalloc.c (ffffffff81276227)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In mm/swapfile.c (ffffffff812892d6)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In mm/hugetlb.c (ffffffff8129627f)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/sparse-vmemmap.c (ffffffff81acf156)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8129f54b)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812b2726)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b9fd3)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812bd27c)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff812d305f)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff813482f7)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In drivers/xen/mem-reservation.c (ffffffff816662a6)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
```
In drivers/xen/xlate_mmu.c (ffffffff816765fa)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff81aafd37)
Location: arch/x86/include/asm/pgtable.h:538
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
In arch/x86/xen/grant-table.c (ffffffff81020d72)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff82cca74d)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_update_mem_tables
```
```
In arch/x86/xen/p2m.c (ffffffff810235e9)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81024de4)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102628c)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103cc85)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81047b4e)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076fb3)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81085f8b)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a228)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8108bb80)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e1f9)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810924e1)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In arch/x86/mm/pti.c (ffffffff82ce819d)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82ce8765)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81246d2b)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8126e5a2)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8128fd9d)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pte_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/mmap.c (ffffffff8129cff0)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
```
```
In mm/mprotect.c (ffffffff8129e657)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/pgtable-generic.c (ffffffff812a3808)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/vmalloc.c (ffffffff812a79d8)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pte_range
```
```
In mm/swapfile.c (ffffffff812bbcc9)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812c9809)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7b16)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812d3b99)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812e7cc6)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812eebb0)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812f29a8)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff81307e57)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage_pte
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/dax.c (ffffffff8138ed77)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
```
```
In lib/ioremap.c (ffffffff815e9885)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pte_range
```
```
In drivers/xen/mem-reservation.c (ffffffff817159ef)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
```
In drivers/xen/xlate_mmu.c (ffffffff817270be)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/grant-table.c (ffffffff810215f4)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff82fb65bb)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_update_mem_tables
```
```
In arch/x86/xen/p2m.c (ffffffff81023bb9)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81025554)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102699c)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103d145)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81bd4dcb)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810775e3)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81bd88ff)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a4ad)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8108bba0)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e0c9)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff81091b82)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In arch/x86/mm/pti.c (ffffffff82fd5bbc)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82fd6178)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81251398)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff81278fa1)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8129a81d)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pte_range
  - mm/memory.c:insert_pfn
```
```
In mm/mmap.c (ffffffff812a83f0)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
```
```
In mm/mprotect.c (ffffffff812a9a17)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/pgtable-generic.c (ffffffff812af0e8)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/vmalloc.c (ffffffff812b228b)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pte_range
```
```
In mm/ioremap.c (ffffffff812b8126)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_pte_range
```
```
In mm/swapfile.c (ffffffff812c7779)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812d557b)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/sparse-vmemmap.c (ffffffff81c4084d)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812df599)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812f30b2)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812fa210)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812fcfcb)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff81313e51)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/dax.c (ffffffff813a0469)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
```
```
In drivers/xen/mem-reservation.c (ffffffff8173236f)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
```
In drivers/xen/xlate_mmu.c (ffffffff8174360c)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/grant-table.c (ffffffff8102397e)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff831c0cae)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_update_mem_tables
```
```
In arch/x86/xen/p2m.c (ffffffff81025de1)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81027a15)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102860c)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103e98e)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81bc721a)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107806d)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81bca7a7)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff8108b10d)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8108c7a4)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ec8c)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810926c1)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In arch/x86/mm/pti.c (ffffffff831e07fb)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff831e0bd3)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81255490)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8127df51)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8129fc37)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_set_pmd
  - mm/memory.c:remap_pfn_range_notrack
```
```
In mm/mmap.c (ffffffff812abe00)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
```
```
In mm/mprotect.c (ffffffff812aeea2)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/pgtable-generic.c (ffffffff812b4198)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_mkinvalid
```
```
In mm/vmalloc.c (ffffffff812b795c)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff812ce0f1)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812dc1ee)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/sparse-vmemmap.c (ffffffff81c328ab)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812e7ec9)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812f943f)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81300fd3)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81303d40)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff8131a009)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/dax.c (ffffffff813a6b2e)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
```
```
In drivers/xen/mem-reservation.c (ffffffff81715e3e)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
```
In drivers/xen/xlate_mmu.c (ffffffff81726ffd)
Location: arch/x86/include/asm/pgtable.h:576
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/grant-table.c (ffffffff81027c1e)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff832a1568)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/p2m.c (ffffffff8102a2ff)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102c095)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102cd25)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff810446fe)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81c9a813)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8108587b)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81c9fc4d)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a6ad)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8109bfe4)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109e740)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810a23e1)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In arch/x86/mm/pti.c (ffffffff832c3ed9)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff832c42ab)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81290ecf)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff812e322d)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_set_pmd
  - mm/memory.c:remap_pfn_range_notrack
```
```
In mm/mmap.c (ffffffff812ed500)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
```
```
In mm/mprotect.c (ffffffff812f0692)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/pgtable-generic.c (ffffffff812f5d78)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_mkinvalid
```
```
In mm/vmalloc.c (ffffffff812fa08c)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81313571)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81323384)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/sparse-vmemmap.c (ffffffff8132c597)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_restore_pte
  - mm/sparse-vmemmap.c:vmemmap_remap_pte
  - mm/sparse-vmemmap.c:vmemmap_remap_range
```
```
In mm/ksm.c (ffffffff8132fde6)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff8133e8ea)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8134ac43)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8134da8f)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff81366d4a)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/dax.c (ffffffff813f65be)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
```
```
In drivers/xen/mem-reservation.c (ffffffff8179309e)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
```
In drivers/xen/xlate_mmu.c (ffffffff817a607d)
Location: arch/x86/include/asm/pgtable.h:547
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/grant-table.c (ffffffff8102c07f)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff83450899)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/p2m.c (ffffffff8102edfc)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81030c5e)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81031c64)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8104ccfc)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81e49c68)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095c31)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81e4f3bd)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff810ad920)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff810af5a5)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b2112)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810b6a5f)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/pti.c (ffffffff834767d6)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83476bf7)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff812e6051)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff813445b4)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_set_pmd
  - mm/memory.c:remap_pfn_range_notrack
```
```
In mm/mprotect.c (ffffffff81353ca3)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/pgtable-generic.c (ffffffff81359ca2)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_mkinvalid
```
```
In mm/vmalloc.c (ffffffff813603c7)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff8137ea61)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81390c72)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/sparse-vmemmap.c (ffffffff8139c60e)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_restore_pte
  - mm/sparse-vmemmap.c:vmemmap_remap_pte
  - mm/sparse-vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/ksm.c (ffffffff813a01b8)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff813b19cf)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff813b7e53)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
```
```
In mm/huge_memory.c (ffffffff813c1dd7)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813c6cd8)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff813e4199)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/dax.c (ffffffff81468cbf)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
```
```
In drivers/xen/mem-reservation.c (ffffffff818cba14)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
```
In drivers/xen/xlate_mmu.c (ffffffff818e0041)
Location: arch/x86/include/asm/pgtable.h:550
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/grant-table.c (ffffffff81032faf)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff83e6cdc6)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/p2m.c (ffffffff81036162)
Location: arch/x86/include/asm/pgtable.h:567
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
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81039534)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8105910d)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81067f88)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab86a)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff820c73af)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7ad0)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff810c9a28)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cc9a3)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810d1cac)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/pti.c (ffffffff83e9f54c)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83e9fe07)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff8134fc99)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff813bc6e8)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_set_pmd
  - mm/memory.c:remap_pfn_range_notrack
```
```
In mm/mprotect.c (ffffffff813ce186)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/pgtable-generic.c (ffffffff813d4675)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_mkinvalid
```
```
In mm/vmalloc.c (ffffffff813dc3ad)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813fd40d)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81412551)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/hugetlb_vmemmap.c (ffffffff81414353)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_restore_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_pte
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff820cb4fd)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8141f09f)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81432429)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff81439b2a)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
```
```
In mm/huge_memory.c (ffffffff81443fb8)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81449132)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff8146bc29)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/dax.c (ffffffff814f985c)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
```
```
In drivers/xen/mem-reservation.c (ffffffff81a1cdd4)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
```
In drivers/xen/xlate_mmu.c (ffffffff81a344e5)
Location: arch/x86/include/asm/pgtable.h:567
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/grant-table.c (ffffffff81032f4f)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff8368d8f6)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/p2m.c (ffffffff810360e2)
Location: arch/x86/include/asm/pgtable.h:568
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
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81039474)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8105a6bb)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81069810)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af42b)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8214b444)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff810cb214)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff810cd0ad)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cffb9)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff836c36cc)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff836c3fa4)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81380e49)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff813f10d6)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pmd
  - mm/memory.c:remap_p4d_range
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mprotect.c (ffffffff81402a3a)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/pgtable-generic.c (0)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
```
```
In mm/vmalloc.c (ffffffff81410ca4)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff814306ea)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81445b27)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/hugetlb_vmemmap.c (ffffffff814478ae)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_restore_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_pte
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff8214f78f)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81453c5c)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81467b9a)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8146e850)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
```
```
In mm/huge_memory.c (ffffffff81479540)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8147e916)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff814a0896)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_pte_zeropage
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/dax.c (ffffffff81530ce0)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
```
```
In drivers/xen/mem-reservation.c (ffffffff81a65fd4)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
```
In drivers/xen/xlate_mmu.c (ffffffff81a7defa)
Location: arch/x86/include/asm/pgtable.h:568
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/grant-table.c (ffffffff8103928f)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff838bd4b6)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/p2m.c (ffffffff8103c2e2)
Location: arch/x86/include/asm/pgtable.h:737
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
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103f924)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff81061934)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81070d50)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5fbb)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8222def4)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff810d3764)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff810d577d)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d8699)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff838f436c)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff838f4c24)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff813aa201)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff8141bdcc)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:set_pte_range
  - mm/memory.c:do_set_pmd
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mprotect.c (ffffffff8142f043)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/pgtable-generic.c (0)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
```
```
In mm/vmalloc.c (ffffffff8143eecd)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff814690a1)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8147f4f2)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/hugetlb_vmemmap.c (ffffffff81481294)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_restore_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_pte
  - mm/hugetlb_vmemmap.c:vmemmap_split_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff82232658)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8148e4a0)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff8149787b)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8149d2c1)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/huge_memory.c (ffffffff814a8ac0)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:pmd_modify
```
```
In mm/khugepaged.c (ffffffff814af5aa)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff814d133f)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/dax.c (ffffffff81565bc0)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
```
```
In drivers/xen/mem-reservation.c (ffffffff81ab8814)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
```
In drivers/xen/xlate_mmu.c (ffffffff81ad01d6)
Location: arch/x86/include/asm/pgtable.h:737
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/grant-table.c (ffffffff8101e7f8)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff828921fb)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/p2m.c (ffffffff81020ee2)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81022ac4)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023cdc)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103a177)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff8289c8c0)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ea42)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e570)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff81083a82)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/pgtable.c (ffffffff81086d8c)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff810881e2)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a1fe)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff828b006b)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b04ed)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81212a04)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff812383df)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81257f36)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
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
In mm/mmap.c (ffffffff81263420)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
```
```
In mm/mprotect.c (ffffffff81266699)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/pgtable-generic.c (ffffffff8126b099)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/vmalloc.c (ffffffff8126e877)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In mm/swapfile.c (ffffffff812818b6)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128e85f)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/sparse-vmemmap.c (ffffffff81a6dfc6)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81297b2b)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812aad06)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b25b3)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b585c)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff812cb63f)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff813408d7)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In drivers/xen/mem-reservation.c (ffffffff8162bfd6)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
```
In drivers/xen/xlate_mmu.c (ffffffff8163c2ea)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff81a4eb87)
Location: arch/x86/include/asm/pgtable.h:538
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
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff81029a54)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff82894a89)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ef67)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106d6a3)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff810726d2)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:populate_pgd
  - arch/x86/mm/pageattr.c:populate_pgd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810759f7)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff81076e34)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff828a825d)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a8682)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff8120576e)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8122b41e)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8124da3a)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
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
In mm/mmap.c (ffffffff81255840)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
```
```
In mm/mprotect.c (ffffffff81258d70)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/pgtable-generic.c (0)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In mm/vmalloc.c (ffffffff81260971)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In mm/swapfile.c (ffffffff81275049)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81280619)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a4f5)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812896d4)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff8129c64e)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a393d)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812a6a72)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff812bc4e8)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff81333015)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In lib/ioremap.c (ffffffff81a0bc91)
Location: arch/x86/include/asm/pgtable.h:538
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
In arch/x86/xen/grant-table.c (ffffffff8101e7a8)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff828a51d5)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/p2m.c (ffffffff81020d42)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81022924)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023b3c)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff81039fd7)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff828af883)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106eef2)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e520)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff81083a32)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/pgtable.c (ffffffff81086d3c)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff81088192)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a1ae)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff828c2f6a)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c33ec)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff812107a4)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8123617f)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81255cd6)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
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
In mm/mmap.c (ffffffff812611c0)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
```
```
In mm/mprotect.c (ffffffff81264439)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/pgtable-generic.c (ffffffff81268e39)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/vmalloc.c (ffffffff8126c617)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In mm/swapfile.c (ffffffff8127f6c6)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128c66f)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/sparse-vmemmap.c (ffffffff81ada3d6)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8129593b)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a8b16)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b03c3)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b366c)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff812c944f)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff8133e3a7)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In drivers/xen/mem-reservation.c (ffffffff8165a0e6)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
```
In drivers/xen/xlate_mmu.c (ffffffff8166a43a)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff81abaf77)
Location: arch/x86/include/asm/pgtable.h:538
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
In arch/x86/xen/grant-table.c (ffffffff8101e9f8)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/xen/setup.c (ffffffff828a51a9)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/p2m.c (ffffffff81020f92)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81022ca4)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023fcc)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:set_pte_mfn
```
```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103afd7)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff828af8b1)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81071172)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81080610)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pfn_pte
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff81085b72)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/pgtable.c (ffffffff81088e6c)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8108a432)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/kmmio.c (ffffffff8108c44e)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff828c60f3)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c6592)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff8121f6b5)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8124645f)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81265766)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
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
In mm/mmap.c (ffffffff81270b90)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
```
```
In mm/mprotect.c (ffffffff81273df9)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/pgtable-generic.c (ffffffff812787c9)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/vmalloc.c (ffffffff8127c157)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In mm/swapfile.c (ffffffff8128f399)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In mm/hugetlb.c (ffffffff8129c457)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/sparse-vmemmap.c (ffffffff81ae688c)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812a5753)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812b8e36)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812c0703)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812c3ac7)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff812da12f)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff81352700)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
```
```
In drivers/xen/mem-reservation.c (ffffffff816746b6)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_update
```
```
In drivers/xen/xlate_mmu.c (ffffffff816849fa)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff81ac73c7)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
</details>
</li>
</ul>

## Differences
