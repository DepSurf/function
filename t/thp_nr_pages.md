# Function: <code>thp_nr_pages</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125a1b5)
Location: include/linux/huge_mm.h:273
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/readahead.c (ffffffff81266f98)
Location: include/linux/huge_mm.h:273
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff81269a28)
Location: include/linux/huge_mm.h:273
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff8126b089)
Location: include/linux/huge_mm.h:273
Inline: True
Inline callers:
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff8127033a)
Location: include/linux/huge_mm.h:273
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/compaction.c (ffffffff8128d183)
Location: include/linux/huge_mm.h:273
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff81291196)
Location: include/linux/huge_mm.h:273
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/mlock.c (ffffffff812a1d02)
Location: include/linux/huge_mm.h:273
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff812ad31a)
Location: include/linux/huge_mm.h:273
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812af891)
Location: include/linux/huge_mm.h:273
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/page_io.c (ffffffff812c3901)
Location: include/linux/huge_mm.h:273
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (ffffffff812c4f5e)
Location: include/linux/huge_mm.h:273
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff812c7b75)
Location: include/linux/huge_mm.h:273
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/mempolicy.c (ffffffff812d7a64)
Location: include/linux/huge_mm.h:273
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff812ec3cb)
Location: include/linux/huge_mm.h:273
Inline: True
```
```
In mm/migrate.c (ffffffff812f349b)
Location: include/linux/huge_mm.h:273
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812f9281)
Location: include/linux/huge_mm.h:273
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/memcontrol.c (ffffffff8130a276)
Location: include/linux/huge_mm.h:273
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memfd.c (ffffffff81317ec2)
Location: include/linux/huge_mm.h:273
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/mpage.c (ffffffff81372429)
Location: include/linux/huge_mm.h:273
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/iomap/buffered-io.c (ffffffff813bd690)
Location: include/linux/huge_mm.h:273
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead_actor
```
```
In fs/ext4/readpage.c (ffffffff8142c29d)
Location: include/linux/huge_mm.h:273
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/fuse/file.c (ffffffff8149136a)
Location: include/linux/huge_mm.h:273
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
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
In mm/filemap.c (ffffffff8125fdd5)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/readahead.c (ffffffff8126bbdb)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff8126d818)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff812711c4)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/truncate.c:__invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff812760f1)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff8128017a)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
```
```
In mm/compaction.c (ffffffff81291b49)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff812967b1)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff8129709c)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
```
```
In mm/memory.c (ffffffff812a0d83)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_page
```
```
In mm/mlock.c (ffffffff812a74f9)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff812b2444)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812b4b11)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/memory_hotplug.c (ffffffff812c6c6c)
Location: include/linux/huge_mm.h:278
Inline: True
```
```
In mm/page_io.c (ffffffff812ca6bc)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (ffffffff812cbc0c)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff812ce4c5)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/mempolicy.c (ffffffff812def83)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/migrate.c (ffffffff812f9864)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff81300138)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff813051c1)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff81310af5)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memfd.c (ffffffff8131e0b2)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/mpage.c (ffffffff81378509)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/iomap/buffered-io.c (ffffffff813c467a)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead_actor
```
```
In fs/ext4/readpage.c (ffffffff81432f8e)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/fuse/file.c (ffffffff814964c2)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
```
```
In lib/iov_iter.c (ffffffff815acc21)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
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
In mm/filemap.c (ffffffff8129c745)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/readahead.c (ffffffff812a88ae)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff812a9e88)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff812ae704)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/truncate.c:__invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff812b25da)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff812be4bd)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
```
```
In mm/compaction.c (ffffffff812d18a4)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff812d6f1b)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff812d7a4f)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
```
```
In mm/memory.c (ffffffff812e1e93)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_page
```
```
In mm/mlock.c (ffffffff812e87d0)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff812f3f94)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812f6961)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/memory_hotplug.c (ffffffff8130b73d)
Location: include/linux/huge_mm.h:278
Inline: True
```
```
In mm/page_io.c (ffffffff8130f6b9)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (ffffffff81310d4c)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81313a55)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/mempolicy.c (ffffffff81326c13)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/migrate.c (ffffffff8134352d)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff81349d88)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff8134ef3d)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8135bdc6)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/mpage.c (ffffffff813c4de9)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/iomap/buffered-io.c (ffffffff81414d6b)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead
```
```
In fs/ext4/readpage.c (ffffffff814868e3)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/fuse/file.c (ffffffff814ef02b)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/iov_iter.c (ffffffff8161985a)
Location: include/linux/huge_mm.h:278
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iter_xarray_populate_pages
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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81305bdd)
Location: include/linux/mm.h:952
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8130f3ba)
Location: include/linux/mm.h:952
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/compaction.c (ffffffff81330d11)
Location: include/linux/mm.h:952
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8134c1d5)
Location: include/linux/mm.h:952
Inline: True
Inline callers:
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/rmap.c (ffffffff8135c181)
Location: include/linux/mm.h:952
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
```
```
In mm/memory_hotplug.c (ffffffff81373f46)
Location: include/linux/mm.h:952
Inline: True
```
```
In mm/page_io.c (ffffffff81378f54)
Location: include/linux/mm.h:952
Inline: True
Inline callers:
  - mm/page_io.c:count_swpout_vm_event
```
```
In mm/swap_state.c (ffffffff8137bbb0)
Location: include/linux/mm.h:952
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff8137f0c9)
Location: include/linux/mm.h:952
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/mempolicy.c (ffffffff81396286)
Location: include/linux/mm.h:952
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/migrate.c (ffffffff813b5da6)
Location: include/linux/mm.h:952
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff813c079b)
Location: include/linux/mm.h:952
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff813c575f)
Location: include/linux/mm.h:952
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/fuse/file.c (ffffffff8157ed70)
Location: include/linux/mm.h:952
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/iov_iter.c (ffffffff816e18f8)
Location: include/linux/mm.h:952
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
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
In kernel/sched/fair.c (ffffffff81152671)
Location: include/linux/mm.h:1082
Inline: True
Inline callers:
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In mm/compaction.c (ffffffff813a7b98)
Location: include/linux/mm.h:1082
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff813c4d55)
Location: include/linux/mm.h:1082
Inline: True
Inline callers:
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/rmap.c (ffffffff813d8f3a)
Location: include/linux/mm.h:1082
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:folio_referenced
```
```
In mm/memory_hotplug.c (ffffffff813f1dc4)
Location: include/linux/mm.h:1082
Inline: True
```
```
In mm/page_io.c (ffffffff813f68e4)
Location: include/linux/mm.h:1082
Inline: True
Inline callers:
  - mm/page_io.c:count_swpout_vm_event
```
```
In mm/mempolicy.c (ffffffff8141628b)
Location: include/linux/mm.h:1082
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/migrate.c (ffffffff81435eec)
Location: include/linux/mm.h:1082
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff81442a22)
Location: include/linux/mm.h:1082
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff8144a0b1)
Location: include/linux/mm.h:1082
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/squashfs/file.c (ffffffff815ee021)
Location: include/linux/mm.h:1082
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff81624a30)
Location: include/linux/mm.h:1082
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/iov_iter.c (ffffffff817d2598)
Location: include/linux/mm.h:1082
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
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
Location: include/linux/mm.h:2035
Inline: True
Inline callers:
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In mm/memory_hotplug.c (ffffffff814257a1)
Location: include/linux/mm.h:2035
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/page_io.c (ffffffff8142aa92)
Location: include/linux/mm.h:2035
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
  - mm/page_io.c:sio_write_complete
```
```
In mm/migrate.c (ffffffff8146bbc5)
Location: include/linux/mm.h:2035
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff81472127)
Location: include/linux/mm.h:2035
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff8148030c)
Location: include/linux/mm.h:2035
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/squashfs/file.c (ffffffff81625fe2)
Location: include/linux/mm.h:2035
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff8165ce09)
Location: include/linux/mm.h:2035
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/iov_iter.c (ffffffff81810c98)
Location: include/linux/mm.h:2035
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
In mm/memory_hotplug.c (ffffffff8145278a)
Location: include/linux/mm.h:2090
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/huge_memory.c (ffffffff814a22b8)
Location: include/linux/mm.h:2090
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In fs/squashfs/file.c (ffffffff8165f122)
Location: include/linux/mm.h:2090
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/fuse/file.c (ffffffff81696b69)
Location: include/linux/mm.h:2090
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In lib/iov_iter.c (ffffffff818570c8)
Location: include/linux/mm.h:2090
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
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
