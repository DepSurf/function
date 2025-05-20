# Function: <code>p4d_none</code>

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
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/pgtable.h:808
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/include/asm/pgtable.h:808
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:808
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable.h:808
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:808
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/include/asm/pgtable.h:808
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: arch/x86/include/asm/pgtable.h:808
Inline: True
```
```
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:808
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:808
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:808
Inline: True
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/pgtable.h:808
Inline: True
```
```
In mm/pagewalk.c (0)
Location: arch/x86/include/asm/pgtable.h:808
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:808
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:808
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/pgtable.h:808
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: arch/x86/include/asm/pgtable.h:808
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:808
Inline: True
```
```
In lib/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:808
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
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff826c5732)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
```
```
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
```
```
In mm/pagewalk.c (0)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:816
Inline: True
```
```
In lib/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:816
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
In arch/x86/xen/mmu_pv.c (ffffffff826d6750)
Location: arch/x86/include/asm/pgtable.h:858
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff826ddb7f)
Location: arch/x86/include/asm/pgtable.h:858
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/mm/init_64.c (ffffffff81074611)
Location: arch/x86/include/asm/pgtable.h:858
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/fault.c (ffffffff81074fd0)
Location: arch/x86/include/asm/pgtable.h:858
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8107a0bf)
Location: arch/x86/include/asm/pgtable.h:858
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/tlb.c (ffffffff8107d1df)
Location: arch/x86/include/asm/pgtable.h:858
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107f314)
Location: arch/x86/include/asm/pgtable.h:858
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff81083343)
Location: arch/x86/include/asm/pgtable.h:858
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f0133)
Location: arch/x86/include/asm/pgtable.h:858
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81087922)
Location: arch/x86/include/asm/pgtable.h:858
Inline: True
```
```
In mm/gup.c (ffffffff812268f2)
Location: arch/x86/include/asm/pgtable.h:858
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812297cd)
Location: arch/x86/include/asm/pgtable.h:858
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:858
Inline: True
```
```
In mm/mremap.c (ffffffff8123a8db)
Location: arch/x86/include/asm/pgtable.h:858
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8123ce09)
Location: arch/x86/include/asm/pgtable.h:858
Inline: True
```
```
In mm/vmalloc.c (ffffffff81240e4f)
Location: arch/x86/include/asm/pgtable.h:858
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:858
Inline: True
```
```
In mm/hugetlb.c (ffffffff81257453)
Location: arch/x86/include/asm/pgtable.h:858
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff819ebf85)
Location: arch/x86/include/asm/pgtable.h:858
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/migrate.c (ffffffff8126eebb)
Location: arch/x86/include/asm/pgtable.h:858
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8128faee)
Location: arch/x86/include/asm/pgtable.h:858
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff819cf956)
Location: arch/x86/include/asm/pgtable.h:858
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
In arch/x86/xen/mmu_pv.c (ffffffff8288c699)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff82893fc7)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/mm/init_64.c (ffffffff8107a501)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/fault.c (ffffffff8107add0)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8108089f)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/tlb.c (ffffffff81083bf8)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81085e87)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff81089ef5)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a6e3b)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8108f078)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
```
```
In mm/gup.c (ffffffff8123a54b)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8123ccdd)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
```
```
In mm/mremap.c (ffffffff8124eade)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812512bb)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff81254b5f)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
```
```
In mm/hugetlb.c (ffffffff8126bad3)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81a271f3)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/migrate.c (ffffffff8128356b)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812a4a0e)
Location: arch/x86/include/asm/pgtable.h:883
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff81a08dc2)
Location: arch/x86/include/asm/pgtable.h:883
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
In arch/x86/xen/mmu_pv.c (ffffffff828a3b46)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff828ab777)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/mm/init_64.c (ffffffff8107e247)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/fault.c (ffffffff8107fcce)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8108439f)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/tlb.c (ffffffff810878a4)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089dad)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff8108dca3)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf4f2)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81092eff)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/gup.c (ffffffff8124b7af)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8124e948)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/mremap.c (ffffffff81260e33)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8126359b)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff81266f0f)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/hugetlb.c (ffffffff81286dd2)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81a97a9e)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/userfaultfd.c (ffffffff812bffcd)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff81a7868a)
Location: arch/x86/include/asm/pgtable.h:900
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
In arch/x86/xen/mmu_pv.c (ffffffff828a6bef)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff828ae785)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/mm/init_64.c (ffffffff8107f2d7)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/fault.c (ffffffff81080d5e)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810850df)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/tlb.c (ffffffff81088594)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108aa1d)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff8108e903)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c596d)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81093f6f)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/gup.c (ffffffff81259c9f)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8125cee5)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/mremap.c (ffffffff8126f5cc)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81272063)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff8127580f)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/hugetlb.c (ffffffff812969d2)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81acf36c)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/migrate.c (ffffffff812aefed)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812d1f1d)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff81aafa3a)
Location: arch/x86/include/asm/pgtable.h:900
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
In arch/x86/xen/mmu_pv.c (ffffffff82ccd1b7)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff810479e5)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff81085ab7)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/fault.c (ffffffff81087e27)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/tlb.c (ffffffff8108aabf)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:sync_current_stack_to_mm
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cd98)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff81094c53)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8c48)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff82ceab69)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff82cec3bb)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_prolog
```
```
In mm/gup.c (ffffffff8128b31a)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff8128d517)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff8129ee64)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff8129fae9)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pmd
```
```
In mm/pagewalk.c (ffffffff812a2c88)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/vmalloc.c (ffffffff812a7222)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/swapfile.c (ffffffff812bdc8b)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812c9f8e)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7d75)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/migrate.c (ffffffff812e5083)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81307d0c)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff815e993a)
Location: arch/x86/include/asm/pgtable.h:900
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
In arch/x86/xen/mmu_pv.c (ffffffff82fb8ff3)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81bd4c6b)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff81086b7c)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cb4a)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff81094013)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd66ce)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff82fd83f0)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In mm/gup.c (ffffffff81294fda)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff8129f9c8)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff812aa224)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812aaf79)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff812ae5a8)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/vmalloc.c (ffffffff812b24a2)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/ioremap.c (ffffffff812b841b)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_page_range
```
```
In mm/swapfile.c (ffffffff812c97ab)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812d5bce)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81c40aa0)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/migrate.c (ffffffff812f0446)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81313a3c)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
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
In arch/x86/xen/mmu_pv.c (ffffffff831c36a0)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81bc70c2)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff81087832)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d73a)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810949b3)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e1122)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff831e2dec)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In mm/gup.c (ffffffff8129a6f4)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff812a5243)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff812af671)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812b03b6)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff812b3979)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/vmalloc.c (ffffffff812b8b89)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff812d041f)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff812dc862)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81c32a02)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/migrate.c (ffffffff812f675e)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81319be9)
Location: arch/x86/include/asm/pgtable.h:899
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
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
In arch/x86/xen/mmu_pv.c (ffffffff832a4124)
Location: arch/x86/include/asm/pgtable.h:870
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81c9a6c2)
Location: arch/x86/include/asm/pgtable.h:870
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff81096b9a)
Location: arch/x86/include/asm/pgtable.h:870
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109cfc3)
Location: arch/x86/include/asm/pgtable.h:870
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810a4923)
Location: arch/x86/include/asm/pgtable.h:870
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c49a9)
Location: arch/x86/include/asm/pgtable.h:870
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff832c678f)
Location: arch/x86/include/asm/pgtable.h:870
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In mm/gup.c (ffffffff812db0b5)
Location: arch/x86/include/asm/pgtable.h:870
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff812e67a0)
Location: arch/x86/include/asm/pgtable.h:870
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff812f0ea1)
Location: arch/x86/include/asm/pgtable.h:870
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812f1bf8)
Location: arch/x86/include/asm/pgtable.h:870
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff812f54f9)
Location: arch/x86/include/asm/pgtable.h:870
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/vmalloc.c (ffffffff812fb13b)
Location: arch/x86/include/asm/pgtable.h:870
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff8131596a)
Location: arch/x86/include/asm/pgtable.h:870
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81323a30)
Location: arch/x86/include/asm/pgtable.h:870
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81d513d3)
Location: arch/x86/include/asm/pgtable.h:870
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/migrate.c (ffffffff81340da8)
Location: arch/x86/include/asm/pgtable.h:870
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81366996)
Location: arch/x86/include/asm/pgtable.h:870
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
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
In arch/x86/xen/mmu_pv.c (ffffffff834533c9)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81e49b2c)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff810a9658)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b083a)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810b91c3)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff834773d6)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff834794ff)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In mm/percpu.c (ffffffff8348b8c9)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff8133ac63)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff8133d78e)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff81354a11)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813557bd)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff813593a0)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/vmalloc.c (ffffffff81362640)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81380f06)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8139161f)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81f2165c)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/migrate_device.c (ffffffff813b7c88)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
```
```
In mm/userfaultfd.c (ffffffff813e3d26)
Location: arch/x86/include/asm/pgtable.h:868
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
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
In arch/x86/xen/mmu_pv.c (ffffffff83e70929)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81067e90)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff810c2a5e)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810caf0a)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810d4b35)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea08d1)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff83ea367a)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In mm/percpu.c (ffffffff83ebc7d8)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff813b29fd)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_p4d_mask
```
```
In mm/memory.c (ffffffff813b67ae)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff813cef6f)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813cff2d)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff813d3c70)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/vmalloc.c (ffffffff813ddfd6)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813ff74e)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8140e61f)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff820cb7d3)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/migrate_device.c (ffffffff81439943)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8146b746)
Location: arch/x86/include/asm/pgtable.h:886
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
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
In arch/x86/xen/mmu_pv.c (ffffffff836917a9)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81069740)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff810c613e)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce53a)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810d8045)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4a3b)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff836c790a)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In mm/percpu.c (ffffffff836e4e58)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff813e74e4)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_p4d_mask
```
```
In mm/memory.c (ffffffff813eb1cc)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_p4d_range
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff8140362f)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff814049f0)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff81408640)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/vmalloc.c (ffffffff81412836)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff814327be)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff814419e2)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff8214fa63)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/migrate_device.c (ffffffff8146e6ef)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814a0549)
Location: arch/x86/include/asm/pgtable.h:887
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
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
In arch/x86/xen/mmu_pv.c (ffffffff838c12b9)
Location: arch/x86/include/asm/pgtable.h:1109
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81070c80)
Location: arch/x86/include/asm/pgtable.h:1109
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff810ce58e)
Location: arch/x86/include/asm/pgtable.h:1109
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d6c1a)
Location: arch/x86/include/asm/pgtable.h:1109
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810e08c5)
Location: arch/x86/include/asm/pgtable.h:1109
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f563b)
Location: arch/x86/include/asm/pgtable.h:1109
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff838f850a)
Location: arch/x86/include/asm/pgtable.h:1109
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In mm/percpu.c (ffffffff839176d4)
Location: arch/x86/include/asm/pgtable.h:1109
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff81412169)
Location: arch/x86/include/asm/pgtable.h:1109
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff814151f5)
Location: arch/x86/include/asm/pgtable.h:1109
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff8142fbaf)
Location: arch/x86/include/asm/pgtable.h:1109
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff81430fc0)
Location: arch/x86/include/asm/pgtable.h:1109
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff81434d60)
Location: arch/x86/include/asm/pgtable.h:1109
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/vmalloc.c (ffffffff8143f2a6)
Location: arch/x86/include/asm/pgtable.h:1109
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff8146bbde)
Location: arch/x86/include/asm/pgtable.h:1109
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8147bc52)
Location: arch/x86/include/asm/pgtable.h:1109
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff82232922)
Location: arch/x86/include/asm/pgtable.h:1109
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/migrate_device.c (ffffffff8149d163)
Location: arch/x86/include/asm/pgtable.h:1109
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/userfaultfd.c (ffffffff814cfbe9)
Location: arch/x86/include/asm/pgtable.h:1109
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
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
In mm/gup.c (0)
Location: include/asm-generic/5level-fixup.h:24
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/5level-fixup.h:24
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/5level-fixup.h:24
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/5level-fixup.h:24
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/5level-fixup.h:24
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/5level-fixup.h:24
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/5level-fixup.h:24
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: include/asm-generic/5level-fixup.h:24
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
In mm/gup.c (0)
Location: include/asm-generic/5level-fixup.h:24
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/5level-fixup.h:24
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/5level-fixup.h:24
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/5level-fixup.h:24
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/5level-fixup.h:24
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/5level-fixup.h:24
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/5level-fixup.h:24
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
In mm/gup.c (0)
Location: include/asm-generic/5level-fixup.h:24
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/5level-fixup.h:24
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/5level-fixup.h:24
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/5level-fixup.h:24
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/5level-fixup.h:24
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/5level-fixup.h:24
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/5level-fixup.h:24
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: include/asm-generic/5level-fixup.h:24
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
In mm/gup.c (0)
Location: include/asm-generic/pgtable-nopud.h:31
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable-nopud.h:31
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable-nopud.h:31
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable-nopud.h:31
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable-nopud.h:31
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable-nopud.h:31
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable-nopud.h:31
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/asm-generic/pgtable-nopud.h:31
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: include/asm-generic/pgtable-nopud.h:31
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/pgtable-nopud.h:31
Inline: True
```
```
In lib/ioremap.c (0)
Location: include/asm-generic/pgtable-nopud.h:31
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
In arch/x86/xen/mmu_pv.c (ffffffff82894bf8)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff8289c7a4)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/mm/init_64.c (ffffffff8107e2d7)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/fault.c (ffffffff8107fd5e)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810840df)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/tlb.c (ffffffff81087594)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810899dd)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff8108d8c3)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b0905)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81092f2f)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/gup.c (ffffffff812522ef)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81255535)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/mremap.c (ffffffff81267c1c)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8126a6b3)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff8126de5f)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128efb2)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81a6e1dc)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/migrate.c (ffffffff812a75cd)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812ca4fd)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff81a4e88a)
Location: arch/x86/include/asm/pgtable.h:900
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
In arch/x86/kernel/tboot.c (ffffffff8289497e)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/mm/init_64.c (ffffffff8106d3a5)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/fault.c (ffffffff8106dabe)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81070b89)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pgd
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/tlb.c (ffffffff81076204)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810782d4)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff8107c3f3)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8a8a)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810819af)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/gup.c (ffffffff812450bf)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81247c75)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/mremap.c (ffffffff81259f74)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8125c5a7)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff8125fe8c)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/hugetlb.c (ffffffff81280cc1)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a623)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/migrate.c (ffffffff8129901d)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812bb541)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff81a0b97a)
Location: arch/x86/include/asm/pgtable.h:900
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
In arch/x86/xen/mmu_pv.c (ffffffff828a7bef)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff828af767)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/mm/init_64.c (ffffffff8107e287)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/fault.c (ffffffff8107fd0e)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8108408f)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/tlb.c (ffffffff81087544)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108998d)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff8108d873)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c3804)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81092edf)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/gup.c (ffffffff8125008f)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812532d5)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/mremap.c (ffffffff812659bc)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81268453)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff8126bbff)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128cdc2)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81ada5ec)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/migrate.c (ffffffff812a53dd)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812c830d)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff81abac7a)
Location: arch/x86/include/asm/pgtable.h:900
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
In arch/x86/xen/mmu_pv.c (ffffffff828a7bf5)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff828af795)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/mm/init_64.c (ffffffff81080377)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
```
```
In arch/x86/mm/fault.c (ffffffff81081dfe)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810861cf)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/tlb.c (ffffffff81089674)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108bc2d)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff8108fc53)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c69aa)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8109542f)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/gup.c (ffffffff8125fa1f)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81262ce5)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/mremap.c (ffffffff8127535e)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81277dd3)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff8127b60f)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/hugetlb.c (ffffffff8129cb92)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81ae6aa2)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/migrate.c (ffffffff812b4b0d)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812d901d)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In lib/ioremap.c (ffffffff81ac70ca)
Location: arch/x86/include/asm/pgtable.h:900
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
</details>
</li>
</ul>

## Differences
