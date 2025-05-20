# Function: <code>pmd_page_paddr</code>

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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/fault.c (ffff8000100ad4f0)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - arch/arm64/mm/fault.c:show_pte
```
```
In arch/arm64/mm/mmu.c (ffff8000100ae53c)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - arch/arm64/mm/mmu.c:kern_addr_valid
  - arch/arm64/mm/mmu.c:init_pmd
  - arch/arm64/mm/mmu.c:init_pmd
```
```
In arch/arm64/mm/pageattr.c (ffff8000100b0730)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - arch/arm64/mm/pageattr.c:kernel_page_present
```
```
In arch/arm64/mm/hugetlbpage.c (ffff8000100b10d0)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - arch/arm64/mm/hugetlbpage.c:huge_pte_offset
  - arch/arm64/mm/hugetlbpage.c:huge_pte_alloc
```
```
In arch/arm64/mm/dump.c (ffff8000100b1e0c)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
```
```
In virt/kvm/arm/mmu.c (ffff8000100c8658)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:stage2_wp_range
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:stage2_get_leaf_entry
  - virt/kvm/arm/mmu.c:__create_hyp_mappings
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
```
```
In mm/shmem.c (ffff8000102d314c)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffff8000102f1118)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffff8000102f45f8)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
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
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffff8000102fcff0)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffff80001030510c)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffff8000103060c4)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffff8000103072c4)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffff800010307a68)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
```
```
In mm/vmalloc.c (ffff80001030bd38)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffff80001031ea80)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffff800010322234)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffff800010326080)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/mempolicy.c (ffff8000103386b8)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffff800010da0ce8)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffff80001033ec04)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffff800010350e3c)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
```
```
In mm/huge_memory.c (ffff800010355f20)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffff80001035f4a0)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffff800010368ad4)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (0)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
```
```
In mm/userfaultfd.c (ffff800010378c58)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/hmm.c (ffff80001037b714)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffff8000103f9438)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffff800010439bc4)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffff800010d8975c)
Location: arch/arm64/include/asm/pgtable.h:491
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
