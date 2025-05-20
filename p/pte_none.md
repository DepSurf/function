# Function: <code>pte_none</code>

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
Location: arch/x86/include/asm/pgtable.h:452
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:452
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:452
Inline: True
```
```
In mm/filemap.c (0)
Location: arch/x86/include/asm/pgtable.h:452
Inline: True
```
```
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:452
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:452
Inline: True
```
```
In mm/mincore.c (0)
Location: arch/x86/include/asm/pgtable.h:452
Inline: True
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/pgtable.h:452
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:452
Inline: True
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:452
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/pgtable.h:452
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: arch/x86/include/asm/pgtable.h:452
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:452
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:452
Inline: True
```
```
In mm/memcontrol.c (0)
Location: arch/x86/include/asm/pgtable.h:452
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:452
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:452
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:452
Inline: True
```
```
In lib/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:452
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
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In mm/mincore.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In mm/hugetlb.c (ffffffff811fbeed)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/sparse-vmemmap.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In mm/memcontrol.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81283bc5)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In lib/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
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
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In mm/mincore.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In mm/hugetlb.c (ffffffff8120c996)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/sparse-vmemmap.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In mm/memcontrol.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In fs/userfaultfd.c (ffffffff812977b5)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
```
```
In lib/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:481
Inline: True
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
Location: arch/x86/include/asm/pgtable.h:620
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:620
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:620
Inline: True
```
```
In mm/shmem.c (0)
Location: arch/x86/include/asm/pgtable.h:620
Inline: True
```
```
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:620
Inline: True
```
```
In mm/memory.c (ffffffff811f6320)
Location: arch/x86/include/asm/pgtable.h:620
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mincore.c (0)
Location: arch/x86/include/asm/pgtable.h:620
Inline: True
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/pgtable.h:620
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: arch/x86/include/asm/pgtable.h:620
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:620
Inline: True
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:620
Inline: True
```
```
In mm/hugetlb.c (ffffffff81218303)
Location: arch/x86/include/asm/pgtable.h:620
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/sparse-vmemmap.c (0)
Location: arch/x86/include/asm/pgtable.h:620
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:620
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:620
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:620
Inline: True
```
```
In mm/memcontrol.c (0)
Location: arch/x86/include/asm/pgtable.h:620
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:620
Inline: True
```
```
In fs/userfaultfd.c (ffffffff812a50f9)
Location: arch/x86/include/asm/pgtable.h:620
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:620
Inline: True
```
```
In lib/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:620
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
In arch/x86/xen/mmu_pv.c (ffffffff826ad5e7)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
```
```
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (0)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
```
```
In mm/shmem.c (0)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
```
```
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
```
```
In mm/mincore.c (0)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
```
```
In mm/swap_state.c (0)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
```
```
In mm/hugetlb.c (ffffffff81233187)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/sparse-vmemmap.c (0)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
```
```
In mm/memcontrol.c (0)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
```
```
In fs/userfaultfd.c (ffffffff812c862f)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:635
Inline: True
```
```
In lib/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:635
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
In arch/x86/xen/mmu_pv.c (ffffffff826d68da)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/mm/init_64.c (ffffffff8107473a)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/pageattr.c (ffffffff8107886e)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pti.c (ffffffff826ef8e8)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efdfc)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f02a2)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/shmem.c (ffffffff8120f9cf)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff81227f85)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8122e17f)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mincore.c (ffffffff812323be)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mremap.c (ffffffff8123ae03)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8123c5b3)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/vmalloc.c (ffffffff81240c69)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
```
```
In mm/madvise.c (ffffffff812462e7)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8124861a)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/hugetlb.c (ffffffff81256d22)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/sparse-vmemmap.c (ffffffff819ebcda)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/migrate.c (ffffffff8126e0e4)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff8127711f)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8127ceb5)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff8127fbe7)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff81290aeb)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812935fa)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff812f14dc)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff8131a04d)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffff819cfb54)
Location: arch/x86/include/asm/pgtable.h:677
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
In arch/x86/xen/mmu_pv.c (ffffffff8288c823)
Location: arch/x86/include/asm/pgtable.h:702
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/mm/init_64.c (ffffffff8107a62a)
Location: arch/x86/include/asm/pgtable.h:702
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/pageattr.c (ffffffff8107f05b)
Location: arch/x86/include/asm/pgtable.h:702
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pti.c (ffffffff828a669b)
Location: arch/x86/include/asm/pgtable.h:702
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6ab9)
Location: arch/x86/include/asm/pgtable.h:702
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a6faa)
Location: arch/x86/include/asm/pgtable.h:702
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/shmem.c (ffffffff812227aa)
Location: arch/x86/include/asm/pgtable.h:702
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8123b7fd)
Location: arch/x86/include/asm/pgtable.h:702
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812423bb)
Location: arch/x86/include/asm/pgtable.h:702
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mincore.c (ffffffff81245b91)
Location: arch/x86/include/asm/pgtable.h:702
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mremap.c (ffffffff8124eff1)
Location: arch/x86/include/asm/pgtable.h:702
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812509cd)
Location: arch/x86/include/asm/pgtable.h:702
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/vmalloc.c (ffffffff8125553f)
Location: arch/x86/include/asm/pgtable.h:702
Inline: True
```
```
In mm/madvise.c (ffffffff8125a707)
Location: arch/x86/include/asm/pgtable.h:702
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8125cbf0)
Location: arch/x86/include/asm/pgtable.h:702
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/hugetlb.c (ffffffff8126b2cb)
Location: arch/x86/include/asm/pgtable.h:702
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/sparse-vmemmap.c (ffffffff81a26f48)
Location: arch/x86/include/asm/pgtable.h:702
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/migrate.c (ffffffff81282f55)
Location: arch/x86/include/asm/pgtable.h:702
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff8128896e)
Location: arch/x86/include/asm/pgtable.h:702
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff81291a1f)
Location: arch/x86/include/asm/pgtable.h:702
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff81294557)
Location: arch/x86/include/asm/pgtable.h:702
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff812a5b20)
Location: arch/x86/include/asm/pgtable.h:702
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812a7b6e)
Location: arch/x86/include/asm/pgtable.h:702
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81305e9c)
Location: arch/x86/include/asm/pgtable.h:702
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff81331120)
Location: arch/x86/include/asm/pgtable.h:702
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffff81a09145)
Location: arch/x86/include/asm/pgtable.h:702
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
In arch/x86/xen/mmu_pv.c (ffffffff828a3cc2)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/mm/init_64.c (ffffffff8107e379)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81082ef6)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pti.c (ffffffff828bec8a)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bf159)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf660)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/shmem.c (ffffffff81231db0)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8124cce3)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812547af)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mincore.c (ffffffff81257ce9)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mremap.c (ffffffff81261353)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81262cad)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/vmalloc.c (ffffffff81267891)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
```
```
In mm/madvise.c (ffffffff812757e4)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81277dcd)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8127b0ce)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff812865a2)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/sparse-vmemmap.c (ffffffff81a977f3)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/migrate.c (ffffffff8129f3ad)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812a35af)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812abdc8)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812b0819)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff812c1207)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812c3cf1)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (ffffffff81327434)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff81358f28)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffff81a789c6)
Location: arch/x86/include/asm/pgtable.h:719
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
In arch/x86/xen/mmu_pv.c (ffffffff828a6d5c)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/mm/init_64.c (ffffffff8107f409)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81083fc6)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pti.c (ffffffff828c5171)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c55d4)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c5ae3)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/shmem.c (ffffffff8123fe70)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8125b213)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81262d0f)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mincore.c (ffffffff812661f9)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mremap.c (ffffffff8126faf6)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8127145d)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/vmalloc.c (ffffffff812761f1)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
```
```
In mm/madvise.c (ffffffff812847b4)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812878bd)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8128abae)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81296187)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/sparse-vmemmap.c (ffffffff81acf0ba)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/migrate.c (ffffffff812ae8c6)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812b4aaf)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812bdee3)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812c2279)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff812d3157)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812d5a53)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (ffffffff8133a214)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff81371178)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffff81aafd76)
Location: arch/x86/include/asm/pgtable.h:719
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
In arch/x86/xen/mmu_pv.c (ffffffff82cccf22)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd
```
```
In arch/x86/mm/init_64.c (ffffffff81085d9e)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e070)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:unmap_pte_range
```
```
In arch/x86/mm/pti.c (ffffffff82ce8207)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_setup_vsyscall
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82ce87e4)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8d7f)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In mm/shmem.c (ffffffff8126e68d)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff812893ab)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812922f5)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault_around
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pte_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff81296544)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mprotect.c (ffffffff8129e743)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812a0122)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812a1b5b)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/vmalloc.c (ffffffff812a7989)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pte_range
```
```
In mm/madvise.c (ffffffff812b695d)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812b983e)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff812bd8dd)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff812c9704)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7a7e)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/migrate.c (ffffffff812e3f8e)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812ea056)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812f379a)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_copy
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_pages
```
```
In mm/memcontrol.c (ffffffff812f912a)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff813089a5)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mfill_zeropage_pte
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/hmm.c (ffffffff8130b6b0)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (ffffffff8137458e)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff813b7d01)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In lib/ioremap.c (ffffffff815e98bf)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff82fb8d5e)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd
```
```
In arch/x86/mm/init_64.c (ffffffff81086e30)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108df40)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
```
```
In arch/x86/mm/pti.c (ffffffff82fd5c26)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_setup_vsyscall
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82fd61f6)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd6805)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In mm/shmem.c (ffffffff8127908b)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8129308b)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129cba5)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault_around
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pte_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff812a14b7)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mprotect.c (ffffffff812a9b03)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812ab57f)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812ad410)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/vmalloc.c (ffffffff812b2a68)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pte_range
```
```
In mm/ioremap.c (ffffffff812b815b)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_pte_range
```
```
In mm/madvise.c (ffffffff812c2bad)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812c52a7)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff812c93fd)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff812d5313)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/sparse-vmemmap.c (ffffffff81c407b0)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/migrate.c (ffffffff812efc7b)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812f5233)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812fef77)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_pages
```
```
In mm/memcontrol.c (ffffffff81304fbb)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff81314782)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/hmm.c (ffffffff81317578)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (ffffffff813824e6)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff813c9791)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In arch/x86/xen/mmu_pv.c (ffffffff831c341d)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/mm/init_64.c (ffffffff81087ae6)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108eaff)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
```
```
In arch/x86/mm/pti.c (ffffffff831e0883)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff831e0c51)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e126b)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/filemap.c (ffffffff8125fe24)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/shmem.c (ffffffff8127e039)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff81298a44)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812a2294)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff812a6caf)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mprotect.c (ffffffff812aef8e)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812b0982)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812b258f)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/vmalloc.c (ffffffff812b7d53)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff812c9a29)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812cbf55)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff812cff7f)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff812dc0e5)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/sparse-vmemmap.c (ffffffff81c32819)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/migrate.c (ffffffff812f55fb)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812fb77b)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff81305b83)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff8130a44b)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff8131a92f)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/hmm.c (ffffffff8131d278)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (ffffffff8138956c)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff813d0892)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In arch/x86/xen/mmu_pv.c (ffffffff832a3e57)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/mm/init_64.c (ffffffff81096e68)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109e5dc)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
```
```
In arch/x86/mm/pti.c (ffffffff832c3f61)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff832c4329)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c4af5)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/filemap.c (ffffffff8129c794)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (ffffffff812d94af)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812e3604)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:insert_pfn
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff812e818f)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mprotect.c (ffffffff812f077e)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812f2312)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812f4187)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/vmalloc.c (ffffffff812fa485)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff8130ea49)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81311125)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff81315490)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81323251)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/sparse-vmemmap.c (ffffffff81d5126e)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/migrate.c (ffffffff8133fbfd)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff813454f0)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff8134f9ed)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff81355bab)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff8136782b)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff8136a613)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (ffffffff813d6866)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff81421ec8)
Location: arch/x86/include/asm/pgtable.h:725
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In arch/x86/xen/mmu_pv.c (ffffffff834530dc)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/mm/init_64.c (ffffffff810a9888)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b1fac)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
```
```
In arch/x86/mm/pti.c (ffffffff8347687c)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83476cea)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83477527)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/filemap.c (ffffffff812f390e)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (ffffffff8133948b)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813449ad)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:insert_pfn
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff813494a9)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mprotect.c (ffffffff81353e22)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81356073)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81358162)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8135d804)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81361776)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff81376873)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8137c15e)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff81380a07)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81390b8a)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/sparse-vmemmap.c (ffffffff81f214a6)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/migrate.c (ffffffff813b49be)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff813b7082)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813bb4fe)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff813c7cc1)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff813ce8ec)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff813e42c1)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff813e81d6)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (ffffffff8145d9f0)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff814994a5)
Location: arch/x86/include/asm/pgtable.h:723
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In arch/x86/xen/mmu_pv.c (ffffffff83e705d2)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/mm/init_64.c (ffffffff810c2ca1)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cc7fc)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
```
```
In arch/x86/mm/pti.c (ffffffff83e9f8c2)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83ea0005)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea0b63)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In mm/filemap.c (ffffffff8135dc6c)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (ffffffff813b0da0)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813bcbb1)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:insert_pfn
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff813c1898)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mprotect.c (ffffffff813ce2cc)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff813d06b6)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff813d27ca)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff813d8667)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff813dd117)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff813f41e1)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff813f98fe)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff813ff30e)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81412461)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/sparse-vmemmap.c (ffffffff820cb463)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81421a4c)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
```
```
In mm/migrate.c (ffffffff81433b0e)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff81438bd3)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8143d90a)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff8144beab)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff81453369)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff8146bd59)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814700e7)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (ffffffff814ed420)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152e73c)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6609)
Location: arch/x86/include/asm/pgtable.h:740
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
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
In arch/x86/xen/mmu_pv.c (ffffffff8369144c)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/mm/init_64.c (ffffffff810c6381)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cfe1c)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
```
```
In arch/x86/mm/pti.c (ffffffff836c3a52)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff836c414c)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4c6e)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In mm/filemap.c (ffffffff8138fb4b)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (ffffffff813e51a5)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813f151d)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_p4d_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff813f6731)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mprotect.c (ffffffff81402ba9)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81404b90)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff814075f3)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/rmap.c (ffffffff8140ce55)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8141197f)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff81427867)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8142c78d)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff814321f2)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81445a29)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/sparse-vmemmap.c (ffffffff8214f6f6)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff814567bd)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate.c (ffffffff81469589)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff8146f466)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff814816cc)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_pages
```
```
In mm/memcontrol.c (ffffffff81488f74)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff814a090d)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_pte_zeropage
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814a48bd)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/userfaultfd.c (ffffffff8152412e)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81566a4c)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
```
In fs/hugetlbfs/inode.c (ffffffff8162e6cf)
Location: arch/x86/include/asm/pgtable.h:741
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
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
In arch/x86/xen/mmu_pv.c (ffffffff838c0f5c)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/mm/init_64.c (ffffffff810ce7d1)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d84fc)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
```
```
In arch/x86/mm/pti.c (ffffffff838f4642)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff838f4dcc)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f586e)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In mm/filemap.c (ffffffff813b94e2)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (ffffffff8140fa35)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81420a2d)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:set_pte_range
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:alloc_anon_folio
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:insert_pfn
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff814223e1)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mprotect.c (ffffffff8142f1bc)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81431163)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81433c67)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/rmap.c (ffffffff81439549)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8143e17c)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff81461045)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81465edd)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff8146b5e2)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8147f469)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8148503d)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff822325c1)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81491242)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate.c (ffffffff8149849b)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff8149d31d)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff814b066f)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_pages
```
```
In mm/memcontrol.c (ffffffff814b8ee2)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff814d2b06)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814d58ed)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/userfaultfd.c (ffffffff81558690)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8159d29f)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_category
  - fs/proc/task_mmu.c:make_uffd_wp_pte
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
```
In fs/hugetlbfs/inode.c (ffffffff81667b9f)
Location: arch/x86/include/asm/pgtable.h:948
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
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
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000eebf48)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:808
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable
```
```
In arch/powerpc/xmon/xmon.c (c00000000010d518)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:808
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:show_pte
```
```
In mm/shmem.c (c000000000391bd4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:808
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (c0000000003b6450)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:808
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003c4138)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:808
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (c0000000003c86b4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:808
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mremap.c (c0000000003d36e8)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:808
Inline: True
```
```
In mm/page_vma_mapped.c (c0000000003d55d4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:808
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/vmalloc.c (c0000000003dc584)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:808
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_page_range_noflush
  - mm/vmalloc.c:vunmap_page_range
```
```
In mm/madvise.c (c0000000003f30d4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:808
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (c0000000003f7e14)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:808
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (c0000000003fc214)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:808
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (c00000000040fcd0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:808
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/sparse-vmemmap.c (c000000000eedbb0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:808
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/migrate.c (c0000000004345ec)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:808
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (c00000000043c3fc)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:808
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (c00000000044a220)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:808
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (c000000000450e48)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:808
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (c00000000046b9d4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:808
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (c00000000046fb28)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:808
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (c000000000501668)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:808
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (c00000000054d1a0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:808
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (c000000000eca274)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:808
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
In arch/riscv/mm/init.c (0)
Location: arch/riscv/include/asm/pgtable.h:209
Inline: True
```
```
In mm/shmem.c (0)
Location: arch/riscv/include/asm/pgtable.h:209
Inline: True
```
```
In mm/gup.c (0)
Location: arch/riscv/include/asm/pgtable.h:209
Inline: True
```
```
In mm/memory.c (0)
Location: arch/riscv/include/asm/pgtable.h:209
Inline: True
```
```
In mm/mincore.c (0)
Location: arch/riscv/include/asm/pgtable.h:209
Inline: True
```
```
In mm/mremap.c (0)
Location: arch/riscv/include/asm/pgtable.h:209
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: arch/riscv/include/asm/pgtable.h:209
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/riscv/include/asm/pgtable.h:209
Inline: True
```
```
In mm/madvise.c (0)
Location: arch/riscv/include/asm/pgtable.h:209
Inline: True
```
```
In mm/swap_state.c (0)
Location: arch/riscv/include/asm/pgtable.h:209
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/riscv/include/asm/pgtable.h:209
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/riscv/include/asm/pgtable.h:209
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: arch/riscv/include/asm/pgtable.h:209
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/riscv/include/asm/pgtable.h:209
Inline: True
```
```
In mm/memcontrol.c (0)
Location: arch/riscv/include/asm/pgtable.h:209
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/riscv/include/asm/pgtable.h:209
Inline: True
```
```
In mm/hmm.c (0)
Location: arch/riscv/include/asm/pgtable.h:209
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: arch/riscv/include/asm/pgtable.h:209
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/riscv/include/asm/pgtable.h:209
Inline: True
```
```
In lib/ioremap.c (0)
Location: arch/riscv/include/asm/pgtable.h:209
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
In arch/x86/xen/mmu_pv.c (ffffffff82894d65)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/mm/init_64.c (ffffffff8107e409)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81082fc6)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pti.c (ffffffff828b0109)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b056c)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b0a7b)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/shmem.c (ffffffff812384c0)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff81253863)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8125b35f)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mincore.c (ffffffff8125e849)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mremap.c (ffffffff81268146)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81269aad)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/vmalloc.c (ffffffff8126e841)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
```
```
In mm/madvise.c (ffffffff8127ce04)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8127fe54)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8128318e)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8128e767)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/sparse-vmemmap.c (ffffffff81a6df2a)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/migrate.c (ffffffff812a6ea6)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812ad08f)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812b64c3)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812ba859)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff812cb737)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812ce033)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (ffffffff813327f4)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff81369758)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffff81a4ebc6)
Location: arch/x86/include/asm/pgtable.h:719
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
In arch/x86/mm/init_64.c (ffffffff8106d539)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/pageattr.c (ffffffff810717a7)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pti.c (ffffffff828a82f6)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a86f1)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8c00)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/shmem.c (ffffffff8122b4c2)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff812464eb)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8124d780)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff81250c9d)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mremap.c (ffffffff8125a371)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8125bd40)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/vmalloc.c (ffffffff812605d2)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
```
```
In mm/madvise.c (ffffffff8126ec62)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81271c9b)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81274c73)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81280526)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a459)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/migrate.c (ffffffff812988ea)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff8129e0d6)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812a766d)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812aba17)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff812bc5a9)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812bee99)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (ffffffff813233ae)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff813595ea)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffff81a0bcb7)
Location: arch/x86/include/asm/pgtable.h:719
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
In arch/x86/xen/mmu_pv.c (ffffffff828a7d5c)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/mm/init_64.c (ffffffff8107e3b9)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81082f76)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pti.c (ffffffff828c3008)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c346b)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c397a)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/shmem.c (ffffffff81236260)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff81251603)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812590ff)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mincore.c (ffffffff8125c5e9)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mremap.c (ffffffff81265ee6)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8126784d)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/vmalloc.c (ffffffff8126c5e1)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
```
```
In mm/madvise.c (ffffffff8127aba4)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8127dcad)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81280f9e)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8128c577)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/sparse-vmemmap.c (ffffffff81ada33a)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/migrate.c (ffffffff812a4cb6)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812aae9f)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812b42d3)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812b8669)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff812c9547)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812cbe43)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (ffffffff813302c4)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff81367228)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffff81abafb6)
Location: arch/x86/include/asm/pgtable.h:719
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
In arch/x86/xen/mmu_pv.c (ffffffff828a7d62)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
```
```
In arch/x86/mm/init_64.c (ffffffff810804a9)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pte_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81085096)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pti.c (ffffffff828c6191)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c6611)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c6b20)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/shmem.c (ffffffff8124653d)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff81260f9c)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81268aff)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
```
```
In mm/mincore.c (ffffffff8126bfd2)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mremap.c (ffffffff81275888)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812771e3)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/vmalloc.c (ffffffff8127c121)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
```
```
In mm/madvise.c (ffffffff8128a785)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8128d85d)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81290cae)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8129c362)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/sparse-vmemmap.c (ffffffff81ae67f0)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/migrate.c (ffffffff812b5812)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812bb1ef)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812c47a3)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812c8ca9)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (ffffffff812da227)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812dcba1)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (ffffffff81342c1b)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff8137a877)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In lib/ioremap.c (ffffffff81ac7406)
Location: arch/x86/include/asm/pgtable.h:719
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
</details>
</li>
</ul>

## Differences
