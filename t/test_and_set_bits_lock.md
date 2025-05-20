# Function: <code>test_and_set_bits_lock</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/watchdog.c (c0000000000374ec)
Location: arch/powerpc/include/asm/bitops.h:134
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
Location: arch/powerpc/include/asm/bitops.h:134
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
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/idle.c:power9_idle_stop
  - arch/powerpc/platforms/powernv/idle.c:power7_idle_insn
  - arch/powerpc/platforms/powernv/idle.c:power7_idle_insn
  - arch/powerpc/platforms/powernv/idle.c:power7_idle_insn
```
```
In arch/powerpc/kvm/book3s_64_vio_hv.c (c000000000118e14)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_64_vio_hv.c:kvmppc_rm_h_put_tce_indirect
```
```
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c00000000011fb84)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_h_clear_ref
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:remove_revmap_chain
```
```
In kernel/futex.c (c00000000021d028)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/offload.c (c0000000003355c4)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/uprobes.c (c000000000358250)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (c000000000367108)
Location: arch/powerpc/include/asm/bitops.h:134
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
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (c000000000377a24)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
```
```
In mm/truncate.c (c00000000037e178)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (c00000000038992c)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (c000000000392790)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (c0000000003b8110)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003bb698)
Location: arch/powerpc/include/asm/bitops.h:134
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
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (c0000000003db390)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (c0000000003f34dc)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (c0000000003f5e10)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (c0000000003f6f08)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (c0000000003fd3e0)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (c00000000040e6b8)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (c00000000041e658)
Location: arch/powerpc/include/asm/bitops.h:134
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
Location: arch/powerpc/include/asm/bitops.h:134
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
Location: arch/powerpc/include/asm/bitops.h:134
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
Location: arch/powerpc/include/asm/bitops.h:134
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
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (c0000000004544d0)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (c000000000460c58)
Location: arch/powerpc/include/asm/bitops.h:134
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
Location: arch/powerpc/include/asm/bitops.h:134
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
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/page_idle.c (c00000000046c2b0)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
```
```
In fs/read_write.c (c00000000047713c)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (c0000000004873c0)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (c0000000004a1128)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:___d_drop
```
```
In fs/splice.c (c0000000004ce910)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (c0000000004e3c7c)
Location: arch/powerpc/include/asm/bitops.h:134
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
Location: arch/powerpc/include/asm/bitops.h:134
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
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (c00000000053f038)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/balloc.c (c00000000057d010)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (c000000000587c44)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (c0000000005953d8)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (c000000000599d48)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (c00000000059c1d0)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (c0000000005b0574)
Location: arch/powerpc/include/asm/bitops.h:134
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
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (c0000000005d01e4)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (c0000000005d3314)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (c0000000005ef91c)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (c0000000005fc440)
Location: arch/powerpc/include/asm/bitops.h:134
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
Location: arch/powerpc/include/asm/bitops.h:134
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
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (c0000000006099e8)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (c000000000613d6c)
Location: arch/powerpc/include/asm/bitops.h:134
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
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (c0000000006224ac)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (c0000000006264dc)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (c000000000636d1c)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (c0000000006509b8)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (c000000000666600)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/policy_unpack.c (c00000000070f910)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
```
```
In lib/rhashtable.c (c0000000007dca44)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/sbitmap.c (c00000000081e8ec)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/video/fbdev/core/fb_defio.c (c0000000008ae110)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/rtc/dev.c (c000000000b8c814)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In net/core/xdp.c (c000000000cf0d14)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (c000000000cf2c74)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (c000000000d4d470)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c000000000dda0f0)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (c000000000deb434)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c000000000dfcd2c)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/ipv6/ip6mr.c (c000000000e7965c)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c000000000e8aa48)
Location: arch/powerpc/include/asm/bitops.h:134
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
</details>
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
