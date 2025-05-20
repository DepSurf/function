# Function: <code>radix__pte_none</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000eebf60)
Location: arch/powerpc/include/asm/book3s/64/radix.h:185
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable
```
```
In arch/powerpc/xmon/xmon.c (c00000000010d51c)
Location: arch/powerpc/include/asm/book3s/64/radix.h:185
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:show_pte
```
```
In mm/shmem.c (c000000000391bd8)
Location: arch/powerpc/include/asm/book3s/64/radix.h:185
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (c0000000003b6454)
Location: arch/powerpc/include/asm/book3s/64/radix.h:185
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003c413c)
Location: arch/powerpc/include/asm/book3s/64/radix.h:185
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
In mm/mincore.c (c0000000003c86b8)
Location: arch/powerpc/include/asm/book3s/64/radix.h:185
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mremap.c (c0000000003d36ec)
Location: arch/powerpc/include/asm/book3s/64/radix.h:185
Inline: True
```
```
In mm/page_vma_mapped.c (c0000000003d55d8)
Location: arch/powerpc/include/asm/book3s/64/radix.h:185
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/vmalloc.c (c0000000003dc588)
Location: arch/powerpc/include/asm/book3s/64/radix.h:185
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_page_range_noflush
  - mm/vmalloc.c:vunmap_page_range
```
```
In mm/madvise.c (c0000000003f30d8)
Location: arch/powerpc/include/asm/book3s/64/radix.h:185
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (c0000000003f7e18)
Location: arch/powerpc/include/asm/book3s/64/radix.h:185
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (c0000000003fc218)
Location: arch/powerpc/include/asm/book3s/64/radix.h:185
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (c00000000040fcd4)
Location: arch/powerpc/include/asm/book3s/64/radix.h:185
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
In mm/sparse-vmemmap.c (c000000000eedbb8)
Location: arch/powerpc/include/asm/book3s/64/radix.h:185
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/migrate.c (c0000000004345f0)
Location: arch/powerpc/include/asm/book3s/64/radix.h:185
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (c00000000043c400)
Location: arch/powerpc/include/asm/book3s/64/radix.h:185
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (c00000000044a224)
Location: arch/powerpc/include/asm/book3s/64/radix.h:185
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
In mm/memcontrol.c (c000000000450e4c)
Location: arch/powerpc/include/asm/book3s/64/radix.h:185
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (c00000000046b9d8)
Location: arch/powerpc/include/asm/book3s/64/radix.h:185
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (c00000000046fb2c)
Location: arch/powerpc/include/asm/book3s/64/radix.h:185
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (c00000000050166c)
Location: arch/powerpc/include/asm/book3s/64/radix.h:185
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (c00000000054d1a4)
Location: arch/powerpc/include/asm/book3s/64/radix.h:185
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (c000000000eca278)
Location: arch/powerpc/include/asm/book3s/64/radix.h:185
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
