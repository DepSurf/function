# Function: <code>radix__pmd_bad</code>

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
In arch/powerpc/mm/hugetlbpage.c (c0000000000a5d1c)
Location: arch/powerpc/include/asm/book3s/64/radix.h:214
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
```
```
In mm/gup.c (c0000000003b8420)
Location: arch/powerpc/include/asm/book3s/64/radix.h:214
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003bb118)
Location: arch/powerpc/include/asm/book3s/64/radix.h:214
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mincore.c (c0000000003c8608)
Location: arch/powerpc/include/asm/book3s/64/radix.h:214
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (c0000000003d2130)
Location: arch/powerpc/include/asm/book3s/64/radix.h:214
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d3f14)
Location: arch/powerpc/include/asm/book3s/64/radix.h:214
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (c0000000003d6b24)
Location: arch/powerpc/include/asm/book3s/64/radix.h:214
Inline: True
```
```
In mm/vmalloc.c (c0000000003dbb50)
Location: arch/powerpc/include/asm/book3s/64/radix.h:214
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_page_range
```
```
In mm/madvise.c (c0000000003f3004)
Location: arch/powerpc/include/asm/book3s/64/radix.h:214
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (c0000000003fd044)
Location: arch/powerpc/include/asm/book3s/64/radix.h:214
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (c0000000004133d8)
Location: arch/powerpc/include/asm/book3s/64/radix.h:214
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (c000000000435158)
Location: arch/powerpc/include/asm/book3s/64/radix.h:214
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/memcontrol.c (c000000000456e90)
Location: arch/powerpc/include/asm/book3s/64/radix.h:214
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/hmm.c (c000000000470664)
Location: arch/powerpc/include/asm/book3s/64/radix.h:214
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (c00000000054d6c8)
Location: arch/powerpc/include/asm/book3s/64/radix.h:214
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
