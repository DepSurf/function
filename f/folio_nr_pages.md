# Function: <code>folio_nr_pages</code>

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
In kernel/events/uprobes.c (ffffffff812e5deb)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812f44d0)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_free_folio
  - mm/filemap.c:__filemap_remove_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff812fef44)
Location: include/linux/mm.h:1649
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
In mm/folio-compat.c (ffffffff81300a52)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/folio-compat.c:pagecache_get_page
```
```
In mm/readahead.c (ffffffff81301548)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff81303248)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__folio_activate
  - mm/swap.c:__folio_activate
  - mm/swap.c:__folio_activate
  - mm/swap.c:lru_note_cost_folio
  - mm/swap.c:pagevec_move_tail_fn
  - mm/swap.c:pagevec_move_tail_fn
  - mm/swap.c:pagevec_move_tail_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff81308d0d)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pagevec
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:mapping_evict_folio
```
```
In mm/vmscan.c (ffffffff8130f514)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
  - mm/vmscan.c:__acct_reclaim_writeback
```
```
In mm/shmem.c (ffffffff81319216)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff8131dfe5)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/util.c:folio_copy
  - mm/util.c:folio_mapcount
```
```
In mm/compaction.c (ffffffff81330c73)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff813366dc)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff81337c8d)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:unpin_user_page_range_dirty_lock
```
```
In mm/memory.c (ffffffff81342dd4)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_folio
```
```
In mm/mlock.c (ffffffff8134c0db)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
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
In mm/rmap.c (ffffffff8135bae6)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced_one
```
```
In mm/swap_slots.c (ffffffff81383dca)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/migrate.c (ffffffff813b1e99)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff813bf79e)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/memcontrol.c (ffffffff813d54d1)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/page_idle.c (ffffffff813e633f)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/fs-writeback.c (ffffffff81432729)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/mpage.c (ffffffff8144bc39)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/verity/enable.c (ffffffff814720a1)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/iomap/buffered-io.c (ffffffff81488548)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/readpage.c (ffffffff8150a0e6)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8135e5b2)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_free_folio
  - mm/filemap.c:__filemap_remove_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff81369691)
Location: include/linux/mm.h:1776
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
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - mm/folio-compat.c:pagecache_get_page
```
```
In mm/readahead.c (ffffffff8136bbf8)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff8136f75e)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:lru_add_fn
  - mm/swap.c:lru_add_fn
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/truncate.c (ffffffff81372528)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:mapping_evict_folio
```
```
In mm/vmscan.c (ffffffff8137e6f1)
Location: include/linux/mm.h:1776
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
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:update_batch_size
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_folios
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
Location: include/linux/mm.h:1776
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
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff81391a45)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - mm/util.c:folio_copy
```
```
In mm/compaction.c (ffffffff813a7aed)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff813ad94c)
Location: include/linux/mm.h:1776
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
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:unpin_user_page_range_dirty_lock
```
```
In mm/memory.c (ffffffff813bbcf1)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_mapping_folio
```
```
In mm/mlock.c (ffffffff813c4c37)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
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
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced_one
```
```
In mm/swap_state.c (ffffffff813f96f7)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff813fd156)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:put_swap_folio
```
```
In mm/swap_slots.c (ffffffff8140170a)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/migrate.c (ffffffff81435344)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81443160)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff81449b01)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8145af9f)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/userfaultfd.c (ffffffff8146d511)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
```
```
In mm/page_idle.c (ffffffff8146de2f)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/fs-writeback.c (ffffffff814c048c)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/mpage.c (ffffffff814da256)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/verity/enable.c (ffffffff815040f9)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/iomap/buffered-io.c (ffffffff8151c3c3)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/inode.c (ffffffff81579cd8)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/readpage.c (ffffffff815a4d13)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/events/uprobes.c (ffffffff81380c34)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8138ca97)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_free_folio
  - mm/filemap.c:__filemap_remove_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff8139b831)
Location: include/linux/mm.h:2002
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
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - mm/folio-compat.c:pagecache_get_page
```
```
In mm/readahead.c (ffffffff8139de85)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff813a187e)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:lru_add_fn
  - mm/swap.c:lru_add_fn
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/truncate.c (ffffffff813a46a5)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:mapping_evict_folio
```
```
In mm/vmscan.c (ffffffff813afdd5)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:drain_evictable
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
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_folios
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
Location: include/linux/mm.h:2002
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
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff813c4435)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - mm/util.c:folio_copy
```
```
In mm/compaction.c (ffffffff813dafd0)
Location: include/linux/mm.h:2002
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
```
```
In mm/workingset.c (ffffffff813e1e3c)
Location: include/linux/mm.h:2002
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
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:unpin_user_page_range_dirty_lock
```
```
In mm/memory.c (ffffffff813f5cb7)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - mm/memory.c:copy_folio_from_user
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_mapping_folio
```
```
In mm/mlock.c (ffffffff813f92e5)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - mm/mlock.c:mlock_new_folio
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
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:folio_referenced_one
```
```
In mm/memory_hotplug.c (ffffffff814257a1)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/page_io.c (ffffffff8142aa92)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
  - mm/page_io.c:sio_write_complete
```
```
In mm/swap_state.c (ffffffff8142c388)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81430460)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:put_swap_folio
```
```
In mm/swap_slots.c (ffffffff814345ea)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/mempolicy.c (ffffffff8144953c)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_folio_add
```
```
In mm/migrate.c (ffffffff8146bbc5)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_hugetlbs
  - mm/migrate.c:migrate_folio_done
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff814780fc)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8147fe9f)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:release_pte_folio
```
```
In mm/memcontrol.c (ffffffff81490c0f)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/userfaultfd.c (ffffffff814a1f45)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_continue
```
```
In mm/page_idle.c (ffffffff814a292f)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/fs-writeback.c (ffffffff814f587c)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/mpage.c (ffffffff8150e196)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_read_end_io
  - fs/mpage.c:mpage_read_end_io
  - fs/mpage.c:mpage_read_end_io
```
```
In fs/crypto/bio.c (ffffffff8153a63a)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff8153e69c)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff815545ce)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/inode.c (ffffffff815b5bfd)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/page-io.c (ffffffff815d9bf8)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff815db685)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ext4/verity.c (ffffffff81611dd8)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
```
In fs/squashfs/file.c (ffffffff81625fe2)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff8165ce09)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/iov_iter.c (ffffffff81810c98)
Location: include/linux/mm.h:2002
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
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
Location: include/linux/mm.h:2057
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
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/events/uprobes.c (ffffffff813aa014)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff813bb0c1)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_free_folio
  - mm/filemap.c:__filemap_remove_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff813c4338)
Location: include/linux/mm.h:2057
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
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/folio-compat.c:pagecache_get_page
```
```
In mm/readahead.c (ffffffff813c7b32)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff813cb50a)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:lru_add_fn
  - mm/swap.c:lru_add_fn
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/truncate.c (ffffffff813ce203)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:mapping_evict_folio
```
```
In mm/vmscan.c (ffffffff813d92c5)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:drain_evictable
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
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_folios
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
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff813ee275)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/util.c:folio_copy
```
```
In mm/compaction.c (ffffffff81405159)
Location: include/linux/mm.h:2057
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
```
```
In mm/workingset.c (ffffffff8140c66c)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/gup.c (ffffffff8140daf6)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:unpin_user_page_range_dirty_lock
```
```
In mm/memory.c (ffffffff81421997)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/memory.c:copy_folio_from_user
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_mapping_folio
  - mm/memory.c:__pte_alloc
```
```
In mm/mlock.c (ffffffff8142524e)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_new_folio
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
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pte_free_now
```
```
In mm/rmap.c (ffffffff81437ff5)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_remove_rmap_pmd
  - mm/rmap.c:folio_add_file_rmap_pmd
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:folio_add_anon_rmap_pmd
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:folio_referenced_one
  - mm/rmap.c:folio_referenced_one
```
```
In mm/memory_hotplug.c (ffffffff8145278a)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/page_io.c (ffffffff8146421e)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
  - mm/page_io.c:swap_writepage_fs
```
```
In mm/swap_state.c (ffffffff81466870)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81468e38)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:put_swap_folio
```
```
In mm/swap_slots.c (ffffffff8146d9e7)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/mempolicy.c (ffffffff81482f96)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_folio_add
```
```
In mm/migrate.c (ffffffff8149ab8c)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_hugetlbs
  - mm/migrate.c:migrate_folio_done
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff814a7846)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
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
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_folio
```
```
In mm/memcontrol.c (ffffffff814c057f)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_replace_folio
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff814c66cf)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:has_extra_refcount
```
```
In mm/page_isolation.c (ffffffff814c9cf4)
Location: include/linux/mm.h:2057
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814d1818)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_continue
```
```
In mm/page_idle.c (ffffffff814d37e8)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/fs-writeback.c (ffffffff81529f8c)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/mpage.c (ffffffff81542c76)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_read_end_io
  - fs/mpage.c:bio_first_folio
```
```
In fs/dax.c (0)
Location: include/linux/mm.h:2057
Inline: True
```
```
In fs/crypto/bio.c (ffffffff8156fa1e)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/crypto/bio.c:bio_first_folio
```
```
In fs/verity/verify.c (ffffffff81573c5c)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8158a7ab)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/inode.c (ffffffff815ee9ab)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/page-io.c (ffffffff81612474)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81613f55)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ext4/verity.c (ffffffff8164ab7a)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
```
In fs/squashfs/file.c (ffffffff8165f122)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff81696b69)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In block/bio.c (ffffffff817abadb)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:__bio_release_pages
  - block/bio.c:bio_first_folio
```
```
In lib/iov_iter.c (ffffffff818570c8)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9c257)
Location: include/linux/mm.h:2057
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_put_pages
  - drivers/gpu/drm/drm_gem.c:drm_gem_get_pages
  - drivers/gpu/drm/drm_gem.c:drm_gem_get_pages
  - drivers/gpu/drm/drm_gem.c:drm_gem_get_pages
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
