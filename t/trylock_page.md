# Function: <code>trylock_page</code>

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
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff8118776f)
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8118daa6)
Location: include/linux/pagemap.h:446
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
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff8119bc16)
Location: include/linux/pagemap.h:446
Inline: True
```
```
In mm/truncate.c (ffffffff8119e900)
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff811a0b41)
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_active_list
```
```
In mm/shmem.c (ffffffff811a916c)
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff811ba5f8)
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811bbdfd)
Location: include/linux/pagemap.h:446
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
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/rmap.c (ffffffff811cc305)
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/swap_state.c (ffffffff811d29a7)
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:free_pages_and_swap_cache
```
```
In mm/swapfile.c (ffffffff811d4773)
Location: include/linux/pagemap.h:446
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
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (ffffffff811e4b66)
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/migrate.c (ffffffff811f2197)
Location: include/linux/pagemap.h:446
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
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff811fd293)
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81201d02)
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/balloon_compaction.c (ffffffff81207385)
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_isolate
  - mm/balloon_compaction.c:balloon_page_putback
```
```
In mm/page_idle.c (ffffffff81208336)
Location: include/linux/pagemap.h:446
Inline: True
```
```
In fs/pipe.c (ffffffff81214ab1)
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff8123e7a9)
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:__generic_file_splice_read
```
```
In fs/buffer.c (ffffffff812459f7)
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:nobh_truncate_page
```
```
In fs/dax.c (ffffffff8125dcc7)
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - fs/dax.c:__dax_fault
```
```
In fs/ext4/file.c (ffffffff81292488)
Location: include/linux/pagemap.h:446
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81297d58)
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/ext4/crypto.c (ffffffff812e5490)
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_encrypt
```
```
In fs/jbd2/commit.c (ffffffff812eb160)
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/hugetlbfs/inode.c (ffffffff812f39a0)
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff8130449d)
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff81316215)
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81473589)
Location: include/linux/pagemap.h:446
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
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
In kernel/futex.c (ffffffff8110770b)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81199d61)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811a141c)
Location: include/linux/pagemap.h:422
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
In mm/page-writeback.c (ffffffff811ad964)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff811b0d66)
Location: include/linux/pagemap.h:422
Inline: True
```
```
In mm/truncate.c (ffffffff811b43b4)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811baceb)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811c0acc)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff811d5188)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811d7028)
Location: include/linux/pagemap.h:422
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
In mm/mlock.c (ffffffff811df05e)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff811e927d)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff811eecc8)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff811f018f)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff811f0791)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff811f3ac4)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map
```
```
In mm/hugetlb.c (ffffffff811fd21e)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/mempolicy.c (ffffffff811fefa1)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81205059)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff81211d84)
Location: include/linux/pagemap.h:422
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
In mm/huge_memory.c (ffffffff812180b4)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8121ad0e)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81220d70)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81227c0c)
Location: include/linux/pagemap.h:422
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
In mm/zsmalloc.c (ffffffff8122b251)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:trylock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In mm/balloon_compaction.c (ffffffff8122cee1)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In mm/page_idle.c (ffffffff8122dcbb)
Location: include/linux/pagemap.h:422
Inline: True
```
```
In fs/pipe.c (ffffffff8123b849)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff81266eb8)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - fs/splice.c:__generic_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8126ed8c)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
```
```
In fs/dax.c (ffffffff81287ab4)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - fs/dax.c:dax_fault
```
```
In fs/crypto/crypto.c (ffffffff81288d22)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
```
```
In fs/iomap.c (ffffffff8129c17d)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff812bfa46)
Location: include/linux/pagemap.h:422
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812cd93a)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/jbd2/commit.c (ffffffff81318a01)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/hugetlbfs/inode.c (ffffffff81327d55)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff8133855d)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8134a155)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814c1e3e)
Location: include/linux/pagemap.h:422
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
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
In kernel/futex.c (ffffffff8110eecb)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811a94be)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811b1138)
Location: include/linux/pagemap.h:441
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
In mm/page-writeback.c (ffffffff811bdec4)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff811c1366)
Location: include/linux/pagemap.h:441
Inline: True
```
```
In mm/truncate.c (ffffffff811c4a54)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811cb37b)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811d10b3)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff811e51a3)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811e9711)
Location: include/linux/pagemap.h:441
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
In mm/mlock.c (ffffffff811eee78)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff811fa5cd)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff811ff5f8)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff81200b53)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8120117f)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812045f7)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map
```
```
In mm/hugetlb.c (ffffffff8120dced)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/mempolicy.c (ffffffff812107e3)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81217015)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff81223fee)
Location: include/linux/pagemap.h:441
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
In mm/huge_memory.c (ffffffff8122a654)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8122e655)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff812334c0)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8123a1a3)
Location: include/linux/pagemap.h:441
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
In mm/zsmalloc.c (ffffffff8123d7b2)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:trylock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In mm/balloon_compaction.c (ffffffff8123f401)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In mm/page_idle.c (ffffffff8124020b)
Location: include/linux/pagemap.h:441
Inline: True
```
```
In fs/read_write.c (ffffffff812445d3)
Location: include/linux/pagemap.h:441
Inline: True
```
```
In fs/pipe.c (ffffffff8124e5e9)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff81278d95)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff81281f96)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/dax.c (ffffffff8129bfcf)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In fs/crypto/crypto.c (ffffffff8129d9ef)
Location: include/linux/pagemap.h:441
Inline: True
```
```
In fs/iomap.c (ffffffff812b1cad)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff812d4c56)
Location: include/linux/pagemap.h:441
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812e370a)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/jbd2/commit.c (ffffffff8132e9f5)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/hugetlbfs/inode.c (ffffffff8133daa3)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff8134e31d)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8135fa95)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814e3e2e)
Location: include/linux/pagemap.h:441
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
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
In kernel/futex.c (ffffffff811101f8)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811b09f2)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811b8589)
Location: include/linux/pagemap.h:457
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
In mm/page-writeback.c (ffffffff811c6074)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff811c9656)
Location: include/linux/pagemap.h:457
Inline: True
```
```
In mm/truncate.c (ffffffff811ccd30)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811d3f8b)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811d9aee)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff811ef06d)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811f485e)
Location: include/linux/pagemap.h:457
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
In mm/mlock.c (ffffffff811f9e45)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff812052ba)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff8120a2be)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8120b828)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8120bfce)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8120fa37)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/hugetlb.c (ffffffff81219b22)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/mempolicy.c (ffffffff8121c105)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81222add)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff8122f91c)
Location: include/linux/pagemap.h:457
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
In mm/huge_memory.c (ffffffff8123628f)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81238d9d)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8123eda0)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81245fa0)
Location: include/linux/pagemap.h:457
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
In mm/zsmalloc.c (ffffffff8124911a)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:trylock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In mm/balloon_compaction.c (ffffffff8124ad54)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In mm/page_idle.c (ffffffff8124c0ab)
Location: include/linux/pagemap.h:457
Inline: True
```
```
In fs/read_write.c (ffffffff81250024)
Location: include/linux/pagemap.h:457
Inline: True
```
```
In fs/pipe.c (ffffffff8125a5a9)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff81286305)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8129037d)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/crypto/crypto.c (ffffffff812ac6a6)
Location: include/linux/pagemap.h:457
Inline: True
```
```
In fs/iomap.c (ffffffff812befdc)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff812f1568)
Location: include/linux/pagemap.h:457
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8130794e)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/jbd2/commit.c (ffffffff81343bda)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/hugetlbfs/inode.c (ffffffff8135279c)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff81362e9d)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff81374688)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814efbdf)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
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
In kernel/futex.c (ffffffff8111b951)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811c4562)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811cccf4)
Location: include/linux/pagemap.h:470
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
In mm/page-writeback.c (ffffffff811dae84)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff811de476)
Location: include/linux/pagemap.h:470
Inline: True
```
```
In mm/truncate.c (ffffffff811e1fc4)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811e94d8)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811ef7e0)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff81206963)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8120c638)
Location: include/linux/pagemap.h:470
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
In mm/mlock.c (ffffffff81212295)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8121e26a)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff81223523)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff81224d4e)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff812255fe)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8122b2ef)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/hugetlb.c (ffffffff81234b6b)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/mempolicy.c (0)
Location: include/linux/pagemap.h:470
Inline: True
```
```
In mm/ksm.c (ffffffff8123df44)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff8124c1b3)
Location: include/linux/pagemap.h:470
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
In mm/huge_memory.c (ffffffff812550cf)
Location: include/linux/pagemap.h:470
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
In mm/khugepaged.c (ffffffff8125976a)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8125e920)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81265fdd)
Location: include/linux/pagemap.h:470
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
In mm/zsmalloc.c (ffffffff81269355)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:trylock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In mm/balloon_compaction.c (ffffffff8126afc4)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In mm/page_idle.c (ffffffff8126c48b)
Location: include/linux/pagemap.h:470
Inline: True
```
```
In mm/hmm.c (ffffffff8126d054)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_alloc_locked_page
```
```
In fs/read_write.c (ffffffff81271f19)
Location: include/linux/pagemap.h:470
Inline: True
```
```
In fs/pipe.c (ffffffff8127c8a9)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff812a8d85)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff812b30d2)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/crypto/crypto.c (ffffffff812cfec6)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
```
```
In fs/iomap.c (ffffffff812e2a50)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff8132c59e)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/jbd2/commit.c (ffffffff8136822d)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/hugetlbfs/inode.c (ffffffff813772b1)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff81387b3d)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff81399358)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8152474f)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
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
In kernel/futex.c (ffffffff81128495)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811e4a75)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811eddf4)
Location: include/linux/pagemap.h:470
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
```
```
In mm/page-writeback.c (ffffffff811fc364)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff811ffb46)
Location: include/linux/pagemap.h:470
Inline: True
```
```
In mm/truncate.c (ffffffff8120372a)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8120a9e2)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81210cc2)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff8122644f)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8122d27e)
Location: include/linux/pagemap.h:470
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
In mm/mlock.c (ffffffff81232fcc)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff812400e8)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff8124638c)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff812472fb)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff81247b9f)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8124c75a)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/hugetlb.c (ffffffff81257ac7)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff81261839)
Location: include/linux/pagemap.h:470
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
In mm/migrate.c (ffffffff8126fcd7)
Location: include/linux/pagemap.h:470
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
In mm/huge_memory.c (ffffffff81278f2a)
Location: include/linux/pagemap.h:470
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
In mm/khugepaged.c (ffffffff8127b58d)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81282b28)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8128a135)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff8128e315)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:trylock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In mm/balloon_compaction.c (ffffffff8128f9b4)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In mm/page_idle.c (ffffffff81291059)
Location: include/linux/pagemap.h:470
Inline: True
```
```
In mm/hmm.c (ffffffff81291e14)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_alloc_locked_page
```
```
In fs/read_write.c (ffffffff81297ec3)
Location: include/linux/pagemap.h:470
Inline: True
```
```
In fs/pipe.c (ffffffff812a37f9)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff812cf90c)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff812da2d3)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/crypto/crypto.c (ffffffff812fa79a)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
```
```
In fs/iomap.c (ffffffff8130dc68)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/iomap.c:page_cache_seek_hole_data
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff8135ab65)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/jbd2/commit.c (ffffffff81396aba)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/hugetlbfs/inode.c (ffffffff813a5fd2)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff813b6803)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff813c8e08)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8155a4be)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
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
In kernel/futex.c (ffffffff81133d77)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811f5138)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff811ff3f3)
Location: include/linux/pagemap.h:470
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
```
```
In mm/page-writeback.c (ffffffff8120e864)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff812123c6)
Location: include/linux/pagemap.h:470
Inline: True
```
```
In mm/truncate.c (ffffffff81215ffa)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8121d6e5)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81222cec)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff8123a7ad)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8123d1e5)
Location: include/linux/pagemap.h:470
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
In mm/mlock.c (ffffffff812467a1)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff812547e8)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff8125a7ae)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8125b750)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8125c16f)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81260ca4)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8126c180)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff8127609d)
Location: include/linux/pagemap.h:470
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
In mm/migrate.c (ffffffff81284381)
Location: include/linux/pagemap.h:470
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
In mm/huge_memory.c (ffffffff8128d5da)
Location: include/linux/pagemap.h:470
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
In mm/khugepaged.c (ffffffff81290084)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81296cc8)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8129f0df)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff812a3079)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff812a48d4)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In mm/page_idle.c (ffffffff812a6079)
Location: include/linux/pagemap.h:470
Inline: True
```
```
In mm/hmm.c (ffffffff812a6e04)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_alloc_locked_page
```
```
In fs/read_write.c (ffffffff812acf93)
Location: include/linux/pagemap.h:470
Inline: True
```
```
In fs/pipe.c (ffffffff812b8949)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff812e4c7c)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff812ef7b1)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/crypto/crypto.c (ffffffff8130fb1a)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
```
```
In fs/iomap.c (ffffffff81324b23)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/iomap.c:page_cache_seek_hole_data
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff81372e25)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/jbd2/commit.c (ffffffff813af835)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/hugetlbfs/inode.c (ffffffff813be9f8)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff813cfd53)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff813e2188)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81571dce)
Location: include/linux/pagemap.h:470
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
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
In kernel/futex.c (ffffffff8113ecba)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff8120ce3d)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81216485)
Location: include/linux/pagemap.h:457
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
```
```
In mm/page-writeback.c (ffffffff8121e385)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff81221d87)
Location: include/linux/pagemap.h:457
Inline: True
```
```
In mm/truncate.c (ffffffff812259fa)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8122d158)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff812330ec)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff8124bac1)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124ee85)
Location: include/linux/pagemap.h:457
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
In mm/mlock.c (ffffffff81258a59)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff81266a91)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff81275867)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff812768b8)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8127733e)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8127bbdb)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8128753e)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff81291731)
Location: include/linux/pagemap.h:457
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
In mm/migrate.c (ffffffff8129fa32)
Location: include/linux/pagemap.h:457
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
In mm/huge_memory.c (ffffffff812a7f6a)
Location: include/linux/pagemap.h:457
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
In mm/khugepaged.c (ffffffff812aae8f)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812b2a21)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812ba4c8)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff812be394)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff812bfd02)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff812c179e)
Location: include/linux/pagemap.h:457
Inline: True
```
```
In fs/read_write.c (ffffffff812c9bda)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffff812d551c)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff8130346e)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff81310ffb)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffffffff8134b3b0)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffff8134e2e2)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff8139c282)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/jbd2/commit.c (ffffffff813d9d85)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/hugetlbfs/inode.c (ffffffff813e91bb)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff813fa938)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8140d9c9)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a228f)
Location: include/linux/pagemap.h:457
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
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
In kernel/futex.c (ffffffff8114a6e4)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff8121a11a)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81223d95)
Location: include/linux/pagemap.h:467
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
```
```
In mm/page-writeback.c (ffffffff8122be25)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff8122f837)
Location: include/linux/pagemap.h:467
Inline: True
```
```
In mm/truncate.c (ffffffff8123384a)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8123b378)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8124130c)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff81259fb1)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125d465)
Location: include/linux/pagemap.h:467
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
In mm/mlock.c (ffffffff81266f29)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff812753b1)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff81284837)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff812863a8)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff81286e1e)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8128b6bb)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8129714e)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff812a14b1)
Location: include/linux/pagemap.h:467
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
In mm/migrate.c (ffffffff812aff6a)
Location: include/linux/pagemap.h:467
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
In mm/huge_memory.c (ffffffff812b9455)
Location: include/linux/pagemap.h:467
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
In mm/khugepaged.c (ffffffff812bc5b6)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812c4461)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812cbbf8)
Location: include/linux/pagemap.h:467
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
In mm/zsmalloc.c (ffffffff812d0284)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff812d1c52)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff812d36ce)
Location: include/linux/pagemap.h:467
Inline: True
```
```
In fs/read_write.c (ffffffff812db6b6)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffff812e708c)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff813164ee)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff81323fdb)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffffffff81363660)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffff813665d2)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813b4d92)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/jbd2/commit.c (ffffffff813f3db4)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/hugetlbfs/inode.c (ffffffff8140325b)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff81414808)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff81426bc9)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815c310f)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
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
In kernel/futex.c (ffffffff8115b234)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81246aa0)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81252c3c)
Location: include/linux/pagemap.h:508
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
```
```
In mm/page-writeback.c (ffffffff812587b5)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff8125c937)
Location: include/linux/pagemap.h:508
Inline: True
```
```
In mm/truncate.c (ffffffff81260f6f)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81268497)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff8126db5e)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff812884d1)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8128becf)
Location: include/linux/pagemap.h:508
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
In mm/mlock.c (ffffffff8129719f)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff812a6825)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff812b69e2)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff812b879e)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff812b939d)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812be59d)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff812ca746)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_page_mapping_lock_write
```
```
In mm/ksm.c (ffffffff812d63c4)
Location: include/linux/pagemap.h:508
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
In mm/migrate.c (ffffffff812e39e7)
Location: include/linux/pagemap.h:508
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
In mm/huge_memory.c (ffffffff812edfba)
Location: include/linux/pagemap.h:508
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
In mm/khugepaged.c (ffffffff812f197b)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812fa329)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81302650)
Location: include/linux/pagemap.h:508
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
In mm/zsmalloc.c (ffffffff81306847)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In mm/balloon_compaction.c (ffffffff81307b83)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff81309182)
Location: include/linux/pagemap.h:508
Inline: True
```
```
In fs/read_write.c (ffffffff81311663)
Location: include/linux/pagemap.h:508
Inline: True
```
```
In fs/pipe.c (ffffffff8131e867)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/splice.c (ffffffff8135061e)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/buffer.c (ffffffff8135d684)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffffffff813aa471)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffff813ae143)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff8140021e)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/jbd2/commit.c (ffffffff8143f9b6)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/hugetlbfs/inode.c (ffffffff81450ede)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff81462b38)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8147715d)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8166d2ce)
Location: include/linux/pagemap.h:508
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
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
In kernel/futex.c (ffffffff81157375)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81251103)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8125d80c)
Location: include/linux/pagemap.h:597
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
In mm/page-writeback.c (ffffffff81262dc5)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff81266cb7)
Location: include/linux/pagemap.h:597
Inline: True
```
```
In mm/truncate.c (ffffffff8126b36f)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81272f35)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page_prepare
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff8127989e)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff812921ba)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81296e4f)
Location: include/linux/pagemap.h:597
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
In mm/mlock.c (ffffffff812a214f)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff812b1cc5)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff812c2c32)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff812c3e07)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff812c4d2d)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812ca174)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff812d6376)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff812e1ed8)
Location: include/linux/pagemap.h:597
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
In mm/migrate.c (ffffffff812eee57)
Location: include/linux/pagemap.h:597
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
In mm/huge_memory.c (ffffffff812f962a)
Location: include/linux/pagemap.h:597
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
In mm/khugepaged.c (ffffffff812fdeff)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff8130622a)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8130dafc)
Location: include/linux/pagemap.h:597
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
In mm/zsmalloc.c (ffffffff81312587)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In mm/balloon_compaction.c (ffffffff813138b3)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff81314ff2)
Location: include/linux/pagemap.h:597
Inline: True
```
```
In fs/pipe.c (ffffffff81329dc7)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/splice.c (ffffffff8135d6ae)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff813669e3)
Location: include/linux/pagemap.h:597
Inline: True
```
```
In fs/buffer.c (ffffffff8136b265)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffffffff813bbac1)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffff813bf7b3)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff81412a26)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/jbd2/commit.c (ffffffff8145ba86)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/hugetlbfs/inode.c (ffffffff8146d3fe)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff8147e638)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff81491f9d)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8168d9ee)
Location: include/linux/pagemap.h:597
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
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
In kernel/futex.c (ffffffff81158789)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81255203)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812605d3)
Location: include/linux/pagemap.h:613
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
In mm/page-writeback.c (ffffffff812677e5)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff8126b6e7)
Location: include/linux/pagemap.h:613
Inline: True
```
```
In mm/truncate.c (ffffffff81270464)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81278222)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff8127e9fe)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff81297efb)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129ca9f)
Location: include/linux/pagemap.h:613
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
In mm/mlock.c (ffffffff812a79df)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff812b7395)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff812c9aae)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff812cac0a)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff812cb9bd)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812d0c57)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff812dd520)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff812e9693)
Location: include/linux/pagemap.h:613
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
In mm/migrate.c (ffffffff812f4fe7)
Location: include/linux/pagemap.h:613
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
In mm/huge_memory.c (ffffffff81300162)
Location: include/linux/pagemap.h:613
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
In mm/khugepaged.c (ffffffff813048ac)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff8130c6fe)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81313d0e)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/zsmalloc.c (ffffffff81318607)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:trylock_zspage
```
```
In mm/balloon_compaction.c (ffffffff81319a43)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff8131b732)
Location: include/linux/pagemap.h:613
Inline: True
```
```
In fs/pipe.c (ffffffff8132fd87)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/splice.c (ffffffff8136414e)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff8136d293)
Location: include/linux/pagemap.h:613
Inline: True
```
```
In fs/buffer.c (ffffffff81371b05)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffffffff813c2bb1)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff81418e86)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/jbd2/commit.c (ffffffff814613c6)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/hugetlbfs/inode.c (ffffffff81472a81)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff81484108)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8149715d)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff816706de)
Location: include/linux/pagemap.h:613
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int trylock_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8117d696)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81290c45)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8129cfc4)
Location: include/linux/pagemap.h:612
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
In mm/page-writeback.c (ffffffff812a4345)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff812a83c7)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - mm/readahead.c:read_cache_pages_invalidate_page
```
```
In mm/truncate.c (ffffffff812ae0fa)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff812b5ebb)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff812bc57d)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff812d893b)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812dd86f)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mlock.c (ffffffff812e8fff)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff812f99e7)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff8130eace)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff8130fc09)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff813109cf)
Location: include/linux/pagemap.h:612
Inline: True
```
```
In mm/swapfile.c (ffffffff8131632e)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff813246c9)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff813315cc)
Location: include/linux/pagemap.h:612
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
In mm/migrate.c (ffffffff8133f5e7)
Location: include/linux/pagemap.h:612
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
In mm/huge_memory.c (ffffffff81349db2)
Location: include/linux/pagemap.h:612
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
In mm/khugepaged.c (ffffffff8134e610)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff813578fe)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8135efee)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/zsmalloc.c (ffffffff81364b3a)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:trylock_zspage
```
```
In mm/balloon_compaction.c (ffffffff81366233)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/page_idle.c (ffffffff81368a02)
Location: include/linux/pagemap.h:612
Inline: True
```
```
In fs/pipe.c (ffffffff8137d547)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/splice.c (ffffffff813b293e)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff813bbf73)
Location: include/linux/pagemap.h:612
Inline: True
```
```
In fs/buffer.c (ffffffff813c063b)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffffffff81412d88)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff8146c0ba)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/jbd2/commit.c (ffffffff814b68b6)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/hugetlbfs/inode.c (ffffffff814c954e)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff814db788)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff814eea4d)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff816e49ae)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff812dd040-ffffffff812dd05b: trylock_page (STB_LOCAL)
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
In mm/vmscan.c (ffffffff8130f18f)
Location: include/linux/pagemap.h:911
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
```
```
In mm/compaction.c (ffffffff813312bb)
Location: include/linux/pagemap.h:911
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff81342b72)
Location: include/linux/pagemap.h:911
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/madvise.c (ffffffff81376908)
Location: include/linux/pagemap.h:911
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8137b724)
Location: include/linux/pagemap.h:911
Inline: True
```
```
In mm/swapfile.c (ffffffff8137fd38)
Location: include/linux/pagemap.h:911
Inline: True
Inline callers:
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff81392c47)
Location: include/linux/pagemap.h:911
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (ffffffff813a2605)
Location: include/linux/pagemap.h:911
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff813b3990)
Location: include/linux/pagemap.h:911
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff813b6f12)
Location: include/linux/pagemap.h:911
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c07b1)
Location: include/linux/pagemap.h:911
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff813c5178)
Location: include/linux/pagemap.h:911
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/zsmalloc.c (ffffffff813e2873)
Location: include/linux/pagemap.h:911
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff813e321a)
Location: include/linux/pagemap.h:911
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
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
In mm/compaction.c (ffffffff813a7f80)
Location: include/linux/pagemap.h:907
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff813b644e)
Location: include/linux/pagemap.h:907
Inline: True
Inline callers:
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/madvise.c (ffffffff813f4d07)
Location: include/linux/pagemap.h:907
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff814115f3)
Location: include/linux/pagemap.h:907
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (ffffffff81422295)
Location: include/linux/pagemap.h:907
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff814334a8)
Location: include/linux/pagemap.h:907
Inline: True
Inline callers:
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff81438800)
Location: include/linux/pagemap.h:907
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81442ea4)
Location: include/linux/pagemap.h:907
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814494e1)
Location: include/linux/pagemap.h:907
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/zsmalloc.c (ffffffff81469dd3)
Location: include/linux/pagemap.h:907
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff8146ab96)
Location: include/linux/pagemap.h:907
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
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
In mm/memory.c (ffffffff813ebdb7)
Location: include/linux/pagemap.h:928
Inline: True
Inline callers:
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/ksm.c (ffffffff81456f7e)
Location: include/linux/pagemap.h:928
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate_device.c (ffffffff8146e500)
Location: include/linux/pagemap.h:928
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81478774)
Location: include/linux/pagemap.h:928
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff8147f6d2)
Location: include/linux/pagemap.h:928
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff81488efb)
Location: include/linux/pagemap.h:928
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/zsmalloc.c (ffffffff8149efd3)
Location: include/linux/pagemap.h:928
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff8149fa26)
Location: include/linux/pagemap.h:928
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
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
In mm/memory.c (ffffffff81416c8c)
Location: include/linux/pagemap.h:1017
Inline: True
Inline callers:
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/ksm.c (ffffffff81491a7c)
Location: include/linux/pagemap.h:1017
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate_device.c (ffffffff8149ee90)
Location: include/linux/pagemap.h:1017
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff814adba5)
Location: include/linux/pagemap.h:1017
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff814b8f61)
Location: include/linux/pagemap.h:1017
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/zsmalloc.c (ffffffff814ce733)
Location: include/linux/pagemap.h:1017
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff814cf176)
Location: include/linux/pagemap.h:1017
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
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
In kernel/futex.c (ffff8000101b7b74)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffff8000102a552c)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffff8000102b1674)
Location: include/linux/pagemap.h:467
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
```
```
In mm/page-writeback.c (ffff8000102bc36c)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffff8000102bf254)
Location: include/linux/pagemap.h:467
Inline: True
```
```
In mm/truncate.c (ffff8000102c3d20)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffff8000102cc474)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffff8000102d36f0)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffff8000102f2140)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffff8000102f49ac)
Location: include/linux/pagemap.h:467
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
In mm/mlock.c (ffff8000102fe180)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffff80001030b278)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffff80001031eb84)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffff8000103209d0)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffff8000103217c4)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffff800010326984)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffff800010334f60)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffff800010340de8)
Location: include/linux/pagemap.h:467
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
In mm/migrate.c (ffff80001035123c)
Location: include/linux/pagemap.h:467
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
In mm/huge_memory.c (ffff800010359bd0)
Location: include/linux/pagemap.h:467
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
In mm/khugepaged.c (ffff80001035d338)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffff800010367060)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffff800010370248)
Location: include/linux/pagemap.h:467
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
In mm/zsmalloc.c (ffff800010374f0c)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffff8000103779f8)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffff800010379068)
Location: include/linux/pagemap.h:467
Inline: True
```
```
In fs/read_write.c (ffff80001038058c)
Location: include/linux/pagemap.h:467
Inline: True
```
```
In fs/pipe.c (ffff80001038fc40)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffff8000103ce28c)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffff8000103dd33c)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffff80001042a3b8)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffff80001042dd50)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffff800010489530)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/jbd2/commit.c (ffff8000104cf3a0)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/hugetlbfs/inode.c (ffff8000104e1dfc)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffff8000104f5f10)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffff80001050b1ac)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffff80001074c090)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
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
In kernel/futex.c (c0401908)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (c04d4920)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (c04de120)
Location: include/linux/pagemap.h:467
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
```
```
In mm/page-writeback.c (c04e6d0c)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (c04eaaf8)
Location: include/linux/pagemap.h:467
Inline: True
```
```
In mm/truncate.c (c04ee8b0)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (c04f61e8)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (c04fb998)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (c0514354)
Location: include/linux/pagemap.h:467
Inline: True
```
```
In mm/memory.c (c0516b5c)
Location: include/linux/pagemap.h:467
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
In mm/mlock.c (c051ce48)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (c05276e4)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (c053779c)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (c05393a8)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (c0539fb8)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (c053e158)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/ksm.c (c0547030)
Location: include/linux/pagemap.h:467
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
In mm/migrate.c (c0552880)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
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
In mm/memcontrol.c (c05587f4)
Location: include/linux/pagemap.h:467
Inline: True
```
```
In mm/zsmalloc.c (c056126c)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (c0563478)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (c05645bc)
Location: include/linux/pagemap.h:467
Inline: True
```
```
In fs/read_write.c (c056b51c)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (c0576a48)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (c05a99e4)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (c05b6828)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (c05f31c8)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (c05f6cfc)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (c064b9f8)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/jbd2/commit.c (c0692068)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/ecryptfs/mmap.c (c06b3788)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (c06c683c)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (c08cecd8)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
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
In kernel/futex.c (c00000000021d018)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (c000000000358240)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (c0000000003670f8)
Location: include/linux/pagemap.h:467
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
```
```
In mm/page-writeback.c (c0000000003730fc)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (c000000000377a08)
Location: include/linux/pagemap.h:467
Inline: True
```
```
In mm/truncate.c (c00000000037e168)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (c00000000038991c)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (c000000000392780)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (c0000000003b80fc)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003bb688)
Location: include/linux/pagemap.h:467
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
In mm/mlock.c (c0000000003c98a8)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (c0000000003db380)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (c0000000003f34cc)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (c0000000003f5e00)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (c0000000003f6f08)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (c0000000003fd3d0)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (c00000000040e6a8)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (c00000000041e648)
Location: include/linux/pagemap.h:467
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
In mm/migrate.c (c0000000004362e0)
Location: include/linux/pagemap.h:467
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
In mm/huge_memory.c (c000000000443344)
Location: include/linux/pagemap.h:467
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
In mm/khugepaged.c (c0000000004486c4)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (c0000000004544c0)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (c000000000460c48)
Location: include/linux/pagemap.h:467
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
In mm/zsmalloc.c (c000000000467600)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (c00000000046a0f0)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/page_idle.c (c00000000046c2a0)
Location: include/linux/pagemap.h:467
Inline: True
```
```
In fs/read_write.c (c00000000047712c)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (c0000000004873b0)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (c0000000004ce900)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (c0000000004e2a7c)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (c00000000053acd4)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (c00000000053f028)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (c0000000005b0564)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/jbd2/commit.c (c000000000608120)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/hugetlbfs/inode.c (c00000000061e7a4)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (c000000000636d0c)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (c0000000006509a4)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (c0000000008ae110)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
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
In kernel/futex.c (ffffffe00013c85e)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/filemap.c (ffffffe0001d6f12)
Location: include/linux/pagemap.h:467
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
```
```
In mm/page-writeback.c (ffffffe0001ddaa4)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffe0001e1340)
Location: include/linux/pagemap.h:467
Inline: True
```
```
In mm/truncate.c (ffffffe0001e495a)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffe0001eaf62)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffe0001ef7b0)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffe00020481c)
Location: include/linux/pagemap.h:467
Inline: True
```
```
In mm/memory.c (ffffffe000205eae)
Location: include/linux/pagemap.h:467
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
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffe000214c70)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffe0002205d4)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffe000222008)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffe000222a0c)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffe000226a7c)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffe00023175a)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffe00023554e)
Location: include/linux/pagemap.h:467
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
In mm/migrate.c (ffffffe00023fc4e)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
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
In mm/memcontrol.c (ffffffe0002452f2)
Location: include/linux/pagemap.h:467
Inline: True
```
```
In mm/zsmalloc.c (ffffffe00024dd9a)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffe00024f6c0)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffe000250894)
Location: include/linux/pagemap.h:467
Inline: True
```
```
In fs/read_write.c (ffffffe000255bcc)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffe00025f6c0)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffe00028a270)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffe000295412)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffffffe0002c7f02)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffe0002ca780)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffe000310cf8)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/jbd2/commit.c (ffffffe000346c80)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/hugetlbfs/inode.c (ffffffe0003558ec)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffe000364d1a)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffe000375ecc)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffe0004f9e6a)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
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
In kernel/futex.c (ffffffff81142d04)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff8121276a)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8121c3e5)
Location: include/linux/pagemap.h:467
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
```
```
In mm/page-writeback.c (ffffffff81224475)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff81227e87)
Location: include/linux/pagemap.h:467
Inline: True
```
```
In mm/truncate.c (ffffffff8122be9a)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff812339c8)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8123995c)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff81252601)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81255ab5)
Location: include/linux/pagemap.h:467
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
In mm/mlock.c (ffffffff8125f579)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8126da01)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff8127ce87)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff8127e9f8)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8127f46e)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81283c9b)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8128f72e)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff81299a91)
Location: include/linux/pagemap.h:467
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
In mm/migrate.c (ffffffff812a854a)
Location: include/linux/pagemap.h:467
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
In mm/huge_memory.c (ffffffff812b1a35)
Location: include/linux/pagemap.h:467
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
In mm/khugepaged.c (ffffffff812b4b96)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812bca41)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812c41d8)
Location: include/linux/pagemap.h:467
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
In mm/zsmalloc.c (ffffffff812c8864)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff812ca232)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff812cbcae)
Location: include/linux/pagemap.h:467
Inline: True
```
```
In fs/read_write.c (ffffffff812d3c96)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffff812df66c)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff8130eace)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8131c5bb)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffffffff8135bc40)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffff8135ebb2)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813ad372)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/jbd2/commit.c (ffffffff813ec394)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/hugetlbfs/inode.c (ffffffff813fb83b)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff8140cde8)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8141f1a9)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b725f)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
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
In kernel/futex.c (ffffffff81136064)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff812054fa)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8120f5cf)
Location: include/linux/pagemap.h:467
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
```
```
In mm/page-writeback.c (ffffffff81217625)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff8121afc7)
Location: include/linux/pagemap.h:467
Inline: True
```
```
In mm/truncate.c (ffffffff8121ef7a)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81226a3c)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8122c98c)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff81245b1a)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81248195)
Location: include/linux/pagemap.h:467
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
In mm/mlock.c (ffffffff81251999)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8125fa31)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff8126ed3b)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff81270828)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8127128e)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81275b24)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff812813f7)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff8128b651)
Location: include/linux/pagemap.h:467
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
In mm/migrate.c (ffffffff81299f0a)
Location: include/linux/pagemap.h:467
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
In mm/huge_memory.c (ffffffff812a2e05)
Location: include/linux/pagemap.h:467
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
In mm/khugepaged.c (ffffffff812a5be8)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812adba1)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812b5218)
Location: include/linux/pagemap.h:467
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
In mm/zsmalloc.c (ffffffff812b98a4)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff812bb272)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff812bcb1e)
Location: include/linux/pagemap.h:467
Inline: True
```
```
In fs/read_write.c (ffffffff812c4916)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffff812d02ac)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff812ff6de)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8130d15b)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffffffff8134c8e0)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffff8134f852)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff8139de02)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/jbd2/commit.c (ffffffff813dce14)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/hugetlbfs/inode.c (ffffffff813ec2bb)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff813fd868)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8140fc29)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a603f)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
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
In kernel/futex.c (ffffffff81140bb4)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff8121050a)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8121a185)
Location: include/linux/pagemap.h:467
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
```
```
In mm/page-writeback.c (ffffffff81222215)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff81225c27)
Location: include/linux/pagemap.h:467
Inline: True
```
```
In mm/truncate.c (ffffffff81229c3a)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81231768)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff812376fc)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff812503a1)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81253855)
Location: include/linux/pagemap.h:467
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
In mm/mlock.c (ffffffff8125d319)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8126b7a1)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff8127ac27)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff8127c798)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8127d20e)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81281aab)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8128d53e)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff812978a1)
Location: include/linux/pagemap.h:467
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
In mm/migrate.c (ffffffff812a635a)
Location: include/linux/pagemap.h:467
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
In mm/huge_memory.c (ffffffff812af845)
Location: include/linux/pagemap.h:467
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
In mm/khugepaged.c (ffffffff812b29a6)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812ba851)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812c1fe8)
Location: include/linux/pagemap.h:467
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
In mm/zsmalloc.c (ffffffff812c6674)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff812c8042)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff812c9abe)
Location: include/linux/pagemap.h:467
Inline: True
```
```
In fs/read_write.c (ffffffff812d1aa6)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffff812dd47c)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff8130c8be)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8131a08b)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffffffff81359710)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffff8135c682)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813aabd2)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/jbd2/commit.c (ffffffff813e9714)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/hugetlbfs/inode.c (ffffffff813f8bbb)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff8140a168)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8141b349)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b77ef)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
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
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff8121f452)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8122925c)
Location: include/linux/pagemap.h:467
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
```
```
In mm/page-writeback.c (ffffffff81231655)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff81234f27)
Location: include/linux/pagemap.h:467
Inline: True
```
```
In mm/truncate.c (ffffffff81239035)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81240b91)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81246c36)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff8125fd25)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8126321e)
Location: include/linux/pagemap.h:467
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
In mm/mlock.c (ffffffff8126ccff)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8127b131)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff8128a808)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff8128c368)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8128cdce)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812917b7)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8129d2ec)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff812a7678)
Location: include/linux/pagemap.h:467
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
In mm/migrate.c (ffffffff812b6675)
Location: include/linux/pagemap.h:467
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
In mm/huge_memory.c (ffffffff812bfb85)
Location: include/linux/pagemap.h:467
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
In mm/khugepaged.c (ffffffff812c2be3)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812caf91)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff812d2a83)
Location: include/linux/pagemap.h:467
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
In mm/zsmalloc.c (ffffffff812d7edd)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff812d8d52)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff812da7ae)
Location: include/linux/pagemap.h:467
Inline: True
```
```
In fs/read_write.c (ffffffff812e28c3)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffff812ee3f5)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff8131e0de)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8132bd4e)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffffffff8136ce0f)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffff8136fdaf)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813bf51d)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/jbd2/commit.c (ffffffff813ff018)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/hugetlbfs/inode.c (ffffffff8140ea06)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff8141fe62)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff81432374)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815d125a)
Location: include/linux/pagemap.h:467
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
