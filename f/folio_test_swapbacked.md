# Function: <code>folio_test_swapbacked</code>

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
In kernel/futex/core.c (ffffffff811b2748)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In mm/filemap.c (ffffffff812f42e7)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff812fefe8)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_mark_dirty
```
```
In mm/swap.c (ffffffff813032b6)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
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
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/truncate.c (ffffffff81308851)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8130f4c1)
Location: include/linux/page-flags.h:521
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
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_write_folio
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_write_folio
```
```
In mm/shmem.c (ffffffff813185f4)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff8131d541)
Location: include/linux/page-flags.h:521
Inline: True
```
```
In mm/compaction.c (ffffffff81330c1f)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff81336345)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/gup.c (ffffffff81337ca5)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
```
```
In mm/memory.c (ffffffff81343cac)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mlock.c (ffffffff8134add3)
Location: include/linux/page-flags.h:521
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
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8135d8d6)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memory_hotplug.c (ffffffff81374236)
Location: include/linux/page-flags.h:521
Inline: True
```
```
In mm/madvise.c (ffffffff813768ed)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8137a0b9)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:sio_write_complete
```
```
In mm/swap_state.c (ffffffff8137b6ce)
Location: include/linux/page-flags.h:521
Inline: True
```
```
In mm/swapfile.c (ffffffff8137fa67)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_free_swap
```
```
In mm/hugetlb.c (ffffffff8138c3ae)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_basepage_index
```
```
In mm/mempolicy.c (ffffffff813962ac)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/ksm.c (ffffffff813a0692)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff813b5def)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff813c1723)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff813c445a)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff813d0860)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff813da389)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/task_mmu.c (ffffffff81499683)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff814b1303)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex/core.c (ffffffff811f35e8)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In mm/filemap.c (ffffffff8135b6c6)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff81369777)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_mark_dirty
```
```
In mm/swap.c (ffffffff8136f6f5)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:lru_add_fn
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:lru_gen_add_folio
  - mm/swap.c:lru_gen_add_folio
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/vmscan.c (ffffffff8137e79a)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:isolate_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
  - mm/vmscan.c:walk_pte_range
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
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_write_folio
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_write_folio
  - mm/vmscan.c:lru_gen_add_folio
  - mm/vmscan.c:lru_gen_add_folio
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/shmem.c (ffffffff8138c4eb)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff813911f1)
Location: include/linux/page-flags.h:500
Inline: True
```
```
In mm/compaction.c (ffffffff813a7a82)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff813ad5c5)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/gup.c (ffffffff813ae97a)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
```
```
In mm/memory.c (ffffffff813bbd57)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mlock.c (ffffffff813c39ed)
Location: include/linux/page-flags.h:500
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
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff813d8736)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memory_hotplug.c (ffffffff813f1d09)
Location: include/linux/page-flags.h:500
Inline: True
```
```
In mm/madvise.c (ffffffff813f4262)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff813f7ba9)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:sio_write_complete
```
```
In mm/swap_state.c (ffffffff813f9053)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff813fe5c5)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/swapfile.c:folio_free_swap
```
```
In mm/hugetlb.c (ffffffff8140ae81)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_basepage_index
```
```
In mm/mempolicy.c (ffffffff814162b1)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/ksm.c (ffffffff8141fe75)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff81435f83)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff814437d4)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff81448549)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff81455e74)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81461e49)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/task_mmu.c (ffffffff8152d83a)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff81547cc3)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex/core.c (ffffffff81207d9e)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In mm/filemap.c (ffffffff8138d523)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff8139b914)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_mark_dirty
```
```
In mm/swap.c (ffffffff813a1815)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:lru_add_fn
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:lru_gen_add_folio
  - mm/swap.c:lru_gen_add_folio
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/vmscan.c (ffffffff813afe81)
Location: include/linux/page-flags.h:493
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
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
  - mm/vmscan.c:walk_pte_range
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
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_write_folio
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_write_folio
  - mm/vmscan.c:lru_gen_add_folio
  - mm/vmscan.c:lru_gen_add_folio
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/shmem.c (ffffffff813beafe)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff813c3bb1)
Location: include/linux/page-flags.h:493
Inline: True
```
```
In mm/compaction.c (ffffffff813daff1)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff813e1c8b)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/gup.c (ffffffff813e327a)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
```
```
In mm/memory.c (ffffffff813f076c)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mlock.c (ffffffff813f8ca4)
Location: include/linux/page-flags.h:493
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
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8140cf24)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/memory_hotplug.c (ffffffff814258b6)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/madvise.c (ffffffff814278d4)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8142ad69)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:sio_write_complete
```
```
In mm/swap_state.c (ffffffff8142be23)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff81431565)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/swapfile.c:folio_free_swap
```
```
In mm/hugetlb.c (ffffffff8143e52b)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_basepage_index
```
```
In mm/mempolicy.c (ffffffff8144954e)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_folio_add
```
```
In mm/ksm.c (ffffffff81454a87)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff8146bc0d)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:migrate_folio_done
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff81478dff)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_folio
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8147ddf4)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_folio
```
```
In mm/memcontrol.c (ffffffff8148cf15)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8149758f)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/task_mmu.c (ffffffff81565c6a)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff8157f8d8)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex/core.c (ffffffff8121ef1b)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In mm/filemap.c (ffffffff813b75e1)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff813c4383)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_mark_dirty
```
```
In mm/swap.c (ffffffff813cb496)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:lru_add_fn
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:lru_gen_add_folio
  - mm/swap.c:lru_gen_add_folio
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/vmscan.c (ffffffff813d936e)
Location: include/linux/page-flags.h:495
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
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
  - mm/vmscan.c:walk_pte_range
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
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_write_folio
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_write_folio
  - mm/vmscan.c:lru_gen_add_folio
  - mm/vmscan.c:lru_gen_add_folio
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/shmem.c (ffffffff813e9b03)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/util.c (ffffffff813ee761)
Location: include/linux/page-flags.h:495
Inline: True
```
```
In mm/compaction.c (ffffffff81405177)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff8140c4cb)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/gup.c (ffffffff8140db06)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
```
```
In mm/memory.c (ffffffff814200e7)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mlock.c (ffffffff8142485f)
Location: include/linux/page-flags.h:495
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
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff81439639)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_remove_rmap_pmd
  - mm/rmap.c:folio_add_file_rmap_pmd
```
```
In mm/memory_hotplug.c (ffffffff81452b08)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/madvise.c (ffffffff814610af)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8146450d)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/page_io.c:swap_read_folio_fs
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:sio_write_complete
```
```
In mm/swap_state.c (ffffffff81465583)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff8146a955)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/swapfile.c:folio_free_swap
```
```
In mm/mempolicy.c (ffffffff81482fa5)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_folio_add
```
```
In mm/ksm.c (ffffffff8148fc71)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff8149abc1)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:migrate_folio_done
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff814a83df)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_folio
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff814ad093)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_folio
```
```
In mm/memcontrol.c (ffffffff814bc852)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff814c66c4)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/task_mmu.c (ffffffff8159dc47)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff815b82f9)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
