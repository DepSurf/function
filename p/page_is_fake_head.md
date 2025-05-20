# Function: <code>page_is_fake_head</code>

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
In kernel/futex/core.c (ffffffff811b2a78)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff812e5dfb)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812f44da)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_free_folio
  - mm/filemap.c:__filemap_remove_folio
  - mm/filemap.c:__filemap_remove_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
  - mm/filemap.c:trace_event_raw_event_mm_filemap_op_page_cache
```
```
In mm/page-writeback.c (ffffffff812feee2)
Location: include/linux/page-flags.h:265
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
In mm/folio-compat.c (ffffffff81301331)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/folio-compat.c:isolate_lru_page
  - mm/folio-compat.c:pagecache_get_page
```
```
In mm/readahead.c (ffffffff81301f61)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff81303255)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
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
  - mm/swap.c:put_pages_list
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff81308d18)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pagevec
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:mapping_evict_folio
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_cleanup_folio
```
```
In mm/vmscan.c (ffffffff8130f3b5)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
  - mm/vmscan.c:__acct_reclaim_writeback
```
```
In mm/shmem.c (ffffffff81319228)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
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
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff8131e006)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/util.c:folio_copy
  - mm/util.c:folio_mapcount
```
```
In mm/compaction.c (ffffffff81331c48)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/workingset.c (ffffffff813366eb)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/debug.c (ffffffff81336987)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff81337c9c)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:unpin_user_page_range_dirty_lock
```
```
In mm/memory.c (ffffffff81342f9b)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:unmap_mapping_folio
```
```
In mm/mlock.c (ffffffff8134c482)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/mlock.c:munlock_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/page_vma_mapped.c (ffffffff81357d7f)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:vma_address
  - mm/page_vma_mapped.c:vma_address
```
```
In mm/rmap.c (ffffffff8135bbcf)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced_one
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff8136e040)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:free_compound_page
```
```
In mm/memory_hotplug.c (ffffffff81f1bb4a)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff81375fee)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
```
```
In mm/page_io.c (ffffffff8137a50b)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:count_swpout_vm_event
  - mm/page_io.c:count_swpout_vm_event
```
```
In mm/swap_state.c (ffffffff8137bbba)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
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
In mm/swapfile.c (ffffffff8137f0e4)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff81383dd9)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/zswap.c (ffffffff81385eb0)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff8139476c)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:PageHeadHuge
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/mempolicy.c (ffffffff81398b94)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/ksm.c (ffffffff813a04d7)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/slub.c (ffffffff813a7eed)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:slab_pad_check
```
```
In mm/migrate.c (ffffffff813b5dad)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff813c07a8)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff813c576f)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff813d5710)
Location: include/linux/page-flags.h:265
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
In mm/hugetlb_cgroup.c (ffffffff813d8583)
Location: include/linux/page-flags.h:265
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
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff813dd45d)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/page_isolation.c (ffffffff813de306)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/page_isolation.c:isolate_single_pageblock
```
```
In mm/secretmem.c (ffffffff813e3873)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_free_folio
```
```
In mm/page_idle.c (ffffffff813e634c)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In mm/usercopy.c (ffffffff813e6ccc)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In mm/memfd.c (ffffffff813e964f)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/libfs.c (ffffffff8142c8fe)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - fs/libfs.c:simple_read_folio
```
```
In fs/fs-writeback.c (ffffffff81432738)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/remap_range.c (ffffffff81441fe2)
Location: include/linux/page-flags.h:265
Inline: True
```
```
In fs/buffer.c (ffffffff81446c60)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_is_partially_uptodate
  - fs/buffer.c:block_is_partially_uptodate
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:block_invalidate_folio
```
```
In fs/direct-io.c (ffffffff81448f8b)
Location: include/linux/page-flags.h:265
Inline: True
```
```
In fs/mpage.c (ffffffff8144bc4a)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/verity/enable.c (ffffffff814720ab)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/iomap/buffered-io.c (ffffffff8148a55a)
Location: include/linux/page-flags.h:265
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
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:__iomap_write_begin
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
In fs/proc/task_mmu.c (ffffffff81499e81)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff814b11b9)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
```
```
In fs/ext4/inline.c (ffffffff814dbdbd)
Location: include/linux/page-flags.h:265
Inline: True
```
```
In fs/ext4/inode.c (ffffffff814e0cd3)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/move_extent.c (ffffffff814fe8db)
Location: include/linux/page-flags.h:265
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815085cd)
Location: include/linux/page-flags.h:265
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff8150a0f0)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff8153fe3f)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
```
```
In fs/hugetlbfs/inode.c (ffffffff8155487b)
Location: include/linux/page-flags.h:265
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff81568d5d)
Location: include/linux/page-flags.h:265
Inline: True
```
```
In fs/fuse/file.c (ffffffff8157ed80)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In block/bio.c (ffffffff81671bfb)
Location: include/linux/page-flags.h:265
Inline: True
```
```
In io_uring/io_uring.c (ffffffff81e90a58)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_mmap
  - io_uring/io_uring.c:io_buffer_account_pin
```
```
In lib/iov_iter.c (ffffffff816e6bf1)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:page_copy_sane
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff819f2b19)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
```
```
In net/xdp/xsk.c (ffffffff81e16015)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In kernel/sched/fair.c (ffffffff81152682)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/futex/core.c (ffffffff811f3918)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In mm/filemap.c (ffffffff8135d88e)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/folio-compat.c (ffffffff8136b9c1)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - mm/folio-compat.c:isolate_lru_page
```
```
In mm/truncate.c (ffffffff813713bb)
Location: include/linux/page-flags.h:244
Inline: True
```
```
In mm/vmscan.c (ffffffff8137ebd8)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/shmem.c (ffffffff8138a76b)
Location: include/linux/page-flags.h:244
Inline: True
```
```
In mm/compaction.c (ffffffff813a7bff)
Location: include/linux/page-flags.h:244
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
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff813adc1d)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff813baf3d)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/mlock.c (ffffffff813c5012)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - mm/mlock.c:munlock_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/page_vma_mapped.c (ffffffff813d31b8)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_mapped_in_vma
```
```
In mm/rmap.c (ffffffff813d688a)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff813ea380)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__free_pages
  - mm/page_alloc.c:free_compound_page
```
```
In mm/memory_hotplug.c (ffffffff820c39ec)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff813f3867)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
```
```
In mm/page_io.c (ffffffff813f7faf)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:count_swpout_vm_event
  - mm/page_io.c:count_swpout_vm_event
```
```
In mm/zswap.c (ffffffff81403cf0)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff8140aeb4)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:PageHeadHuge
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/mempolicy.c (ffffffff8141629a)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/ksm.c (ffffffff8141fce7)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff81435ef3)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff814429b7)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff8144ac42)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
```
```
In mm/hugetlb_cgroup.c (ffffffff8145d4e7)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff814619d5)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (ffffffff81464f96)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - mm/page_isolation.c:isolate_single_pageblock
```
```
In mm/secretmem.c (ffffffff8146b0c8)
Location: include/linux/page-flags.h:244
Inline: True
```
```
In mm/memfd.c (ffffffff8147162c)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/libfs.c (ffffffff814b9b6c)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - fs/libfs.c:zero_user_segments
  - fs/libfs.c:zero_user_segments
  - fs/libfs.c:zero_user_segments
```
```
In fs/buffer.c (ffffffff814d257c)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - fs/buffer.c:zero_user_segments
  - fs/buffer.c:zero_user_segments
  - fs/buffer.c:zero_user_segments
```
```
In fs/direct-io.c (ffffffff814d727b)
Location: include/linux/page-flags.h:244
Inline: True
```
```
In fs/mpage.c (ffffffff814d97dd)
Location: include/linux/page-flags.h:244
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8151bdcc)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:zero_user_segments
  - fs/iomap/buffered-io.c:zero_user_segments
  - fs/iomap/buffered-io.c:zero_user_segments
```
```
In fs/proc/task_mmu.c (ffffffff8152e125)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff81547b79)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
```
```
In fs/ext4/inline.c (ffffffff81574d3d)
Location: include/linux/page-flags.h:244
Inline: True
```
```
In fs/ext4/inode.c (ffffffff815799cc)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - fs/ext4/inode.c:zero_user_segments
  - fs/ext4/inode.c:zero_user_segments
  - fs/ext4/inode.c:zero_user_segments
```
```
In fs/ext4/move_extent.c (ffffffff8159911b)
Location: include/linux/page-flags.h:244
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815a30bd)
Location: include/linux/page-flags.h:244
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff815a460d)
Location: include/linux/page-flags.h:244
Inline: True
```
```
In fs/squashfs/file.c (ffffffff815ee031)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/hugetlbfs/inode.c (ffffffff815f634b)
Location: include/linux/page-flags.h:244
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff8160c6cd)
Location: include/linux/page-flags.h:244
Inline: True
```
```
In fs/fuse/file.c (ffffffff81624a40)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In block/bio.c (ffffffff8172d4bb)
Location: include/linux/page-flags.h:244
Inline: True
```
```
In io_uring/io_uring.c (ffffffff81789c23)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_mmap
```
```
In io_uring/rsrc.c (ffffffff817a0b3f)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_account_pin
```
```
In lib/iov_iter.c (ffffffff817d25a2)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:page_copy_sane
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81b70933)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
```
```
In net/xdp/xsk.c (ffffffff81fed062)
Location: include/linux/page-flags.h:244
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In kernel/futex/core.c (ffffffff8120809f)
Location: include/linux/page-flags.h:238
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In mm/folio-compat.c (ffffffff8139dc34)
Location: include/linux/page-flags.h:238
Inline: True
Inline callers:
  - mm/folio-compat.c:isolate_lru_page
```
```
In mm/debug.c (ffffffff813e1fae)
Location: include/linux/page-flags.h:238
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff813e3a87)
Location: include/linux/page-flags.h:238
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff814070fb)
Location: include/linux/page-flags.h:238
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:vma_address
```
```
In mm/rmap.c (ffffffff8140ba2f)
Location: include/linux/page-flags.h:238
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:vma_address
```
```
In mm/page_alloc.c (ffffffff8141efc4)
Location: include/linux/page-flags.h:238
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages
  - mm/page_alloc.c:free_tail_page_prepare
```
```
In mm/memory_hotplug.c (ffffffff8142578b)
Location: include/linux/page-flags.h:238
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/page_io.c (ffffffff8142ab1e)
Location: include/linux/page-flags.h:238
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
  - mm/page_io.c:sio_write_complete
```
```
In mm/zswap.c (ffffffff81436b56)
Location: include/linux/page-flags.h:238
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff81445588)
Location: include/linux/page-flags.h:238
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/ksm.c (ffffffff81454923)
Location: include/linux/page-flags.h:238
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff81468a7e)
Location: include/linux/page-flags.h:238
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff8147827b)
Location: include/linux/page-flags.h:238
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814814c3)
Location: include/linux/page-flags.h:238
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/memory-failure.c (ffffffff8149727a)
Location: include/linux/page-flags.h:238
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs_anon
```
```
In mm/page_idle.c (ffffffff814a2aaf)
Location: include/linux/page-flags.h:238
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_folio
```
```
In mm/memfd.c (ffffffff814a5b67)
Location: include/linux/page-flags.h:238
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/page.c (ffffffff8157f798)
Location: include/linux/page-flags.h:238
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
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
In mm/folio-compat.c (ffffffff813c7914)
Location: include/linux/page-flags.h:240
Inline: True
Inline callers:
  - mm/folio-compat.c:isolate_lru_page
```
```
In mm/debug.c (ffffffff8140c7c1)
Location: include/linux/page-flags.h:240
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8140e301)
Location: include/linux/page-flags.h:240
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff8143378f)
Location: include/linux/page-flags.h:240
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:vma_address
```
```
In mm/rmap.c (ffffffff814382ef)
Location: include/linux/page-flags.h:240
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:vma_address
```
```
In mm/page_alloc.c (ffffffff8144bc91)
Location: include/linux/page-flags.h:240
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages
  - mm/page_alloc.c:free_tail_page_prepare
```
```
In mm/memory_hotplug.c (ffffffff81452774)
Location: include/linux/page-flags.h:240
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/hugetlb.c (ffffffff8147b78f)
Location: include/linux/page-flags.h:240
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_follow_page_mask
```
```
In mm/ksm.c (ffffffff8148fb50)
Location: include/linux/page-flags.h:240
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/huge_memory.c (ffffffff814a79bb)
Location: include/linux/page-flags.h:240
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/memory-failure.c (ffffffff814c8709)
Location: include/linux/page-flags.h:240
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs_anon
```
```
In mm/page_idle.c (ffffffff814d393f)
Location: include/linux/page-flags.h:240
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_folio
```
```
In mm/memfd.c (ffffffff814d6b14)
Location: include/linux/page-flags.h:240
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/page.c (ffffffff815b81d5)
Location: include/linux/page-flags.h:240
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
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
