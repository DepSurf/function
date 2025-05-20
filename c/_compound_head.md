# Function: <code>_compound_head</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81c948da)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - init/do_mounts.c:put_page
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81004d0e)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070614)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81071788)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/exit.c (ffffffff810bc549)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/resource.c (ffffffff810be7c5)
Location: include/linux/page-flags.h:194
Inline: True
```
```
In kernel/power/swap.c (ffffffff811354a3)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff8117d696)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/relay.c (ffffffff811cf826)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff8127ac07)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff81291249)
Location: include/linux/page-flags.h:194
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
```
```
In kernel/watch_queue.c (ffffffff8129712b)
Location: include/linux/page-flags.h:194
Inline: True
```
```
In mm/filemap.c (ffffffff81298cb5)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/filemap.c:try_to_release_page
  - mm/filemap.c:try_to_release_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_async
  - mm/filemap.c:page_endio
  - mm/filemap.c:page_endio
  - mm/filemap.c:page_endio
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:wait_on_page_private_2_killable
  - mm/filemap.c:wait_on_page_private_2
  - mm/filemap.c:end_page_private_2
  - mm/filemap.c:end_page_private_2
  - mm/filemap.c:unlock_page
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:add_to_page_cache_lru
  - mm/filemap.c:add_to_page_cache_lru
  - mm/filemap.c:add_to_page_cache_lru
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:filemap_range_needs_writeback
  - mm/filemap.c:filemap_range_needs_writeback
  - mm/filemap.c:filemap_range_needs_writeback
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff812a4735)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/page-writeback.c:wait_for_stable_page
  - mm/page-writeback.c:wait_on_page_writeback_killable
  - mm/page-writeback.c:wait_on_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty
  - mm/page-writeback.c:__set_page_dirty
  - mm/page-writeback.c:__set_page_dirty
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff812a8739)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
  - mm/readahead.c:read_cache_pages_invalidate_page
  - mm/readahead.c:read_cache_pages_invalidate_page
```
```
In mm/swap.c (ffffffff812a9e55)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
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
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
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
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
  - mm/swap.c:lru_cache_add
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:get_kernel_pages
  - mm/swap.c:put_pages_list
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/truncate.c (ffffffff812ad5b2)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:truncate_cleanup_page
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff812b2600)
Location: include/linux/page-flags.h:194
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
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
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
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
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
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/shmem.c (ffffffff812be05d)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
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
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff812c083f)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
  - mm/util.c:__page_mapcount
  - mm/util.c:page_mapping
  - mm/util.c:page_mapping
  - mm/util.c:page_mapping
  - mm/util.c:page_mapping
  - mm/util.c:page_anon_vma
  - mm/util.c:page_rmapping
```
```
In mm/slab_common.c (ffffffff812cc9e3)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_dump_obj
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/compaction.c (ffffffff812d18d6)
Location: include/linux/page-flags.h:194
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
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/workingset.c (ffffffff812d6bd5)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/debug.c (ffffffff812d706b)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff812dac46)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
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
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:unpin_user_pages
  - mm/gup.c:unpin_user_pages
  - mm/gup.c:unpin_user_pages
  - mm/gup.c:unpin_user_pages
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
  - mm/gup.c:put_compound_head
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff812e3125)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:vm_insert_page
  - mm/memory.c:validate_page_before_insert
  - mm/memory.c:validate_page_before_insert
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:restore_exclusive_pte
  - mm/memory.c:restore_exclusive_pte
  - mm/memory.c:put_page
```
```
In mm/mincore.c (ffffffff812e8274)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:__mincore_unmapped_range
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/mlock.c (ffffffff812e8f84)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff812ea5e0)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/mprotect.c (ffffffff812f085a)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812f4bf8)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812f9d8a)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:page_mlock
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap
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
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_move_anon_rmap
  - mm/rmap.c:page_mkclean
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff8130a0b1)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/memory_hotplug.c (ffffffff81d4c0e2)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff8130eabb)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
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
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/page_io.c (ffffffff8130fc09)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:swap_slot_free_notify
  - mm/page_io.c:swap_slot_free_notify
  - mm/page_io.c:swap_slot_free_notify
  - mm/page_io.c:end_swap_bio_write
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/swap_state.c (ffffffff813111cc)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81317195)
Location: include/linux/page-flags.h:194
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
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/frontswap.c (ffffffff813189d8)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
```
```
In mm/zswap.c (ffffffff8131a498)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff813259b6)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:hugetlb_basepage_index
```
```
In mm/mempolicy.c (ffffffff81329790)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:lookup_node
```
```
In mm/ksm.c (ffffffff813322a5)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/ksm.c:ksm_migrate_page
  - mm/ksm.c:rmap_walk_ksm
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
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
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
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
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
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
  - mm/ksm.c:break_ksm
```
```
In mm/slub.c (ffffffff81336498)
Location: include/linux/page-flags.h:194
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
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/kfence/core.c (ffffffff832dce0b)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
  - mm/kfence/core.c:kfence_init_pool
```
```
In mm/migrate.c (ffffffff8133f203)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
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
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff8134ac00)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_pid
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
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:page_trans_huge_mapcount
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
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
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
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:is_transparent_hugepage
```
```
In mm/khugepaged.c (ffffffff8135016e)
Location: include/linux/page-flags.h:194
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
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff81358dc3)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:unlock_page_memcg
  - mm/memcontrol.c:lock_page_memcg
  - mm/memcontrol.c:__mod_lruvec_page_state
```
```
In mm/memory-failure.c (ffffffff81361166)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
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
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:identify_page_state
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
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_pagecache_dirty
  - mm/memory-failure.c:me_pagecache_clean
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/page_isolation.c (ffffffff813620a2)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/zsmalloc.c (ffffffff81364b3a)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:__free_zspage
  - mm/zsmalloc.c:trylock_zspage
```
```
In mm/balloon_compaction.c (ffffffff81366233)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/secretmem.c (ffffffff813667a5)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff813683bb)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/page_idle.c (ffffffff81368e23)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/usercopy.c (ffffffff8136907c)
Location: include/linux/page-flags.h:194
Inline: True
```
```
In mm/memremap.c (ffffffff813697a1)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In mm/hmm.c (0)
Location: include/linux/page-flags.h:194
Inline: True
```
```
In mm/memfd.c (ffffffff8136b5e2)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/exec.c (ffffffff8137af95)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff8137db88)
Location: include/linux/page-flags.h:194
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
In fs/namei.c (ffffffff813806a5)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff813a727e)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/fs-writeback.c (ffffffff813ae1ac)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/splice.c (ffffffff813b2b45)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_release
  - fs/splice.c:page_cache_pipe_buf_try_steal
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff813bbe0e)
Location: include/linux/page-flags.h:194
Inline: True
```
```
In fs/buffer.c (ffffffff813bf982)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
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
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/direct-io.c (ffffffff813c3ba3)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_zero_block
  - fs/direct-io.c:dio_zero_block
  - fs/direct-io.c:dio_zero_block
```
```
In fs/mpage.c (ffffffff813c5276)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readahead
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff813d9656)
Location: include/linux/page-flags.h:194
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
In fs/io_uring.c (ffffffff813df3df)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_buffer_account_pin
  - fs/io_uring.c:io_buffer_account_pin
  - fs/io_uring.c:io_buffer_account_pin
```
```
In fs/crypto/crypto.c (ffffffff813f824d)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/crypto/bio.c (ffffffff813fd538)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/enable.c (ffffffff813fe7c5)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:read_file_data_page
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/verity/read_metadata.c (ffffffff814002d1)
Location: include/linux/page-flags.h:194
Inline: True
```
```
In fs/verity/verify.c (ffffffff81400d54)
Location: include/linux/page-flags.h:194
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
In fs/coredump.c (ffffffff814105cc)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/iomap/buffered-io.c (ffffffff81413cfa)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_releasepage
  - fs/iomap/buffered-io.c:iomap_releasepage
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readpage
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/iomap/direct-io.c (ffffffff8141535e)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/proc/task_mmu.c (ffffffff81420904)
Location: include/linux/page-flags.h:194
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
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In fs/proc/kcore.c (ffffffff8143540c)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/page.c (ffffffff81436ccb)
Location: include/linux/page-flags.h:194
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
  - fs/proc/page.c:kpagecount_read
```
```
In fs/ext4/inline.c (ffffffff8145f0cc)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8146c0ba)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:mpage_release_unused_pages
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
In fs/ext4/mballoc.c (ffffffff81473c2a)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff8147c318)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81485d80)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff8148682d)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
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
In fs/ext4/symlink.c (ffffffff814a7385)
Location: include/linux/page-flags.h:194
Inline: True
```
```
In fs/ext4/verity.c (ffffffff814b2e69)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffff814b6424)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In fs/jbd2/commit.c (ffffffff814b68b6)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
  - fs/jbd2/commit.c:release_buffer_page
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/squashfs/file.c (ffffffff814c3d49)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81ccf1ab)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff814c6201)
Location: include/linux/page-flags.h:194
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
In fs/hugetlbfs/inode.c (ffffffff814ca06d)
Location: include/linux/page-flags.h:194
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
In fs/ecryptfs/mmap.c (ffffffff814db97d)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/ecryptfs/read_write.c (ffffffff814dbc75)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff814e813e)
Location: include/linux/page-flags.h:194
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
In fs/fuse/file.c (ffffffff814eea4d)
Location: include/linux/page-flags.h:194
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
In fs/fuse/readdir.c (ffffffff814f8dfa)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/selinux/selinuxfs.c (ffffffff81537b6f)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In security/tomoyo/domain.c (ffffffff815651ad)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/fops.c (ffffffff815c5363)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
```
```
In block/bio.c (ffffffff815c8ebb)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:__bio_iov_append_get_pages
  - block/bio.c:__bio_iov_append_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_add_page
```
```
In block/blk-map.c (ffffffff815d3335)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In block/partitions/core.c (ffffffff815e6cf6)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
  - block/partitions/core.c:read_part_sector
```
```
In block/partitions/amiga.c (ffffffff815e6e86)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff815e77d3)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff815e7c9e)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff815e8cc6)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff815eaae8)
Location: include/linux/page-flags.h:194
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
In block/partitions/msdos.c (ffffffff815ebba5)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
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
In block/partitions/osf.c (ffffffff815ec34c)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff815ec5bd)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff815ec871)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff815ecb1f)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff815ece98)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff815eddb3)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff815edfeb)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In lib/iov_iter.c (ffffffff81615d55)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:pipe_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:copy_page_to_iter
```
```
In lib/buildid.c (ffffffff8165d1c9)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff816e49ae)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178d9ee)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff8178f971)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff817f7fd8)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff817fde4c)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff818ab5f8)
Location: include/linux/page-flags.h:194
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
In drivers/scsi/scsicam.c (ffffffff818af93e)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/scsi/sg.c (ffffffff818cc864)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/ata/libata-sff.c (ffffffff818ea1c7)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pio_xfer
```
```
In drivers/net/tun.c (ffffffff8190f142)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:__tun_build_skb
  - drivers/net/tun.c:tun_napi_alloc_frags
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/xen-netfront.c (ffffffff8191cd42)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/md/md.c (ffffffff819f393c)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff81a00ff4)
Location: include/linux/page-flags.h:194
Inline: True
```
```
In net/socket.c (ffffffff81a73d48)
Location: include/linux/page-flags.h:194
Inline: True
```
```
In net/core/sock.c (ffffffff81a7b287)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81a87da3)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_gro_receive
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
  - net/core/skbuff.c:build_skb
```
```
In net/core/datagram.c (ffffffff81a8b671)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/dev.c (ffffffff81a97f78)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff81ac8600)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81ad3878)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81ad9385)
Location: include/linux/page-flags.h:194
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
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/core/skmsg.c (ffffffff81b06351)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81b4d571)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81b603fb)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_output.c (ffffffff81b6f677)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc82b5)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd6bcb)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81be38bc)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81bf08d7)
Location: include/linux/page-flags.h:194
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c52c0e)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81c73489)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff81c7e64d)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_clean_una
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int _compound_head(const struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81e43a6d)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - init/do_mounts.c:put_page
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81003db5)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107db6e)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107f7f9)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/exit.c (ffffffff810d30dd)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/resource.c (ffffffff810d5d0a)
Location: include/linux/page-flags.h:270
Inline: True
```
```
In kernel/power/swap.c (ffffffff811579a0)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex/core.c (ffffffff811b270f)
Location: include/linux/page-flags.h:270
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
```
```
In kernel/relay.c (ffffffff81203ab6)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff812cdbea)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff812e67ed)
Location: include/linux/page-flags.h:270
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
```
```
In kernel/watch_queue.c (ffffffff812ecf97)
Location: include/linux/page-flags.h:270
Inline: True
```
```
In mm/filemap.c (ffffffff812f1b08)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:page_endio
  - mm/filemap.c:page_endio
  - mm/filemap.c:page_endio
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff812fc5e4)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/folio-compat.c (ffffffff813013a5)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/folio-compat.c:putback_lru_page
  - mm/folio-compat.c:try_to_release_page
  - mm/folio-compat.c:delete_from_page_cache
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
In mm/readahead.c (ffffffff81301990)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
```
```
In mm/swap.c (ffffffff81306e71)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add
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
  - mm/swap.c:__activate_page
  - mm/swap.c:pagevec_move_tail_fn
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:get_kernel_pages
  - mm/swap.c:__put_page
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff81308026)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:generic_error_remove_page
```
```
In mm/vmscan.c (ffffffff8130f395)
Location: include/linux/page-flags.h:270
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
  - mm/vmscan.c:reclaim_pages
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
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/shmem.c (ffffffff8131992f)
Location: include/linux/page-flags.h:270
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
```
```
In mm/util.c (ffffffff8131d7c0)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
  - mm/util.c:__page_mapcount
  - mm/util.c:page_rmapping
```
```
In mm/slab_common.c (ffffffff8132bcf9)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/compaction.c (ffffffff81331c25)
Location: include/linux/page-flags.h:270
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
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/debug.c (ffffffff813368c5)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8133b0ae)
Location: include/linux/page-flags.h:270
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
  - mm/gup.c:follow_page_pte
  - mm/gup.c:unpin_user_pages
  - mm/gup.c:unpin_user_pages
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_get_folio
  - mm/gup.c:try_get_folio
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813480ec)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:insert_pages
  - mm/memory.c:insert_pages
  - mm/memory.c:insert_pages
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mincore.c (ffffffff813495e4)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:__mincore_unmapped_range
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/mlock.c (ffffffff8134c6ff)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:munlock_page
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
```
```
In mm/mmap.c (ffffffff8134d0bf)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/mprotect.c (ffffffff81353bd0)
Location: include/linux/page-flags.h:270
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
In mm/page_vma_mapped.c (ffffffff81357e0b)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:vma_address
```
```
In mm/rmap.c (ffffffff8136009d)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
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
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_move_anon_rmap
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/vmalloc.c (ffffffff81366bcf)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vunmap
```
```
In mm/page_alloc.c (ffffffff8137292a)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_compound_page
```
```
In mm/memory_hotplug.c (ffffffff81f1bad1)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff81375fcf)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
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
In mm/page_io.c (ffffffff8137a456)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/swap_state.c (ffffffff8137c128)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff813828d3)
Location: include/linux/page-flags.h:270
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
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffff81385962)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81394610)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
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
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:free_huge_page
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff81398a75)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/sparse-vmemmap.c (ffffffff81f214d7)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff813a309b)
Location: include/linux/page-flags.h:270
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
In mm/slub.c (ffffffff813a7d00)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/kfence/core.c (ffffffff813aef62)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:kfence_init
```
```
In mm/migrate.c (ffffffff813b5ddb)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
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
  - mm/migrate.c:migrate_page
  - mm/migrate.c:migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff813b635b)
Location: include/linux/page-flags.h:270
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
In mm/huge_memory.c (ffffffff813c1d90)
Location: include/linux/page-flags.h:270
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
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_pid
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
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff813c832a)
Location: include/linux/page-flags.h:270
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
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
Direct callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/memcontrol.c (ffffffff813d5ac5)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
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
In mm/memory-failure.c (ffffffff813dd3fe)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
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
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:memory_failure_dev_pagemap
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
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:page_handle_poison
Direct callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
```
In mm/page_isolation.c (ffffffff813deb2f)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
```
```
In mm/zsmalloc.c (ffffffff813e1d9a)
Location: include/linux/page-flags.h:270
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
In mm/balloon_compaction.c (ffffffff813e321a)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/secretmem.c (ffffffff813e3ace)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff813e5a3d)
Location: include/linux/page-flags.h:270
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
In mm/page_idle.c (ffffffff813e677d)
Location: include/linux/page-flags.h:270
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
In mm/usercopy.c (ffffffff813e6c7f)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In mm/memremap.c (ffffffff813e7c00)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
  - mm/memremap.c:free_zone_device_page
```
```
In mm/hmm.c (0)
Location: include/linux/page-flags.h:270
Inline: True
```
```
In mm/memfd.c (ffffffff813e9671)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/exec.c (ffffffff813fb262)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff813fe3e0)
Location: include/linux/page-flags.h:270
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
In fs/namei.c (ffffffff81400695)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8142c785)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff81437bb6)
Location: include/linux/page-flags.h:270
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
In fs/buffer.c (ffffffff8144686b)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
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
  - fs/buffer.c:clean_bdev_aliases
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
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/direct-io.c (ffffffff8144a771)
Location: include/linux/page-flags.h:270
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
In fs/mpage.c (ffffffff8144c207)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readahead
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff8146371a)
Location: include/linux/page-flags.h:270
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
In fs/crypto/crypto.c (ffffffff8146af31)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/crypto/bio.c (ffffffff81470d49)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/enable.c (ffffffff814722df)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff81474063)
Location: include/linux/page-flags.h:270
Inline: True
```
```
In fs/verity/verify.c (ffffffff81474dfa)
Location: include/linux/page-flags.h:270
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
In fs/coredump.c (ffffffff814860bc)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/iomap/buffered-io.c (ffffffff8148a485)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_migrate_page
  - fs/iomap/buffered-io.c:iomap_migrate_page
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/iomap/direct-io.c (ffffffff8148ca37)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/proc/task_mmu.c (ffffffff8149966e)
Location: include/linux/page-flags.h:270
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
  - fs/proc/task_mmu.c:smaps_page_accumulate
  - fs/proc/task_mmu.c:smaps_page_accumulate
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/kcore.c (ffffffff814af6af)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/page.c (ffffffff814b1532)
Location: include/linux/page-flags.h:270
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
  - fs/proc/page.c:kpagecount_read
```
```
In fs/ext4/inline.c (ffffffff814dda11)
Location: include/linux/page-flags.h:270
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
In fs/ext4/inode.c (ffffffff814ec0a4)
Location: include/linux/page-flags.h:270
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
In fs/ext4/mballoc.c (ffffffff814f5410)
Location: include/linux/page-flags.h:270
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
In fs/ext4/move_extent.c (ffffffff814fea88)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81509338)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff8150a127)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
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
In fs/ext4/verity.c (ffffffff8153c5cc)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/commit.c (ffffffff81540322)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/squashfs/file.c (ffffffff8154eab0)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81e82235)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/file_direct.c (ffffffff815511be)
Location: include/linux/page-flags.h:270
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
In fs/hugetlbfs/inode.c (ffffffff81555d80)
Location: include/linux/page-flags.h:270
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
In fs/ecryptfs/mmap.c (ffffffff8156955e)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff815698ec)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81577115)
Location: include/linux/page-flags.h:270
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
In fs/fuse/file.c (ffffffff8157f178)
Location: include/linux/page-flags.h:270
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
In fs/fuse/readdir.c (ffffffff8158944a)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/selinux/selinuxfs.c (ffffffff815cf00f)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In security/tomoyo/domain.c (ffffffff816009be)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/fops.c (ffffffff81670462)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
```
```
In block/bio.c (ffffffff81673f81)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_release_pages
  - block/bio.c:__bio_add_page
```
```
In block/blk-map.c (ffffffff8167f093)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In block/partitions/core.c (ffffffff81695e7e)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
  - block/partitions/core.c:read_part_sector
```
```
In block/partitions/amiga.c (ffffffff816960d1)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff81696c07)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8169724c)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:read_lba
```
```
In block/partitions/mac.c (ffffffff8169845a)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8169a632)
Location: include/linux/page-flags.h:270
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
In block/partitions/msdos.c (ffffffff8169bb93)
Location: include/linux/page-flags.h:270
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
In block/partitions/osf.c (ffffffff8169c57a)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff8169c8ff)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff8169cbf4)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff8169cfbb)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8169d3c3)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff8169e3a2)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8169e6f5)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In io_uring/io_uring.c (ffffffff816cd235)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_buffer_account_pin
  - io_uring/io_uring.c:io_buffer_account_pin
  - io_uring/io_uring.c:io_buffer_account_pin
Direct callers:
  - io_uring/io_uring.c:virt_to_head_page
```
```
In lib/iov_iter.c (ffffffff816e2971)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:pipe_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:pipe_get_pages
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:page_copy_sane
```
```
In lib/buildid.c (ffffffff81776630)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8180f367)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c61a2)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff818c7ee2)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff819365ec)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff8193de6b)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff819f5d42)
Location: include/linux/page-flags.h:270
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
In drivers/scsi/sg.c (ffffffff81a19c4b)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/ata/libata-sff.c (ffffffff81a3b8d6)
Location: include/linux/page-flags.h:270
Inline: True
```
```
In drivers/net/tun.c (ffffffff81a63a3c)
Location: include/linux/page-flags.h:270
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
In drivers/net/xen-netfront.c (ffffffff81a72bb7)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/md/md.c (ffffffff81b5d5cb)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff81b6873c)
Location: include/linux/page-flags.h:270
Inline: True
```
```
In net/socket.c (ffffffff81be77e8)
Location: include/linux/page-flags.h:270
Inline: True
```
```
In net/core/sock.c (ffffffff81bed232)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81bfd1ce)
Location: include/linux/page-flags.h:270
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
In net/core/datagram.c (ffffffff81c00c9f)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81c44b4a)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81c5118e)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81c53946)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/page_pool.c (ffffffff81c5a5a5)
Location: include/linux/page-flags.h:270
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
In net/core/skmsg.c (ffffffff81c8c0fe)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81cdad4b)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ceed05)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_output.c (ffffffff81cfed3a)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5db50)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6d7a2)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81d7b310)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81d88fa6)
Location: include/linux/page-flags.h:270
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df6841)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81e15ff3)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff81e22baf)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:dfrag_clear
```
**Symbols:**

```
ffffffff81336bf0-ffffffff81336c52: _compound_head (STB_LOCAL)
ffffffff8133cc20-ffffffff8133cc82: _compound_head (STB_LOCAL)
ffffffff81e71380-ffffffff81e713c7: _compound_head (STB_LOCAL)
ffffffff813b8a90-ffffffff813b8af2: _compound_head (STB_LOCAL)
ffffffff813c27d0-ffffffff813c2832: _compound_head (STB_LOCAL)
ffffffff813d89c0-ffffffff813d8a22: _compound_head (STB_LOCAL)
ffffffff81568a70-ffffffff81568ad2: _compound_head (STB_LOCAL)
ffffffff816c5dc0-ffffffff816c5e22: _compound_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int _compound_head(const struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff83e62318)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81004885)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108f0fc)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810918e5)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/exit.c (ffffffff810f1c0b)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/resource.c (ffffffff810f4fba)
Location: include/linux/page-flags.h:249
Inline: True
```
```
In kernel/power/swap.c (ffffffff8118888c)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex/core.c (ffffffff811f35af)
Location: include/linux/page-flags.h:249
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
```
```
In kernel/relay.c (ffffffff8124bbc6)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff81339173)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff813502d1)
Location: include/linux/page-flags.h:249
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
In kernel/watch_queue.c (ffffffff81357317)
Location: include/linux/page-flags.h:249
Inline: True
```
```
In mm/filemap.c (ffffffff8135cbc5)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:page_endio
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff813668f4)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/folio-compat.c (ffffffff8136ba45)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/folio-compat.c:putback_lru_page
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
In mm/readahead.c (ffffffff8136c186)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
```
```
In mm/swap.c (ffffffff8136f527)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/truncate.c (ffffffff81371fd6)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:generic_error_remove_page
```
```
In mm/vmscan.c (ffffffff8137ebda)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:get_pfn_folio
```
```
In mm/shmem.c (ffffffff8138ccbb)
Location: include/linux/page-flags.h:249
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
In mm/util.c (ffffffff81391995)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/util.c:page_rmapping
```
```
In mm/slab_common.c (ffffffff813a23e2)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/slab_common.c:__ksize
  - mm/slab_common.c:kfree
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/compaction.c (ffffffff813a7f80)
Location: include/linux/page-flags.h:249
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
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff813adb55)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff813b2d09)
Location: include/linux/page-flags.h:249
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
In mm/memory.c (ffffffff813c058d)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:insert_pages
  - mm/memory.c:insert_pages
  - mm/memory.c:insert_pages
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:do_fault
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mlock.c (ffffffff813c5297)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:munlock_page
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
```
```
In mm/mmap.c (ffffffff813c5d5c)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/mprotect.c (ffffffff813ce0a6)
Location: include/linux/page-flags.h:249
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
In mm/page_vma_mapped.c (ffffffff813d329d)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
```
```
In mm/rmap.c (ffffffff813db008)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:make_device_exclusive_range
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
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_move_anon_rmap
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/vmalloc.c (ffffffff813e295c)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vunmap
```
```
In mm/page_alloc.c (ffffffff813f009a)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_compound_page
```
```
In mm/memory_hotplug.c (ffffffff820c39bf)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff813f3845)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
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
In mm/page_io.c (ffffffff813f7ef6)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:sio_write_complete
  - mm/page_io.c:swap_writepage
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
  - mm/page_io.c:end_swap_bio_write
```
```
In mm/swap_state.c (ffffffff813f98c8)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff813fc87f)
Location: include/linux/page-flags.h:249
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
In mm/zswap.c (ffffffff8140369f)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81412f97)
Location: include/linux/page-flags.h:249
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
  - mm/hugetlb.c:PageHuge
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:__update_and_free_page
Direct callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/mempolicy.c (ffffffff81418909)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff820cb479)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81422d1b)
Location: include/linux/page-flags.h:249
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
In mm/slub.c (ffffffff8142c3ee)
Location: include/linux/page-flags.h:249
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
In mm/kfence/core.c (ffffffff8142f4bf)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:kfence_init
```
```
In mm/migrate.c (ffffffff81435f0c)
Location: include/linux/page-flags.h:249
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
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8143a429)
Location: include/linux/page-flags.h:249
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
In mm/huge_memory.c (ffffffff81443f70)
Location: include/linux/page-flags.h:249
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
Direct callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8144aae8)
Location: include/linux/page-flags.h:249
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
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
Direct callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/memcontrol.c (ffffffff8145880a)
Location: include/linux/page-flags.h:249
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
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hugetlb_cgroup.c (ffffffff8145de05)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff8146411d)
Location: include/linux/page-flags.h:249
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
  - mm/memory-failure.c:page_handle_poison
Direct callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In mm/page_isolation.c (ffffffff814657ef)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
```
```
In mm/zsmalloc.c (ffffffff8146937d)
Location: include/linux/page-flags.h:249
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
In mm/balloon_compaction.c (ffffffff8146ab96)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/secretmem.c (ffffffff8146b4ab)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff8146d5e6)
Location: include/linux/page-flags.h:249
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
In mm/page_idle.c (ffffffff8146e27d)
Location: include/linux/page-flags.h:249
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
In mm/usercopy.c (ffffffff8146e859)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In mm/memremap.c (ffffffff8146f856)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:free_zone_device_page
  - mm/memremap.c:free_zone_device_page
```
```
In mm/hmm.c (0)
Location: include/linux/page-flags.h:249
Inline: True
```
```
In mm/memfd.c (ffffffff81471647)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/exec.c (ffffffff81485323)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff81488060)
Location: include/linux/page-flags.h:249
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
In fs/namei.c (ffffffff8148a865)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff814b9ff5)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff814c5eb4)
Location: include/linux/page-flags.h:249
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
In fs/buffer.c (ffffffff814d5980)
Location: include/linux/page-flags.h:249
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
```
```
In fs/direct-io.c (ffffffff814d8e73)
Location: include/linux/page-flags.h:249
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
In fs/mpage.c (ffffffff814da63a)
Location: include/linux/page-flags.h:249
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
In fs/aio.c (ffffffff814f280a)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/crypto/crypto.c (ffffffff814fc0a1)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/verity/enable.c (ffffffff81503dcd)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff815062b7)
Location: include/linux/page-flags.h:249
Inline: True
```
```
In fs/verity/verify.c (ffffffff81506759)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/coredump.c (ffffffff8151990b)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/iomap/buffered-io.c (ffffffff8151de65)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/iomap/direct-io.c (ffffffff8151ff47)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/proc/task_mmu.c (ffffffff8152d8ec)
Location: include/linux/page-flags.h:249
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
In fs/proc/kcore.c (ffffffff81545fb5)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/page.c (ffffffff81548118)
Location: include/linux/page-flags.h:249
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
  - fs/proc/page.c:kpagecount_read
  - fs/proc/page.c:kpagecount_read
```
```
In fs/ext4/inline.c (ffffffff81576a56)
Location: include/linux/page-flags.h:249
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
In fs/ext4/inode.c (ffffffff81585e0e)
Location: include/linux/page-flags.h:249
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
```
```
In fs/ext4/mballoc.c (ffffffff81590e30)
Location: include/linux/page-flags.h:249
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
In fs/ext4/move_extent.c (ffffffff815992d8)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff815a3f15)
Location: include/linux/page-flags.h:249
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
In fs/ext4/readpage.c (ffffffff815a4c4c)
Location: include/linux/page-flags.h:249
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
In fs/ext4/verity.c (ffffffff815dad25)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/commit.c (ffffffff815deea2)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/squashfs/file.c (ffffffff815eedd5)
Location: include/linux/page-flags.h:249
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
In fs/squashfs/symlink.c (ffffffff815f1b36)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/file_direct.c (ffffffff815f231e)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff815f7478)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8160d13e)
Location: include/linux/page-flags.h:249
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
In fs/ecryptfs/read_write.c (ffffffff8160d51d)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8161b7f5)
Location: include/linux/page-flags.h:249
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
In fs/fuse/file.c (ffffffff81624e45)
Location: include/linux/page-flags.h:249
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
In fs/fuse/readdir.c (ffffffff8162f6d2)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/selinux/selinuxfs.c (ffffffff8167cb7c)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In security/tomoyo/domain.c (ffffffff816b1925)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/fops.c (ffffffff8172b802)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
```
```
In block/bio.c (ffffffff8172fbf1)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_release_pages
```
```
In block/blk-map.c (ffffffff8173c191)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In io_uring/io_uring.c (ffffffff81789c01)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_mmap
```
```
In io_uring/rsrc.c (ffffffff817a0925)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_account_pin
  - io_uring/rsrc.c:io_buffer_account_pin
  - io_uring/rsrc.c:io_buffer_account_pin
```
```
In lib/iov_iter.c (ffffffff817d2c7a)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:pipe_get_pages
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:page_copy_sane
```
```
In drivers/pci/p2pdma.c (ffffffff8191beda)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8193e107)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a16ad2)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81a194a2)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81a9642c)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff81a9f2cb)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81b73306)
Location: include/linux/page-flags.h:249
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
In drivers/scsi/sg.c (ffffffff81b9ad3b)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/ata/libata-sff.c (ffffffff81bc0f56)
Location: include/linux/page-flags.h:249
Inline: True
```
```
In drivers/net/tun.c (ffffffff81bf2c1c)
Location: include/linux/page-flags.h:249
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
In drivers/net/xen-netfront.c (ffffffff81c05337)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/md/md.c (ffffffff81cf751f)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff81d041dc)
Location: include/linux/page-flags.h:249
Inline: True
```
```
In net/socket.c (ffffffff81d93ff8)
Location: include/linux/page-flags.h:249
Inline: True
```
```
In net/core/sock.c (ffffffff81d994f2)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81dac142)
Location: include/linux/page-flags.h:249
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
In net/core/datagram.c (ffffffff81db0142)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81dff10a)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81e06969)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81e090fa)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/page_pool.c (ffffffff81e10085)
Location: include/linux/page-flags.h:249
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
In net/core/skmsg.c (ffffffff81e47350)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81e9b56d)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81eb1f81)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_output.c (ffffffff81ec3b86)
Location: include/linux/page-flags.h:249
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f27800)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff81f38d72)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81f4837f)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81f56dce)
Location: include/linux/page-flags.h:249
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fcae00)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81fed040)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff81ffb8d9)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:dfrag_clear
```
```
In lib/buildid.c (ffffffff8201f07d)
Location: include/linux/page-flags.h:249
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
**Symbols:**

```
ffffffff813b4910-ffffffff813b4949: _compound_head (STB_LOCAL)
ffffffff81405490-ffffffff814054c9: _compound_head (STB_LOCAL)
ffffffff8143ac30-ffffffff8143ac69: _compound_head (STB_LOCAL)
ffffffff81444b90-ffffffff81444bc9: _compound_head (STB_LOCAL)
ffffffff8144d920-ffffffff8144d959: _compound_head (STB_LOCAL)
ffffffff8145e580-ffffffff8145e5b9: _compound_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int _compound_head(const struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff83682825)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - init/do_mounts.c:mount_root_generic
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81004045)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81091ffc)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81094822)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/exit.c (ffffffff810fdb8e)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/resource.c (ffffffff811013ea)
Location: include/linux/page-flags.h:243
Inline: True
```
```
In kernel/power/swap.c (ffffffff81199a4c)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex/core.c (ffffffff81207d65)
Location: include/linux/page-flags.h:243
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
```
```
In kernel/relay.c (ffffffff81262e36)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff8136a78f)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff813814b6)
Location: include/linux/page-flags.h:243
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
In kernel/watch_queue.c (ffffffff81388b92)
Location: include/linux/page-flags.h:243
Inline: True
```
```
In mm/filemap.c (ffffffff8138ebf8)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff81398f64)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
```
```
In mm/folio-compat.c (ffffffff8139dc95)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/folio-compat.c:putback_lru_page
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
In mm/swap.c (ffffffff813a1647)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/truncate.c (ffffffff813a4176)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_inode_page
  - mm/truncate.c:generic_error_remove_page
```
```
In mm/vmscan.c (ffffffff813b7683)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:get_pfn_folio
```
```
In mm/shmem.c (ffffffff813be529)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_swapin
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
```
```
In mm/util.c (ffffffff813c4375)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/util.c:page_rmapping
```
```
In mm/slab_common.c (ffffffff813d58cf)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/slab_common.c:__ksize
  - mm/slab_common.c:kfree
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/compaction.c (ffffffff813dacb9)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff813e1ee5)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff813e797a)
Location: include/linux/page-flags.h:243
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
In mm/memory.c (ffffffff813f52e3)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:vm_normal_folio
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
  - mm/memory.c:pfn_swap_entry_to_page
```
```
In mm/mlock.c (ffffffff813f9774)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mmap.c (ffffffff813fa1ac)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/mprotect.c (ffffffff81402945)
Location: include/linux/page-flags.h:243
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
In mm/page_vma_mapped.c (ffffffff81407162)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:vma_address
```
```
In mm/rmap.c (ffffffff8140f665)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
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
```
```
In mm/vmalloc.c (ffffffff8141752e)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vfree
```
```
In mm/page_alloc.c (ffffffff81423c17)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_tail_page_prepare
  - mm/page_alloc.c:free_compound_page
```
```
In mm/memory_hotplug.c (ffffffff8214795d)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/madvise.c (ffffffff814293b4)
Location: include/linux/page-flags.h:243
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
In mm/page_io.c (ffffffff8142afe6)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:swap_writepage_fs
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
In mm/swap_state.c (ffffffff8142c841)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff8142fc88)
Location: include/linux/page-flags.h:243
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
In mm/frontswap.c (ffffffff81434ad4)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
```
```
In mm/zswap.c (ffffffff814375b9)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81440ccf)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
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
Direct callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/mempolicy.c (ffffffff814494ea)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_folio_add
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff8214f70b)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff814584a5)
Location: include/linux/page-flags.h:243
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
In mm/slub.c (ffffffff8146199e)
Location: include/linux/page-flags.h:243
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
In mm/kfence/core.c (ffffffff81464f19)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/migrate.c (ffffffff8146bd15)
Location: include/linux/page-flags.h:243
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
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
```
```
In mm/migrate_device.c (ffffffff8146fd79)
Location: include/linux/page-flags.h:243
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
In mm/huge_memory.c (ffffffff814794f2)
Location: include/linux/page-flags.h:243
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
  - mm/huge_memory.c:split_huge_page_to_list
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
  - mm/huge_memory.c:can_change_pmd_writable
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81480cef)
Location: include/linux/page-flags.h:243
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
Direct callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/memcontrol.c (ffffffff8148e3d7)
Location: include/linux/page-flags.h:243
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
Direct callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hugetlb_cgroup.c (ffffffff81492c21)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff81499bd0)
Location: include/linux/page-flags.h:243
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
  - mm/memory-failure.c:__add_to_kill
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/page_isolation.c (ffffffff8149b1e4)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
```
```
In mm/zsmalloc.c (ffffffff8149e30c)
Location: include/linux/page-flags.h:243
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
In mm/balloon_compaction.c (ffffffff8149fa26)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/secretmem.c (ffffffff814a028d)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff814a0b33)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/page_idle.c (ffffffff814a2ab1)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_folio
  - mm/page_idle.c:page_idle_get_folio
```
```
In mm/usercopy.c (ffffffff814a2fee)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In mm/memremap.c (ffffffff814a4036)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:free_zone_device_page
  - mm/memremap.c:free_zone_device_page
```
```
In mm/hmm.c (0)
Location: include/linux/page-flags.h:243
Inline: True
```
```
In mm/memfd.c (ffffffff814a5b84)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/exec.c (ffffffff814ba391)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff814bcf4d)
Location: include/linux/page-flags.h:243
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
In fs/namei.c (ffffffff814c0a35)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff814eef65)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/fs-writeback.c (ffffffff814f4d57)
Location: include/linux/page-flags.h:243
Inline: True
```
```
In fs/splice.c (ffffffff814fb394)
Location: include/linux/page-flags.h:243
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
In fs/buffer.c (ffffffff8150b7c5)
Location: include/linux/page-flags.h:243
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
In fs/mpage.c (ffffffff8150f1a1)
Location: include/linux/page-flags.h:243
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
In fs/direct-io.c (ffffffff81510275)
Location: include/linux/page-flags.h:243
Inline: True
```
```
In fs/aio.c (ffffffff8152942d)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/crypto/crypto.c (ffffffff81533303)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/crypto/bio.c (ffffffff8153a5cf)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/read_metadata.c (ffffffff8153d5ed)
Location: include/linux/page-flags.h:243
Inline: True
```
```
In fs/verity/verify.c (ffffffff8153e630)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
```
```
In fs/coredump.c (ffffffff815511ff)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/iomap/buffered-io.c (ffffffff81554564)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/proc/task_mmu.c (ffffffff81565d1c)
Location: include/linux/page-flags.h:243
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
In fs/proc/kcore.c (ffffffff8157d927)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore_iter
```
```
In fs/proc/page.c (ffffffff8157fceb)
Location: include/linux/page-flags.h:243
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
  - fs/proc/page.c:kpagecount_read
  - fs/proc/page.c:kpagecount_read
```
```
In fs/ext4/inode.c (ffffffff815bc55f)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/mballoc.c (ffffffff815c2193)
Location: include/linux/page-flags.h:243
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
In fs/ext4/page-io.c (ffffffff815dad32)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff815db03a)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/block.c (ffffffff81624181)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In fs/squashfs/file.c (ffffffff81626dc1)
Location: include/linux/page-flags.h:243
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
In fs/squashfs/symlink.c (ffffffff81629c26)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/file_direct.c (ffffffff8162a40e)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff8162fae2)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff81644ffe)
Location: include/linux/page-flags.h:243
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
In fs/ecryptfs/read_write.c (ffffffff816453dc)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81653965)
Location: include/linux/page-flags.h:243
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
In fs/fuse/file.c (ffffffff8165d1cb)
Location: include/linux/page-flags.h:243
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
In fs/fuse/readdir.c (ffffffff81667945)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/selinux/selinuxfs.c (ffffffff816b4e4f)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In security/tomoyo/domain.c (ffffffff816ea328)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/fops.c (ffffffff81767682)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
```
```
In block/bio.c (ffffffff8176be1f)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
```
```
In io_uring/io_uring.c (ffffffff817c99fc)
Location: include/linux/page-flags.h:243
Inline: True
```
```
In io_uring/kbuf.c (ffffffff817e0107)
Location: include/linux/page-flags.h:243
Inline: True
```
```
In io_uring/rsrc.c (ffffffff817e35ba)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_buffer_account_pin
  - io_uring/rsrc.c:io_buffer_account_pin
  - io_uring/rsrc.c:io_buffer_account_pin
```
```
In lib/iov_iter.c (ffffffff81813680)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_to_iter_nofault
```
```
In drivers/pci/p2pdma.c (ffffffff8195f4ed)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81982607)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5fb62)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81a623c2)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81ae1c3c)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff81aeac2b)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81bc6d60)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff81bf11fb)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/ata/libata-sff.c (ffffffff81c18b05)
Location: include/linux/page-flags.h:243
Inline: True
```
```
In drivers/net/tun.c (ffffffff81c4a1c8)
Location: include/linux/page-flags.h:243
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
In drivers/net/virtio_net.c (ffffffff81c541be)
Location: include/linux/page-flags.h:243
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
In drivers/net/xen-netfront.c (ffffffff81c6aa47)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/md/md.c (ffffffff81d5ee1b)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff81d6cf6c)
Location: include/linux/page-flags.h:243
Inline: True
```
```
In net/core/sock.c (ffffffff81e07812)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81e14b5c)
Location: include/linux/page-flags.h:243
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
In net/core/datagram.c (ffffffff81e2045e)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81e70bda)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81e79604)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81e7b765)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/page_pool.c (ffffffff81e838e5)
Location: include/linux/page-flags.h:243
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
In net/core/skmsg.c (ffffffff81ea2db8)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81efa136)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81f1062f)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81f25477)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f86173)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff81f98a5e)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81fa7f30)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff81fb682f)
Location: include/linux/page-flags.h:243
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202c083)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff8206adcc)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff82077c5f)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:dfrag_clear
```
```
In lib/buildid.c (ffffffff8209f090)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
**Symbols:**

```
ffffffff813e9530-ffffffff813e9569: _compound_head (STB_LOCAL)
ffffffff814389b0-ffffffff814389e9: _compound_head (STB_LOCAL)
ffffffff81470580-ffffffff814705b9: _compound_head (STB_LOCAL)
ffffffff8147a1c0-ffffffff8147a1f9: _compound_head (STB_LOCAL)
ffffffff81483240-ffffffff81483279: _compound_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int _compound_head(const struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff838b18c5)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - init/do_mounts.c:mount_root_generic
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81006951)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109936c)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109bd02)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/fork.c (ffffffff810f9b07)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (ffffffff81106941)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/resource.c (ffffffff8110ab1a)
Location: include/linux/page-flags.h:245
Inline: True
```
```
In kernel/power/swap.c (ffffffff811a8aac)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex/core.c (ffffffff8121ee8a)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/relay.c (ffffffff8127d056)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff8139311f)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff813aa865)
Location: include/linux/page-flags.h:245
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
In kernel/watch_queue.c (ffffffff813b25f2)
Location: include/linux/page-flags.h:245
Inline: True
```
```
In mm/filemap.c (ffffffff813b7fe8)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff813c2d64)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
```
```
In mm/folio-compat.c (ffffffff813c7975)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/folio-compat.c:putback_lru_page
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
In mm/swap.c (ffffffff813cb2c7)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/truncate.c (ffffffff813cdcc6)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:pagecache_isize_extended
```
```
In mm/vmscan.c (ffffffff813e051b)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:get_pfn_folio
```
```
In mm/shmem.c (ffffffff813e9217)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
```
```
In mm/slab_common.c (ffffffff813ff582)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/slab_common.c:__ksize
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/compaction.c (ffffffff81404bb3)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff8140c715)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff814125ea)
Location: include/linux/page-flags.h:245
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
In mm/memory.c (ffffffff814158f5)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:vm_normal_folio_pmd
Direct callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_read_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:set_pte_range
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
  - mm/memory.c:pfn_swap_entry_to_page
```
```
In mm/mlock.c (ffffffff81425421)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mmap.c (ffffffff81425f6c)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/mmu_gather.c (ffffffff8142dd70)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_rmap_batch
```
```
In mm/mprotect.c (ffffffff8142f4c3)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/page_vma_mapped.c (ffffffff814337ed)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:vma_address
```
```
In mm/rmap.c (ffffffff814382d4)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
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
```
```
In mm/vmalloc.c (ffffffff8144403e)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff81450b54)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_tail_page_prepare
```
```
In mm/memory_hotplug.c (ffffffff82229fdd)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/slub.c (ffffffff8145dcd2)
Location: include/linux/page-flags.h:245
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
In mm/madvise.c (ffffffff81462be4)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff814644f8)
Location: include/linux/page-flags.h:245
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
In mm/swap_state.c (ffffffff8146564e)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff81468ce5)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_index
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8147adff)
Location: include/linux/page-flags.h:245
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
Direct callers:
  - mm/hugetlb.c:hugetlb_follow_page_mask
```
```
In mm/mempolicy.c (ffffffff81486ff4)
Location: include/linux/page-flags.h:245
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
In mm/sparse-vmemmap.c (ffffffff822325d6)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81492c15)
Location: include/linux/page-flags.h:245
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
In mm/kfence/core.c (ffffffff81493b60)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/migrate.c (ffffffff8149acc8)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
```
```
In mm/migrate_device.c (ffffffff8149eff6)
Location: include/linux/page-flags.h:245
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
In mm/huge_memory.c (ffffffff814a8995)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_pid
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
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:can_change_pmd_writable
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814aecc9)
Location: include/linux/page-flags.h:245
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
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_pages
```
```
In mm/memcontrol.c (ffffffff814bdc44)
Location: include/linux/page-flags.h:245
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
Direct callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hugetlb_cgroup.c (ffffffff814c2337)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff814c93c0)
Location: include/linux/page-flags.h:245
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
  - mm/memory-failure.c:__add_to_kill
  - mm/memory-failure.c:page_handle_poison
Direct callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In mm/page_isolation.c (ffffffff814ca8c4)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
```
```
In mm/zsmalloc.c (ffffffff814cd43e)
Location: include/linux/page-flags.h:245
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
In mm/balloon_compaction.c (ffffffff814cf176)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/userfaultfd.c (ffffffff814d334e)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - mm/userfaultfd.c:mfill_atomic_install_pte
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/page_idle.c (ffffffff814d3941)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_folio
  - mm/page_idle.c:page_idle_get_folio
```
```
In mm/usercopy.c (ffffffff814d3e82)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In mm/memremap.c (ffffffff814d4ee6)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:free_zone_device_page
  - mm/memremap.c:free_zone_device_page
```
```
In mm/hmm.c (0)
Location: include/linux/page-flags.h:245
Inline: True
```
```
In mm/memfd.c (ffffffff814d6b31)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/exec.c (ffffffff814ec911)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff814ef3ed)
Location: include/linux/page-flags.h:245
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
In fs/namei.c (ffffffff814f3085)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81522bda)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (ffffffff81529467)
Location: include/linux/page-flags.h:245
Inline: True
```
```
In fs/splice.c (ffffffff81530086)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_release
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/buffer.c (ffffffff81541f49)
Location: include/linux/page-flags.h:245
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
In fs/mpage.c (ffffffff81542e44)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - fs/mpage.c:bio_first_folio
```
```
In fs/direct-io.c (ffffffff81544725)
Location: include/linux/page-flags.h:245
Inline: True
```
```
In fs/aio.c (ffffffff8155e301)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/crypto/crypto.c (ffffffff815681fb)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/crypto/bio.c (ffffffff8156f084)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - fs/crypto/bio.c:bio_first_folio
```
```
In fs/verity/read_metadata.c (ffffffff81572a4d)
Location: include/linux/page-flags.h:245
Inline: True
```
```
In fs/verity/verify.c (ffffffff81573c9f)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
```
```
In fs/coredump.c (ffffffff815870e3)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/iomap/buffered-io.c (ffffffff8158a73a)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/proc/task_mmu.c (ffffffff8159dcf9)
Location: include/linux/page-flags.h:245
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
In fs/proc/kcore.c (ffffffff815b636f)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore_iter
```
```
In fs/proc/page.c (ffffffff815b86e3)
Location: include/linux/page-flags.h:245
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
  - fs/proc/page.c:kpagecount_read
  - fs/proc/page.c:kpagecount_read
```
```
In fs/ext4/inode.c (ffffffff815f533f)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/mballoc.c (ffffffff81601cbb)
Location: include/linux/page-flags.h:245
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
In fs/ext4/page-io.c (ffffffff81613572)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81613ac7)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/jbd2/journal.c (ffffffff8165c9c8)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/block.c (ffffffff8165d221)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In fs/squashfs/file.c (ffffffff8165ff22)
Location: include/linux/page-flags.h:245
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
In fs/squashfs/symlink.c (ffffffff81662e76)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/file_direct.c (ffffffff81663738)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff8167e52e)
Location: include/linux/page-flags.h:245
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
In fs/ecryptfs/read_write.c (ffffffff8167e8fd)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8168cf75)
Location: include/linux/page-flags.h:245
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
In fs/fuse/file.c (ffffffff81696f2b)
Location: include/linux/page-flags.h:245
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
In fs/fuse/readdir.c (ffffffff816a1c89)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/selinux/selinuxfs.c (ffffffff816f19af)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In security/tomoyo/domain.c (ffffffff81727038)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/fops.c (ffffffff817a9472)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
```
```
In block/bio.c (ffffffff817aaba4)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - block/bio.c:bio_first_folio
```
```
In block/bio-integrity.c (ffffffff817f9516)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_map_user
  - block/bio-integrity.c:bio_integrity_map_user
```
```
In io_uring/io_uring.c (ffffffff8180f593)
Location: include/linux/page-flags.h:245
Inline: True
```
```
In io_uring/rsrc.c (ffffffff81827661)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_sqe_buffer_register
  - io_uring/rsrc.c:io_buffer_account_pin
  - io_uring/rsrc.c:io_buffer_account_pin
  - io_uring/rsrc.c:io_buffer_account_pin
```
```
In lib/iov_iter.c (ffffffff81859227)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_to_iter_nofault
```
```
In drivers/pci/p2pdma.c (ffffffff819a8b4d)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819c9d87)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab2372)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81ab4bee)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/xen/grant-table.c:gnttab_add_deferred
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81b3502c)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff81b3e10b)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81c1b8cf)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff81c46abb)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/ata/libata-sff.c (ffffffff81c6d855)
Location: include/linux/page-flags.h:245
Inline: True
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9c27d)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_put_pages
  - drivers/gpu/drm/drm_gem.c:drm_gem_get_pages
```
```
In drivers/net/tun.c (ffffffff81cffb54)
Location: include/linux/page-flags.h:245
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
In drivers/net/virtio_net.c (ffffffff81d078c2)
Location: include/linux/page-flags.h:245
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
In drivers/net/xen-netfront.c (ffffffff81d1f427)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/md/md.c (ffffffff81e1608b)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff81e24197)
Location: include/linux/page-flags.h:245
Inline: True
```
```
In net/core/sock.c (ffffffff81ec4252)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81ed215c)
Location: include/linux/page-flags.h:245
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
In net/core/datagram.c (ffffffff81ede33b)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:__zerocopy_sg_from_iter
```
```
In net/core/filter.c (ffffffff81f302b1)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81f3969e)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81f3b9f5)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/page_pool.c (ffffffff81f43b3f)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_return_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
```
```
In net/core/skmsg.c (ffffffff81f650e8)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81fbe064)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81fd481e)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81fe9d38)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204d753)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff82065dce)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff820751f0)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/ipv6/ip6_output.c (ffffffff8208411a)
Location: include/linux/page-flags.h:245
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820fbb33)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff8213e80c)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff8214cda3)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:dfrag_clear
```
```
In lib/buildid.c (ffffffff82177090)
Location: include/linux/page-flags.h:245
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
**Symbols:**

```
ffffffff81414370-ffffffff814143a6: _compound_head (STB_LOCAL)
ffffffff81472340-ffffffff81472376: _compound_head (STB_LOCAL)
ffffffff8149f940-ffffffff8149f976: _compound_head (STB_LOCAL)
ffffffff814b25f0-ffffffff814b2626: _compound_head (STB_LOCAL)
ffffffff814c3c00-ffffffff814c3c36: _compound_head (STB_LOCAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
