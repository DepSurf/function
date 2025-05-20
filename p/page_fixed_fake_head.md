# Function: <code>page_fixed_fake_head</code>

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
In init/do_mounts.c (ffffffff81e43a7d)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - init/do_mounts.c:put_page
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81003dc1)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107db76)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107f805)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/exit.c (ffffffff810d30e9)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/resource.c (ffffffff810d5d0f)
Location: include/linux/page-flags.h:228
Inline: True
```
```
In kernel/power/swap.c (ffffffff811579ac)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex/core.c (ffffffff811b271f)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/relay.c (ffffffff81203abf)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff812cdbf5)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff812e67f5)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/watch_queue.c (ffffffff812ecfa3)
Location: include/linux/page-flags.h:228
Inline: True
```
```
In mm/filemap.c (ffffffff812f44da)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pmd
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
  - mm/filemap.c:page_endio
  - mm/filemap.c:page_endio
  - mm/filemap.c:page_endio
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:add_to_page_cache_locked
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:__filemap_fdatawait_range
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
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:folio_redirty_for_writepage
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:folio_write_one
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/folio-compat.c (ffffffff813013b1)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/folio-compat.c:putback_lru_page
  - mm/folio-compat.c:isolate_lru_page
  - mm/folio-compat.c:try_to_release_page
  - mm/folio-compat.c:delete_from_page_cache
  - mm/folio-compat.c:pagecache_get_page
  - mm/folio-compat.c:add_to_page_cache_lru
  - mm/folio-compat.c:lru_cache_add
  - mm/folio-compat.c:redirty_page_for_writepage
  - mm/folio-compat.c:clear_page_dirty_for_io
  - mm/folio-compat.c:__set_page_dirty_nobuffers
  - mm/folio-compat.c:__set_page_dirty_nobuffers
  - mm/folio-compat.c:set_page_dirty
  - mm/folio-compat.c:set_page_writeback
  - mm/folio-compat.c:migrate_page_copy
  - mm/folio-compat.c:migrate_page_copy
  - mm/folio-compat.c:migrate_page_states
  - mm/folio-compat.c:migrate_page_states
  - mm/folio-compat.c:migrate_page_move_mapping
  - mm/folio-compat.c:migrate_page_move_mapping
  - mm/folio-compat.c:mark_page_accessed
  - mm/folio-compat.c:page_mapped
  - mm/folio-compat.c:wait_for_stable_page
  - mm/folio-compat.c:wait_on_page_writeback
  - mm/folio-compat.c:end_page_writeback
  - mm/folio-compat.c:unlock_page
```
```
In mm/readahead.c (ffffffff8130199c)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff81306e7d)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__activate_page
  - mm/swap.c:__folio_activate
  - mm/swap.c:__folio_activate
  - mm/swap.c:__folio_activate
  - mm/swap.c:lru_note_cost_folio
  - mm/swap.c:pagevec_move_tail_fn
  - mm/swap.c:pagevec_move_tail_fn
  - mm/swap.c:pagevec_move_tail_fn
  - mm/swap.c:pagevec_move_tail_fn
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:get_kernel_pages
  - mm/swap.c:put_pages_list
  - mm/swap.c:__put_page
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff81308032)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_mapping_pagevec
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:mapping_evict_folio
  - mm/truncate.c:generic_error_remove_page
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_cleanup_folio
```
```
In mm/vmscan.c (ffffffff8130f3a1)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
  - mm/vmscan.c:__acct_reclaim_writeback
```
```
In mm/shmem.c (ffffffff81319937)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
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
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff8131e006)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/util.c:folio_copy
  - mm/util.c:folio_mapcount
  - mm/util.c:__page_mapcount
  - mm/util.c:__page_mapcount
  - mm/util.c:page_rmapping
```
```
In mm/slab_common.c (ffffffff8132bd05)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/compaction.c (ffffffff81331c31)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
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
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/workingset.c (ffffffff813366eb)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/debug.c (ffffffff813368e7)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8133b0ba)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
  - mm/gup.c:lockless_pages_from_mm
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:unpin_user_pages
  - mm/gup.c:unpin_user_pages
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_get_folio
  - mm/gup.c:try_get_folio
```
```
In mm/memory.c (ffffffff813480f8)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:do_set_pmd
  - mm/memory.c:unmap_mapping_folio
  - mm/memory.c:insert_pages
  - mm/memory.c:insert_pages
  - mm/memory.c:insert_pages
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff813495f0)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:__mincore_unmapped_range
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/mlock.c (ffffffff8134c70b)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:munlock_page
  - mm/mlock.c:munlock_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/mmap.c (ffffffff8134d0c7)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/mprotect.c (ffffffff81353bdd)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81357d7f)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:vma_address
  - mm/page_vma_mapped.c:vma_address
  - mm/page_vma_mapped.c:vma_address
```
```
In mm/rmap.c (ffffffff813600a6)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
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
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_move_anon_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced_one
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/vmalloc.c (ffffffff81366bdc)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vunmap
```
```
In mm/page_alloc.c (ffffffff81372936)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_compound_page
  - mm/page_alloc.c:free_compound_page
```
```
In mm/memory_hotplug.c (ffffffff81f1bad9)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff81375fd7)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
  - mm/madvise.c:madvise_inject_error
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/page_io.c (ffffffff8137a462)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:count_swpout_vm_event
  - mm/page_io.c:count_swpout_vm_event
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/swap_state.c (ffffffff8137c134)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff813828df)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:try_to_free_swap
  - mm/swapfile.c:try_to_free_swap
  - mm/swapfile.c:try_to_free_swap
  - mm/swapfile.c:try_to_free_swap
  - mm/swapfile.c:try_to_free_swap
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/swap_slots.c (ffffffff81383dd9)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/zswap.c (ffffffff81385eb0)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8139476c)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:PageHeadHuge
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/mempolicy.c (ffffffff81398a91)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/sparse-vmemmap.c (ffffffff81f214e4)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff813a30ad)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
  - mm/ksm.c:break_ksm
```
```
In mm/slub.c (ffffffff813a7d09)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:slab_pad_check
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/kfence/core.c (ffffffff813aef13)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:kfence_init
```
```
In mm/migrate.c (ffffffff813b5dad)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:writeout
  - mm/migrate.c:writeout
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_page
  - mm/migrate.c:migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff813b6369)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_finalize
  - mm/migrate_device.c:migrate_vma_finalize
  - mm/migrate_device.c:migrate_vma_finalize
  - mm/migrate_device.c:migrate_vma_finalize
  - mm/migrate_device.c:migrate_vma_finalize
  - mm/migrate_device.c:migrate_vma_finalize
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c1d9c)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
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
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813c8336)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff813d5ad2)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
  - mm/memcontrol.c:get_obj_cgroup_from_page
  - mm/memcontrol.c:get_obj_cgroup_from_page
  - mm/memcontrol.c:get_obj_cgroup_from_page
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:unlock_page_memcg
  - mm/memcontrol.c:lock_page_memcg
  - mm/memcontrol.c:__mod_lruvec_page_state
  - mm/memcontrol.c:__mod_lruvec_page_state
  - mm/memcontrol.c:mem_cgroup_css_from_page
```
```
In mm/hugetlb_cgroup.c (ffffffff813d8583)
Location: include/linux/page-flags.h:228
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
In mm/memory-failure.c (ffffffff813dd40a)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_swapcache_clean
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/memory-failure.c:me_pagecache_clean
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/page_isolation.c (ffffffff813deb38)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
```
```
In mm/zsmalloc.c (ffffffff813e1da6)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/balloon_compaction.c (ffffffff813e3222)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/secretmem.c (ffffffff813e3873)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_free_folio
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff813e5a49)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
  - mm/userfaultfd.c:mcopy_atomic_pte
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/page_idle.c (ffffffff813e6789)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_clear_pte_refs
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/usercopy.c (ffffffff813e6c89)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
  - mm/usercopy.c:check_heap_object
```
```
In mm/memremap.c (ffffffff813e7c0e)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
  - mm/memremap.c:free_zone_device_page
```
```
In mm/hmm.c (0)
Location: include/linux/page-flags.h:228
Inline: True
```
```
In mm/memfd.c (ffffffff813e964f)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/exec.c (ffffffff813fb26e)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff813fe3ec)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:generic_pipe_buf_get
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff814006a9)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8142c794)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_read_folio
```
```
In fs/fs-writeback.c (ffffffff81432738)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/splice.c (ffffffff81437bc2)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_release
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff81441fe2)
Location: include/linux/page-flags.h:228
Inline: True
```
```
In fs/buffer.c (ffffffff81446878)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_is_partially_uptodate
  - fs/buffer.c:block_is_partially_uptodate
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/direct-io.c (ffffffff8144a77d)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff8144c214)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readahead
  - fs/mpage.c:mpage_readahead
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff81463727)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/crypto/crypto.c (ffffffff81e7869b)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/crypto/bio.c (ffffffff81470d51)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/enable.c (ffffffff814722eb)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/verity/read_metadata.c (ffffffff8147406f)
Location: include/linux/page-flags.h:228
Inline: True
```
```
In fs/verity/verify.c (ffffffff81474e02)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/coredump.c (ffffffff814860c8)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/iomap/buffered-io.c (ffffffff8148a55a)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
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
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
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
  - fs/iomap/buffered-io.c:iomap_migrate_page
  - fs/iomap/buffered-io.c:iomap_migrate_page
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
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/iomap/direct-io.c (ffffffff8148ca40)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/proc/task_mmu.c (ffffffff8149967b)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
  - fs/proc/task_mmu.c:smaps_page_accumulate
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/kcore.c (ffffffff814af6bb)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/page.c (ffffffff814b153e)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/ext4/inline.c (ffffffff814dda1d)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff814ec0b6)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff814f541c)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff814fea94)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff8150934b)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff8150a0f0)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ext4/verity.c (ffffffff8153c5d8)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffff8153fe3f)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
```
```
In fs/jbd2/commit.c (ffffffff8154032a)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/squashfs/file.c (ffffffff8154eabc)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81e82269)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/file_direct.c (ffffffff815511cb)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff81555d8c)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_huge_page
  - fs/hugetlbfs/inode.c:remove_huge_page
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8156956b)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/ecryptfs/read_write.c (ffffffff815698f8)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81577121)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8157f186)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
```
```
In fs/fuse/readdir.c (ffffffff81589461)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/selinux/selinuxfs.c (ffffffff815cf018)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In security/tomoyo/domain.c (ffffffff816009ca)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/fops.c (ffffffff8167046f)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
```
```
In block/bio.c (ffffffff81673f8e)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_release_pages
  - block/bio.c:__bio_add_page
```
```
In block/blk-map.c (ffffffff8167f0a0)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In block/partitions/core.c (ffffffff81695e8a)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
  - block/partitions/core.c:read_part_sector
```
```
In block/partitions/amiga.c (ffffffff816960dd)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff81696c13)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff81697258)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:read_lba
```
```
In block/partitions/mac.c (ffffffff81698466)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8169a63e)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff8169bb9f)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/osf.c (ffffffff8169c586)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff8169c90b)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff8169cc00)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff8169cfc7)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8169d3cf)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff8169e3ae)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8169e6fd)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In io_uring/io_uring.c (ffffffff81e90a58)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_mmap
  - io_uring/io_uring.c:io_buffer_account_pin
  - io_uring/io_uring.c:io_buffer_account_pin
  - io_uring/io_uring.c:io_buffer_account_pin
  - io_uring/io_uring.c:io_buffer_account_pin
```
```
In lib/iov_iter.c (ffffffff816e6bf1)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:pipe_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:pipe_get_pages
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:page_copy_sane
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
In lib/buildid.c (ffffffff8177663c)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8180f371)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c61ae)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff818c7ec5)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff819365f9)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff8193de73)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff819f2b19)
Location: include/linux/page-flags.h:228
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
In drivers/dma-buf/udmabuf.c (ffffffff819f5d4e)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff81a19c58)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/ata/libata-sff.c (ffffffff81a3b8de)
Location: include/linux/page-flags.h:228
Inline: True
```
```
In drivers/net/tun.c (ffffffff81a63a45)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:__tun_build_skb
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/xen-netfront.c (ffffffff81a72ac7)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/md/md.c (ffffffff81b5d5d8)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff81b68748)
Location: include/linux/page-flags.h:228
Inline: True
```
```
In net/socket.c (ffffffff81be77f4)
Location: include/linux/page-flags.h:228
Inline: True
```
```
In net/core/sock.c (ffffffff81bed23f)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81bfd1db)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:napi_build_skb
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/datagram.c (ffffffff81c00cab)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81c44b58)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81c51196)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81c5394f)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/page_pool.c (ffffffff81c5a5b4)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_skb_page
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/core/skmsg.c (ffffffff81c8c10e)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81cdad57)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ceed11)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_output.c (ffffffff81cfed46)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5db60)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6d7ae)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81d7b320)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81d88fb2)
Location: include/linux/page-flags.h:228
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df684e)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81e16000)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
  - net/xdp/xsk.c:xsk_mmap
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff81e22bbc)
Location: include/linux/page-flags.h:228
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:dfrag_clear
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
In init/do_mounts.c (ffffffff83e62324)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81004891)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108f104)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810918f1)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/exit.c (ffffffff810f1c17)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/resource.c (ffffffff810f4fbf)
Location: include/linux/page-flags.h:212
Inline: True
```
```
In kernel/sched/fair.c (ffffffff81152682)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/power/swap.c (ffffffff81188898)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex/core.c (ffffffff811f35bf)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/relay.c (ffffffff8124bbcf)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff81339182)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff813502d9)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/watch_queue.c (ffffffff81357323)
Location: include/linux/page-flags.h:212
Inline: True
```
```
In mm/filemap.c (ffffffff8135cbd1)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:page_endio
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff813668fe)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/folio-compat.c (ffffffff8136ba51)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/folio-compat.c:putback_lru_page
  - mm/folio-compat.c:isolate_lru_page
  - mm/folio-compat.c:add_to_page_cache_lru
  - mm/folio-compat.c:lru_cache_add_inactive_or_unevictable
  - mm/folio-compat.c:redirty_page_for_writepage
  - mm/folio-compat.c:clear_page_dirty_for_io
  - mm/folio-compat.c:__set_page_dirty_nobuffers
  - mm/folio-compat.c:__set_page_dirty_nobuffers
  - mm/folio-compat.c:set_page_dirty
  - mm/folio-compat.c:set_page_writeback
  - mm/folio-compat.c:mark_page_accessed
  - mm/folio-compat.c:wait_for_stable_page
  - mm/folio-compat.c:wait_on_page_writeback
  - mm/folio-compat.c:end_page_writeback
  - mm/folio-compat.c:unlock_page
```
```
In mm/readahead.c (ffffffff8136c090)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
```
```
In mm/swap.c (ffffffff8136f535)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/truncate.c (ffffffff81371fe2)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:generic_error_remove_page
```
```
In mm/vmscan.c (ffffffff8137ebd8)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:get_pfn_folio
```
```
In mm/shmem.c (ffffffff8138ccc9)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
```
```
In mm/util.c (ffffffff813919a1)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/util.c:page_rmapping
```
```
In mm/slab_common.c (ffffffff813a23eb)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/slab_common.c:__ksize
  - mm/slab_common.c:kfree
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/compaction.c (ffffffff813a7bff)
Location: include/linux/page-flags.h:212
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
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:pageblock_skip_persistent
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff813adb77)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff813b2d15)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
  - mm/gup.c:lockless_pages_from_mm
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:unpin_user_pages
  - mm/gup.c:unpin_user_pages
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff813c0599)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_set_pmd
  - mm/memory.c:insert_pages
  - mm/memory.c:insert_pages
  - mm/memory.c:insert_pages
```
```
In mm/mlock.c (ffffffff813c52a3)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:munlock_page
  - mm/mlock.c:munlock_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/mmap.c (ffffffff813c5d64)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/mprotect.c (ffffffff813ce0b2)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/page_vma_mapped.c (ffffffff813d31b8)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_mapped_in_vma
```
```
In mm/rmap.c (ffffffff813db011)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
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
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_move_anon_rmap
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/vmalloc.c (ffffffff813e2968)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vunmap
```
```
In mm/page_alloc.c (ffffffff813f00a6)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__free_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_compound_page
  - mm/page_alloc.c:free_compound_page
```
```
In mm/memory_hotplug.c (ffffffff820c39cb)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff813f384e)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
  - mm/madvise.c:madvise_inject_error
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/page_io.c (ffffffff813f7f02)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:count_swpout_vm_event
  - mm/page_io.c:count_swpout_vm_event
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/swap_state.c (ffffffff813f98d4)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff813fc88b)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/zswap.c (ffffffff81403cf0)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81412fa3)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_add_to_page_cache
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:return_unused_surplus_pages
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:alloc_fresh_hugetlb_folio
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:PageHeadHuge
  - mm/hugetlb.c:PageHuge
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_hpage_workfn
  - mm/hugetlb.c:__update_and_free_page
```
```
In mm/mempolicy.c (ffffffff81418917)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff820cb485)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81422d29)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff8142c3f7)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:cache_from_obj
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/kfence/core.c (ffffffff8142f4c8)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:kfence_init
```
```
In mm/migrate.c (ffffffff81435ef3)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8143a437)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81443f7d)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:can_change_pmd_writable
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff8144aaf5)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:set_huge_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:alloc_charge_hpage
  - mm/khugepaged.c:alloc_charge_hpage
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff81458816)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
  - mm/memcontrol.c:get_obj_cgroup_from_page
  - mm/memcontrol.c:get_obj_cgroup_from_page
  - mm/memcontrol.c:get_obj_cgroup_from_page
  - mm/memcontrol.c:mem_cgroup_from_slab_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:unlock_page_memcg
  - mm/memcontrol.c:lock_page_memcg
  - mm/memcontrol.c:__mod_lruvec_page_state
  - mm/memcontrol.c:__mod_lruvec_page_state
  - mm/memcontrol.c:mem_cgroup_css_from_page
```
```
In mm/hugetlb_cgroup.c (ffffffff8145de11)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff81464126)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:__free_raw_hwp_pages
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_swapcache_clean
  - mm/memory-failure.c:me_swapcache_clean
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/memory-failure.c:me_pagecache_clean
  - mm/memory-failure.c:truncate_error_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/page_isolation.c (ffffffff814657f8)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
```
```
In mm/zsmalloc.c (ffffffff81469389)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/balloon_compaction.c (ffffffff8146ab9e)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/secretmem.c (ffffffff8146b4b8)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff8146d5f2)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/page_idle.c (ffffffff8146e289)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_clear_pte_refs
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/usercopy.c (ffffffff8146e863)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In mm/memremap.c (ffffffff8146f862)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:free_zone_device_page
  - mm/memremap.c:free_zone_device_page
```
```
In mm/hmm.c (0)
Location: include/linux/page-flags.h:212
Inline: True
```
```
In mm/memfd.c (ffffffff8147162c)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/exec.c (ffffffff8148532f)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff8148806c)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:generic_pipe_buf_get
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff8148a879)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff814ba004)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:zero_user_segments
  - fs/libfs.c:zero_user_segments
  - fs/libfs.c:zero_user_segments
```
```
In fs/splice.c (ffffffff814c5ec0)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_release
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/buffer.c (ffffffff814d598c)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:__find_get_block_slow
  - fs/buffer.c:zero_user_segments
  - fs/buffer.c:zero_user_segments
  - fs/buffer.c:zero_user_segments
```
```
In fs/direct-io.c (ffffffff814d8e7f)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff814da646)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
  - fs/mpage.c:clean_page_buffers
```
```
In fs/aio.c (ffffffff814f2817)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/crypto/crypto.c (ffffffff8206a459)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/verity/enable.c (ffffffff81503dd9)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff815062c3)
Location: include/linux/page-flags.h:212
Inline: True
```
```
In fs/verity/verify.c (ffffffff81506765)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/coredump.c (ffffffff81519917)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/iomap/buffered-io.c (ffffffff8151de8b)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:zero_user_segments
  - fs/iomap/buffered-io.c:zero_user_segments
  - fs/iomap/buffered-io.c:zero_user_segments
```
```
In fs/iomap/direct-io.c (ffffffff8151ff50)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/proc/task_mmu.c (ffffffff8152d8fa)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
  - fs/proc/task_mmu.c:smaps_page_accumulate
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/kcore.c (ffffffff81545fc1)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/page.c (ffffffff81548124)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
  - fs/proc/page.c:kpagecount_read
```
```
In fs/ext4/inline.c (ffffffff81576a62)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81585e20)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:zero_user_segments
  - fs/ext4/inode.c:zero_user_segments
  - fs/ext4/inode.c:zero_user_segments
```
```
In fs/ext4/mballoc.c (ffffffff81590e3c)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff815992e4)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff815a3f2b)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff815a4c58)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ext4/verity.c (ffffffff815dad36)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/commit.c (ffffffff815deeaa)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/squashfs/file.c (ffffffff815eeddd)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file.c:squashfs_fill_page
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/squashfs/symlink.c (ffffffff815f1b3e)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/file_direct.c (ffffffff815f232b)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff815f7484)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8160d14b)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/ecryptfs/read_write.c (ffffffff8160d529)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8161b801)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff81624e53)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
```
```
In fs/fuse/readdir.c (ffffffff8162f6de)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/selinux/selinuxfs.c (ffffffff8167cb85)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In security/tomoyo/domain.c (ffffffff816b1931)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/fops.c (ffffffff8172b80f)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
```
```
In block/bio.c (ffffffff8172fbfe)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_release_pages
```
```
In block/blk-map.c (ffffffff8173c19d)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In io_uring/io_uring.c (ffffffff81789c23)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_mmap
  - io_uring/io_uring.c:io_uring_mmap
```
```
In io_uring/rsrc.c (ffffffff817a0931)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_account_pin
  - io_uring/rsrc.c:io_buffer_account_pin
  - io_uring/rsrc.c:io_buffer_account_pin
  - io_uring/rsrc.c:io_buffer_account_pin
```
```
In lib/iov_iter.c (ffffffff817d2c8b)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:pipe_get_pages
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:page_copy_sane
  - lib/iov_iter.c:page_copy_sane
```
```
In drivers/pci/p2pdma.c (ffffffff8191bedf)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8193e111)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a16ade)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81a19485)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81a96439)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff81a9f2d3)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81b70933)
Location: include/linux/page-flags.h:212
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
In drivers/dma-buf/udmabuf.c (ffffffff81b73312)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff81b9ad48)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/ata/libata-sff.c (ffffffff81bc0f5e)
Location: include/linux/page-flags.h:212
Inline: True
```
```
In drivers/net/tun.c (ffffffff81bf2c25)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:__tun_build_skb
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/xen-netfront.c (ffffffff81c05247)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/md/md.c (ffffffff81cf752c)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff81d041e8)
Location: include/linux/page-flags.h:212
Inline: True
```
```
In net/socket.c (ffffffff81d94004)
Location: include/linux/page-flags.h:212
Inline: True
```
```
In net/core/sock.c (ffffffff81d994ff)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81dac14f)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:__skb_zcopy_downgrade_managed
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:napi_build_skb
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/datagram.c (ffffffff81db014f)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81dff118)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81e0696e)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81e09103)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/page_pool.c (ffffffff81e10094)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_skb_page
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/core/skmsg.c (ffffffff81e47360)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81e9b57a)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81eb1f8d)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_output.c (ffffffff81ec3b8e)
Location: include/linux/page-flags.h:212
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f27810)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff81f38d7e)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81f4838f)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81f56ddb)
Location: include/linux/page-flags.h:212
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fcae0d)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81fed04d)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
  - net/xdp/xsk.c:xsk_mmap
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff81ffb8e6)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:dfrag_clear
```
```
In lib/buildid.c (ffffffff8201f089)
Location: include/linux/page-flags.h:212
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
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
In init/do_mounts.c (ffffffff83682831)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - init/do_mounts.c:mount_root_generic
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81004051)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092004)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109482e)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/exit.c (ffffffff810fdb9a)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/resource.c (ffffffff811013f3)
Location: include/linux/page-flags.h:206
Inline: True
```
```
In kernel/power/swap.c (ffffffff81199a58)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex/core.c (ffffffff81207d75)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/relay.c (ffffffff81262e3f)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff8136a793)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff813814bf)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/watch_queue.c (ffffffff81388b9e)
Location: include/linux/page-flags.h:206
Inline: True
```
```
In mm/filemap.c (ffffffff8138ec04)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff81398f6e)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
```
```
In mm/folio-compat.c (ffffffff8139dca1)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/folio-compat.c:putback_lru_page
  - mm/folio-compat.c:isolate_lru_page
  - mm/folio-compat.c:add_to_page_cache_lru
  - mm/folio-compat.c:lru_cache_add_inactive_or_unevictable
  - mm/folio-compat.c:redirty_page_for_writepage
  - mm/folio-compat.c:clear_page_dirty_for_io
  - mm/folio-compat.c:__set_page_dirty_nobuffers
  - mm/folio-compat.c:__set_page_dirty_nobuffers
  - mm/folio-compat.c:set_page_dirty
  - mm/folio-compat.c:set_page_writeback
  - mm/folio-compat.c:mark_page_accessed
  - mm/folio-compat.c:wait_for_stable_page
  - mm/folio-compat.c:wait_on_page_writeback
  - mm/folio-compat.c:end_page_writeback
  - mm/folio-compat.c:unlock_page
```
```
In mm/swap.c (ffffffff813a1655)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/truncate.c (ffffffff813a4184)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:generic_error_remove_page
```
```
In mm/vmscan.c (ffffffff813b7693)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:get_pfn_folio
```
```
In mm/shmem.c (ffffffff813be535)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_swapin
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
```
```
In mm/util.c (ffffffff813c4381)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/util.c:page_rmapping
```
```
In mm/slab_common.c (ffffffff813d58d8)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/slab_common.c:__ksize
  - mm/slab_common.c:kfree
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/compaction.c (ffffffff813dacc5)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff813e1f07)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff813e7986)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
  - mm/gup.c:lockless_pages_from_mm
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:migrate_longterm_unpinnable_pages
  - mm/gup.c:migrate_longterm_unpinnable_pages
  - mm/gup.c:migrate_longterm_unpinnable_pages
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff813f52ef)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:vm_normal_folio
```
```
In mm/mlock.c (ffffffff813f9779)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mmap.c (ffffffff813fa1b4)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/mprotect.c (ffffffff81402951)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/page_vma_mapped.c (ffffffff814070fb)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:vma_address
  - mm/page_vma_mapped.c:vma_address
```
```
In mm/rmap.c (ffffffff8140f676)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_move_anon_rmap
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:vma_address
  - mm/rmap.c:vma_address
```
```
In mm/vmalloc.c (ffffffff8141753a)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vfree
```
```
In mm/page_alloc.c (ffffffff81423c23)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:__free_pages
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_tail_page_prepare
  - mm/page_alloc.c:free_tail_page_prepare
  - mm/page_alloc.c:free_compound_page
```
```
In mm/memory_hotplug.c (ffffffff82147965)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/madvise.c (ffffffff814293b9)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:shmem_swapin_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/page_io.c (ffffffff8142aff2)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:bio_associate_blkg_from_page
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:__end_swap_bio_read
  - mm/page_io.c:__end_swap_bio_read
  - mm/page_io.c:__end_swap_bio_write
  - mm/page_io.c:__end_swap_bio_write
```
```
In mm/swap_state.c (ffffffff8142c84e)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff8142fc94)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/frontswap.c (ffffffff81434add)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
```
```
In mm/zswap.c (ffffffff81436b56)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81440cd9)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:return_unused_surplus_pages
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:alloc_fresh_hugetlb_folio
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:PageHuge
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/mempolicy.c (ffffffff814494fa)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_folio_add
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff8214f717)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff814584cd)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/ksm.c:collect_procs_ksm
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm_pmd_entry
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/slub.c (ffffffff814619a7)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:cache_from_obj
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/kfence/core.c (ffffffff81464f22)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/migrate.c (ffffffff8146bd23)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
```
```
In mm/migrate_device.c (ffffffff8146fd87)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814794fe)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:can_change_pmd_writable
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81480cfb)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:set_huge_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:alloc_charge_hpage
  - mm/khugepaged.c:alloc_charge_hpage
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_pages
```
```
In mm/memcontrol.c (ffffffff8148e3e3)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
  - mm/memcontrol.c:get_obj_cgroup_from_page
  - mm/memcontrol.c:get_obj_cgroup_from_page
  - mm/memcontrol.c:get_obj_cgroup_from_page
  - mm/memcontrol.c:mem_cgroup_from_slab_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_page_state
  - mm/memcontrol.c:__mod_lruvec_page_state
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/hugetlb_cgroup.c (ffffffff81492c2a)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff81499bd9)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:try_to_split_thp_page
  - mm/memory-failure.c:try_to_split_thp_page
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_swapcache_clean
  - mm/memory-failure.c:me_swapcache_clean
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/memory-failure.c:me_pagecache_clean
  - mm/memory-failure.c:truncate_error_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:collect_procs_anon
  - mm/memory-failure.c:collect_procs_anon
  - mm/memory-failure.c:collect_procs_anon
  - mm/memory-failure.c:__add_to_kill
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/page_isolation.c (ffffffff8149b1f1)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
```
```
In mm/zsmalloc.c (ffffffff8149e318)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/balloon_compaction.c (ffffffff8149fa2e)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/secretmem.c (ffffffff814a029b)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff814a0b40)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/page_idle.c (ffffffff814a2aaf)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_folio
  - mm/page_idle.c:page_idle_get_folio
  - mm/page_idle.c:page_idle_get_folio
```
```
In mm/usercopy.c (ffffffff814a2ff8)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In mm/memremap.c (ffffffff814a4042)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:free_zone_device_page
  - mm/memremap.c:free_zone_device_page
```
```
In mm/hmm.c (0)
Location: include/linux/page-flags.h:206
Inline: True
```
```
In mm/memfd.c (ffffffff814a5b67)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/exec.c (ffffffff814ba39d)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff814bcf59)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:generic_pipe_buf_get
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff814c0a49)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff814eef74)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/fs-writeback.c (ffffffff814f4d5f)
Location: include/linux/page-flags.h:206
Inline: True
```
```
In fs/splice.c (ffffffff814fb3a1)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_release
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/buffer.c (ffffffff8150b7eb)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_commit_write
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/mpage.c (ffffffff8150f1ad)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
  - fs/mpage.c:clean_page_buffers
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_read_end_io
  - fs/mpage.c:mpage_read_end_io
```
```
In fs/direct-io.c (ffffffff81510281)
Location: include/linux/page-flags.h:206
Inline: True
```
```
In fs/aio.c (ffffffff8152943a)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/crypto/crypto.c (ffffffff8153330f)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/crypto/bio.c (ffffffff8153a5dc)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/read_metadata.c (ffffffff8153d5f9)
Location: include/linux/page-flags.h:206
Inline: True
```
```
In fs/verity/verify.c (ffffffff8153e63f)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
```
```
In fs/coredump.c (ffffffff8155120b)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/iomap/buffered-io.c (ffffffff81554573)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/proc/task_mmu.c (ffffffff81565d2a)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
  - fs/proc/task_mmu.c:smaps_page_accumulate
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/kcore.c (ffffffff8157d934)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore_iter
```
```
In fs/proc/page.c (ffffffff8157fcf7)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
  - fs/proc/page.c:kpagecount_read
```
```
In fs/ext4/inode.c (ffffffff815bc56c)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/mballoc.c (ffffffff815c219f)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/page-io.c (ffffffff815dad3e)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff815db048)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/block.c (ffffffff8162418d)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In fs/squashfs/file.c (ffffffff81626dcd)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81629c2e)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/file_direct.c (ffffffff8162a41b)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff8162faee)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8164500b)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/ecryptfs/read_write.c (ffffffff816453e8)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81653971)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8165d1d9)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
```
```
In fs/fuse/readdir.c (ffffffff81667951)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/selinux/selinuxfs.c (ffffffff816b4e58)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In security/tomoyo/domain.c (ffffffff816ea334)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/fops.c (ffffffff8176768f)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
```
```
In block/bio.c (ffffffff8176be2c)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
```
```
In io_uring/io_uring.c (ffffffff817c9a05)
Location: include/linux/page-flags.h:206
Inline: True
```
```
In io_uring/kbuf.c (ffffffff817e010c)
Location: include/linux/page-flags.h:206
Inline: True
```
```
In io_uring/rsrc.c (ffffffff817e35c6)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_buffer_account_pin
  - io_uring/rsrc.c:io_buffer_account_pin
  - io_uring/rsrc.c:io_buffer_account_pin
```
```
In lib/iov_iter.c (ffffffff8181368e)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_to_iter_nofault
```
```
In drivers/pci/p2pdma.c (ffffffff8195f4f2)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81982611)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5fb6e)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81a623a5)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81ae1c49)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff81aeac33)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81bc6d68)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff81bf1208)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/ata/libata-sff.c (ffffffff81c18b0d)
Location: include/linux/page-flags.h:206
Inline: True
```
```
In drivers/net/tun.c (ffffffff81c4a1d1)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:__tun_build_skb
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/virtio_net.c (ffffffff81c541ca)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_rq_free_unused_buf
  - drivers/net/virtio_net.c:virtnet_rq_free_unused_buf
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:mergeable_buf_free
  - drivers/net/virtio_net.c:mergeable_buf_free
  - drivers/net/virtio_net.c:receive_small
  - drivers/net/virtio_net.c:receive_small
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:page_to_skb
```
```
In drivers/net/xen-netfront.c (ffffffff81c6a957)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/md/md.c (ffffffff81d5ee28)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff81d6cf78)
Location: include/linux/page-flags.h:206
Inline: True
```
```
In net/core/sock.c (ffffffff81e0781f)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81e14b65)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_splice_from_iter
  - net/core/skbuff.c:skb_splice_from_iter
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:__skb_zcopy_downgrade_managed
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:napi_build_skb
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/datagram.c (ffffffff81e2046c)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81e70be8)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81e7960c)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81e7b772)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/page_pool.c (ffffffff81e838f5)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_skb_page
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/core/skmsg.c (ffffffff81ea2dc8)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81efa142)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81f1063c)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81f25484)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f86186)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff81f98a6b)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81fa7f43)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81fb683b)
Location: include/linux/page-flags.h:206
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202c08f)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff8206addb)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff82077c6c)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:dfrag_clear
```
```
In lib/buildid.c (ffffffff8209f09c)
Location: include/linux/page-flags.h:206
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
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
In init/do_mounts.c (ffffffff838b18d1)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - init/do_mounts.c:mount_root_generic
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/entry/vdso/vma.c (ffffffff8100695d)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81099374)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109bd0e)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/fork.c (ffffffff810f9b0f)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (ffffffff8110694d)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/resource.c (ffffffff8110ab1f)
Location: include/linux/page-flags.h:208
Inline: True
```
```
In kernel/power/swap.c (ffffffff811a8ab8)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex/core.c (ffffffff8121ee96)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/relay.c (ffffffff8127d05f)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff81393123)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff813aa86e)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/watch_queue.c (ffffffff813b25fe)
Location: include/linux/page-flags.h:208
Inline: True
```
```
In mm/filemap.c (ffffffff813b7ff4)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff813c2d6e)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
```
```
In mm/folio-compat.c (ffffffff813c7981)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/folio-compat.c:putback_lru_page
  - mm/folio-compat.c:isolate_lru_page
  - mm/folio-compat.c:add_to_page_cache_lru
  - mm/folio-compat.c:redirty_page_for_writepage
  - mm/folio-compat.c:clear_page_dirty_for_io
  - mm/folio-compat.c:__set_page_dirty_nobuffers
  - mm/folio-compat.c:__set_page_dirty_nobuffers
  - mm/folio-compat.c:set_page_dirty
  - mm/folio-compat.c:set_page_writeback
  - mm/folio-compat.c:mark_page_accessed
  - mm/folio-compat.c:wait_for_stable_page
  - mm/folio-compat.c:wait_on_page_writeback
  - mm/folio-compat.c:end_page_writeback
  - mm/folio-compat.c:unlock_page
```
```
In mm/swap.c (ffffffff813cb2d5)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/truncate.c (ffffffff813cdcd4)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:pagecache_isize_extended
```
```
In mm/vmscan.c (ffffffff813e052b)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:get_pfn_folio
```
```
In mm/shmem.c (ffffffff813e922b)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
```
```
In mm/slab_common.c (ffffffff813ff58b)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/slab_common.c:__ksize
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/compaction.c (ffffffff81404bbf)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff8140c733)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff814125f6)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
  - mm/gup.c:lockless_pages_from_mm
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff81415901)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:vm_normal_folio_pmd
```
```
In mm/mlock.c (ffffffff8142542a)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mmap.c (ffffffff81425f74)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/mmu_gather.c (ffffffff8142dd7a)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_rmap_batch
```
```
In mm/mprotect.c (ffffffff8142f4cc)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/page_vma_mapped.c (ffffffff8143378f)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:vma_address
  - mm/page_vma_mapped.c:vma_address
```
```
In mm/rmap.c (ffffffff814382e1)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:vma_address
  - mm/rmap.c:vma_address
```
```
In mm/vmalloc.c (ffffffff8144404a)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff81450b60)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:__free_pages
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_tail_page_prepare
  - mm/page_alloc.c:free_tail_page_prepare
```
```
In mm/memory_hotplug.c (ffffffff82229fe9)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/slub.c (ffffffff8145dcdc)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__memcg_slab_post_alloc_hook
```
```
In mm/madvise.c (ffffffff81462be9)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff81464505)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/page_io.c:swap_read_folio_fs
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:__end_swap_bio_read
  - mm/page_io.c:__end_swap_bio_write
```
```
In mm/swap_state.c (ffffffff81465656)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff81468cf2)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_index
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8147ae09)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__alloc_fresh_hugetlb_folio
  - mm/hugetlb.c:PageHuge
```
```
In mm/mempolicy.c (ffffffff81486fd7)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_folio_add
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/mempolicy.c:queue_folios_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff822325e2)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81492c3d)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/ksm.c:collect_procs_ksm
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm_pmd_entry
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/kfence/core.c (ffffffff81493b69)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/migrate.c (ffffffff8149acd8)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
```
```
In mm/migrate_device.c (ffffffff8149f004)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a89ba)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814aecd5)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:set_huge_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_pages
```
```
In mm/memcontrol.c (ffffffff814bdc50)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
  - mm/memcontrol.c:mem_cgroup_from_slab_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/hugetlb_cgroup.c (ffffffff814c2344)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff814c93c8)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:is_raw_hwpoison_page_in_hugepage
  - mm/memory-failure.c:try_to_split_thp_page
  - mm/memory-failure.c:try_to_split_thp_page
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_swapcache_clean
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/memory-failure.c:me_pagecache_clean
  - mm/memory-failure.c:has_extra_refcount
  - mm/memory-failure.c:has_extra_refcount
  - mm/memory-failure.c:collect_procs_anon
  - mm/memory-failure.c:collect_procs_anon
  - mm/memory-failure.c:__add_to_kill
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/page_isolation.c (ffffffff814ca8d1)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
```
```
In mm/zsmalloc.c (ffffffff814cd44a)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/balloon_compaction.c (ffffffff814cf17e)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/userfaultfd.c (ffffffff814d335b)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/page_idle.c (ffffffff814d393f)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_folio
  - mm/page_idle.c:page_idle_get_folio
  - mm/page_idle.c:page_idle_get_folio
```
```
In mm/usercopy.c (ffffffff814d3e8c)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In mm/memremap.c (ffffffff814d4ef2)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:free_zone_device_page
  - mm/memremap.c:free_zone_device_page
```
```
In mm/hmm.c (0)
Location: include/linux/page-flags.h:208
Inline: True
```
```
In mm/memfd.c (ffffffff814d6b14)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/exec.c (ffffffff814ec91d)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff814ef3f9)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:generic_pipe_buf_get
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_try_steal
  - fs/pipe.c:anon_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff814f3095)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81522bee)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (ffffffff8152946f)
Location: include/linux/page-flags.h:208
Inline: True
```
```
In fs/splice.c (ffffffff81530093)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_release
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/buffer.c (ffffffff81541f55)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_commit_write
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/mpage.c (ffffffff81542e51)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/mpage.c:bio_first_folio
```
```
In fs/direct-io.c (ffffffff81544731)
Location: include/linux/page-flags.h:208
Inline: True
```
```
In fs/aio.c (ffffffff8155e30e)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/crypto/crypto.c (ffffffff81568207)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/crypto/bio.c (ffffffff8156f091)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/crypto/bio.c:bio_first_folio
```
```
In fs/verity/read_metadata.c (ffffffff81572a59)
Location: include/linux/page-flags.h:208
Inline: True
```
```
In fs/verity/verify.c (ffffffff81573cac)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
```
```
In fs/coredump.c (ffffffff815870eb)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/iomap/buffered-io.c (ffffffff8158a748)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/proc/task_mmu.c (ffffffff8159dd07)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_category
  - fs/proc/task_mmu.c:pagemap_thp_category
  - fs/proc/task_mmu.c:pagemap_thp_category
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
  - fs/proc/task_mmu.c:smaps_page_accumulate
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/kcore.c (ffffffff815b637b)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore_iter
```
```
In fs/proc/page.c (ffffffff815b86ef)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
  - fs/proc/page.c:kpagecount_read
```
```
In fs/ext4/inode.c (ffffffff815f534c)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/mballoc.c (ffffffff81601cc7)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/page-io.c (ffffffff8161357e)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81613ad4)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/jbd2/journal.c (ffffffff8165c9d1)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/block.c (ffffffff8165d22d)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In fs/squashfs/file.c (ffffffff8165ff2e)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81662e7e)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/file_direct.c (ffffffff81663745)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff8167e53b)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/ecryptfs/read_write.c (ffffffff8167e909)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8168cf81)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff81696f39)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
```
```
In fs/fuse/readdir.c (ffffffff816a1c95)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/selinux/selinuxfs.c (ffffffff816f19b8)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In security/tomoyo/domain.c (ffffffff81727044)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/fops.c (ffffffff817a947f)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
```
```
In block/bio.c (ffffffff817aabb1)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - block/bio.c:bio_first_folio
```
```
In block/bio-integrity.c (ffffffff817f9520)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_map_user
  - block/bio-integrity.c:bio_integrity_map_user
```
```
In io_uring/io_uring.c (ffffffff8180f59c)
Location: include/linux/page-flags.h:208
Inline: True
```
```
In io_uring/rsrc.c (ffffffff8182766d)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_buffer_account_pin
  - io_uring/rsrc.c:io_buffer_account_pin
  - io_uring/rsrc.c:io_buffer_account_pin
```
```
In lib/iov_iter.c (ffffffff81859238)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_to_iter_nofault
```
```
In drivers/pci/p2pdma.c (ffffffff819a8b52)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819c9d91)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab237e)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81ab4bd5)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81b35039)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff81b3e113)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81c1b8d7)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff81c46ac8)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/ata/libata-sff.c (ffffffff81c6d85d)
Location: include/linux/page-flags.h:208
Inline: True
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9c289)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_put_pages
  - drivers/gpu/drm/drm_gem.c:drm_gem_get_pages
```
```
In drivers/net/tun.c (ffffffff81cffb5d)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:__tun_build_skb
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/virtio_net.c (ffffffff81d078ca)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:free_receive_page_frags
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:mergeable_buf_free
  - drivers/net/virtio_net.c:mergeable_buf_free
  - drivers/net/virtio_net.c:receive_small
  - drivers/net/virtio_net.c:receive_small
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:virtnet_rq_alloc
  - drivers/net/virtio_net.c:virtnet_rq_alloc
  - drivers/net/virtio_net.c:virtnet_rq_unmap
  - drivers/net/virtio_net.c:virtnet_rq_unmap
  - drivers/net/virtio_net.c:page_to_skb
```
```
In drivers/net/xen-netfront.c (ffffffff81d1f337)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/md/md.c (ffffffff81e16098)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff81e241a3)
Location: include/linux/page-flags.h:208
Inline: True
```
```
In net/core/sock.c (ffffffff81ec425f)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81ed2165)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_splice_from_iter
  - net/core/skbuff.c:skb_splice_from_iter
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:__skb_zcopy_downgrade_managed
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:napi_pp_put_page
  - net/core/skbuff.c:skb_add_rx_frag
  - net/core/skbuff.c:napi_build_skb
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/datagram.c (ffffffff81ede349)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81f302bf)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81f396a6)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81f3ba02)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/page_pool.c (ffffffff81f43b4c)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_return_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
```
```
In net/core/skmsg.c (ffffffff81f650f8)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81fbe070)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81fd482b)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81fe9d45)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204d766)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff82065ddb)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff82075203)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff82084126)
Location: include/linux/page-flags.h:208
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820fbb3f)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff8213e75d)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff8214cdb0)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:dfrag_clear
```
```
In lib/buildid.c (ffffffff8217709c)
Location: include/linux/page-flags.h:208
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
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
