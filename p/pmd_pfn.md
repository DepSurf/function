# Function: <code>pmd_pfn</code>

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
In arch/x86/xen/mmu.c (ffffffff81f62a77)
Location: arch/x86/include/asm/pgtable.h:150
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff81069a81)
Location: arch/x86/include/asm/pgtable.h:150
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/fault.c (ffffffff8106a7aa)
Location: arch/x86/include/asm/pgtable.h:150
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8106d3f9)
Location: arch/x86/include/asm/pgtable.h:150
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In fs/proc/task_mmu.c (ffffffff81278675)
Location: arch/x86/include/asm/pgtable.h:150
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In arch/x86/xen/mmu.c (ffffffff81f8a658)
Location: arch/x86/include/asm/pgtable.h:161
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff81069809)
Location: arch/x86/include/asm/pgtable.h:161
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/fault.c (ffffffff8106a526)
Location: arch/x86/include/asm/pgtable.h:161
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8106d75e)
Location: arch/x86/include/asm/pgtable.h:161
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
```
```
In arch/x86/mm/gup.c (ffffffff8107155a)
Location: arch/x86/include/asm/pgtable.h:161
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
```
```
In mm/memory.c (ffffffff811d8ab9)
Location: arch/x86/include/asm/pgtable.h:161
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/huge_memory.c (ffffffff8121486a)
Location: arch/x86/include/asm/pgtable.h:161
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In fs/proc/task_mmu.c (ffffffff812a4d53)
Location: arch/x86/include/asm/pgtable.h:161
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In arch/x86/xen/mmu.c (ffffffff81fc5a52)
Location: arch/x86/include/asm/pgtable.h:161
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff8106d3e9)
Location: arch/x86/include/asm/pgtable.h:161
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/fault.c (ffffffff8106e0c6)
Location: arch/x86/include/asm/pgtable.h:161
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810713ea)
Location: arch/x86/include/asm/pgtable.h:161
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
```
```
In arch/x86/mm/gup.c (ffffffff810750d4)
Location: arch/x86/include/asm/pgtable.h:161
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
```
```
In mm/memory.c (ffffffff811e7f89)
Location: arch/x86/include/asm/pgtable.h:161
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/huge_memory.c (ffffffff81226dfa)
Location: arch/x86/include/asm/pgtable.h:161
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In fs/dax.c (ffffffff8129b98e)
Location: arch/x86/include/asm/pgtable.h:161
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812ba6bd)
Location: arch/x86/include/asm/pgtable.h:161
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In arch/x86/mm/init_64.c (ffffffff8106c9c9)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/fault.c (ffffffff8106d606)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81070df4)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
```
```
In mm/gup.c (ffffffff811f0f50)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
```
```
In mm/memory.c (ffffffff811f3129)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/huge_memory.c (ffffffff81232caa)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In fs/dax.c (ffffffff812aa847)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff812c870f)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_pfn(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81020f30)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/mm/init_64.c (ffffffff810719de)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/fault.c (ffffffff8107263f)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8107650b)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5e42)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/shmem.c (ffffffff811eedeb)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff812059ae)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812089e3)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:free_pgd_range
```
```
In mm/mincore.c (ffffffff8121156d)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81218004)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81219385)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8121a7ba)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/madvise.c (ffffffff8122335a)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81229040)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff812354e4)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
```
```
In mm/mempolicy.c (ffffffff81237407)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff8123cb7d)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8124b1cc)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff8125277d)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (ffffffff812583f7)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8125ed1d)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff8126bffe)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff8126e62a)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff812ce0e8)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff812eba43)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff810705d0-ffffffff8107061c: pmd_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_pfn(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81021b9e)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/mm/init_64.c (ffffffff8107469d)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff810791b2)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/kmmio.c (ffffffff8107fe26)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efbfc)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/shmem.c (ffffffff8120f930)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff81226e2a)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81229a4b)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:free_pgd_range
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff812322e2)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812390c5)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8123ac01)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8123c79a)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff8123d8f3)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/madvise.c (ffffffff812461ca)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8124a35d)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81258403)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
```
```
In mm/mempolicy.c (ffffffff8125a942)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81260464)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8126ddda)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81276b96)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (ffffffff8127cde9)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81282ff5)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff81290a4f)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff81293337)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff812f863d)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff81318efb)
Location: arch/x86/include/asm/pgtable.h:199
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81073150-ffffffff81073199: pmd_pfn (STB_LOCAL)
ffffffff81228d00-ffffffff81228d49: pmd_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_pfn(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81021340)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/mm/init_64.c (ffffffff8107a58d)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8107fa69)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/kmmio.c (ffffffff81086966)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a68b9)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/shmem.c (ffffffff812226f0)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff81239eaf)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8123cf65)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:free_pgd_range
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff81245ab2)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8124d65c)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124ee12)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81250ba6)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81251ea3)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/madvise.c (ffffffff8125a5ea)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8125e99d)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8126cad3)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
```
```
In mm/mempolicy.c (ffffffff8126e808)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81274bc4)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81282c4a)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff8128bad5)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (ffffffff8129194d)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81299045)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff812a5a32)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812a7834)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff8130c3c9)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8132ffab)
Location: arch/x86/include/asm/pgtable.h:201
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff810791f0-ffffffff81079239: pmd_pfn (STB_LOCAL)
ffffffff8123c5a0-ffffffff8123c5e9: pmd_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_pfn(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81022ea7)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/mm/init_64.c (ffffffff8107e2d4)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pageattr.c (ffffffff81083424)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a57c)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bef6b)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/shmem.c (ffffffff81231cf9)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8124b106)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124ebdd)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff81257c03)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8125f65d)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8126116b)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81262e86)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81264184)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/madvise.c (ffffffff812756cf)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812796ce)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
```
```
In mm/hugetlb.c (ffffffff81287efd)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
```
```
In mm/mempolicy.c (ffffffff81289ecf)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff8128f6b6)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a0e85)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812a670e)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In mm/khugepaged.c (ffffffff812ab0cb)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff812b4437)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff812c1124)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812c4963)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff8133390f)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81357ddd)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8107ce00-ffffffff8107ce49: pmd_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_pfn(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810237e7)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/mm/init_64.c (ffffffff8107f364)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pageattr.c (ffffffff810844f4)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff8108b1ec)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c53e4)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/shmem.c (ffffffff8123fdb9)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff812595f6)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125d19d)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff81266113)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8126de6d)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8126f904)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81271636)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff812729f4)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/madvise.c (ffffffff8128469f)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812891ae)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
```
```
In mm/hugetlb.c (ffffffff81297afd)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
```
```
In mm/mempolicy.c (ffffffff81299a3f)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff8129f437)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812ae6ea)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812b7be7)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In mm/khugepaged.c (ffffffff812bca64)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff812c5d57)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff812d3074)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812d63a8)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff813474d4)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8137000d)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8107de90-ffffffff8107ded9: pmd_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_pfn(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025cf5)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pmd_walk
```
```
In arch/x86/mm/init_64.c (ffffffff81085c19)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108daed)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
```
```
In arch/x86/mm/kmmio.c (ffffffff81092490)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82ce85f5)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/shmem.c (ffffffff8126e5d8)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8128ac9d)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8128fcec)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pte_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:free_pud_range
Direct callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_pte_range
```
```
In mm/mincore.c (ffffffff8129645b)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8129e504)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8129ff73)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812a1c32)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/pagewalk.c (ffffffff812a24d8)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/pgtable-generic.c (ffffffff812a37b6)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/madvise.c (ffffffff812b6834)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812bbb70)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812cb197)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
```
```
In mm/mempolicy.c (ffffffff812ced97)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff812d3a86)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812e3d4a)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812ecdb8)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In mm/khugepaged.c (ffffffff812f11fc)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff812fba3f)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff81307e77)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage_pte
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/hmm.c (ffffffff8130b19a)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pmd
```
```
In fs/dax.c (ffffffff8138d8af)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813b8030)
Location: arch/x86/include/asm/pgtable.h:220
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81086303-ffffffff81086359: pmd_pfn (STB_LOCAL)
ffffffff81287cc0-ffffffff81287d09: pmd_pfn (STB_LOCAL)
ffffffff8128bf50-ffffffff8128bf99: pmd_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_pfn(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81026410)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pmd_walk
```
```
In arch/x86/mm/init_64.c (ffffffff81086cc5)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d9bd)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
```
```
In arch/x86/mm/kmmio.c (ffffffff81091b30)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82fd6013)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/shmem.c (ffffffff81278fd6)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8129495d)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129a76c)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:remap_pte_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:free_pud_range
Direct callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
```
```
In mm/mincore.c (ffffffff812a13ce)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812a98c4)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812ab3db)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812ad734)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/pagewalk.c (ffffffff812ade11)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/pgtable-generic.c (ffffffff812af096)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/madvise.c (ffffffff812c2a84)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812c7620)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812d6da7)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
```
```
In mm/mempolicy.c (ffffffff812da6d7)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff812df486)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812efaa9)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812f800b)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In mm/khugepaged.c (ffffffff812fc903)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8130768f)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff81313e7b)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/hmm.c (ffffffff8131705a)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pmd
```
```
In fs/dax.c (ffffffff8139f32f)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813c9ef0)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81bd8c47-ffffffff81bd8c9d: pmd_pfn (STB_LOCAL)
ffffffff81291be0-ffffffff81291c29: pmd_pfn (STB_LOCAL)
ffffffff81296fb0-ffffffff81296ff9: pmd_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_pfn(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81028d3d)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/mm/init_64.c (ffffffff81087979)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e574)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
```
```
In arch/x86/mm/kmmio.c (ffffffff81092670)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff831e0a7e)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/filemap.c (ffffffff8125fcd4)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/shmem.c (ffffffff8127df86)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8129a39d)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812a0967)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:free_pud_range
Direct callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff812a6bcb)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812aed54)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812b07db)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812b25e8)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812b3208)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/pgtable-generic.c (ffffffff812b4146)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_mkinvalid
```
```
In mm/vmalloc.c (ffffffff812b8d9d)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff812c9904)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812cdf64)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812ddfd7)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
```
```
In mm/mempolicy.c (ffffffff812e1f47)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff812e7da6)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812f5429)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812fe5bb)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (ffffffff8130366e)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8130de0f)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff8131a038)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/hmm.c (ffffffff8131d6e3)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff813a609f)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813d1550)
Location: arch/x86/include/asm/pgtable.h:219
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81bcaaf7-ffffffff81bcab47: pmd_pfn (STB_LOCAL)
ffffffff8129c2c0-ffffffff8129c30d: pmd_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_pfn(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102d47d)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/mm/init_64.c (ffffffff81096ceb)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109e035)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
```
```
In arch/x86/mm/kmmio.c (ffffffff810a2390)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff832c415d)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/filemap.c (ffffffff8129c644)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (ffffffff812dad40)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812e4e6b)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:free_pud_range
Direct callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:zap_pte_range
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff812e80ab)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812f0544)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812f2019)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812f41d7)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812f4d96)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/pgtable-generic.c (ffffffff812f5d26)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_mkinvalid
```
```
In mm/vmalloc.c (ffffffff812fb352)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8130e924)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff813133e4)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff813251e7)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
```
```
In mm/mempolicy.c (ffffffff81329027)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff8132c1b4)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_range
```
```
In mm/ksm.c (ffffffff8132fcd6)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff8133fa29)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff8134815b)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In mm/khugepaged.c (ffffffff8134d3d8)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81358c6f)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8135f460)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff81366d6c)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff8136aa83)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff813f5b0f)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81422a50)
Location: arch/x86/include/asm/pgtable.h:190
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81c9ffdf-ffffffff81ca002f: pmd_pfn (STB_LOCAL)
ffffffff812dcdc0-ffffffff812dce0d: pmd_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_pfn(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810322c3)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/mm/init_64.c (ffffffff810a97f0)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pgtable.c (ffffffff810ad591)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b197f)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
```
```
In arch/x86/mm/kmmio.c (ffffffff810b6a14)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810b9875)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In mm/filemap.c (ffffffff812f37e5)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (ffffffff8133a8e8)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8134679b)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:free_pud_range
Direct callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:insert_pages
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff813493c4)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff8134c626)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff81353a78)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81355d87)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff813581b0)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81358c86)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/pgtable-generic.c (ffffffff81359c56)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_mkinvalid
```
```
In mm/rmap.c (ffffffff8135e9ff)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/vmalloc.c (ffffffff81362855)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff813767b5)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8137e780)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81393b3b)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
```
```
In mm/mempolicy.c (ffffffff8139828c)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff8139bcc7)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/ksm.c (ffffffff813a00a2)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff813b4a92)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff813b6e9d)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813be468)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In mm/khugepaged.c (ffffffff813c7bce)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff813d2e92)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff813d9b79)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff813e41cb)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff813e8c5d)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81499b6a)
Location: arch/x86/include/asm/pgtable.h:193
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff810a8070-ffffffff810a80c0: pmd_pfn (STB_LOCAL)
ffffffff8133ca20-ffffffff8133ca77: pmd_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_pfn(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81039bc4)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/mm/init_64.c (ffffffff810c2c00)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pgtable.c (ffffffff810c76d4)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cc0dd)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
```
```
In arch/x86/mm/kmmio.c (ffffffff810d1c5e)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810d550b)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In mm/filemap.c (ffffffff8135db3f)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/vmscan.c (ffffffff8137fbf7)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
  - mm/vmscan.c:walk_pmd_range
  - mm/vmscan.c:walk_pte_range
```
```
In mm/gup.c (ffffffff813b2400)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813beb8a)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:free_pud_range
Direct callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:insert_pages
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff813c1798)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff813c51a5)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff813cdf27)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff813d03a6)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff813d281a)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813d355a)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/pgtable-generic.c (ffffffff813d4629)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_mkinvalid
```
```
In mm/rmap.c (ffffffff813d98bc)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/vmalloc.c (ffffffff813de1f1)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff813f4119)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff813fd192)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb_vmemmap.c (ffffffff8141414d)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/mempolicy.c (ffffffff81418023)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff8141ef7c)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81433bec)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff814389e2)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81440ccc)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8144bd9d)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff814586ac)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8145ff34)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff8146bc65)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff81470bdf)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8152ddb2)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff813b47a0-ffffffff813b47f7: pmd_pfn (STB_LOCAL)
ffffffff8143bae0-ffffffff8143bb39: pmd_pfn (STB_LOCAL)
ffffffff81447220-ffffffff81447279: pmd_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_pfn(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810396d4)
Location: arch/x86/include/asm/pgtable.h:195
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/mm/init_64.c (ffffffff810c62e0)
Location: arch/x86/include/asm/pgtable.h:195
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pgtable.c (ffffffff810cae34)
Location: arch/x86/include/asm/pgtable.h:195
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cf715)
Location: arch/x86/include/asm/pgtable.h:195
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
```
```
In arch/x86/mm/kmmio.c (ffffffff810d510e)
Location: arch/x86/include/asm/pgtable.h:195
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810d8a42)
Location: arch/x86/include/asm/pgtable.h:195
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In mm/vmscan.c (ffffffff813b117b)
Location: arch/x86/include/asm/pgtable.h:195
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/gup.c (ffffffff813e7150)
Location: arch/x86/include/asm/pgtable.h:195
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_huge_pmd
```
```
In mm/memory.c (ffffffff813ee3b5)
Location: arch/x86/include/asm/pgtable.h:195
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:free_pud_range
```
```
In mm/mlock.c (ffffffff813f96d5)
Location: arch/x86/include/asm/pgtable.h:195
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mremap.c (ffffffff81405116)
Location: arch/x86/include/asm/pgtable.h:195
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff814079da)
Location: arch/x86/include/asm/pgtable.h:195
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81409a71)
Location: arch/x86/include/asm/pgtable.h:195
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map_lock
  - mm/pgtable-generic.c:pte_offset_map_nolock
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/rmap.c (ffffffff8140dd65)
Location: arch/x86/include/asm/pgtable.h:195
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/vmalloc.c (ffffffff81412a4b)
Location: arch/x86/include/asm/pgtable.h:195
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff814282be)
Location: arch/x86/include/asm/pgtable.h:195
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb_vmemmap.c (ffffffff814476ad)
Location: arch/x86/include/asm/pgtable.h:195
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/mempolicy.c (ffffffff8144b325)
Location: arch/x86/include/asm/pgtable.h:195
Inline: True
```
```
In mm/migrate_device.c (ffffffff8146f147)
Location: arch/x86/include/asm/pgtable.h:195
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81476570)
Location: arch/x86/include/asm/pgtable.h:195
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In mm/khugepaged.c (ffffffff8147ca1e)
Location: arch/x86/include/asm/pgtable.h:195
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_huge_page
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81489936)
Location: arch/x86/include/asm/pgtable.h:195
Inline: True
```
```
In mm/memory-failure.c (ffffffff8149569a)
Location: arch/x86/include/asm/pgtable.h:195
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/hmm.c (ffffffff814a5187)
Location: arch/x86/include/asm/pgtable.h:195
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81567cfa)
Location: arch/x86/include/asm/pgtable.h:195
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff8147c900-ffffffff8147c959: pmd_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_pfn(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103fb84)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/mm/init_64.c (ffffffff810ce730)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pgtable.c (ffffffff810d3384)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d7df5)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
```
```
In arch/x86/mm/kmmio.c (ffffffff810dd816)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810e12c2)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In mm/vmscan.c (ffffffff813da6fb)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/gup.c (ffffffff81411dd0)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_huge_pmd
```
```
In mm/memory.c (ffffffff81419ea5)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:free_pud_range
```
```
In mm/mlock.c (ffffffff81425383)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mremap.c (ffffffff814315f6)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81433fd1)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81436291)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map_lock
  - mm/pgtable-generic.c:pte_offset_map_nolock
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/rmap.c (ffffffff8143a581)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/vmalloc.c (ffffffff8143f4bb)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff81461a80)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb_vmemmap.c (ffffffff81480e33)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_pmd_entry
```
```
In mm/mempolicy.c (ffffffff81484d0e)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pmd
```
```
In mm/migrate_device.c (ffffffff8149dc48)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a5e00)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In mm/khugepaged.c (ffffffff814acc4e)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_huge_page
Direct callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff814b86a6)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
```
```
In mm/memory-failure.c (ffffffff814c4e84)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff814d3303)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:move_pages
```
```
In mm/hmm.c (ffffffff814d56e5)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8159ece8)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_thp_category
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff814a0a90-ffffffff814a0ae9: pmd_pfn (STB_LOCAL)
ffffffff814abaa0-ffffffff814abaf9: pmd_pfn (STB_LOCAL)
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
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_pfn(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023947)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/mm/init_64.c (ffffffff8107e364)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pageattr.c (ffffffff810834f4)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a1ac)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b037c)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/shmem.c (ffffffff81238409)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff81251c46)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812557ed)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff8125e763)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812664bd)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81267f54)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81269c86)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff8126b044)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/madvise.c (ffffffff8127ccef)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8128178e)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
```
```
In mm/hugetlb.c (ffffffff812900dd)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
```
```
In mm/mempolicy.c (ffffffff8129201f)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81297a17)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a6cca)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812b01c7)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In mm/khugepaged.c (ffffffff812b5044)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff812be337)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff812cb654)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812ce988)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff8133fab4)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813685ed)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8107ce90-ffffffff8107ced9: pmd_pfn (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff8106d4d0)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pageattr.c (ffffffff8107227d)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
```
```
In arch/x86/mm/kmmio.c (ffffffff81078c4a)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a855c)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/shmem.c (ffffffff8122b44c)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff812449c9)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81247ee0)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:free_pgd_range
```
```
In mm/mincore.c (ffffffff81250bd3)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81258bc0)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8125a230)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8125beea)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff8125d068)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/madvise.c (ffffffff8126eb83)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81274f3e)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81281da2)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
```
```
In mm/mempolicy.c (ffffffff81283be8)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff8128960c)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff8129877e)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812a1684)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In mm/khugepaged.c (ffffffff812a6072)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff812af435)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff812bc512)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812bf696)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff813307db)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8135990b)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_pfn(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810237a7)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/mm/init_64.c (ffffffff8107e314)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pageattr.c (ffffffff810834a4)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a15c)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c327b)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/shmem.c (ffffffff812361a9)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8124f9e6)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125358d)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff8125c503)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8126425d)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81265cf4)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81267a26)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81268de4)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/madvise.c (ffffffff8127aa8f)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8127f59e)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128deed)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
```
```
In mm/mempolicy.c (ffffffff8128fe2f)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81295827)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a4ada)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812adfd7)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In mm/khugepaged.c (ffffffff812b2e54)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff812bc147)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff812c9464)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812cc798)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff8133d584)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813660bd)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8107ce40-ffffffff8107ce89: pmd_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pmd_pfn(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023c57)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/mm/init_64.c (ffffffff81080404)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pageattr.c (ffffffff810851ab)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff8108c3fc)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c6421)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/shmem.c (ffffffff81246489)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8125f373)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81262f80)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff8126beec)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81273c1d)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81275696)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812773bc)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81278774)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/madvise.c (ffffffff8128a66f)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8128f26e)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
```
```
In mm/hugetlb.c (ffffffff8129dc99)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
```
```
In mm/mempolicy.c (ffffffff8129f2ca)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff812a5645)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812b5638)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812be32e)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In mm/khugepaged.c (ffffffff812c328f)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff812cc915)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff812da144)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812dd4f8)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff8135049a)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81379ca6)
Location: arch/x86/include/asm/pgtable.h:218
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff8107ef30-ffffffff8107ef79: pmd_pfn (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
