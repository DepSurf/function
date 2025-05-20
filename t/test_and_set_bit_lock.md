# Function: <code>test_and_set_bit_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff810ffab7)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff8118776f)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8118daa6)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:filemap_fault
```
```
In mm/page-writeback.c (ffffffff81198b24)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff8119bc16)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In mm/swap.c (ffffffff8119d390)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/swap.c:__get_page_tail
```
```
In mm/truncate.c (ffffffff8119e900)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff811a0b41)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_active_list
```
```
In mm/shmem.c (ffffffff811a916c)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff811ba5f8)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811bbdfd)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:handle_mm_fault
```
```
In mm/mlock.c (ffffffff811c2f01)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/rmap.c (ffffffff811cc305)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/swap_state.c (ffffffff811d29a7)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:free_pages_and_swap_cache
```
```
In mm/swapfile.c (ffffffff811d4773)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:scan_swap_map
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff811dedad)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (ffffffff811e4b66)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff811e9b7d)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_create
```
```
In mm/migrate.c (ffffffff811f0eee)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff811f522e)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memcontrol.c (ffffffff811fd293)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81201d02)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/zsmalloc.c (ffffffff8120545c)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
```
```
In mm/balloon_compaction.c (ffffffff81207385)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_isolate
  - mm/balloon_compaction.c:balloon_page_putback
```
```
In mm/page_idle.c (ffffffff81208336)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In fs/pipe.c (ffffffff81214ab1)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff81223480)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/dcache.c:__d_drop
  - fs/dcache.c:__d_obtain_alias
```
```
In fs/splice.c (ffffffff8123e7a9)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:__generic_file_splice_read
```
```
In fs/buffer.c (ffffffff81243f4f)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
```
```
In fs/dax.c (ffffffff8125dcc7)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/dax.c:__dax_fault
```
```
In fs/mbcache.c (ffffffff8126cbdc)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
  - fs/mbcache.c:mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_insert
  - fs/mbcache.c:mb_cache_entry_insert
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_shrink_scan
  - fs/mbcache.c:mb_cache_shrink_scan
  - fs/mbcache.c:mb_cache_entry_alloc
  - fs/mbcache.c:mb_cache_entry_alloc
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/ext4/balloc.c (ffffffff8128fcd3)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/file.c (ffffffff81292488)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff81293520)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81296403)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/ext4/page-io.c (ffffffff8129f71f)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/super.c (ffffffff812b8ca5)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/resize.c (ffffffff812bef77)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/extents.c (ffffffff812c528e)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/mmp.c (ffffffff812d7954)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/indirect.c (ffffffff812d923d)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/xattr.c (ffffffff812dd0e9)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/ext4/inline.c (ffffffff812dfe6f)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/crypto.c (ffffffff812e5490)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_encrypt
```
```
In fs/jbd2/transaction.c (ffffffff812e8128)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
```
```
In fs/jbd2/commit.c (ffffffff812e9bde)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff812ec25b)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff812f1939)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
```
```
In fs/hugetlbfs/inode.c (ffffffff812f39a0)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff8130449d)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff81316215)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In block/blk-tag.c (ffffffff813bbece)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_start_tag
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81473589)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
```
```
In drivers/rtc/interface.c (ffffffff81673c50)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_register
```
```
In drivers/rtc/rtc-dev.c (ffffffff81675387)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8110771a)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81199d74)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811a142b)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
```
```
In mm/page-writeback.c (ffffffff811ad973)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff811b0d75)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In mm/truncate.c (ffffffff811b43c3)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811bacf9)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811c0adb)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff811d5197)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811d7037)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff811df06e)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff811e928c)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff811eecd7)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff811f019e)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff811f07a1)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff811f3ad3)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map
```
```
In mm/hugetlb.c (ffffffff811fd22d)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/mempolicy.c (ffffffff811fefb1)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81205069)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff8120c701)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff81211d97)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812180c7)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8121ad1d)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81220d80)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81227c1b)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff8122be72)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:trylock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In mm/balloon_compaction.c (ffffffff8122cef0)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In mm/page_idle.c (ffffffff8122dcca)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In fs/pipe.c (ffffffff8123b858)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff8124bb63)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_drop
```
```
In fs/splice.c (ffffffff81266ec7)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/splice.c:__generic_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8126dbab)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/dax.c (ffffffff81287ac3)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/dax.c:dax_fault
```
```
In fs/crypto/crypto.c (ffffffff81288d31)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
```
```
In fs/mbcache.c (ffffffff81298a78)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_block
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap.c (ffffffff8129c18c)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/balloc.c (ffffffff812bd203)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/file.c (ffffffff812bfa56)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff812c0ae1)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812cd94a)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/page-io.c (ffffffff812ce016)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/super.c (ffffffff812e7afd)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/resize.c (ffffffff812ee882)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/extents.c (ffffffff812f4b01)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/mmp.c (ffffffff813076b6)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/indirect.c (ffffffff81308ff6)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/xattr.c (ffffffff8130d4dc)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/inline.c (ffffffff8130fb20)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/jbd2/transaction.c (ffffffff81317238)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81317af8)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81319d6d)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81320a8f)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff81327d64)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff8133856c)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8134a164)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In block/blk-tag.c (ffffffff813ffcd7)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_start_tag
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814c1e4d)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/rtc/interface.c (ffffffff816d444b)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_register
```
```
In drivers/rtc/rtc-dev.c (ffffffff816d5c37)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8110eeda)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811a94d1)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811b1148)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In mm/page-writeback.c (ffffffff811bded3)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff811c1375)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
```
```
In mm/truncate.c (ffffffff811c4a63)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811cb389)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811d10c2)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff811e51b2)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811e9720)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff811eee87)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff811fa5dc)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff811ff607)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff81200b62)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8120118e)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81204606)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map
```
```
In mm/hugetlb.c (ffffffff8120dcfc)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/mempolicy.c (ffffffff812107f6)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81217025)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff8121e761)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff81224001)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff8122a667)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8122e664)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff812334d0)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8123a1b6)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff8123e3b5)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:trylock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In mm/balloon_compaction.c (ffffffff8123f410)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In mm/page_idle.c (ffffffff8124021a)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
```
```
In fs/read_write.c (ffffffff812445e2)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
```
```
In fs/pipe.c (ffffffff8124e5f8)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff8125eb43)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_drop
```
```
In fs/splice.c (ffffffff81278da4)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff81280dfb)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/dax.c (ffffffff8129bfde)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In fs/crypto/crypto.c (ffffffff8129d9ff)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
```
```
In fs/mbcache.c (ffffffff812ad4f6)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_block
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap.c (ffffffff812b1cbc)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/balloc.c (ffffffff812d2853)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/file.c (ffffffff812d4c66)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff812d6111)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812e371a)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/page-io.c (ffffffff812e3e06)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/super.c (ffffffff812fd83d)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/resize.c (ffffffff81304852)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/extents.c (ffffffff8130aab1)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/mmp.c (ffffffff8131d6a6)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/indirect.c (ffffffff8131f006)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/xattr.c (ffffffff813233d1)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/ext4/inline.c (ffffffff81325940)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/jbd2/transaction.c (ffffffff8132d228)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8132dae8)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff8132fd5d)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8133693f)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff8133dab2)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff8134e32c)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8135faa4)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In block/blk-tag.c (ffffffff81419584)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_start_tag
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814e3e3d)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/rtc/interface.c (ffffffff8170412b)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_register
```
```
In drivers/rtc/rtc-dev.c (ffffffff81705917)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111020b)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811b0a01)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811b8598)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In mm/page-writeback.c (ffffffff811c6083)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff811c9665)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
```
```
In mm/truncate.c (ffffffff811ccd3f)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811d3f9a)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811d9afd)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff811ef07c)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811f486d)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff811f9e54)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff812052c9)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff8120a2cd)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8120b837)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8120bfdd)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8120fa46)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/hugetlb.c (ffffffff81219b31)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/mempolicy.c (ffffffff8121c114)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81222aed)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff8122a2ca)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff8122f92f)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812362a2)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81238dac)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8123edb0)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81245fb0)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff81249df4)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:trylock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In mm/balloon_compaction.c (ffffffff8124ad63)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In mm/page_idle.c (ffffffff8124c0ba)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
```
```
In fs/read_write.c (ffffffff81250033)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
```
```
In fs/pipe.c (ffffffff8125a5b8)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff8126c513)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_drop
```
```
In fs/splice.c (ffffffff81286314)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8129038c)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/crypto/crypto.c (ffffffff812ac6b5)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
```
```
In fs/mbcache.c (ffffffff812ba99e)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap.c (ffffffff812befec)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/balloc.c (ffffffff812e3ecf)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff812e9145)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/file.c (ffffffff812f1577)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff812f4491)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff812f7c7f)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff812f9988)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8130795e)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff81314374)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffffffff8131d9f2)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff8131f3e6)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff81332593)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff8133c829)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813423f8)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81342c76)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81344d0b)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8134b5ef)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff813527ac)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff81362eac)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff81374697)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In block/blk-tag.c (ffffffff8142747d)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_start_tag
```
```
In block/blk-mq.c (ffffffff81431954)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814efbee)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/rtc/interface.c (ffffffff81719bc0)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_register
```
```
In drivers/rtc/rtc-dev.c (ffffffff8171b5c7)
Location: arch/x86/include/asm/bitops.h:230
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111b964)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811c4572)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811ccd03)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In mm/page-writeback.c (ffffffff811dae93)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff811de485)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
```
```
In mm/truncate.c (ffffffff811e1fd3)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811e94e7)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811ef7ef)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff81206973)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8120c647)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff812122a4)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8121e279)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff81223533)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff81224d5d)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8122560d)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8122b2fe)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/hugetlb.c (ffffffff81234b7a)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
```
```
In mm/ksm.c (ffffffff8123df54)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff8124547a)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff8124c1c2)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812550e2)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8125977a)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8125e930)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81265fed)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff8126a028)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:trylock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In mm/balloon_compaction.c (ffffffff8126afd3)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In mm/page_idle.c (ffffffff8126c49a)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
```
```
In mm/hmm.c (ffffffff8126d063)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_alloc_locked_page
```
```
In fs/read_write.c (ffffffff81271f28)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
```
```
In fs/pipe.c (ffffffff8127c8b8)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff8128e6a3)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:___d_drop
```
```
In fs/splice.c (ffffffff812a8d94)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff812b30e1)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/crypto/crypto.c (ffffffff812cfed5)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
```
```
In fs/mbcache.c (ffffffff812de27e)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap.c (ffffffff812e2a5f)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/balloc.c (ffffffff813088bf)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8130dbe5)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff81318bd1)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8131c2bf)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8131dfc8)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8132c5ae)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff81338b34)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffffffff81342002)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff81343a86)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff81356aa3)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff81360dac)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff81366a28)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813672a9)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff813693ab)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8136fc1f)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff813772c1)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff81387b4c)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff81399367)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In block/blk-tag.c (ffffffff8145247d)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_start_tag
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8152475e)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/rtc/interface.c (ffffffff8178ae39)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_register
```
```
In drivers/rtc/rtc-dev.c (ffffffff8178c863)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811284a8)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811e4a85)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811ede03)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In mm/page-writeback.c (ffffffff811fc373)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff811ffb55)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
```
```
In mm/truncate.c (ffffffff81203739)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8120a9f1)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81210cd1)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff8122645f)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8122d28d)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff81232fdb)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff812400f7)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff8124639c)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8124730a)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff81247bae)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8124c769)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/hugetlb.c (ffffffff81257ad6)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff81261849)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff812695ad)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff8126fce6)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81278f35)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8127b59c)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81282b34)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8128a145)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff8128e939)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:trylock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In mm/balloon_compaction.c (ffffffff8128f9c3)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In mm/page_idle.c (ffffffff81291068)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
```
```
In mm/hmm.c (ffffffff81291e23)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_alloc_locked_page
```
```
In fs/read_write.c (ffffffff81297ed2)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
```
```
In fs/pipe.c (ffffffff812a3808)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff812b4933)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/splice.c (ffffffff812cf91b)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff812d912c)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/crypto/crypto.c (ffffffff812fa7ad)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
```
```
In fs/mbcache.c (ffffffff8130a4be)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap.c (ffffffff8130dc77)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - fs/iomap.c:page_cache_seek_hole_data
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/balloc.c (ffffffff8133688c)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8133cb5f)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff81346c18)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8134a294)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8134bfad)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8135ab78)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff81367074)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffffffff8136fea2)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813718b2)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff81384dd1)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff8138f70e)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff81395118)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81395b16)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81397b59)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8139e12f)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff813a5fe2)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff813b6812)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff813c8e17)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In block/blk-tag.c (ffffffff814858e9)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_start_tag
```
```
In lib/sbitmap.c (ffffffff814f822b)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8155a4cd)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/rtc/interface.c (ffffffff817cc030)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_register
```
```
In drivers/rtc/rtc-dev.c (ffffffff817cf5d3)
Location: arch/x86/include/asm/bitops.h:232
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81133d8a)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811f5147)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff811ff402)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In mm/page-writeback.c (ffffffff8120e873)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff812123d5)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
```
```
In mm/truncate.c (ffffffff81216009)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8121d6f4)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81222cfb)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff8123a7bd)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8123d1f4)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff812467b0)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff812547f7)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff8125a7be)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8125b760)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8125c17e)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81260cb3)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8126c18f)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff812760ac)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff8127c685)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff81284390)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff8128d5e5)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff81290093)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81296cd4)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8129f0ef)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff812a2ad9)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/balloon_compaction.c (ffffffff812a48e3)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In mm/page_idle.c (ffffffff812a6088)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
```
```
In mm/hmm.c (ffffffff812a6e13)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_alloc_locked_page
```
```
In fs/read_write.c (ffffffff812acfa2)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
```
```
In fs/pipe.c (ffffffff812b8958)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff812c9bb3)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/splice.c (ffffffff812e4c8b)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff812ee5fc)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/crypto/crypto.c (ffffffff8130fb2d)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
```
```
In fs/mbcache.c (ffffffff8131fc9e)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap.c (ffffffff81324b32)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/iomap.c:page_cache_seek_hole_data
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/balloc.c (ffffffff8134db0c)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8135420f)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff8135edc8)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff81362457)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff813640ed)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81372e38)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff8137f4f4)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffffffff81388332)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff81389d79)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff8139d8c1)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813a8095)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813ade88)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813ae862)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813b08df)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813b6e9f)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff813bea08)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff813cfd62)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff813e2197)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In lib/sbitmap.c (ffffffff8150c6eb)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81571ddd)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/rtc/dev.c (ffffffff817f5fd3)
Location: arch/x86/include/asm/bitops.h:231
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8113ecc9)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/offload.c (ffffffff811f4e42)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/uprobes.c (ffffffff8120ce4c)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81216494)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In mm/page-writeback.c (ffffffff8121e395)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff81221d96)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
```
```
In mm/truncate.c (ffffffff81225a09)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8122d166)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff812330fb)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff8124bad0)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124ee94)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff81258a68)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff81266aa1)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff81275876)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff812768c7)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8127734d)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8127bbea)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8128754d)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff81291740)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff81298258)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff8129fa3d)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812a7f75)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff812aae9e)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812b2a31)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812ba4d8)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff812bde65)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/balloon_compaction.c (ffffffff812bfd11)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff812c17ae)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
```
```
In fs/read_write.c (ffffffff812c9bed)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffff812d552c)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff812e65c6)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/splice.c (ffffffff8130347e)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8130fdf3)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffff8134750d)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff8134b3bf)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffff8134e2f1)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/balloc.c (ffffffff813764f0)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8137ca04)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff8138801d)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8138a799)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8138dc46)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8139c291)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813a8974)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffffffff813b23cd)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813b47e1)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff813c7ae1)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813d2581)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813d81fb)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813d8d27)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813dae6e)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813e15a0)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff813e91cb)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff813fa948)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8140d9d9)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff8141cf79)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff81488d9b)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
```
```
In lib/rhashtable.c (ffffffff8150d606)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/sbitmap.c (ffffffff8153adfc)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a229e)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/rtc/dev.c (ffffffff81836ce3)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In net/core/xdp.c (ffffffff819307a3)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
```
```
In net/sched/cls_api.c (ffffffff819629cc)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81969ca1)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfaa0)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819db937)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e98f8)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a44111)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f5d6)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114a6f3)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/offload.c (ffffffff81201e52)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/uprobes.c (ffffffff8121a12a)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81223da4)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In mm/page-writeback.c (ffffffff8122be35)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff8122f846)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
```
```
In mm/truncate.c (ffffffff81233859)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8123b386)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8124131b)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff81259fc0)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125d474)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff81266f38)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff812753c1)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff81284846)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff812863b7)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff81286e2d)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8128b6ca)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8129715d)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff812a14c0)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff812a80b8)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812aff79)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812b9460)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff812bc5c5)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812c4470)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812cbc08)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff812cfd55)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/balloon_compaction.c (ffffffff812d1c61)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff812d36de)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
```
```
In fs/read_write.c (ffffffff812db6c9)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffff812e709c)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff812f8126)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/splice.c (ffffffff813164fe)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff81322dc3)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffff8135f67d)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff8136366f)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffff813665e1)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/balloc.c (ffffffff8138e760)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81395104)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813a09e2)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff813a31e9)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff813a66a6)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813b4da1)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813c1884)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffffffff813cb471)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813cd6e1)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff813e0ea1)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813ebc61)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813f22db)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813f2d17)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813f4ebe)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813fb5f0)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff8140326b)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff81405639)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81408939)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff81414818)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff81426bd9)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff81436dc9)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2c4b)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152b456)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/sbitmap.c (ffffffff8155bc1c)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815c311e)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/rtc/dev.c (ffffffff81868653)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In net/core/xdp.c (ffffffff81962cac)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81963ec4)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819a0711)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a06630)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a12867)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2160d)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a7ad01)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a86266)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115b247)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/offload.c (ffffffff81229266)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81246ab0)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81252c4b)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:wait_on_page_bit_common
```
```
In mm/page-writeback.c (ffffffff812587c5)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff8125c946)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
```
```
In mm/truncate.c (ffffffff81260f7e)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff812684a5)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff8126db71)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff812884e0)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8128bede)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_shared
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff812971af)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff812a6835)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff812b69f1)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff812b87ad)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff812b93ac)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812be5ac)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff812ca755)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_page_mapping_lock_write
```
```
In mm/ksm.c (ffffffff812d63d4)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff812dd2e6)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812e39f6)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812edfc5)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff812f198a)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812fa339)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81302660)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff81306856)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:find_alloced_obj
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/balloon_compaction.c (ffffffff81307b92)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff81309192)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
```
```
In fs/read_write.c (ffffffff81311676)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
```
```
In fs/pipe.c (ffffffff8131e877)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/dcache.c (ffffffff81330e86)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/splice.c (ffffffff8135062e)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/buffer.c (ffffffff8135d833)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/io_uring.c (ffffffff81388d89)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqes
```
```
In fs/mbcache.c (ffffffff813a5259)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff813aa480)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffff813ae152)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/balloc.c (ffffffff813d9f1b)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813ddd6c)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813eccb1)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff813ef3cc)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff813f257a)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81400231)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff8140dbe1)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff81419b3d)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff8142da73)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff81438e49)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff8143f460)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81440921)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/jbd2/recovery.c (ffffffff81442214)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81448dc5)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff81450eee)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff81453609)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff814562bd)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff81462b48)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8147716d)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff814868d3)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff814fcf32)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
```
```
In lib/rhashtable.c (ffffffff8158e9e2)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
```
```
In lib/sbitmap.c (ffffffff815e579c)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8166d2dd)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/rtc/dev.c (ffffffff8193c243)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In net/core/xdp.c (ffffffff81a35fa3)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a791ee)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5e93)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b01ccb)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b108e9)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b7525b)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b81403)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
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
In kernel/futex.c (ffffffff81157384)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/offload.c (ffffffff81230df6)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81251113)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8125d81b)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read_pagenotuptodate
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__wait_on_page_locked_async
```
```
In mm/page-writeback.c (ffffffff81262dd5)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff81266cc6)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
```
```
In mm/truncate.c (ffffffff8126b37e)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81272f43)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page_prepare
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff812798b1)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff812921c9)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81296e5e)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_shared
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff812a215f)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff812b1cd5)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff812c2c41)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff812c3e16)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff812c4d3c)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812ca183)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff812d6385)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff812e1ee8)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff812e60b6)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812eee66)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812f9635)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff812fdf0e)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff81306239)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8130db0b)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff81312596)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:find_alloced_obj
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/balloon_compaction.c (ffffffff813138c2)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff81315002)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
```
```
In fs/pipe.c (ffffffff81329dd7)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/dcache.c (ffffffff8133c816)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/splice.c (ffffffff8135d6be)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff813669f6)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
```
```
In fs/buffer.c (ffffffff8136b423)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/io_uring.c (ffffffff81399a7f)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqes
```
```
In fs/mbcache.c (ffffffff813b5fb9)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff813bbad0)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffff813bf7c2)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/balloc.c (ffffffff813ebbc5)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813ef65c)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff813fb0e3)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff813feebc)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff81401b1c)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff81404cca)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81412a35)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff8141513f)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/mmp.c (ffffffff8142104c)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8142a21c)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/resize.c (ffffffff8142d546)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff81446733)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_update_super
```
```
In fs/ext4/xattr.c (ffffffff81451972)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_update_super_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/ext4/fast_commit.c (ffffffff8145428b)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/jbd2/transaction.c (ffffffff8145b6c0)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8145cb4e)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/jbd2/recovery.c (ffffffff8145e565)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81465965)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff8146d40e)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff8146fab9)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8147267d)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff8147e648)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff81491fad)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff814a3f83)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a142)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
```
```
In lib/rhashtable.c (ffffffff815ab542)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
```
```
In lib/sbitmap.c (ffffffff81609b75)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8168d9fd)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/rtc/dev.c (ffffffff81942233)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In net/core/xdp.c (ffffffff81a38373)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a81ffe)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02d03)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b0fdab)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1ebd9)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b83fcb)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90c43)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
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
In kernel/futex.c (ffffffff81158798)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/watchdog.c (ffffffff811a252e)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/bpf/offload.c (ffffffff81234f99)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81255213)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812605e2)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__lock_page_async
```
```
In mm/page-writeback.c (ffffffff812677f5)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff8126b6f6)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
```
```
In mm/truncate.c (ffffffff81270473)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81278230)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff8127ea0d)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff81297f0b)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129caae)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff812a79ef)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff812b73a5)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff812c9abd)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff812cac1a)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff812cb9cc)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812d0c67)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff812dd52f)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff812e96a3)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff812ed846)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812f4ff6)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81300169)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff813048bb)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff8130c70d)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81313d1e)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/zsmalloc.c (ffffffff8131807b)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:trylock_zspage
```
```
In mm/balloon_compaction.c (ffffffff81319a52)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff8131b742)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
```
```
In fs/pipe.c (ffffffff8132fd97)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/dcache.c (ffffffff81342c9b)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/splice.c (ffffffff8136415e)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff8136d2a6)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
```
```
In fs/buffer.c (ffffffff81371cc3)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/mbcache.c (ffffffff813bd109)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff813c2bc0)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/balloc.c (ffffffff813f2105)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813f5b1b)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff814015b3)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff814051d0)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff81408061)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8140b235)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81418e95)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff8141b03c)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/mmp.c (ffffffff814277fc)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff81430f1c)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/resize.c (ffffffff81434206)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff8144bee3)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_update_super
```
```
In fs/ext4/xattr.c (ffffffff81458970)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/ext4/fast_commit.c (ffffffff81459bbb)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/jbd2/transaction.c (ffffffff81461000)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff814621e5)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/jbd2/recovery.c (ffffffff81463dea)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8146b115)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff81472a90)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff81474f7a)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8147808d)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff81484118)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8149716d)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff814a9eb7)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff81520a51)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
```
```
In lib/rhashtable.c (ffffffff815b63a4)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/sbitmap.c (ffffffff815ecdc1)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff816706ed)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/rtc/dev.c (ffffffff81925a63)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In net/core/xdp.c (ffffffff81a1f1b7)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81a6b0ed)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee607)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81afd99d)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0c864)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b72c4d)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7fe57)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
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
In kernel/futex.c (ffffffff8117d6a5)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/watchdog.c (ffffffff811cbd0e)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/bpf/offload.c (ffffffff8126f0c9)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81290c55)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8129cfd3)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__lock_page_async
```
```
In mm/page-writeback.c (ffffffff812a4355)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff812a83d6)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/readahead.c:read_cache_pages_invalidate_page
```
```
In mm/truncate.c (ffffffff812ae109)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff812b5ec9)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff812bc58c)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff812d894b)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812dd87e)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff812e900f)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff812f99f6)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff8130eadd)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff8130fc18)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff813109df)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
```
```
In mm/swapfile.c (ffffffff8131633e)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff813246d8)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff813315dc)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff81335bbd)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff8133f5f6)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81349db9)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8134e61f)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff8135790d)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8135effe)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/zsmalloc.c (ffffffff81364582)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:trylock_zspage
```
```
In mm/balloon_compaction.c (ffffffff81366242)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/page_idle.c (ffffffff81368a12)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
```
```
In fs/pipe.c (ffffffff8137d557)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/dcache.c (ffffffff813906db)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/splice.c (ffffffff813b294e)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff813bbf86)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
```
```
In fs/buffer.c (ffffffff813c0ce3)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/io-wq.c (ffffffff813f1916)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/io-wq.c:io_queue_worker_create
```
```
In fs/mbcache.c (ffffffff8140cea7)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff81412d98)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/balloc.c (ffffffff814440e5)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8144837b)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff81453b3c)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff814579e4)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8145a99d)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8145deb4)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8146c0c9)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff8146df40)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/mmp.c (ffffffff8147b44d)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff81487c69)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff8149ff57)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_update_super
```
```
In fs/ext4/xattr.c (ffffffff814aca83)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/ext4/fast_commit.c (ffffffff814adcab)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/ext4/orphan.c (ffffffff814b184c)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/jbd2/transaction.c (ffffffff814b64e0)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff814b76db)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/jbd2/recovery.c (ffffffff814b93bc)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff814c17c5)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff814c955d)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff814cd528)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff814cf30d)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff814db798)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff814eea5d)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff81502367)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/apparmor/policy_unpack.c (ffffffff8157ebf1)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
```
```
In lib/rhashtable.c (ffffffff8161c8d4)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/sbitmap.c (ffffffff81659ce1)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff816e49bd)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/rtc/dev.c (ffffffff819c89d3)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In net/core/xdp.c (ffffffff81ad3447)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/netlink/af_netlink.c (ffffffff81b2470d)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae9b7)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81bbfa9d)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcfa54)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81c3a19d)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/ip6mr.c (ffffffff81c3d18d)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b6f7)
Location: include/asm-generic/bitops/instrumented-lock.h:53
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
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
In kernel/futex/core.c (ffffffff811b2724)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/watchdog.c (ffffffff811ffab9)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/bpf/offload.c (ffffffff812be019)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff812e5f52)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812f4060)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/page-writeback.c (ffffffff812fc5f3)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff8130762c)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8130f1a2)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff813185e7)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff813312cf)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff813375f6)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In mm/memory.c (ffffffff81342559)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/rmap.c (ffffffff8135bfb7)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:folio_referenced
```
```
In mm/madvise.c (ffffffff8137691c)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8137b731)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In mm/swapfile.c (ffffffff81381496)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff81392c5b)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff813a2454)
Location: include/asm-generic/bitops/instrumented-lock.h:55
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
In mm/slub.c (ffffffff813a7374)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff813b5240)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:writeout
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff813b6f26)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c07c5)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff813c518a)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff813d0668)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff813da0b0)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
```
In mm/zsmalloc.c (ffffffff813e2887)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff813e3227)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/page_idle.c (ffffffff813e6551)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
```
```
In fs/pipe.c (ffffffff813fe37a)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/dcache.c (ffffffff81413192)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/splice.c (ffffffff814389fa)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff81441e9f)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In fs/buffer.c (ffffffff8144503b)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
```
```
In fs/mbcache.c (ffffffff81481cf9)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff8148a879)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/balloc.c (ffffffff814bffdb)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff814c48cc)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff814d101f)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff814d53dc)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff814d871e)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff814dbc5b)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff814ec0bf)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff814eec97)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mmp.c (ffffffff814fd8ad)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff8150b546)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff81526b8b)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_update_super
```
```
In fs/ext4/xattr.c (ffffffff81534a3f)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/ext4/fast_commit.c (ffffffff81535b9b)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/ext4/orphan.c (ffffffff8153a3a3)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/ext4/crypto.c (ffffffff8153cd3b)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
```
```
In fs/jbd2/transaction.c (ffffffff8153fdd4)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81540eba)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/jbd2/recovery.c (ffffffff815430e8)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8154c15b)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff815556f7)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff8155930f)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8155be24)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff81569336)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8157f18b)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff815939b9)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d6eb)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In io_uring/io-wq.c (ffffffff816da2da)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
```
```
In lib/rhashtable.c (ffffffff816ea0e5)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/sbitmap.c (ffffffff81772436)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8180f3af)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/rtc/dev.c (ffffffff81b29953)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In net/core/xdp.c (ffffffff81c50cf9)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81cabfed)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81d418ca)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d55e07)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d68145)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81dd7f01)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81ddb51c)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deae1f)
Location: include/asm-generic/bitops/instrumented-lock.h:55
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
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/watchdog.c (ffffffff812474d9)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/bpf/offload.c (ffffffff813216ab)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134d55e)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8134fba9)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8135e351)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/page-writeback.c (ffffffff81366903)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff8137174a)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8137dfe9)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff8138c4db)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff813a7f94)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff813ae720)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In mm/memory.c (ffffffff813ba6a6)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/rmap.c (ffffffff813d7527)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:folio_referenced
```
```
In mm/madvise.c (ffffffff813f4279)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff813f90b1)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff813ffcda)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff814115f8)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff814220b1)
Location: include/asm-generic/bitops/instrumented-lock.h:55
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
In mm/slub.c (ffffffff81429f9a)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
```
```
In mm/migrate.c (ffffffff8143527b)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:writeout
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8143a43f)
Location: include/asm-generic/bitops/instrumented-lock.h:55
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
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff814494f5)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff81455d56)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8146184e)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
```
In mm/zsmalloc.c (ffffffff81469de7)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff8146aba3)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/page_idle.c (ffffffff8146e01e)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
```
```
In mm/memremap.c (ffffffff8146f864)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
```
```
In fs/pipe.c (ffffffff81487fea)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/dcache.c (ffffffff8149e44c)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/splice.c (ffffffff814c6ffa)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff814d097c)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In fs/buffer.c (ffffffff814d33d1)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
```
```
In fs/mbcache.c (ffffffff81514f62)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff8151e126)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/balloc.c (ffffffff81557fe6)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8155ce0c)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff81569a63)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff8156e33a)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff81571506)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff81574bbb)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81585e29)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff81588d5b)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mmp.c (ffffffff8159808d)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff815a61e9)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff815c446b)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
```
```
In fs/ext4/xattr.c (ffffffff815d2f6c)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:__ext4_xattr_check_block
```
```
In fs/ext4/fast_commit.c (ffffffff815d404b)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/ext4/orphan.c (ffffffff815d8913)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/ext4/crypto.c (ffffffff815db500)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
```
```
In fs/jbd2/transaction.c (ffffffff815de96a)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff815e000d)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/jbd2/recovery.c (ffffffff815e1f40)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff815ebf3b)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6b2b)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff815fc414)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff815fdd1f)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff8160cec6)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff81624e58)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff8163c54e)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff816d11a0)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In io_uring/io-wq.c (ffffffff817a638a)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
```
```
In lib/rhashtable.c (ffffffff817da308)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/sbitmap.c (ffffffff818a2cba)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8193e14f)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/rtc/dev.c (ffffffff81cbd573)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In net/core/xdp.c (ffffffff81e0639e)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e69bc1)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a6e9)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f2053b)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f331d9)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff81fa98f7)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81fae120)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbea03)
Location: include/asm-generic/bitops/instrumented-lock.h:55
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
In kernel/futex/core.c (ffffffff81207d7a)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/watchdog.c (ffffffff8125e599)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/bpf/offload.c (ffffffff8135124c)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137e4ff)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81380d68)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff813910c4)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/page-writeback.c (ffffffff81398f73)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff813a385a)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff813afa26)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff813bf848)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_get_partial_folio
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff813db573)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff813e3020)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In mm/memory.c (ffffffff813ef066)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/rmap.c (ffffffff8140ba34)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:folio_referenced
```
```
In mm/madvise.c (ffffffff81427b3f)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8142be81)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff81432b7f)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff81444ac3)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff81456d9a)
Location: include/asm-generic/bitops/instrumented-lock.h:55
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
In mm/slub.c (ffffffff8145f439)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
```
```
In mm/migrate.c (ffffffff8146a7e9)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:writeout
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8146fd8f)
Location: include/asm-generic/bitops/instrumented-lock.h:55
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
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8147f6e6)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff81488f0f)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8149706d)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:try_to_split_thp_page
```
```
In mm/zsmalloc.c (ffffffff8149efe7)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff8149fa33)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/page_idle.c (ffffffff814a2894)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
```
```
In mm/memremap.c (ffffffff814a4044)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
```
```
In fs/pipe.c (ffffffff814bcee2)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/dcache.c (ffffffff814d376c)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/splice.c (ffffffff814fc438)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff8150707c)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In fs/buffer.c (ffffffff8150a661)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
```
```
In fs/mbcache.c (ffffffff8154c962)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff8155628c)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/balloc.c (ffffffff8158fd33)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81594c2c)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff815a1853)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff815a61fa)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff815a926d)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff815aca8b)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff815bc6ff)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff815bf5d0)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_getuuid
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mmp.c (ffffffff815ceb3d)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/resize.c (ffffffff815dca59)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff815fbb4c)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
```
```
In fs/ext4/xattr.c (ffffffff8160aaba)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:check_xattrs
```
```
In fs/ext4/fast_commit.c (ffffffff8160bc2b)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/ext4/orphan.c (ffffffff816104b4)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/ext4/crypto.c (ffffffff81612fb0)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
```
```
In fs/jbd2/transaction.c (ffffffff816163ca)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81617329)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff8161975c)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/checkpoint.c (ffffffff8161a7c0)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_try_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81623a1b)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff8162ebe6)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff816343a4)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81635cd0)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff81644d76)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8165d1de)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff81674a07)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8170a0b0)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In io_uring/io-wq.c (ffffffff817e72eb)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
```
```
In lib/rhashtable.c (ffffffff81819689)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/sbitmap.c (ffffffff818e5ca1)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_find_bit
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8198264f)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/rtc/dev.c (ffffffff81d24e83)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In net/core/xdp.c (ffffffff81e78c21)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81ec5b5b)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a219)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f80037)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f92559)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff8200a277)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff8200e8cb)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201f8d9)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/handshake/request.c (ffffffff82092c0f)
Location: include/asm-generic/bitops/instrumented-lock.h:55
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
In kernel/futex/core.c (ffffffff8121ef0f)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/watchdog.c (ffffffff812784d9)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_hardlockup_check
```
```
In kernel/bpf/offload.c (ffffffff813786ac)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a775f)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff813aa129)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff813bae64)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/page-writeback.c (ffffffff813c2d73)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff813cd3bf)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff813d9147)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff813ea861)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_get_partial_folio
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff81404e32)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8140d857)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In mm/memory.c (ffffffff8141af6e)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/rmap.c (ffffffff814382f4)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:folio_referenced
```
```
In mm/slub.c (ffffffff8145a682)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In mm/madvise.c (ffffffff8146134f)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff814655db)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff8146bf9e)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff8147eb1a)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff8149189e)
Location: include/asm-generic/bitops/instrumented-lock.h:55
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
In mm/migrate.c (ffffffff814997c9)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:writeout
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8149f00c)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a784e)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff814adbba)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff814b8f75)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff814c6402)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:try_to_split_thp_page
```
```
In mm/zsmalloc.c (ffffffff814ce747)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff814cf183)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/userfaultfd.c (ffffffff814d2c64)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:move_pages_pte
```
```
In mm/page_idle.c (ffffffff814d3731)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
```
```
In mm/memremap.c (ffffffff814d4ef4)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
```
```
In fs/pipe.c (ffffffff814ef37f)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/dcache.c (ffffffff81505eec)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:___d_drop
```
```
In fs/splice.c (ffffffff815301f9)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff8153c3a2)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In fs/buffer.c (ffffffff8153f611)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
```
```
In fs/mbcache.c (ffffffff81582792)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff8158c75c)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/balloc.c (ffffffff815c88c2)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff815cd8dc)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff815da603)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff815df079)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff815e1e7c)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff815e582a)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff815f54dc)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff815f8376)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_getuuid
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mmp.c (ffffffff816073bd)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/resize.c (ffffffff8161533f)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff816346ec)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
```
```
In fs/ext4/xattr.c (ffffffff8164386a)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:check_xattrs
```
```
In fs/ext4/fast_commit.c (ffffffff816449eb)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/ext4/orphan.c (ffffffff81649274)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/ext4/crypto.c (ffffffff8164bdb0)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
```
```
In fs/jbd2/transaction.c (ffffffff8164f1ec)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81650143)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81652681)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/checkpoint.c (ffffffff816536e7)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_try_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8165cabb)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff816680ad)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff8166d883)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8166f1bf)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff8167e296)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff81696f3e)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff816b0dc7)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81747bb0)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In block/bio.c (ffffffff817abb00)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:__bio_release_pages
```
```
In io_uring/io-wq.c (ffffffff8182d0ab)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
```
```
In io_uring/futex.c (ffffffff8182f0d6)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - io_uring/futex.c:io_futex_wakev_fn
```
```
In lib/rhashtable.c (ffffffff8185e9d9)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/sbitmap.c (ffffffff8192cca1)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_find_bit
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819c9dcf)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/rtc/dev.c (ffffffff81ddabf3)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In net/core/xdp.c (ffffffff81f38af1)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81f88dbb)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff820308c9)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff820466b7)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff820602c9)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/ipv6/ioam6.c (ffffffff820d9218)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff820dd85b)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eea09)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
```
In net/handshake/request.c (ffffffff821694bf)
Location: include/asm-generic/bitops/instrumented-lock.h:55
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101b7b84)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/offload.c (ffff80001028a204)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/uprobes.c (ffff8000102a553c)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffff8000102b1684)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:wait_on_page_bit_common
```
```
In mm/page-writeback.c (ffff8000102bc37c)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffff8000102bf264)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
```
```
In mm/truncate.c (ffff8000102c3d30)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffff8000102cc484)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffff8000102d3700)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffff8000102f2150)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffff8000102f49bc)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffff8000102fe190)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffff80001030b288)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffff80001031eb94)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffff8000103209e0)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffff8000103217d4)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffff800010326994)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffff800010334f70)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffff800010340df8)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffff8000103493a0)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffff80001035124c)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffff800010359bdc)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffff80001035d348)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffff800010367070)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffff800010370254)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffff800010374904)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/balloon_compaction.c (ffff800010377a08)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffff800010379078)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
```
```
In fs/read_write.c (ffff8000103805a0)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
```
```
In fs/pipe.c (ffff80001038fc50)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffff8000103a56c0)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/splice.c (ffff8000103ce29c)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffff8000103dbea4)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffff8000104252d8)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffff80001042a3c8)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffff80001042dd60)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/balloc.c (ffff8000104609b8)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffff800010467e4c)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffff800010474078)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffff800010476ab0)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffff800010479f94)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffff800010489540)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffff80001049904c)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffff8000104a3330)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffff8000104a6c64)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffff8000104ba218)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffff8000104c4b00)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffff8000104cca28)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffff8000104ce194)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffff8000104d081c)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffff8000104d8dbc)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffff8000104e1e0c)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffff8000104e49f4)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffff8000104e8ea4)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffff8000104f5f20)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffff80001050b1bc)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffff80001051d494)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffff800010598990)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
```
```
In lib/rhashtable.c (ffff800010636b58)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/sbitmap.c (ffff800010669b40)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/video/fbdev/core/fb_defio.c (ffff80001074c0a0)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/rtc/dev.c (ffff800010aaa490)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In net/core/xdp.c (ffff800010c067a8)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffff800010c08634)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffff800010c4edcc)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf480)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffff800010ccbf3c)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdcd6c)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffff800010d44b58)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51e80)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c0401910)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/offload.c (c04b9884)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/uprobes.c (c04d4930)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (c04de130)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In mm/page-writeback.c (c04e6d14)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (c04eab00)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
```
```
In mm/truncate.c (c04ee8b8)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (c04f61f0)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (c04fb9a0)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (c051435c)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
```
```
In mm/memory.c (c0516b64)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (c051ce50)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (c05276ec)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (c05377a4)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (c05393b0)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (c0539fc0)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (c053e160)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/ksm.c (c0547038)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (c054d54c)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__slab_free
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (c0552884)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memcontrol.c (c0558808)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
```
```
In mm/zsmalloc.c (c056171c)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/balloon_compaction.c (c0563480)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (c05645cc)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
```
```
In fs/read_write.c (c056b528)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (c0576a50)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (c0588eb8)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/splice.c (c05a99f4)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (c05b5220)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (c05ede60)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (c05f31d0)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (c05f6d0c)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/balloc.c (c062115c)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (c0628b6c)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (c063548c)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (c06385e4)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (c063b7e0)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (c064ba00)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (c065a9a4)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (c06652ec)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (c0668a68)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (c067d89c)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (c0688b14)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (c06902f4)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (c0690e6c)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (c0693484)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (c069acc0)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/dir.c (c06a3764)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (c06a6db8)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (c06b3790)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (c06c6844)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (c06d987c)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c0749bc8)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
```
```
In lib/rhashtable.c (c07dc880)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/sbitmap.c (c0811a08)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/video/fbdev/core/fb_defio.c (c08cece0)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/rtc/dev.c (c0b893cc)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In net/core/xdp.c (c0d1f934)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (c0d21724)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c0d5eed4)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c0dcadf8)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c0dd7d50)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (c0de7a64)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c0e47010)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c0e52f24)
Location: include/asm-generic/bitops/lock.h:18
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/watchdog.c (c0000000000374ec)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:stop_watchdog
  - arch/powerpc/kernel/watchdog.c:start_watchdog
  - arch/powerpc/kernel/watchdog.c:watchdog_timer_fn
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
```
```
In arch/powerpc/mm/book3s64/hash_native.c (c000000000092604)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_native.c:native_flush_hash_range
  - arch/powerpc/mm/book3s64/hash_native.c:native_hugepage_invalidate
  - arch/powerpc/mm/book3s64/hash_native.c:native_hpte_invalidate
  - arch/powerpc/mm/book3s64/hash_native.c:native_hpte_updatepp
  - arch/powerpc/mm/book3s64/hash_native.c:native_hpte_remove
  - arch/powerpc/mm/book3s64/hash_native.c:native_hpte_insert
```
```
In arch/powerpc/platforms/powernv/idle.c (c0000000000c7540)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/idle.c:power9_idle_stop
  - arch/powerpc/platforms/powernv/idle.c:power7_idle_insn
  - arch/powerpc/platforms/powernv/idle.c:power7_idle_insn
  - arch/powerpc/platforms/powernv/idle.c:power7_idle_insn
```
```
In arch/powerpc/kvm/book3s_64_vio_hv.c (c000000000118e14)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_64_vio_hv.c:kvmppc_rm_h_put_tce_indirect
```
```
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c00000000011fb84)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_h_clear_ref
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:remove_revmap_chain
```
```
In kernel/futex.c (c00000000021d028)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/offload.c (c0000000003355c4)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/uprobes.c (c000000000358250)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (c000000000367108)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In mm/page-writeback.c (c000000000373110)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (c000000000377a24)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
```
```
In mm/truncate.c (c00000000037e178)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (c00000000038992c)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (c000000000392790)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (c0000000003b8110)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003bb698)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (c0000000003c98b8)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (c0000000003db390)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (c0000000003f34dc)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (c0000000003f5e10)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (c0000000003f6f08)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (c0000000003fd3e0)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (c00000000040e6b8)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (c00000000041e658)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (c000000000428584)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (c0000000004362f0)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (c000000000443350)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (c0000000004486d0)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (c0000000004544d0)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (c000000000460c58)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (c000000000467d64)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/balloon_compaction.c (c00000000046a100)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/page_idle.c (c00000000046c2b0)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
```
```
In fs/read_write.c (c00000000047713c)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (c0000000004873c0)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (c0000000004a1128)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:___d_drop
```
```
In fs/splice.c (c0000000004ce910)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (c0000000004e3c7c)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (c000000000534554)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (c00000000053ace8)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (c00000000053f038)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/balloc.c (c00000000057d010)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (c000000000587c44)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (c0000000005953d8)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (c000000000599d48)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (c00000000059c1d0)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (c0000000005b0574)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (c0000000005c3190)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (c0000000005d01e4)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (c0000000005d3314)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (c0000000005ef91c)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (c0000000005fc440)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (c000000000606138)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (c000000000606d90)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (c0000000006099e8)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (c000000000613d6c)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (c00000000061e7b4)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (c0000000006224ac)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (c0000000006264dc)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (c000000000636d1c)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (c0000000006509b8)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (c000000000666600)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c00000000070f910)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
```
```
In lib/rhashtable.c (c0000000007dca44)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/sbitmap.c (c00000000081e8d4)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/video/fbdev/core/fb_defio.c (c0000000008ae110)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/rtc/dev.c (c000000000b8c814)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In net/core/xdp.c (c000000000cf0d14)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (c000000000cf2c74)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c000000000d4d470)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c000000000dda0f0)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c000000000deb434)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c000000000dfcd2c)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c000000000e7965c)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c000000000e8aa48)
Location: arch/powerpc/include/asm/bitops.h:147
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe00013c86c)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/offload.c (ffffffe0001be2a8)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/filemap.c (ffffffe0001d6f1e)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In mm/page-writeback.c (ffffffe0001ddaae)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffe0001e134a)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
```
```
In mm/truncate.c (ffffffe0001e4968)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffe0001eaf6e)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffe0001ef7be)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffe00020482a)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
```
```
In mm/memory.c (ffffffe000205eb8)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffe00020c25c)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffe000214c7a)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffe0002205e0)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffe000222014)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffe000222a0c)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffe000226a7c)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffe000231768)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffe00023555c)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffe00023b128)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffe00023fc60)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memcontrol.c (ffffffe0002452fe)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
```
```
In mm/zsmalloc.c (ffffffe00024d82e)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/balloon_compaction.c (ffffffe00024f6c0)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffe00025089e)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
```
```
In fs/read_write.c (ffffffe000255bdc)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffe00025f6ca)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffe00026c288)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/splice.c (ffffffe00028a27c)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffe000294404)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffe0002c43e4)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffe0002c7f0e)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffe0002ca78e)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/balloc.c (ffffffe0002efe86)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffe0002f5bc2)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffe0002ffaba)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffe000302b88)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffe000304284)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffe000310d06)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffe00031cbd8)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffffffe000324bb2)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffe000326c6c)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffe000336746)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffe00033f3f8)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffe00034538c)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffe000345d32)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffe000347f10)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffe00034e720)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffe0003558f6)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffe0003577fe)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffe000359e06)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffe000364d24)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffe000375ed6)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffe000384d80)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e5304)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
```
```
In lib/rhashtable.c (ffffffe000464104)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/sbitmap.c (ffffffe00049414a)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffe0004f9e6a)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/rtc/dev.c (ffffffe0006b58d0)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In net/core/xdp.c (ffffffe000784cca)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (ffffffe000786478)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffe0007bab16)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffe000815256)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffe00082083c)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082c10a)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffe00087f402)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a4b4)
Location: arch/riscv/include/asm/bitops.h:155
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81142d13)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/offload.c (ffffffff811fa472)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/uprobes.c (ffffffff8121277a)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8121c3f4)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In mm/page-writeback.c (ffffffff81224485)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff81227e96)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
```
```
In mm/truncate.c (ffffffff8122bea9)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff812339d6)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8123996b)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff81252610)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81255ac4)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff8125f588)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8126da11)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff8127ce96)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff8127ea07)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8127f47d)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81283caa)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8128f73d)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff81299aa0)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff812a0698)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812a8559)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812b1a40)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff812b4ba5)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812bca50)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812c41e8)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff812c8335)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/balloon_compaction.c (ffffffff812ca241)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff812cbcbe)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
```
```
In fs/read_write.c (ffffffff812d3ca9)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffff812df67c)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff812f0706)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/splice.c (ffffffff8130eade)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8131b3a3)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffff81357c5d)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff8135bc4f)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffff8135ebc1)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/balloc.c (ffffffff81386d40)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8138d6e4)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff81398fc2)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8139b7c9)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8139ec86)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813ad381)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813b9e64)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffffffff813c3a51)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813c5cc1)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff813d9481)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813e4241)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813ea8bb)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813eb2f7)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ed49e)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813f3bd0)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff813fb84b)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff813fdc19)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81400f19)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff8140cdf8)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8141f1b9)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff8142f3a9)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8149b22b)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
```
```
In lib/rhashtable.c (ffffffff81523a36)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/sbitmap.c (ffffffff8155420c)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b726e)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/nvme/host/core.c (ffffffff81744aad)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_setup_discard
```
```
In drivers/rtc/dev.c (ffffffff8181b303)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In net/core/xdp.c (ffffffff81902c7c)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81903e94)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81940581)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819a63d0)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819b2127)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c0c9d)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a391)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a258f6)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81136073)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/offload.c (ffffffff811ed1c2)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/uprobes.c (ffffffff8120550a)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8120f5de)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In mm/page-writeback.c (ffffffff81217635)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff8121afd6)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
```
```
In mm/truncate.c (ffffffff8121ef89)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81226a4a)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8122c99b)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff81245b2e)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812481a4)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff812519a8)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8125fa41)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff8126ed4a)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff81270837)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8127129d)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81275b33)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81281406)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff8128b660)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff812921a8)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff81299f19)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812a2e10)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff812a5bf7)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812adbb0)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812b5228)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff812b9375)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/balloon_compaction.c (ffffffff812bb281)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff812bcb2e)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
```
```
In fs/read_write.c (ffffffff812c4929)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffff812d02bc)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff812e1336)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/splice.c (ffffffff812ff6ee)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8130bf43)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffff8134890d)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff8134c8ef)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffff8134f861)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/balloc.c (ffffffff813777d0)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8137e174)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff81389a52)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8138c259)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8138f716)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8139de11)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813aa8f4)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffffffff813b44d6)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813b6741)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff813c9f01)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813d4cc1)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813db33b)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813dbd77)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ddf1e)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813e4650)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff813ec2cb)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff813ee699)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff813f1999)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff813fd878)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8140fc39)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff8141fe29)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff8148bc4b)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
```
```
In lib/rhashtable.c (ffffffff81513d16)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/sbitmap.c (ffffffff8154448c)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a604e)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/nvme/host/core.c (ffffffff8172673d)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_setup_discard
```
```
In drivers/rtc/dev.c (ffffffff817e29f3)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In net/core/xdp.c (ffffffff818bcaac)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff818bdcc4)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff818fa071)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff8195fe90)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff8196e757)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197da8d)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff819d7151)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e26b6)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81140bc3)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/offload.c (ffffffff811f8242)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/uprobes.c (ffffffff8121051a)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8121a194)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In mm/page-writeback.c (ffffffff81222225)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff81225c36)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
```
```
In mm/truncate.c (ffffffff81229c49)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81231776)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8123770b)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff812503b0)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81253864)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff8125d328)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8126b7b1)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff8127ac36)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff8127c7a7)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8127d21d)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81281aba)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8128d54d)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff812978b0)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff8129e4a8)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812a6369)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812af850)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff812b29b5)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812ba860)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812c1ff8)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff812c6145)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/balloon_compaction.c (ffffffff812c8051)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff812c9ace)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
```
```
In fs/read_write.c (ffffffff812d1ab9)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffff812dd48c)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff812ee516)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/splice.c (ffffffff8130c8ce)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff81318e73)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffff8135572d)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff8135971f)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffff8135c691)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/balloc.c (ffffffff81384810)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8138b044)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff81396822)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff81399029)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8139c4e6)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813aabe1)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813b76c4)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffffffff813c0ee1)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813c3151)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff813d6911)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813e15c1)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813e7c3b)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813e8677)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ea81e)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813f0f50)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff813f8bcb)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff813faf99)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff813fe299)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff8140a178)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8141b359)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff8142b549)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814972cb)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
```
```
In lib/rhashtable.c (ffffffff8151fac6)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/sbitmap.c (ffffffff8154ff4c)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b77fe)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/rtc/dev.c (ffffffff8185c7e3)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In net/core/xdp.c (ffffffff81953cac)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81954ec4)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81991711)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10c70)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a1c9c7)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2b71d)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a84e11)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a90376)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114de1e)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/offload.c (ffffffff812065a8)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/uprobes.c (ffffffff8121f462)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8122926b)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In mm/page-writeback.c (ffffffff8123166f)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff81234f36)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
```
```
In mm/truncate.c (ffffffff81239044)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81240b9f)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81246c45)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff8125fd34)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8126322d)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff8126cd0e)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8127b141)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff8128a817)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff8128c377)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8128cddd)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812917c6)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8129d2fb)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff812a7687)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff812ae222)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812b6684)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812bfb90)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff812c2bf2)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812cafa0)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812d2a93)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff812d78dc)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/balloon_compaction.c (ffffffff812d8d61)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff812da7be)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
```
```
In fs/read_write.c (ffffffff812e28d2)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffff812ee404)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff813004dd)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/splice.c (ffffffff8131e0f5)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8132aaa3)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffff81368d28)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff8136ce1a)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffff8136fdbe)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/balloc.c (ffffffff8139838b)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8139ed7f)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813aaaa8)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff813ae202)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff813b09fd)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813bf52c)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813cc3cf)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffffffff813d6018)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813d82fc)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff813ebbba)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813f69d2)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813fd442)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813fdea1)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81400180)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81406b17)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff8140ea15)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff81410bc8)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81413f40)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff8141fe71)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff81432384)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff814424e2)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (ffffffff814af3aa)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
```
```
In lib/rhashtable.c (ffffffff815393b2)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/sbitmap.c (ffffffff81569d8c)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815d1269)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/rtc/dev.c (ffffffff81877a63)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In net/core/xdp.c (ffffffff81975436)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81976ea6)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819b419d)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b554)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a2798a)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a36d6c)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (ffffffff81a91794)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9cf77)
Location: include/asm-generic/bitops-instrumented.h:170
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
</details>
</li>
</ul>

## Differences
