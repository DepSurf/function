# Function: <code>folio_test_head</code>

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
In mm/filemap.c (ffffffff812f393e)
Location: include/linux/page-flags.h:781
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:filemap_free_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/truncate.c (ffffffff8130824a)
Location: include/linux/page-flags.h:781
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_partial_folio
```
```
In mm/vmscan.c (ffffffff8130e4e6)
Location: include/linux/page-flags.h:781
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81319399)
Location: include/linux/page-flags.h:781
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff8131df05)
Location: include/linux/page-flags.h:781
Inline: True
Inline callers:
  - mm/util.c:folio_mapcount
```
```
In mm/gup.c (ffffffff81337583)
Location: include/linux/page-flags.h:781
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff813402cf)
Location: include/linux/page-flags.h:781
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
```
```
In mm/mlock.c (ffffffff8134c093)
Location: include/linux/page-flags.h:781
Inline: True
Inline callers:
  - mm/mlock.c:mlock_folio
```
```
In mm/rmap.c (ffffffff8135e7a2)
Location: include/linux/page-flags.h:781
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:folio_referenced_one
  - mm/rmap.c:folio_referenced_one
```
```
In mm/swap_slots.c (ffffffff81383c30)
Location: include/linux/page-flags.h:781
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/hugetlb.c (ffffffff81391b5d)
Location: include/linux/page-flags.h:781
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81398af1)
Location: include/linux/page-flags.h:781
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
```
```
In mm/ksm.c (ffffffff813a092d)
Location: include/linux/page-flags.h:781
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff813b1694)
Location: include/linux/page-flags.h:781
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff813b7a6a)
Location: include/linux/page-flags.h:781
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c1c34)
Location: include/linux/page-flags.h:781
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff813d09e6)
Location: include/linux/page-flags.h:781
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/usercopy.c (ffffffff813e6c9a)
Location: include/linux/page-flags.h:781
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In fs/iomap/buffered-io.c (ffffffff81489b82)
Location: include/linux/page-flags.h:781
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
```
```
In fs/proc/task_mmu.c (ffffffff8149a8fc)
Location: include/linux/page-flags.h:781
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
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
In kernel/events/uprobes.c (ffffffff8134fa65)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8135e5b2)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_free_folio
  - mm/filemap.c:filemap_free_folio
  - mm/filemap.c:__filemap_remove_folio
  - mm/filemap.c:__filemap_remove_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
  - mm/filemap.c:trace_event_raw_event_mm_filemap_op_page_cache
```
```
In mm/page-writeback.c (ffffffff81369691)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_redirty_for_writepage
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:folio_write_one
```
```
In mm/folio-compat.c (ffffffff8136b320)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/folio-compat.c:pagecache_get_page
```
```
In mm/readahead.c (ffffffff8136c6c6)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff8136f75e)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:folio_add_lru
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:folio_rotate_reclaimable
  - mm/swap.c:lru_add_fn
  - mm/swap.c:lru_add_fn
  - mm/swap.c:put_pages_list
  - mm/swap.c:__folio_put
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/truncate.c (ffffffff81371760)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:mapping_evict_folio
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_cleanup_folio
  - mm/truncate.c:truncate_cleanup_folio
```
```
In mm/vmscan.c (ffffffff8137e6f1)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:isolate_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:update_batch_size
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:isolate_lru_folios
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
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
  - mm/vmscan.c:__acct_reclaim_writeback
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/shmem.c (ffffffff8138d900)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff81391a45)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/util.c:folio_copy
```
```
In mm/slab_common.c (ffffffff813a2487)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/slab_common.c:__ksize
  - mm/slab_common.c:__ksize
  - mm/slab_common.c:free_large_kmalloc
```
```
In mm/compaction.c (ffffffff813a7aed)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff813ad94c)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/gup.c (ffffffff813ae966)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff813bbcf1)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_mapping_folio
  - mm/memory.c:copy_present_pte
```
```
In mm/mlock.c (ffffffff813c4c37)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/rmap.c (ffffffff813d67a6)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:folio_not_mapped
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:folio_referenced_one
  - mm/rmap.c:folio_referenced_one
  - mm/rmap.c:folio_referenced_one
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:folio_get_anon_vma
```
```
In mm/memory_hotplug.c (ffffffff813f1a07)
Location: include/linux/page-flags.h:778
Inline: True
```
```
In mm/madvise.c (ffffffff813f4251)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swap_state.c (ffffffff813f96f7)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:swap_cache_get_folio
  - mm/swap_state.c:free_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff813fd156)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:folio_free_swap
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/swap_slots.c (ffffffff81401700)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/hugetlb.c (ffffffff814131c5)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff81418997)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
```
```
In mm/ksm.c (ffffffff8141f0fd)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/slub.c (ffffffff81425685)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:slab_pad_check
```
```
In mm/migrate.c (ffffffff81432af2)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff814380c6)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81443dd1)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814499e1)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8145b1a7)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/hugetlb_cgroup.c (ffffffff8145e255)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/page_isolation.c (ffffffff814649c8)
Location: include/linux/page-flags.h:778
Inline: True
```
```
In mm/secretmem.c (ffffffff8146b244)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_free_folio
```
```
In mm/userfaultfd.c (ffffffff8146d511)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
```
```
In mm/page_idle.c (ffffffff8146df93)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In mm/usercopy.c (ffffffff8146e871)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
  - mm/usercopy.c:check_heap_object
```
```
In fs/libfs.c (ffffffff814b9ce5)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - fs/libfs.c:simple_read_folio
```
```
In fs/fs-writeback.c (ffffffff814c048c)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/remap_range.c (ffffffff814d0abf)
Location: include/linux/page-flags.h:778
Inline: True
```
```
In fs/buffer.c (ffffffff814d2c4b)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - fs/buffer.c:block_is_partially_uptodate
  - fs/buffer.c:block_is_partially_uptodate
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:block_invalidate_folio
```
```
In fs/mpage.c (ffffffff814da256)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/verity/enable.c (ffffffff815040f9)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/iomap/buffered-io.c (ffffffff8151df25)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
  - fs/iomap/buffered-io.c:iomap_release_folio
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_folio
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/proc/task_mmu.c (ffffffff8152ee1c)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In fs/ext4/inode.c (ffffffff8157a2b4)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/readpage.c (ffffffff815a4d13)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff815de905)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6b0b)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fuse/dev.c (ffffffff8161afff)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/partitions/core.c (ffffffff8175524c)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In lib/iov_iter.c (ffffffff817d6563)
Location: include/linux/page-flags.h:778
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
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
In kernel/sched/fair.c (ffffffff81161f55)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/events/uprobes.c (ffffffff81380c34)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8138ca97)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:splice_folio_into_pipe
  - mm/filemap.c:splice_folio_into_pipe
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_free_folio
  - mm/filemap.c:filemap_free_folio
  - mm/filemap.c:__filemap_remove_folio
  - mm/filemap.c:__filemap_remove_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
  - mm/filemap.c:trace_event_raw_event_mm_filemap_op_page_cache
```
```
In mm/page-writeback.c (ffffffff8139b831)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_redirty_for_writepage
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/folio-compat.c (ffffffff8139d48e)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/folio-compat.c:pagecache_get_page
```
```
In mm/readahead.c (ffffffff8139e8f6)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff813a187e)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:folio_deactivate
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:folio_add_lru
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:folio_rotate_reclaimable
  - mm/swap.c:lru_add_fn
  - mm/swap.c:lru_add_fn
  - mm/swap.c:put_pages_list
  - mm/swap.c:__folio_put
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/truncate.c (ffffffff813a3870)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:mapping_evict_folio
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_cleanup_folio
  - mm/truncate.c:truncate_cleanup_folio
```
```
In mm/vmscan.c (ffffffff813afdd5)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:update_batch_size
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:isolate_lru_folios
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
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
  - mm/vmscan.c:__acct_reclaim_writeback
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/shmem.c (ffffffff813c02ee)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff813c4435)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/util.c:folio_copy
```
```
In mm/mm_init.c (ffffffff82145f6c)
Location: include/linux/page-flags.h:767
Inline: True
```
```
In mm/slab_common.c (ffffffff813d596e)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/slab_common.c:__ksize
  - mm/slab_common.c:__ksize
  - mm/slab_common.c:free_large_kmalloc
```
```
In mm/compaction.c (ffffffff813dafb8)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff813e1e3c)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/gup.c (ffffffff813e3266)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:folio_add_pin
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff813f5cb7)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/memory.c:copy_folio_from_user
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_mapping_folio
  - mm/memory.c:copy_present_pte
```
```
In mm/mlock.c (ffffffff813f969f)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:munlock_folio
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/rmap.c (ffffffff8140b715)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:folio_not_mapped
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:folio_referenced_one
  - mm/rmap.c:folio_referenced_one
  - mm/rmap.c:folio_referenced_one
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:folio_get_anon_vma
```
```
In mm/page_alloc.c (ffffffff8141c0ba)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/memory_hotplug.c (ffffffff814257a1)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/madvise.c (ffffffff814278c6)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff8142aa92)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
  - mm/page_io.c:sio_write_complete
```
```
In mm/swap_state.c (ffffffff8142c388)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:swap_cache_get_folio
  - mm/swap_state.c:free_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81430460)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:folio_free_swap
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/swap_slots.c (ffffffff814345e0)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/hugetlb.c (ffffffff81446725)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:folio_putback_active_hugetlb
  - mm/hugetlb.c:get_hwpoison_hugetlb_folio
  - mm/hugetlb.c:isolate_hugetlb
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff8144bf42)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/mempolicy.c:new_folio
  - mm/mempolicy.c:new_folio
  - mm/mempolicy.c:new_folio
  - mm/mempolicy.c:new_folio
  - mm/mempolicy.c:migrate_folio_add
```
```
In mm/ksm.c (ffffffff81453d7f)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/slub.c (ffffffff8145a925)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:slab_pad_check
```
```
In mm/migrate.c (ffffffff8146bbc5)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:alloc_misplaced_dst_folio
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_hugetlbs
  - mm/migrate.c:migrate_hugetlbs
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_done
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/migrate_device.c (ffffffff8146dd96)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8147931d)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8147fa90)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:release_pte_pages
  - mm/khugepaged.c:release_pte_folio
```
```
In mm/memcontrol.c (ffffffff81490e17)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/hugetlb_cgroup.c (ffffffff81493f45)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff81496c3e)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/page_isolation.c (ffffffff8149a4c8)
Location: include/linux/page-flags.h:767
Inline: True
```
```
In mm/secretmem.c (ffffffff814a0042)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_free_folio
```
```
In mm/userfaultfd.c (ffffffff814a1f45)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_continue
```
```
In mm/page_idle.c (ffffffff814a2835)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In mm/usercopy.c (ffffffff814a3009)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
  - mm/usercopy.c:check_heap_object
```
```
In fs/libfs.c (ffffffff814eec45)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - fs/libfs.c:simple_read_folio
```
```
In fs/fs-writeback.c (ffffffff814f587c)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/remap_range.c (ffffffff815071bf)
Location: include/linux/page-flags.h:767
Inline: True
```
```
In fs/buffer.c (ffffffff8150b80b)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_is_partially_uptodate
  - fs/buffer.c:block_is_partially_uptodate
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:folio_alloc_buffers
  - fs/buffer.c:folio_alloc_buffers
```
```
In fs/mpage.c (ffffffff8150ede2)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readahead
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_read_end_io
  - fs/mpage.c:mpage_read_end_io
  - fs/mpage.c:mpage_read_end_io
  - fs/mpage.c:mpage_read_end_io
  - fs/mpage.c:mpage_read_end_io
  - fs/mpage.c:mpage_read_end_io
```
```
In fs/crypto/bio.c (ffffffff8153a602)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff8153e667)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff815560b3)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_release_folio
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_folio
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/proc/task_mmu.c (ffffffff8156712c)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In fs/ext4/inline.c (ffffffff815ad783)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_folio
```
```
In fs/ext4/inode.c (ffffffff815bc734)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:ext4_journalled_dirty_folio
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_submit_folio
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/page-io.c (ffffffff815da9cf)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff815db685)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ext4/verity.c (ffffffff81611dd8)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:memcpy_from_file_folio
  - fs/ext4/verity.c:memcpy_from_file_folio
```
```
In fs/jbd2/transaction.c (ffffffff81616365)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
```
```
In fs/squashfs/file.c (ffffffff81625fe2)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/hugetlbfs/inode.c (ffffffff8162ebc8)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fuse/dev.c (ffffffff8165316f)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff8165ce09)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In block/partitions/core.c (ffffffff8179152a)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In lib/scatterlist.c (ffffffff8180dcf1)
Location: include/linux/page-flags.h:767
Inline: True
```
```
In lib/iov_iter.c (ffffffff81813ca7)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
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
In arch/x86/mm/pgtable.c (ffffffff810d3aae)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In kernel/sched/fair.c (ffffffff8116ea25)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/events/uprobes.c (ffffffff813aa014)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff813bb0c1)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:splice_folio_into_pipe
  - mm/filemap.c:splice_folio_into_pipe
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_free_folio
  - mm/filemap.c:filemap_free_folio
  - mm/filemap.c:__filemap_remove_folio
  - mm/filemap.c:__filemap_remove_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
  - mm/filemap.c:trace_event_raw_event_mm_filemap_op_page_cache
```
```
In mm/page-writeback.c (ffffffff813c429c)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_redirty_for_writepage
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/folio-compat.c (ffffffff813c71ea)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/folio-compat.c:pagecache_get_page
```
```
In mm/readahead.c (ffffffff813c8566)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff813cb50a)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:folio_deactivate
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:folio_add_lru
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:folio_rotate_reclaimable
  - mm/swap.c:lru_add_fn
  - mm/swap.c:lru_add_fn
  - mm/swap.c:put_pages_list
  - mm/swap.c:put_pages_list
  - mm/swap.c:__folio_put
  - mm/swap.c:__folio_put
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/truncate.c (ffffffff813cd3d9)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:mapping_evict_folio
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_cleanup_folio
  - mm/truncate.c:truncate_cleanup_folio
```
```
In mm/vmscan.c (ffffffff813d92c5)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:update_batch_size
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:isolate_lru_folios
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
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
  - mm/vmscan.c:__acct_reclaim_writeback
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/shmem.c (ffffffff813eb336)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_alloc_and_add_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff813ee275)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/util.c:folio_copy
```
```
In mm/mm_init.c (ffffffff82228636)
Location: include/linux/page-flags.h:783
Inline: True
```
```
In mm/slab_common.c (ffffffff813ff624)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/slab_common.c:__ksize
  - mm/slab_common.c:__ksize
```
```
In mm/compaction.c (ffffffff81405147)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff8140c66c)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/gup.c (ffffffff8140e96e)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:folio_add_pin
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff81421997)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/memory.c:copy_folio_from_user
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_mapping_folio
  - mm/memory.c:copy_present_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/mlock.c (ffffffff8142524e)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:munlock_folio
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/pgtable-generic.c (ffffffff81435833)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pte_free_now
```
```
In mm/rmap.c (ffffffff81437ff5)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:folio_not_mapped
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_remove_rmap_pmd
  - mm/rmap.c:folio_remove_rmap_pmd
  - mm/rmap.c:folio_remove_rmap_ptes
  - mm/rmap.c:folio_remove_rmap_ptes
  - mm/rmap.c:folio_add_file_rmap_pmd
  - mm/rmap.c:folio_add_file_rmap_pmd
  - mm/rmap.c:folio_add_file_rmap_ptes
  - mm/rmap.c:folio_add_file_rmap_ptes
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:folio_add_anon_rmap_pmd
  - mm/rmap.c:folio_add_anon_rmap_pmd
  - mm/rmap.c:folio_add_anon_rmap_ptes
  - mm/rmap.c:folio_add_anon_rmap_ptes
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:folio_referenced_one
  - mm/rmap.c:folio_referenced_one
  - mm/rmap.c:folio_referenced_one
  - mm/rmap.c:folio_referenced_one
  - mm/rmap.c:folio_referenced_one
  - mm/rmap.c:folio_referenced_one
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
  - mm/rmap.c:folio_get_anon_vma
```
```
In mm/page_alloc.c (ffffffff8144f06d)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/page_alloc.c:__folio_alloc
  - mm/page_alloc.c:destroy_large_folio
  - mm/page_alloc.c:destroy_large_folio
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/memory_hotplug.c (ffffffff8145278a)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/slub.c (ffffffff81454c85)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/slub.c:free_large_kmalloc
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:slab_pad_check
```
```
In mm/madvise.c (ffffffff814610a4)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff8146499c)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/page_io.c:swap_read_folio
  - mm/page_io.c:swap_read_folio_bdev_sync
  - mm/page_io.c:swap_read_folio_fs
  - mm/page_io.c:swap_read_folio_fs
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
  - mm/page_io.c:swap_writepage_bdev_sync
  - mm/page_io.c:swap_writepage_bdev_sync
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:swap_writepage_fs
```
```
In mm/swap_state.c (ffffffff81466870)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cache_get_folio
  - mm/swap_state.c:free_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81468e38)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:folio_free_swap
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/swap_slots.c (ffffffff8146d9e0)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/zswap.c (ffffffff814706a0)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
```
```
In mm/hugetlb.c (ffffffff814801c5)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:folio_putback_active_hugetlb
  - mm/hugetlb.c:get_hwpoison_hugetlb_folio
  - mm/hugetlb.c:isolate_hugetlb
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:PageHuge
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:free_huge_folio
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/mempolicy.c (ffffffff8148754f)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:folio_alloc
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:alloc_migration_target_by_mpol
  - mm/mempolicy.c:alloc_migration_target_by_mpol
  - mm/mempolicy.c:alloc_migration_target_by_mpol
  - mm/mempolicy.c:alloc_migration_target_by_mpol
  - mm/mempolicy.c:alloc_migration_target_by_mpol
  - mm/mempolicy.c:migrate_folio_add
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/ksm.c (ffffffff8149285c)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff8149ab8c)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:alloc_misplaced_dst_folio
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_hugetlbs
  - mm/migrate.c:migrate_hugetlbs
  - mm/migrate.c:migrate_hugetlbs
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_done
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/migrate_device.c (ffffffff8149e766)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a8886)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814ad712)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_pages
  - mm/khugepaged.c:release_pte_folio
```
```
In mm/memcontrol.c (ffffffff814c0787)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_replace_folio
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/hugetlb_cgroup.c (ffffffff814c3825)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff814c63a6)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:is_raw_hwpoison_page_in_hugepage
  - mm/memory-failure.c:has_extra_refcount
```
```
In mm/page_isolation.c (ffffffff814c9cc6)
Location: include/linux/page-flags.h:783
Inline: True
```
```
In mm/secretmem.c (ffffffff814cf79a)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_free_folio
```
```
In mm/userfaultfd.c (ffffffff814d2b81)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:mfill_atomic_continue
```
```
In mm/page_idle.c (ffffffff814d36d5)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In mm/usercopy.c (ffffffff814d3e9d)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
  - mm/usercopy.c:check_heap_object
```
```
In fs/libfs.c (ffffffff81522c82)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_read_folio
```
```
In fs/fs-writeback.c (ffffffff81529f8c)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/remap_range.c (ffffffff8153c524)
Location: include/linux/page-flags.h:783
Inline: True
```
```
In fs/buffer.c (ffffffff815422ed)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/buffer.c:block_write_full_folio
  - fs/buffer.c:block_write_full_folio
  - fs/buffer.c:block_write_full_folio
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_is_partially_uptodate
  - fs/buffer.c:block_is_partially_uptodate
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:folio_alloc_buffers
  - fs/buffer.c:folio_alloc_buffers
```
```
In fs/mpage.c (ffffffff81543698)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readahead
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_read_end_io
  - fs/mpage.c:mpage_read_end_io
  - fs/mpage.c:bio_first_folio
  - fs/mpage.c:bio_first_folio
```
```
In fs/dax.c (0)
Location: include/linux/page-flags.h:783
Inline: True
```
```
In fs/crypto/bio.c (ffffffff8156f9e6)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/crypto/bio.c:bio_first_folio
  - fs/crypto/bio.c:bio_first_folio
```
```
In fs/verity/verify.c (ffffffff81573c26)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8158c57a)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_dirty_folio
  - fs/iomap/buffered-io.c:iomap_release_folio
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_folio
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:ifs_free
  - fs/iomap/buffered-io.c:ifs_alloc
  - fs/iomap/buffered-io.c:ifs_set_range_dirty
  - fs/iomap/buffered-io.c:ifs_set_range_uptodate
```
```
In fs/proc/task_mmu.c (ffffffff8159ccbf)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In fs/ext4/inline.c (ffffffff815e6533)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_folio
```
```
In fs/ext4/inode.c (ffffffff815f5511)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:ext4_journalled_dirty_folio
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_submit_folio
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/page-io.c (ffffffff8161318c)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81613f55)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ext4/verity.c (ffffffff8164ab7a)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:memcpy_from_file_folio
  - fs/ext4/verity.c:memcpy_from_file_folio
```
```
In fs/jbd2/transaction.c (ffffffff8164f185)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
```
```
In fs/jbd2/journal.c (ffffffff8165c9d3)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff8165f122)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/hugetlbfs/inode.c (ffffffff81668091)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fuse/dev.c (ffffffff8168c776)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff81696b69)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In block/bio.c (ffffffff817abaaf)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:__bio_release_pages
  - block/bio.c:__bio_release_pages
  - block/bio.c:bio_first_folio
  - block/bio.c:bio_first_folio
```
```
In block/partitions/core.c (ffffffff817d4e2f)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In lib/scatterlist.c (ffffffff81853985)
Location: include/linux/page-flags.h:783
Inline: True
```
```
In lib/iov_iter.c (ffffffff818570c8)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:copy_page_to_iter_nofault
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9c257)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_put_pages
  - drivers/gpu/drm/drm_gem.c:drm_gem_get_pages
  - drivers/gpu/drm/drm_gem.c:drm_gem_get_pages
  - drivers/gpu/drm/drm_gem.c:drm_gem_get_pages
```
```
In net/core/skbuff.c (ffffffff81ece6d7)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - net/core/skbuff.c:csum_and_copy_from_iter_full
  - net/core/skbuff.c:folio_size
```
```
In net/core/datagram.c (ffffffff81edda6e)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/core/datagram.c:folio_size
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
