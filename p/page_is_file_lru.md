# Function: <code>page_is_file_lru</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8125f64a)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff812658de)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:page_check_dirty_writeback
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/compaction.c (ffffffff81282b0e)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812968ad)
Location: include/linux/mm_inline.h:22
Inline: True
```
```
In mm/mprotect.c (ffffffff8129e854)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mempolicy.c (ffffffff812cc1fb)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff812e1453)
Location: include/linux/mm_inline.h:22
Inline: True
```
```
In mm/migrate.c (ffffffff812e7b27)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff812f097b)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memory-failure.c (ffffffff81301a63)
Location: include/linux/mm_inline.h:22
Inline: True
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
In mm/swap.c (ffffffff81269bc8)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff812702ba)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:page_check_dirty_writeback
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/compaction.c (ffffffff8128d0ce)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff81290de5)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/mlock.c (ffffffff812a1c66)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mprotect.c (ffffffff812a9c0a)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mempolicy.c (ffffffff812d7a8a)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff812ec30c)
Location: include/linux/mm_inline.h:22
Inline: True
```
```
In mm/migrate.c (ffffffff812f2ef7)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff812fc0ed)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memory-failure.c (ffffffff8130d91d)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/memory-failure.c:isolate_page
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
In mm/swap.c (ffffffff8126d8df)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8127613b)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/compaction.c (ffffffff81291b95)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff81296445)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/gup.c (ffffffff812970c1)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
```
```
In mm/mlock.c (ffffffff812a7540)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mprotect.c (ffffffff812af095)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/memory_hotplug.c (ffffffff812c6a2b)
Location: include/linux/mm_inline.h:22
Inline: True
```
```
In mm/mempolicy.c (ffffffff812defa9)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/migrate.c (ffffffff812f9297)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff813030be)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memory-failure.c (ffffffff81313e85)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
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
In mm/swap.c (ffffffff812a9f4e)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff812b2794)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/compaction.c (ffffffff812d18ef)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff812d6bd5)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/gup.c (ffffffff812d7a74)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
```
```
In mm/mlock.c (ffffffff812e881d)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mprotect.c (ffffffff812f08a2)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/memory_hotplug.c (ffffffff8130b4d7)
Location: include/linux/mm_inline.h:22
Inline: True
```
```
In mm/mempolicy.c (ffffffff81326c39)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/migrate.c (ffffffff81343581)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff8134ce2e)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memory-failure.c (ffffffff8135f168)
Location: include/linux/mm_inline.h:22
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
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
In mm/vmscan.c (ffffffff8130f0f1)
Location: include/linux/mm_inline.h:32
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff81330d29)
Location: include/linux/mm_inline.h:32
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mprotect.c (ffffffff81353c12)
Location: include/linux/mm_inline.h:32
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/memory_hotplug.c (ffffffff81374222)
Location: include/linux/mm_inline.h:32
Inline: True
```
```
In mm/mempolicy.c (ffffffff8139629b)
Location: include/linux/mm_inline.h:32
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/migrate.c (ffffffff813b5ddb)
Location: include/linux/mm_inline.h:32
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff813c4446)
Location: include/linux/mm_inline.h:32
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memory-failure.c (ffffffff813da374)
Location: include/linux/mm_inline.h:32
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
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
In mm/compaction.c (ffffffff813a7bb0)
Location: include/linux/mm_inline.h:32
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mprotect.c (ffffffff813ce0e4)
Location: include/linux/mm_inline.h:32
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/memory_hotplug.c (ffffffff813f1cf5)
Location: include/linux/mm_inline.h:32
Inline: True
```
```
In mm/mempolicy.c (ffffffff814162a0)
Location: include/linux/mm_inline.h:32
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/migrate.c (ffffffff81435f6f)
Location: include/linux/mm_inline.h:32
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff81448535)
Location: include/linux/mm_inline.h:32
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memory-failure.c (ffffffff814618e0)
Location: include/linux/mm_inline.h:32
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
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
In mm/mprotect.c (ffffffff81402984)
Location: include/linux/mm_inline.h:32
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/memory_hotplug.c (ffffffff814258a2)
Location: include/linux/mm_inline.h:32
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff8146bbf8)
Location: include/linux/mm_inline.h:32
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
```
```
In mm/khugepaged.c (ffffffff8147dde0)
Location: include/linux/mm_inline.h:32
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memory-failure.c (ffffffff8149757f)
Location: include/linux/mm_inline.h:32
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
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
In mm/memory_hotplug.c (ffffffff81452af4)
Location: include/linux/mm_inline.h:33
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/khugepaged.c (ffffffff814ac673)
Location: include/linux/mm_inline.h:33
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
