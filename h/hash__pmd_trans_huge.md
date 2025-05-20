# Function: <code>hash__pmd_trans_huge</code>

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
In arch/powerpc/mm/pgtable.c (c000000000087be0)
Location: arch/powerpc/include/asm/book3s/64/hash-64k.h:247
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable.c:__find_linux_pte
```
```
In arch/powerpc/mm/book3s64/subpage_prot.c (c00000000009f790)
Location: arch/powerpc/include/asm/book3s/64/hash-64k.h:247
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/subpage_prot.c:subpage_walk_pmd_entry
```
```
In mm/filemap.c (c0000000003650f0)
Location: arch/powerpc/include/asm/book3s/64/hash-64k.h:247
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (c0000000003b6ee0)
Location: arch/powerpc/include/asm/book3s/64/hash-64k.h:247
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (c0000000003c4010)
Location: arch/powerpc/include/asm/book3s/64/hash-64k.h:247
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (c0000000003c8530)
Location: arch/powerpc/include/asm/book3s/64/hash-64k.h:247
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (c0000000003d27c0)
Location: arch/powerpc/include/asm/book3s/64/hash-64k.h:247
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d42c0)
Location: arch/powerpc/include/asm/book3s/64/hash-64k.h:247
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (c0000000003d5d58)
Location: arch/powerpc/include/asm/book3s/64/hash-64k.h:247
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (c0000000003d6c60)
Location: arch/powerpc/include/asm/book3s/64/hash-64k.h:247
Inline: True
```
```
In mm/rmap.c (c0000000003d8830)
Location: arch/powerpc/include/asm/book3s/64/hash-64k.h:247
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (c0000000003f3200)
Location: arch/powerpc/include/asm/book3s/64/hash-64k.h:247
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (c0000000003fd140)
Location: arch/powerpc/include/asm/book3s/64/hash-64k.h:247
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (c000000000413390)
Location: arch/powerpc/include/asm/book3s/64/hash-64k.h:247
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (c00000000043507c)
Location: arch/powerpc/include/asm/book3s/64/hash-64k.h:247
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (c000000000440f40)
Location: arch/powerpc/include/asm/book3s/64/hash-64k.h:247
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (c000000000456ce0)
Location: arch/powerpc/include/asm/book3s/64/hash-64k.h:247
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (c00000000046bd50)
Location: arch/powerpc/include/asm/book3s/64/hash-64k.h:247
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (c0000000004708f0)
Location: arch/powerpc/include/asm/book3s/64/hash-64k.h:247
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (c000000000501cc0)
Location: arch/powerpc/include/asm/book3s/64/hash-64k.h:247
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (c0000000005160e0)
Location: arch/powerpc/include/asm/book3s/64/hash-64k.h:247
Inline: True
```
```
In fs/proc/task_mmu.c (c00000000054d610)
Location: arch/powerpc/include/asm/book3s/64/hash-64k.h:247
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
