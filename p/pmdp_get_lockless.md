# Function: <code>pmdp_get_lockless</code>

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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133b6c1)
Location: include/linux/pgtable.h:399
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/filemap.c (ffffffff8135d8d1)
Location: include/linux/pgtable.h:399
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/vmscan.c (ffffffff8137faab)
Location: include/linux/pgtable.h:399
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/gup.c (ffffffff813b0817)
Location: include/linux/pgtable.h:399
Inline: True
```
```
In mm/memory.c (ffffffff813bcb0a)
Location: include/linux/pgtable.h:399
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
```
```
In mm/mincore.c (ffffffff813c170c)
Location: include/linux/pgtable.h:399
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff813cde74)
Location: include/linux/pgtable.h:399
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff813d0d38)
Location: include/linux/pgtable.h:399
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff813d38c1)
Location: include/linux/pgtable.h:399
Inline: True
```
```
In mm/madvise.c (ffffffff813f4073)
Location: include/linux/pgtable.h:399
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff813ff8fb)
Location: include/linux/pgtable.h:399
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff81417fa0)
Location: include/linux/pgtable.h:399
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate_device.c (ffffffff814390b9)
Location: include/linux/pgtable.h:399
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff8144744e)
Location: include/linux/pgtable.h:399
Inline: True
Inline callers:
  - mm/khugepaged.c:find_pmd_or_thp_or_none
```
```
In mm/memcontrol.c (ffffffff81458627)
Location: include/linux/pgtable.h:399
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8145fe2d)
Location: include/linux/pgtable.h:399
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff8146d431)
Location: include/linux/pgtable.h:399
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff81470a06)
Location: include/linux/pgtable.h:399
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff81471ff1)
Location: include/linux/pgtable.h:399
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/proc/task_mmu.c (ffffffff8152dd33)
Location: include/linux/pgtable.h:399
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:smaps_pte_range
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
In kernel/events/core.c (ffffffff8136d0bd)
Location: include/linux/pgtable.h:407
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813b1082)
Location: include/linux/pgtable.h:407
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/gup.c (ffffffff813e7674)
Location: include/linux/pgtable.h:407
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff813f4931)
Location: include/linux/pgtable.h:407
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffffffff81403237)
Location: include/linux/pgtable.h:407
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff814077a8)
Location: include/linux/pgtable.h:407
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81409ac3)
Location: include/linux/pgtable.h:407
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map_lock
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/ksm.c (ffffffff81453b26)
Location: include/linux/pgtable.h:407
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/khugepaged.c (ffffffff8147cb1e)
Location: include/linux/pgtable.h:407
Inline: True
Inline callers:
  - mm/khugepaged.c:find_pmd_or_thp_or_none
```
```
In mm/userfaultfd.c (ffffffff814a1e40)
Location: include/linux/pgtable.h:407
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/hmm.c (ffffffff814a4ec3)
Location: include/linux/pgtable.h:407
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a6915)
Location: include/linux/pgtable.h:407
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff81524dfc)
Location: include/linux/pgtable.h:407
Inline: True
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
In kernel/events/core.c (ffffffff813962fd)
Location: include/linux/pgtable.h:516
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813da602)
Location: include/linux/pgtable.h:516
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/gup.c (ffffffff814122f2)
Location: include/linux/pgtable.h:516
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff81420f65)
Location: include/linux/pgtable.h:516
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffffffff8142f7c7)
Location: include/linux/pgtable.h:516
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81433e36)
Location: include/linux/pgtable.h:516
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff814362e3)
Location: include/linux/pgtable.h:516
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map_lock
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/ksm.c (ffffffff8148e365)
Location: include/linux/pgtable.h:516
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/khugepaged.c (ffffffff814ac1be)
Location: include/linux/pgtable.h:516
Inline: True
Inline callers:
  - mm/khugepaged.c:find_pmd_or_thp_or_none
```
```
In mm/userfaultfd.c (ffffffff814d3200)
Location: include/linux/pgtable.h:516
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/hmm.c (ffffffff814d5f83)
Location: include/linux/pgtable.h:516
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d7995)
Location: include/linux/pgtable.h:516
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff81558a8d)
Location: include/linux/pgtable.h:516
Inline: True
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
