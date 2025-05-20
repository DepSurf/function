# Function: <code>folio_flags</code>

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
In kernel/futex/core.c (ffffffff811b2724)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff812e5f52)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812f4060)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:page_endio
  - mm/filemap.c:folio_wait_private_2_killable
  - mm/filemap.c:folio_wait_private_2
  - mm/filemap.c:folio_add_wait_queue
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wake_bit
  - mm/filemap.c:filemap_add_folio
```
```
In mm/page-writeback.c (ffffffff812fd991)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:folio_mark_dirty
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (0)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In mm/swap.c (ffffffff81303225)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff8130762c)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8130f1a2)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8131b2e8)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (0)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In mm/compaction.c (ffffffff813312cf)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (0)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In mm/gup.c (ffffffff8133825e)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In mm/memory.c (ffffffff813439e5)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mincore.c (0)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In mm/mlock.c (ffffffff8134c06f)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/mlock.c:mlock_folio
```
```
In mm/mprotect.c (0)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In mm/rmap.c (ffffffff8135bfb7)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:folio_referenced
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In mm/madvise.c (ffffffff8137691c)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff8137a5ee)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/swap_state.c (ffffffff8137b731)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In mm/swapfile.c (ffffffff81381496)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/swap_slots.c (0)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In mm/zswap.c (ffffffff81385b5a)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8138df84)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (0)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In mm/ksm.c (ffffffff813a2454)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff813a633b)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:print_slab_info
```
```
In mm/kfence/core.c (ffffffff8349276a)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init
```
```
In mm/migrate.c (ffffffff813b5240)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:writeout
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff813b6f26)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c07c5)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813c518a)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (0)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In mm/memory-failure.c (ffffffff813da0b0)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
```
In mm/zsmalloc.c (ffffffff813e2887)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff813e3227)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/secretmem.c (ffffffff813e3a58)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff813e45b6)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/page_idle.c (ffffffff813e6551)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
```
```
In mm/usercopy.c (0)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In fs/pipe.c (ffffffff813fe37a)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/namei.c (0)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In fs/libfs.c (ffffffff8142c829)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (0)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In fs/splice.c (ffffffff814389fa)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff81441e9f)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In fs/buffer.c (ffffffff81446c25)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_dirty_folio
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff8144ba98)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff81463582)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff814678ad)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/verity/enable.c (0)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In fs/verity/verify.c (0)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8148a879)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/proc/task_mmu.c (ffffffff8149ab6a)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/proc/page.c (0)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In fs/ext4/inline.c (ffffffff814dc25d)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff814ec0bf)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff814f3867)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff814fed9f)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff8150a60c)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ext4/verity.c (0)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff81540333)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/squashfs/file.c (ffffffff8154e64f)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (0)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In fs/squashfs/file_direct.c (ffffffff81551589)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff81555eb5)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff815696c0)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/ecryptfs/read_write.c (ffffffff81569a36)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff815771ae)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/dir.c (0)
Location: include/linux/page-flags.h:334
Inline: True
```
```
In fs/fuse/file.c (ffffffff8157f18b)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8180f3af)
Location: include/linux/page-flags.h:334
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/page-flags.h:334
Inline: True
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
In kernel/futex/core.c (ffffffff811f35c4)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In mm/filemap.c (ffffffff8135e351)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:page_endio
  - mm/filemap.c:folio_add_wait_queue
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:folio_wake_bit
  - mm/filemap.c:filemap_add_folio
```
```
In mm/page-writeback.c (ffffffff8136b151)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:folio_mark_dirty
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/folio-compat.c (0)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In mm/swap.c (ffffffff8137013d)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_batch_move_lru
  - mm/swap.c:lru_add_fn
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff8137174a)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8137e700)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:isolate_folio
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff8138dcb5)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (0)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In mm/compaction.c (ffffffff813a7f94)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff813ad749)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:lru_gen_refault
```
```
In mm/gup.c (ffffffff813afa27)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In mm/memory.c (ffffffff813bba6c)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mincore.c (0)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In mm/mlock.c (ffffffff813c4c2f)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/mlock.c:mlock_folio
```
```
In mm/mprotect.c (0)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In mm/rmap.c (ffffffff813d7527)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:folio_referenced
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In mm/madvise.c (ffffffff813f4279)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff813f8097)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/swap_state.c (ffffffff813f974a)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:swap_cache_get_folio
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff813ffcda)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:folio_free_swap
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/swap_slots.c (0)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In mm/zswap.c (ffffffff81403949)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8140cc38)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_add_to_page_cache
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__destroy_compound_gigantic_folio
```
```
In mm/mempolicy.c (0)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In mm/ksm.c (ffffffff814220b1)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff814256d4)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:slab_err
```
```
In mm/kfence/core.c (ffffffff83ec6403)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init
```
```
In mm/migrate.c (ffffffff81434801)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8143a43f)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8144316b)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814494f5)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff81455d56)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In mm/memory-failure.c (ffffffff8146184e)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
```
In mm/page_isolation.c (0)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In mm/zsmalloc.c (ffffffff81469de7)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff8146aba3)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/secretmem.c (ffffffff8146b435)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff8146c28c)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff8146e01e)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
```
```
In mm/usercopy.c (0)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In mm/memremap.c (ffffffff8146f864)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
```
```
In fs/pipe.c (ffffffff81487fea)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/namei.c (0)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In fs/libfs.c (ffffffff814ba099)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (0)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In fs/splice.c (ffffffff814c6ffa)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff814d097c)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In fs/buffer.c (ffffffff814d6f47)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_dirty_folio
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (0)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In fs/aio.c (ffffffff814f2672)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff814f7f6d)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/verity/enable.c (0)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In fs/verity/verify.c (0)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8151e126)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
```
```
In fs/proc/task_mmu.c (ffffffff8152f0a7)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/proc/page.c (0)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8157520d)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81585e29)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff8158de43)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff815995f9)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff815a5438)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ext4/verity.c (0)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff815deeea)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/squashfs/file.c (ffffffff815ef0b9)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (0)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In fs/squashfs/file_direct.c (ffffffff815f255e)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff815f75ad)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff8160d24e)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/ecryptfs/read_write.c (ffffffff8160d665)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8161b88e)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/dir.c (0)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In fs/fuse/file.c (ffffffff81624e58)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/readdir.c (ffffffff8162eeea)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In block/partitions/core.c (0)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/page-flags.h:313
Inline: True
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8193e14f)
Location: include/linux/page-flags.h:313
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/page-flags.h:313
Inline: True
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
In kernel/sched/fair.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In kernel/futex/core.c (ffffffff81207d7a)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In mm/filemap.c (ffffffff813910c4)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:folio_add_wait_queue
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:folio_wake_bit
  - mm/filemap.c:filemap_add_folio
```
```
In mm/page-writeback.c (ffffffff8139b983)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:folio_mark_dirty
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/folio-compat.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In mm/swap.c (ffffffff813a22bd)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_batch_move_lru
  - mm/swap.c:folio_batch_move_lru
  - mm/swap.c:lru_add_fn
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff813a385a)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff813afdea)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff813c23c9)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_get_partial_folio
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In mm/compaction.c (ffffffff813db573)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff813e1d66)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:lru_gen_refault
```
```
In mm/gup.c (ffffffff813e7031)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In mm/memory.c (ffffffff813f0358)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/memory.c:do_cow_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mincore.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In mm/mlock.c (ffffffff813f919f)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/mprotect.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In mm/rmap.c (ffffffff8140ba34)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:folio_referenced
```
```
In mm/page_alloc.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In mm/madvise.c (ffffffff814279d5)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff8142b0ce)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:__end_swap_bio_read
```
```
In mm/swap_state.c (ffffffff8142c4ec)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:swap_cache_get_folio
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff81432b7f)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:folio_free_swap
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/swap_slots.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In mm/zswap.c (ffffffff8143789a)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8144005b)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_add_to_page_cache
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__prep_compound_gigantic_folio
```
```
In mm/mempolicy.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In mm/ksm.c (ffffffff81456d9a)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff8145a96e)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:slab_err
```
```
In mm/kfence/core.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In mm/migrate.c (ffffffff8146a7e9)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8146fd8f)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81478107)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8147f6e6)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff81488f0f)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In mm/memory-failure.c (ffffffff8149706d)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:try_to_split_thp_page
```
```
In mm/page_isolation.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In mm/zsmalloc.c (ffffffff8149efe7)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff8149fa33)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/secretmem.c (ffffffff814a021b)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff814a1127)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/page_idle.c (ffffffff814a2894)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
```
```
In mm/usercopy.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In mm/memremap.c (ffffffff814a4044)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
```
```
In fs/pipe.c (ffffffff814bcee2)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/namei.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In fs/libfs.c (ffffffff814eef8d)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In fs/splice.c (ffffffff814fc438)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff8150707c)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In fs/buffer.c (ffffffff8150d3ba)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:block_dirty_folio
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff8150e055)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:mpage_read_end_io
```
```
In fs/aio.c (ffffffff815292a8)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff8152f16d)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/crypto/crypto.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In fs/crypto/bio.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In fs/verity/verify.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8155628c)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
```
```
In fs/proc/task_mmu.c (ffffffff8156735b)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/proc/page.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In fs/ext4/inode.c (ffffffff815bc6ff)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff815c465c)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff815cff2c)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff815db0cf)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/ext4/verity.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff81618111)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/block.c (ffffffff81623ff3)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read_cached
  - fs/squashfs/block.c:squashfs_bio_read_cached
```
```
In fs/squashfs/file.c (ffffffff81627099)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In fs/squashfs/file_direct.c (ffffffff8162a64d)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff8162ebe6)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff8164510e)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/ecryptfs/read_write.c (ffffffff81645524)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff816539f5)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/dir.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In fs/fuse/file.c (ffffffff8165d1de)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/readdir.c (ffffffff8166714d)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In block/partitions/core.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8198264f)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/page-flags.h:307
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
In arch/x86/mm/pgtable.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In kernel/futex/core.c (ffffffff8121ef0f)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In mm/filemap.c (ffffffff813bae64)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:folio_add_wait_queue
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:folio_wake_bit
  - mm/filemap.c:filemap_add_folio
```
```
In mm/page-writeback.c (ffffffff813c43f5)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:folio_mark_dirty
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/folio-compat.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In mm/swap.c (ffffffff813cbf3b)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_batch_move_lru
  - mm/swap.c:folio_batch_move_lru
  - mm/swap.c:lru_add_fn
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff813cd3bf)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff813d92d7)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff813ed14a)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_alloc_and_add_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_get_partial_folio
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In mm/compaction.c (ffffffff81404e32)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In mm/gup.c (ffffffff81411cb1)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In mm/memory.c (ffffffff8141af6e)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mincore.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In mm/mlock.c (ffffffff81424d4f)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/mprotect.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In mm/rmap.c (ffffffff814382f4)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:folio_referenced
```
```
In mm/page_alloc.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In mm/slub.c (ffffffff81459707)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:slab_err
```
```
In mm/madvise.c (ffffffff814611eb)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff814648bc)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/page_io.c:swap_read_folio
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:__end_swap_bio_read
```
```
In mm/swap_state.c (ffffffff81465c27)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:swap_cache_get_folio
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff8146bf9e)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:folio_free_swap
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/swap_slots.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In mm/hugetlb.c (ffffffff81479f69)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_add_to_page_cache
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__destroy_compound_gigantic_folio
```
```
In mm/mempolicy.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In mm/ksm.c (ffffffff8149189e)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/kfence/core.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In mm/migrate.c (ffffffff814997c9)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8149f00c)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a784e)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814adbba)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff814b8f75)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In mm/memory-failure.c (ffffffff814c6402)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:try_to_split_thp_page
  - mm/memory-failure.c:me_swapcache_dirty
```
```
In mm/page_isolation.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In mm/zsmalloc.c (ffffffff814ce747)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff814cf183)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/secretmem.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814d2c64)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/page_idle.c (ffffffff814d3731)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
```
```
In mm/usercopy.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In mm/memremap.c (ffffffff814d4ef4)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
```
```
In fs/pipe.c (ffffffff814ef37f)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/namei.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In fs/libfs.c (ffffffff81522c0b)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In fs/splice.c (ffffffff815301f9)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff8153c3a2)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In fs/buffer.c (ffffffff81541f6a)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:__block_commit_write
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:block_dirty_folio
```
```
In fs/mpage.c (ffffffff81542bd7)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:mpage_read_end_io
```
```
In fs/aio.c (ffffffff8155e178)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff8156404d)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/crypto/crypto.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In fs/crypto/bio.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In fs/verity/verify.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8158c75c)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/proc/task_mmu.c (ffffffff8159d8db)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In fs/proc/page.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In fs/ext4/inode.c (ffffffff815f54dc)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff815fc8ff)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff816087a9)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In fs/ext4/verity.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff81651048)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In fs/squashfs/block.c (ffffffff8165d093)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read_cached
  - fs/squashfs/block.c:squashfs_bio_read_cached
```
```
In fs/squashfs/file.c (ffffffff8166024c)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In fs/squashfs/file_direct.c (ffffffff81663971)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff816680ad)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff8167e63b)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/ecryptfs/read_write.c (ffffffff8167ea1d)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8168d002)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/dir.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In fs/fuse/file.c (ffffffff81696f3e)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/readdir.c (ffffffff816a149a)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In block/bio.c (ffffffff817abb00)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:__bio_release_pages
```
```
In block/partitions/core.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819c9dcf)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/gpu/drm/drm_gem.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/page-flags.h:309
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/page-flags.h:309
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
