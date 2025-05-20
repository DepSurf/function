# Function: <code>folio_is_file_lru</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813032b6)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__folio_activate
  - mm/swap.c:__folio_activate
  - mm/swap.c:lru_note_cost_folio
  - mm/swap.c:pagevec_move_tail_fn
  - mm/swap.c:pagevec_move_tail_fn
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8130f4c1)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_write_folio
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_write_folio
```
```
In mm/compaction.c (ffffffff81330c1f)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff81336345)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/gup.c (ffffffff81337ca5)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
```
```
In mm/mlock.c (ffffffff8134add3)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/mprotect.c (ffffffff81353c27)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/memory_hotplug.c (ffffffff81374236)
Location: include/linux/mm_inline.h:27
Inline: True
```
```
In mm/mempolicy.c (ffffffff813962ac)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/migrate.c (ffffffff813b5def)
Location: include/linux/mm_inline.h:27
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
In mm/khugepaged.c (ffffffff813c445a)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memory-failure.c (ffffffff813da389)
Location: include/linux/mm_inline.h:27
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
In mm/swap.c (ffffffff8136f6f5)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:lru_add_fn
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:lru_gen_add_folio
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/vmscan.c (ffffffff8137e79a)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:get_pfn_folio
  - mm/vmscan.c:update_batch_size
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_write_folio
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_write_folio
  - mm/vmscan.c:lru_gen_add_folio
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/compaction.c (ffffffff813a7a82)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff813ad5c5)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/gup.c (ffffffff813ae97a)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
```
```
In mm/mlock.c (ffffffff813c39ed)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/mprotect.c (ffffffff813ce0f8)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/memory_hotplug.c (ffffffff813f1d09)
Location: include/linux/mm_inline.h:27
Inline: True
```
```
In mm/mempolicy.c (ffffffff814162b1)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/migrate.c (ffffffff81435f83)
Location: include/linux/mm_inline.h:27
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
In mm/khugepaged.c (ffffffff81448549)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memory-failure.c (ffffffff81461e49)
Location: include/linux/mm_inline.h:27
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
In mm/swap.c (ffffffff813a1815)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:lru_add_fn
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:lru_gen_add_folio
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/vmscan.c (ffffffff813afe81)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:get_pfn_folio
  - mm/vmscan.c:update_batch_size
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_write_folio
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_write_folio
  - mm/vmscan.c:lru_gen_add_folio
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/compaction.c (ffffffff813daff1)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff813e1c8b)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/gup.c (ffffffff813e327a)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
```
```
In mm/mlock.c (ffffffff813f8ca4)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/mprotect.c (ffffffff81402998)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/memory_hotplug.c (ffffffff814258b6)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/mempolicy.c (ffffffff8144954e)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_folio_add
```
```
In mm/migrate.c (ffffffff8146bc0d)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:migrate_folio_done
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff8147ddf4)
Location: include/linux/mm_inline.h:27
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_folio
```
```
In mm/memory-failure.c (ffffffff8149758f)
Location: include/linux/mm_inline.h:27
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
In mm/swap.c (ffffffff813cb496)
Location: include/linux/mm_inline.h:28
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:lru_add_fn
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:lru_gen_add_folio
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/vmscan.c (ffffffff813d936e)
Location: include/linux/mm_inline.h:28
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:get_pfn_folio
  - mm/vmscan.c:update_batch_size
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_write_folio
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_write_folio
  - mm/vmscan.c:lru_gen_add_folio
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/compaction.c (ffffffff81405177)
Location: include/linux/mm_inline.h:28
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff8140c4cb)
Location: include/linux/mm_inline.h:28
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/gup.c (ffffffff8140db06)
Location: include/linux/mm_inline.h:28
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
```
```
In mm/mlock.c (ffffffff8142485f)
Location: include/linux/mm_inline.h:28
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/mprotect.c (ffffffff8142ef97)
Location: include/linux/mm_inline.h:28
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/memory_hotplug.c (ffffffff81452b08)
Location: include/linux/mm_inline.h:28
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/mempolicy.c (ffffffff81482fa5)
Location: include/linux/mm_inline.h:28
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_folio_add
```
```
In mm/migrate.c (ffffffff8149abc1)
Location: include/linux/mm_inline.h:28
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:migrate_folio_done
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff814ad093)
Location: include/linux/mm_inline.h:28
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_folio
```
```
In mm/memory-failure.c (ffffffff814c66c4)
Location: include/linux/mm_inline.h:28
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
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
