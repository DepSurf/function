# Function: <code>pfn_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101b950)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:set_aliased_prot
Direct callers:
  - arch/x86/xen/enlighten.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu.c (ffffffff8101deb0)
Location: arch/x86/include/asm/pgtable.h:354
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
Direct callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/xen/p2m.c (ffffffff81024610)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
Direct callers:
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/kernel/tboot.c (ffffffff81f6a3a5)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bbef)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8107d4fe)
Location: arch/x86/include/asm/pgtable.h:354
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:vmemmap_populate
```
```
In arch/x86/mm/ioremap.c (ffffffff81f77fba)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c36a)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/pgtable.c (ffffffff81071145)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:native_set_fixmap
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In kernel/events/uprobes.c (ffffffff81187867)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811bb800)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vm_insert_page
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
```
```
In mm/vmalloc.c (ffffffff811cdecd)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
```
```
In mm/swapfile.c (ffffffff811d45ac)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811daf68)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff8181f285)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff811e5847)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff811f0d22)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff811f7655)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/userfaultfd.c (ffffffff812079ae)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mfill_zeropage
```
```
In lib/ioremap.c (ffffffff813eb0b1)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
```
```
In drivers/xen/xlate_mmu.c (ffffffff814d7000)
Location: arch/x86/include/asm/pgtable.h:354
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff8101b950-ffffffff8101b976: pfn_pte (STB_LOCAL)
ffffffff8101deb0-ffffffff8101ded6: pfn_pte (STB_LOCAL)
ffffffff81024610-ffffffff81024636: pfn_pte (STB_LOCAL)
ffffffff8107d4fe-ffffffff8107d51f: pfn_pte (STB_LOCAL)
ffffffff811bb800-ffffffff811bb826: pfn_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101bdc4)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:set_aliased_prot
Direct callers:
  - arch/x86/xen/enlighten.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu.c (ffffffff8101e0cb)
Location: arch/x86/include/asm/pgtable.h:383
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
Direct callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/xen/p2m.c (ffffffff81023f72)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
Direct callers:
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/kernel/tboot.c (ffffffff81f926cf)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bcd6)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8107efdb)
Location: arch/x86/include/asm/pgtable.h:383
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff81fa0715)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8106daf3)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/pgtable.c (ffffffff810711a7)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In kernel/events/uprobes.c (ffffffff81199e7f)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811db919)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vm_insert_page
```
```
In mm/vmalloc.c (ffffffff811eab0e)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
```
```
In mm/swapfile.c (ffffffff811f2445)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811f90ea)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81899941)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8120441f)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff8120ff9a)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8121638c)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/userfaultfd.c (ffffffff8122d834)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In lib/ioremap.c (ffffffff81431404)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
```
```
In drivers/xen/xlate_mmu.c (ffffffff81527dd5)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff8101ad40-ffffffff8101ad66: pfn_pte (STB_LOCAL)
ffffffff8101d2a0-ffffffff8101d2c6: pfn_pte (STB_LOCAL)
ffffffff810238d0-ffffffff810238f6: pfn_pte (STB_LOCAL)
ffffffff8107efdb-ffffffff8107effc: pfn_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101c5d4)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:set_aliased_prot
Direct callers:
  - arch/x86/xen/enlighten.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu.c (ffffffff8101e7bb)
Location: arch/x86/include/asm/pgtable.h:383
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
Direct callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/xen/p2m.c (ffffffff810246a2)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
Direct callers:
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/kernel/tboot.c (ffffffff81fcd99b)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ec50)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8108368b)
Location: arch/x86/include/asm/pgtable.h:383
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff81fdbc86)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8107177f)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/pgtable.c (ffffffff81074d27)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In kernel/events/uprobes.c (ffffffff811a95ea)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811ea0c6)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vm_insert_page
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
```
```
In mm/vmalloc.c (ffffffff811fbd03)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
```
```
In mm/swapfile.c (ffffffff81202e3c)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81209cd7)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff818cdff3)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81216331)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812220bd)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8122893d)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/userfaultfd.c (ffffffff8123fd72)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In lib/ioremap.c (ffffffff8144d674)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
```
In drivers/xen/xlate_mmu.c (ffffffff81554342)
Location: arch/x86/include/asm/pgtable.h:383
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff8101b470-ffffffff8101b496: pfn_pte (STB_LOCAL)
ffffffff8101d9c0-ffffffff8101d9e6: pfn_pte (STB_LOCAL)
ffffffff81024000-ffffffff81024026: pfn_pte (STB_LOCAL)
ffffffff8108368b-ffffffff810836ac: pfn_pte (STB_LOCAL)
ffffffff811e61c0-ffffffff811e61e6: pfn_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8101d835)
Location: arch/x86/include/asm/pgtable.h:514
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
Direct callers:
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8101f534)
Location: arch/x86/include/asm/pgtable.h:514
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102076f)
Location: arch/x86/include/asm/pgtable.h:514
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
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/tboot.c (ffffffff820adfe5)
Location: arch/x86/include/asm/pgtable.h:514
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e2ec)
Location: arch/x86/include/asm/pgtable.h:514
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106ce7c)
Location: arch/x86/include/asm/pgtable.h:514
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff820bcc56)
Location: arch/x86/include/asm/pgtable.h:514
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff81070f99)
Location: arch/x86/include/asm/pgtable.h:514
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/pgtable.c (ffffffff810742da)
Location: arch/x86/include/asm/pgtable.h:514
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In kernel/events/uprobes.c (ffffffff811b0aeb)
Location: arch/x86/include/asm/pgtable.h:514
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff811dce95)
Location: arch/x86/include/asm/pgtable.h:514
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
```
In mm/memory.c (ffffffff811f4ffb)
Location: arch/x86/include/asm/pgtable.h:514
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/vmalloc.c (ffffffff81206b89)
Location: arch/x86/include/asm/pgtable.h:514
Inline: True
```
```
In mm/swapfile.c (ffffffff8120decf)
Location: arch/x86/include/asm/pgtable.h:514
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81215285)
Location: arch/x86/include/asm/pgtable.h:514
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81905488)
Location: arch/x86/include/asm/pgtable.h:514
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81221b83)
Location: arch/x86/include/asm/pgtable.h:514
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8122df3d)
Location: arch/x86/include/asm/pgtable.h:514
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81231fbd)
Location: arch/x86/include/asm/pgtable.h:514
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/userfaultfd.c (ffffffff8124bc56)
Location: arch/x86/include/asm/pgtable.h:514
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In drivers/xen/xlate_mmu.c (ffffffff81568eb6)
Location: arch/x86/include/asm/pgtable.h:514
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff818ed522)
Location: arch/x86/include/asm/pgtable.h:514
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8101d1f0-ffffffff8101d211: pfn_pte (STB_LOCAL)
ffffffff8101e560-ffffffff8101e581: pfn_pte (STB_LOCAL)
ffffffff8101fca0-ffffffff8101fcc1: pfn_pte (STB_LOCAL)
ffffffff8106ce7c-ffffffff8106ce9d: pfn_pte (STB_LOCAL)
ffffffff811f8df0-ffffffff811f8e11: pfn_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8101e4ba)
Location: arch/x86/include/asm/pgtable.h:529
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
Direct callers:
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102007b)
Location: arch/x86/include/asm/pgtable.h:529
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81021bb0)
Location: arch/x86/include/asm/pgtable.h:529
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
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff81031dce)
Location: arch/x86/include/asm/pgtable.h:529
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff826b4541)
Location: arch/x86/include/asm/pgtable.h:529
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061fe5)
Location: arch/x86/include/asm/pgtable.h:529
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81071b9b)
Location: arch/x86/include/asm/pgtable.h:529
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff826c3832)
Location: arch/x86/include/asm/pgtable.h:529
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff810766e1)
Location: arch/x86/include/asm/pgtable.h:529
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/pgtable.c (ffffffff81079d6a)
Location: arch/x86/include/asm/pgtable.h:529
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8107af70)
Location: arch/x86/include/asm/pgtable.h:529
Inline: True
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5f99)
Location: arch/x86/include/asm/pgtable.h:529
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff811c464a)
Location: arch/x86/include/asm/pgtable.h:529
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff811eedb2)
Location: arch/x86/include/asm/pgtable.h:529
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8120d8df)
Location: arch/x86/include/asm/pgtable.h:529
Inline: True
Inline callers:
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
In mm/vmalloc.c (ffffffff8121fbdd)
Location: arch/x86/include/asm/pgtable.h:529
Inline: True
```
```
In mm/swapfile.c (ffffffff81229141)
Location: arch/x86/include/asm/pgtable.h:529
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8122ff05)
Location: arch/x86/include/asm/pgtable.h:529
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff8198f4cd)
Location: arch/x86/include/asm/pgtable.h:529
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8123ce71)
Location: arch/x86/include/asm/pgtable.h:529
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81249c72)
Location: arch/x86/include/asm/pgtable.h:529
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81252d3e)
Location: arch/x86/include/asm/pgtable.h:529
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/userfaultfd.c (ffffffff8126bfd3)
Location: arch/x86/include/asm/pgtable.h:529
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In drivers/xen/xlate_mmu.c (ffffffff815cd066)
Location: arch/x86/include/asm/pgtable.h:529
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff81973657)
Location: arch/x86/include/asm/pgtable.h:529
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8101dec0-ffffffff8101dee1: pfn_pte (STB_LOCAL)
ffffffff8101f290-ffffffff8101f2b1: pfn_pte (STB_LOCAL)
ffffffff81020910-ffffffff81020931: pfn_pte (STB_LOCAL)
ffffffff81071b9b-ffffffff81071bbc: pfn_pte (STB_LOCAL)
ffffffff8107af70-ffffffff8107af91: pfn_pte (STB_LOCAL)
ffffffff81248d90-ffffffff81248db1: pfn_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8101efe7)
Location: arch/x86/include/asm/pgtable.h:546
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
Direct callers:
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81020b5f)
Location: arch/x86/include/asm/pgtable.h:546
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810226ba)
Location: arch/x86/include/asm/pgtable.h:546
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
Direct callers:
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff8103305c)
Location: arch/x86/include/asm/pgtable.h:546
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff826ddc64)
Location: arch/x86/include/asm/pgtable.h:546
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106508a)
Location: arch/x86/include/asm/pgtable.h:546
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81074863)
Location: arch/x86/include/asm/pgtable.h:546
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff826eda96)
Location: arch/x86/include/asm/pgtable.h:546
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8107906b)
Location: arch/x86/include/asm/pgtable.h:546
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/pgtable.c (ffffffff8107c9f4)
Location: arch/x86/include/asm/pgtable.h:546
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8107dd7d)
Location: arch/x86/include/asm/pgtable.h:546
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efd41)
Location: arch/x86/include/asm/pgtable.h:546
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff811e4b81)
Location: arch/x86/include/asm/pgtable.h:546
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff8120f8c2)
Location: arch/x86/include/asm/pgtable.h:546
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8122dc9b)
Location: arch/x86/include/asm/pgtable.h:546
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
```
```
In mm/vmalloc.c (ffffffff81240c7f)
Location: arch/x86/include/asm/pgtable.h:546
Inline: True
```
```
In mm/swapfile.c (ffffffff8124a447)
Location: arch/x86/include/asm/pgtable.h:546
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81252379)
Location: arch/x86/include/asm/pgtable.h:546
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff819ebd44)
Location: arch/x86/include/asm/pgtable.h:546
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8126055b)
Location: arch/x86/include/asm/pgtable.h:546
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8126d4ad)
Location: arch/x86/include/asm/pgtable.h:546
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81277176)
Location: arch/x86/include/asm/pgtable.h:546
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/userfaultfd.c (ffffffff81290a06)
Location: arch/x86/include/asm/pgtable.h:546
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In drivers/xen/xlate_mmu.c (ffffffff8160577f)
Location: arch/x86/include/asm/pgtable.h:546
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff819cfb61)
Location: arch/x86/include/asm/pgtable.h:546
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8101e920-ffffffff8101e96e: pfn_pte (STB_LOCAL)
ffffffff8101fd50-ffffffff8101fd9e: pfn_pte (STB_LOCAL)
ffffffff810213a0-ffffffff810213ee: pfn_pte (STB_LOCAL)
ffffffff81074863-ffffffff810748b2: pfn_pte (STB_LOCAL)
ffffffff81228d50-ffffffff81228d9e: pfn_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8101e898)
Location: arch/x86/include/asm/pgtable.h:548
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
Direct callers:
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102045f)
Location: arch/x86/include/asm/pgtable.h:548
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102493a)
Location: arch/x86/include/asm/pgtable.h:548
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
Direct callers:
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff81034476)
Location: arch/x86/include/asm/pgtable.h:548
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff828940b0)
Location: arch/x86/include/asm/pgtable.h:548
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106acfa)
Location: arch/x86/include/asm/pgtable.h:548
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8107a753)
Location: arch/x86/include/asm/pgtable.h:548
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff828a4628)
Location: arch/x86/include/asm/pgtable.h:548
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8107fb40)
Location: arch/x86/include/asm/pgtable.h:548
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/pgtable.c (ffffffff81083424)
Location: arch/x86/include/asm/pgtable.h:548
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff810848fd)
Location: arch/x86/include/asm/pgtable.h:548
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pti.c (ffffffff828a65ca)
Location: arch/x86/include/asm/pgtable.h:548
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a69fe)
Location: arch/x86/include/asm/pgtable.h:548
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff811f523a)
Location: arch/x86/include/asm/pgtable.h:548
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff812226a7)
Location: arch/x86/include/asm/pgtable.h:548
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81241160)
Location: arch/x86/include/asm/pgtable.h:548
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/vmalloc.c (ffffffff81255555)
Location: arch/x86/include/asm/pgtable.h:548
Inline: True
```
```
In mm/swapfile.c (ffffffff8125ea88)
Location: arch/x86/include/asm/pgtable.h:548
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff812665d9)
Location: arch/x86/include/asm/pgtable.h:548
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81a26fb2)
Location: arch/x86/include/asm/pgtable.h:548
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81274cc5)
Location: arch/x86/include/asm/pgtable.h:548
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81281b9d)
Location: arch/x86/include/asm/pgtable.h:548
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812889c5)
Location: arch/x86/include/asm/pgtable.h:548
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/userfaultfd.c (ffffffff812a59eb)
Location: arch/x86/include/asm/pgtable.h:548
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In drivers/xen/xlate_mmu.c (ffffffff8162085f)
Location: arch/x86/include/asm/pgtable.h:548
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff81a0914e)
Location: arch/x86/include/asm/pgtable.h:548
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8101e1d0-ffffffff8101e21e: pfn_pte (STB_LOCAL)
ffffffff8101f5d0-ffffffff8101f61e: pfn_pte (STB_LOCAL)
ffffffff81020c10-ffffffff81020c5e: pfn_pte (STB_LOCAL)
ffffffff8107a753-ffffffff8107a7a2: pfn_pte (STB_LOCAL)
ffffffff8123c5f0-ffffffff8123c63e: pfn_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff810203f7)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81021f9f)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025947)
Location: arch/x86/include/asm/pgtable.h:565
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
Direct callers:
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff81036203)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff81039817)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff828ab85e)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e4be)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e4aa)
Location: arch/x86/include/asm/pgtable.h:565
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff828bcb05)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff81083510)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/pgtable.c (ffffffff8108708c)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8108858c)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pti.c (ffffffff828becd3)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bf0ad)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff8120cf21)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff81231cb0)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81253435)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
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
In mm/vmalloc.c (ffffffff812678a7)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
```
```
In mm/swapfile.c (ffffffff812797d7)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128189d)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81a9783a)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8128f7a9)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff8129dca9)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a3605)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/userfaultfd.c (ffffffff812c10d3)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In drivers/xen/xlate_mmu.c (ffffffff8165401a)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff81a789cf)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8101fd50-ffffffff8101fd9b: pfn_pte (STB_LOCAL)
ffffffff81021120-ffffffff8102116b: pfn_pte (STB_LOCAL)
ffffffff81022750-ffffffff8102279b: pfn_pte (STB_LOCAL)
ffffffff8107e4aa-ffffffff8107e4f9: pfn_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81020d57)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff810228df)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025f27)
Location: arch/x86/include/asm/pgtable.h:565
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
Direct callers:
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff81036b2e)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff81039fe8)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff828ae86c)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106fa6e)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107f53a)
Location: arch/x86/include/asm/pgtable.h:565
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff828c2fa0)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff810845e0)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/pgtable.c (ffffffff81087d7c)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff810891fc)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pti.c (ffffffff828c50ad)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c5526)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff8121a212)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8123fd70)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81261995)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
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
In mm/vmalloc.c (ffffffff81276207)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
```
```
In mm/swapfile.c (ffffffff812892b7)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
```
```
In mm/hugetlb.c (ffffffff812912ad)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81acf11c)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8129f52c)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812ad559)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b4b05)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/userfaultfd.c (ffffffff812d3023)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In drivers/xen/xlate_mmu.c (ffffffff816765ba)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff81aafd7f)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff810206b0-ffffffff810206fb: pfn_pte (STB_LOCAL)
ffffffff81021a80-ffffffff81021acb: pfn_pte (STB_LOCAL)
ffffffff81023090-ffffffff810230db: pfn_pte (STB_LOCAL)
ffffffff8107f53a-ffffffff8107f589: pfn_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff810235b6)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81024d5f)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81027177)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
Direct callers:
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff8103893b)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103cc4c)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81047b1f)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076f83)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81085f55)
Location: arch/x86/include/asm/pgtable.h:604
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff82ce6395)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a214)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8108bb53)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e1e7)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/pti.c (ffffffff82ce8177)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82ce8736)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81246b84)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8126e57c)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81291c18)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pte_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/vmalloc.c (ffffffff812a79b0)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pte_range
```
```
In mm/swapfile.c (ffffffff812bbc96)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812c41e3)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7add)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812d3b7a)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812e28b9)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ea0b3)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff81307e31)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage_pte
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In lib/ioremap.c (ffffffff815e9865)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pte_range
```
```
In drivers/xen/xlate_mmu.c (ffffffff81727076)
Location: arch/x86/include/asm/pgtable.h:604
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff81022d40-ffffffff81022d8c: pfn_pte (STB_LOCAL)
ffffffff810242b0-ffffffff810242fc: pfn_pte (STB_LOCAL)
ffffffff810258d0-ffffffff8102591c: pfn_pte (STB_LOCAL)
ffffffff81085f55-ffffffff81085fa2: pfn_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81023b86)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff810254cf)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028287)
Location: arch/x86/include/asm/pgtable.h:603
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
Direct callers:
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff8103928b)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103d108)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81bd4d9c)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810775b3)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81bd88c9)
Location: arch/x86/include/asm/pgtable.h:603
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff82fd3d1b)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a499)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8108bb73)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e0b7)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/pti.c (ffffffff82fd5b96)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82fd614a)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff812511e7)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff81278f70)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8129c4e8)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pte_range
  - mm/memory.c:insert_pfn
Direct callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_pte_range
```
```
In mm/vmalloc.c (ffffffff812b2272)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pte_range
```
```
In mm/ioremap.c (ffffffff812b810a)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_pte_range
```
```
In mm/swapfile.c (ffffffff812c7746)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812cf9d3)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81c40814)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812df57a)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812edceb)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812f5289)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff81313e1e)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In drivers/xen/xlate_mmu.c (ffffffff817435c4)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff81023310-ffffffff8102335c: pfn_pte (STB_LOCAL)
ffffffff81024a30-ffffffff81024a7c: pfn_pte (STB_LOCAL)
ffffffff81025ff0-ffffffff8102603c: pfn_pte (STB_LOCAL)
ffffffff81bd88c9-ffffffff81bd8916: pfn_pte (STB_LOCAL)
ffffffff81296bd0-ffffffff81296c1c: pfn_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81025db6)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81027990)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102ac77)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
Direct callers:
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff8103adbc)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103e94d)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81bc71ee)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107803a)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81bca774)
Location: arch/x86/include/asm/pgtable.h:603
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff831de85c)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pgtable.c (ffffffff8108b0f9)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8108c790)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ec77)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/pti.c (ffffffff831e07d5)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff831e0bab)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff812552f9)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8127df2b)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff812a3c62)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range_notrack
Direct callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_pte_range
```
```
In mm/vmalloc.c (ffffffff812b7928)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff812ce0bf)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812d6ec3)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81c3287a)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812e7e97)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812f3e7b)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812fb7d2)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff81319fd8)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In drivers/xen/xlate_mmu.c (ffffffff81726fc4)
Location: arch/x86/include/asm/pgtable.h:603
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff81025610-ffffffff8102565c: pfn_pte (STB_LOCAL)
ffffffff81026bf0-ffffffff81026c3c: pfn_pte (STB_LOCAL)
ffffffff81bc4e53-ffffffff81bc4e9f: pfn_pte (STB_LOCAL)
ffffffff81bca774-ffffffff81bca7be: pfn_pte (STB_LOCAL)
ffffffff8129c8f0-ffffffff8129c93c: pfn_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8102a2d4)
Location: arch/x86/include/asm/pgtable.h:574
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102c010)
Location: arch/x86/include/asm/pgtable.h:574
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102f2a7)
Location: arch/x86/include/asm/pgtable.h:574
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
Direct callers:
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff810407e6)
Location: arch/x86/include/asm/pgtable.h:574
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff810446bd)
Location: arch/x86/include/asm/pgtable.h:574
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81c9a7e7)
Location: arch/x86/include/asm/pgtable.h:574
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8108584c)
Location: arch/x86/include/asm/pgtable.h:574
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81c9fc1a)
Location: arch/x86/include/asm/pgtable.h:574
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff832c1bd2)
Location: arch/x86/include/asm/pgtable.h:574
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a699)
Location: arch/x86/include/asm/pgtable.h:574
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8109bfd0)
Location: arch/x86/include/asm/pgtable.h:574
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109e72b)
Location: arch/x86/include/asm/pgtable.h:574
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/pti.c (ffffffff832c3eb2)
Location: arch/x86/include/asm/pgtable.h:574
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff832c4283)
Location: arch/x86/include/asm/pgtable.h:574
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81290d3b)
Location: arch/x86/include/asm/pgtable.h:574
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff812e4f7e)
Location: arch/x86/include/asm/pgtable.h:574
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range_notrack
Direct callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_pte_range
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/vmalloc.c (ffffffff812fa058)
Location: arch/x86/include/asm/pgtable.h:574
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff8131353f)
Location: arch/x86/include/asm/pgtable.h:574
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8131cd93)
Location: arch/x86/include/asm/pgtable.h:574
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff8132c564)
Location: arch/x86/include/asm/pgtable.h:574
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_restore_pte
  - mm/sparse-vmemmap.c:vmemmap_remap_pte
  - mm/sparse-vmemmap.c:vmemmap_remap_range
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8132fdc7)
Location: arch/x86/include/asm/pgtable.h:574
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff8133e8cb)
Location: arch/x86/include/asm/pgtable.h:574
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81345633)
Location: arch/x86/include/asm/pgtable.h:574
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff81366d14)
Location: arch/x86/include/asm/pgtable.h:574
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In drivers/xen/xlate_mmu.c (ffffffff817a6044)
Location: arch/x86/include/asm/pgtable.h:574
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff81029b20-ffffffff81029b6c: pfn_pte (STB_LOCAL)
ffffffff8102b110-ffffffff8102b15c: pfn_pte (STB_LOCAL)
ffffffff81c9762f-ffffffff81c9767b: pfn_pte (STB_LOCAL)
ffffffff81c9fc1a-ffffffff81c9fc64: pfn_pte (STB_LOCAL)
ffffffff812dd6c0-ffffffff812dd70c: pfn_pte (STB_LOCAL)
ffffffff8132bd30-ffffffff8132bd7c: pfn_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8102eddd)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81030c47)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810342ce)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
Direct callers:
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff81048198)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/alternative.c (ffffffff8104ccd6)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81e49c59)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095c18)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81e4f3a0)
Location: arch/x86/include/asm/pgtable.h:577
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff834742e3)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pgtable.c (ffffffff810ad90f)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff810af589)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b2112)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/pti.c (ffffffff834767af)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83476be5)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff812e6033)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff8134688e)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range_notrack
Direct callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_present_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/vmalloc.c (ffffffff813603a0)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff8137ea3c)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81389248)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff8139c5e0)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_restore_pte
  - mm/sparse-vmemmap.c:vmemmap_remap_pte
  - mm/sparse-vmemmap.c:__split_vmemmap_huge_pmd
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff813a0196)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff813b19ad)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff813b7e2e)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
```
```
In mm/huge_memory.c (ffffffff813bb615)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff813e417e)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In drivers/xen/xlate_mmu.c (ffffffff818e0014)
Location: arch/x86/include/asm/pgtable.h:577
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff8102e440-ffffffff8102e499: pfn_pte (STB_LOCAL)
ffffffff8102f990-ffffffff8102f9e9: pfn_pte (STB_LOCAL)
ffffffff810312c0-ffffffff81031319: pfn_pte (STB_LOCAL)
ffffffff81e4f3a0-ffffffff81e4f3f8: pfn_pte (STB_LOCAL)
ffffffff8133d2b0-ffffffff8133d309: pfn_pte (STB_LOCAL)
ffffffff8139ba60-ffffffff8139bab9: pfn_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81036143)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83e6ebcf)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103bd9f)
Location: arch/x86/include/asm/pgtable.h:594
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
In arch/x86/kernel/ldt.c (ffffffff81052ee5)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/alternative.c (ffffffff810590e8)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81067f79)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab851)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff820c7390)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff83e9c08e)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7abf)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff810c9a09)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cc9a3)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/pti.c (ffffffff83e9f5ae)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83e9fdf1)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff8134fc6e)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff813bec84)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range_notrack
Direct callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_present_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/vmalloc.c (ffffffff813dc387)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813fd3e8)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81406f48)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
```
```
In mm/hugetlb_vmemmap.c (ffffffff81414324)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_restore_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_pte
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff820cb4de)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8141f07d)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81432407)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff81439b05)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
```
```
In mm/huge_memory.c (ffffffff8143dbae)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff8146bc07)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In drivers/xen/xlate_mmu.c (ffffffff81a344c0)
Location: arch/x86/include/asm/pgtable.h:594
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff813b4f10-ffffffff813b4f69: pfn_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff810360c3)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8368fae5)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103a52f)
Location: arch/x86/include/asm/pgtable.h:595
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
In arch/x86/kernel/ldt.c (ffffffff81053ec8)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/alternative.c (ffffffff8105a696)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff810697fa)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af412)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8214b420)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff836bfb2e)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pgtable.c (ffffffff810cb20b)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff810cd090)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cffb9)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/pti.c (ffffffff836c3737)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff836c3f89)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81380e2b)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff813efcd0)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:remap_p4d_range
  - mm/memory.c:restore_exclusive_pte
Direct callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_present_pte
```
```
In mm/vmalloc.c (ffffffff81410c8e)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff814306c5)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8143af08)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
```
```
In mm/hugetlb_vmemmap.c (ffffffff81447887)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_restore_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_pte
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff8214f770)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81453c2d)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81467b6b)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8146e82b)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
```
```
In mm/huge_memory.c (ffffffff814730cd)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff814a0878)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_pte_zeropage
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In drivers/xen/xlate_mmu.c (ffffffff81a7ded0)
Location: arch/x86/include/asm/pgtable.h:595
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff813e9d70-ffffffff813e9dc5: pfn_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8103c2c3)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff838befb5)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810409ef)
Location: arch/x86/include/asm/pgtable.h:764
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
In arch/x86/kernel/ldt.c (ffffffff8105b0e8)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/alternative.c (ffffffff81061904)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81070d3a)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5fa2)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8222ded0)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff838f064e)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pgtable.c (ffffffff810d375b)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff810d5760)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d8699)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/pti.c (ffffffff838f43d7)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_user_shared
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff838f4c09)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff813aa1f2)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff8141b2ef)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
Inline callers:
  - mm/memory.c:set_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:restore_exclusive_pte
Direct callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_present_pte
```
```
In mm/vmalloc.c (ffffffff8143eeb7)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81469095)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81474dbd)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
```
```
In mm/hugetlb_vmemmap.c (ffffffff81481276)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_restore_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_pte
  - mm/hugetlb_vmemmap.c:vmemmap_split_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff82232638)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8148e47e)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81497856)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8149d2b2)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/huge_memory.c (ffffffff814a1846)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff814d1325)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In drivers/xen/xlate_mmu.c (ffffffff81ad01a4)
Location: arch/x86/include/asm/pgtable.h:764
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff814156f0-ffffffff81415745: pfn_pte (STB_LOCAL)
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
In arch/powerpc/mm/book3s64/hash_pgtable.c (c00000000008b828)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:609
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_pgtable.c:hash__map_kernel_page
```
```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000095a70)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:609
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:pmd_set_huge
  - arch/powerpc/mm/book3s64/radix_pgtable.c:pud_set_huge
  - arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page
  - arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page
```
```
In kernel/events/uprobes.c (c000000000358348)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:609
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (c000000000391b00)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:609
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (c0000000003c2350)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:609
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vm_insert_page
```
```
In mm/vmalloc.c (c0000000003dc640)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:609
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_page_range_noflush
```
```
In mm/swapfile.c (c0000000003fc664)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:609
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (c00000000040cf68)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:609
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/sparse-vmemmap.c (c000000000eedc0c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:609
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (c00000000041ad10)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:609
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (c0000000004314b8)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:609
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (c00000000043c36c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:609
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/userfaultfd.c (c00000000046b8e0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:609
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In lib/ioremap.c (c000000000eca2b4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:609
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
In arch/riscv/mm/init.c (ffffffe000003744)
Location: arch/riscv/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - arch/riscv/mm/init.c:get_pmd_virt
  - arch/riscv/mm/init.c:create_pte_mapping
  - arch/riscv/mm/init.c:get_pte_virt
```
```
In mm/shmem.c (ffffffe0001ee2d4)
Location: arch/riscv/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffe000208f66)
Location: arch/riscv/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/vmalloc.c (ffffffe0002158a4)
Location: arch/riscv/include/asm/pgtable.h:187
Inline: True
```
```
In mm/swapfile.c (ffffffe000226462)
Location: arch/riscv/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffe000230294)
Location: arch/riscv/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/sparse-vmemmap.c (ffffffe000048fdc)
Location: arch/riscv/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffe000234992)
Location: arch/riscv/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffe00023e286)
Location: arch/riscv/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/userfaultfd.c (ffffffe0002504e8)
Location: arch/riscv/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In lib/ioremap.c (ffffffe0008b31b6)
Location: arch/riscv/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81020eb7)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81022a3f)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81026087)
Location: arch/x86/include/asm/pgtable.h:565
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
Direct callers:
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff81036c8e)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103a148)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff8289c88b)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ea0e)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e53a)
Location: arch/x86/include/asm/pgtable.h:565
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff828adf76)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff810835e0)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/pgtable.c (ffffffff81086d7c)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff810881bc)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pti.c (ffffffff828b0045)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b04be)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81212862)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff812383c0)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81259fe5)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
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
In mm/vmalloc.c (ffffffff8126e857)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
```
```
In mm/swapfile.c (ffffffff81281897)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128988d)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81a6df8c)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81297b0c)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a5b39)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ad0e5)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/userfaultfd.c (ffffffff812cb603)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In drivers/xen/xlate_mmu.c (ffffffff8163c2aa)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff81a4ebcf)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81020810-ffffffff8102085b: pfn_pte (STB_LOCAL)
ffffffff81021be0-ffffffff81021c2b: pfn_pte (STB_LOCAL)
ffffffff810231f0-ffffffff8102323b: pfn_pte (STB_LOCAL)
ffffffff8107e53a-ffffffff8107e589: pfn_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810265b3)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff81029a27)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff82894a5c)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ef37)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106d675)
Location: arch/x86/include/asm/pgtable.h:565
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff828a6199)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff81071fbb)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
```
```
In arch/x86/mm/pgtable.c (ffffffff810759e3)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff81076e05)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pti.c (ffffffff828a823a)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a8650)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff812055ef)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8122b406)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8124c413)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
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
In mm/vmalloc.c (ffffffff81260953)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
```
```
In mm/swapfile.c (ffffffff81275016)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8127b72d)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a4be)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812896bc)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81297619)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8129e10f)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/userfaultfd.c (ffffffff812bc4bf)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In lib/ioremap.c (ffffffff81a0bcc0)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8106d675-ffffffff8106d6b4: pfn_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81020d17)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102289f)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025ee7)
Location: arch/x86/include/asm/pgtable.h:565
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
Direct callers:
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff81036aee)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff81039fa8)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff828af84e)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106eebe)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e4ea)
Location: arch/x86/include/asm/pgtable.h:565
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff828c0e75)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff81083590)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/pgtable.c (ffffffff81086d2c)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8108816c)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pti.c (ffffffff828c2f44)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c33bd)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81210602)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff81236160)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81257d85)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
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
In mm/vmalloc.c (ffffffff8126c5f7)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
```
```
In mm/swapfile.c (ffffffff8127f6a7)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128769d)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81ada39c)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8129591c)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a3949)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812aaef5)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/userfaultfd.c (ffffffff812c9413)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In drivers/xen/xlate_mmu.c (ffffffff8166a3fa)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff81abafbf)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81020670-ffffffff810206bb: pfn_pte (STB_LOCAL)
ffffffff81021a40-ffffffff81021a8b: pfn_pte (STB_LOCAL)
ffffffff81023050-ffffffff8102309b: pfn_pte (STB_LOCAL)
ffffffff8107e4ea-ffffffff8107e539: pfn_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pte_t pfn_pte(long unsigned int page_nr, pgprot_t pgprot);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81020f67)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81022c0f)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025067)
Location: arch/x86/include/asm/pgtable.h:565
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
Direct callers:
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff810379ee)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103afa8)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff828af87c)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107113e)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810805da)
Location: arch/x86/include/asm/pgtable.h:565
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff828c3fc0)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff810856bf)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/pgtable.c (ffffffff81088e5c)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:native_set_fixmap
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff8108a40c)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:cea_set_pte
```
```
In arch/x86/mm/pti.c (ffffffff828c60cd)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c6563)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff8121f545)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff81246440)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81267780)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
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
In mm/vmalloc.c (ffffffff8127c137)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
```
```
In mm/swapfile.c (ffffffff8128f37a)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
```
```
In mm/hugetlb.c (ffffffff812981cd)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81ae6852)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812a5734)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812b4159)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812bb245)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/userfaultfd.c (ffffffff812da0fa)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In drivers/xen/xlate_mmu.c (ffffffff816849ba)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
```
In lib/ioremap.c (ffffffff81ac740f)
Location: arch/x86/include/asm/pgtable.h:565
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff810208c0-ffffffff8102090b: pfn_pte (STB_LOCAL)
ffffffff81021c90-ffffffff81021cdb: pfn_pte (STB_LOCAL)
ffffffff810234c0-ffffffff8102350b: pfn_pte (STB_LOCAL)
ffffffff810805da-ffffffff81080629: pfn_pte (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
