# Function: <code>lock_page</code>

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
In kernel/futex.c (ffffffff810ffab2)
Location: include/linux/pagemap.h:454
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff8118776a)
Location: include/linux/pagemap.h:454
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8118db7b)
Location: include/linux/pagemap.h:454
Inline: True
Inline callers:
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:do_read_cache_page
```
```
In mm/page-writeback.c (ffffffff81198b1f)
Location: include/linux/pagemap.h:454
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff8119e8fb)
Location: include/linux/pagemap.h:454
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811a0b3c)
Location: include/linux/pagemap.h:454
Inline: True
```
```
In mm/shmem.c (ffffffff811a9167)
Location: include/linux/pagemap.h:454
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff811bbdf8)
Location: include/linux/pagemap.h:454
Inline: True
Inline callers:
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mlock.c (ffffffff811c2efc)
Location: include/linux/pagemap.h:454
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/swapfile.c (ffffffff811d476e)
Location: include/linux/pagemap.h:454
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff811df275)
Location: include/linux/pagemap.h:454
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (ffffffff811e4b61)
Location: include/linux/pagemap.h:454
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/migrate.c (ffffffff811f2192)
Location: include/linux/pagemap.h:454
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/memory-failure.c (ffffffff81201cfd)
Location: include/linux/pagemap.h:454
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/balloon_compaction.c (ffffffff812075e1)
Location: include/linux/pagemap.h:454
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_putback
```
```
In fs/pipe.c (ffffffff81214aac)
Location: include/linux/pagemap.h:454
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff8123e7a4)
Location: include/linux/pagemap.h:454
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:__generic_file_splice_read
```
```
In fs/buffer.c (ffffffff812459f2)
Location: include/linux/pagemap.h:454
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:nobh_truncate_page
```
```
In fs/ext4/file.c (ffffffff81292483)
Location: include/linux/pagemap.h:454
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81297d53)
Location: include/linux/pagemap.h:454
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/ext4/crypto.c (ffffffff812e548b)
Location: include/linux/pagemap.h:454
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_encrypt
```
```
In fs/hugetlbfs/inode.c (ffffffff812f399b)
Location: include/linux/pagemap.h:454
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff81304498)
Location: include/linux/pagemap.h:454
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff81316210)
Location: include/linux/pagemap.h:454
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81473584)
Location: include/linux/pagemap.h:454
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
In kernel/futex.c (ffffffff81107706)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81199d5c)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811a1417)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
```
```
In mm/page-writeback.c (ffffffff811ad95f)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff811b43af)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811b6f5c)
Location: include/linux/pagemap.h:431
Inline: True
```
```
In mm/shmem.c (ffffffff811c0ac7)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff811d5183)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811d7023)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff811df059)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/swapfile.c (ffffffff811f3abf)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811fd877)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/mempolicy.c (ffffffff811fef9c)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81205054)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff812124bb)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812180af)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memory-failure.c (ffffffff81227c07)
Location: include/linux/pagemap.h:431
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
In mm/zsmalloc.c (ffffffff8122b8d1)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
```
```
In fs/pipe.c (ffffffff8123b844)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff81266eb3)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - fs/splice.c:__generic_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8126ed87)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
```
```
In fs/dax.c (ffffffff81287aaf)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - fs/dax.c:dax_fault
```
```
In fs/crypto/crypto.c (ffffffff81288d1d)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
```
```
In fs/iomap.c (ffffffff8129c178)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff812bfa41)
Location: include/linux/pagemap.h:431
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812cd935)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff81327d50)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff81338558)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8134a150)
Location: include/linux/pagemap.h:431
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814c1e39)
Location: include/linux/pagemap.h:431
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
In kernel/futex.c (ffffffff8110eec6)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811a94b9)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811b1133)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
```
```
In mm/page-writeback.c (ffffffff811bdebf)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff811c4a4f)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811c755c)
Location: include/linux/pagemap.h:450
Inline: True
```
```
In mm/shmem.c (ffffffff811d10ae)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff811e519e)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811e937e)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff811eee73)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/swapfile.c (ffffffff812045f2)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8120e340)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/mempolicy.c (ffffffff812107de)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81217010)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff812246aa)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff8122a64f)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memory-failure.c (ffffffff8123a19e)
Location: include/linux/pagemap.h:450
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
In mm/zsmalloc.c (ffffffff8123de31)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
```
```
In fs/read_write.c (ffffffff812445ce)
Location: include/linux/pagemap.h:450
Inline: True
```
```
In fs/pipe.c (ffffffff8124e5e4)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff81278d90)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff81281f91)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/dax.c (ffffffff8129bfca)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In fs/crypto/crypto.c (ffffffff8129d9ea)
Location: include/linux/pagemap.h:450
Inline: True
```
```
In fs/iomap.c (ffffffff812b1ca8)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff812d4c51)
Location: include/linux/pagemap.h:450
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812e3705)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff8133da9e)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff8134e318)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8135fa90)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814e3e29)
Location: include/linux/pagemap.h:450
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void lock_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811101f3)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811b09ed)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811b8584)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
```
```
In mm/page-writeback.c (ffffffff811c606f)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff811ccd2b)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811cfc5a)
Location: include/linux/pagemap.h:466
Inline: True
```
```
In mm/shmem.c (ffffffff811d9ae9)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff811ef068)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811f44ca)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff811f9e40)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/swapfile.c (ffffffff8120fa32)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81218b86)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/mempolicy.c (ffffffff8121c100)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81222ad8)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff8122fe92)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
Direct callers:
  - mm/migrate.c:move_to_new_page
```
```
In mm/huge_memory.c (ffffffff8123628a)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memory-failure.c (ffffffff81245f9b)
Location: include/linux/pagemap.h:466
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
In mm/zsmalloc.c (ffffffff812497e1)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
```
```
In fs/read_write.c (ffffffff8125001f)
Location: include/linux/pagemap.h:466
Inline: True
```
```
In fs/pipe.c (ffffffff8125a5a4)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff81286300)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff81290378)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/crypto/crypto.c (ffffffff812ac6a1)
Location: include/linux/pagemap.h:466
Inline: True
```
```
In fs/iomap.c (ffffffff812befd7)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/file.c (ffffffff812f1563)
Location: include/linux/pagemap.h:466
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81307949)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff81352797)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff81362e98)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff81374683)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814efbda)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff8122d910-ffffffff8122d941: lock_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void lock_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111b94c)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811c455d)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811cccef)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
```
```
In mm/page-writeback.c (ffffffff811dae7f)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff811e1fbf)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811e50dd)
Location: include/linux/pagemap.h:479
Inline: True
```
```
In mm/shmem.c (ffffffff811ef7db)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff8120695e)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8120c1e7)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff81212290)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/swapfile.c (ffffffff8122b2ea)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81233b37)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/mempolicy.c (0)
Location: include/linux/pagemap.h:479
Inline: False
```
```
In mm/ksm.c (ffffffff8123df3f)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff8124d99d)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
Direct callers:
  - mm/migrate.c:move_to_new_page
```
```
In mm/huge_memory.c (ffffffff81253932)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memory-failure.c (ffffffff81265fd8)
Location: include/linux/pagemap.h:479
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
In mm/zsmalloc.c (ffffffff81269a41)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
```
```
In mm/hmm.c (ffffffff8126d04f)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_alloc_locked_page
```
```
In fs/read_write.c (ffffffff81271f14)
Location: include/linux/pagemap.h:479
Inline: True
```
```
In fs/pipe.c (ffffffff8127c8a4)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff812a8d80)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff812b30cd)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/crypto/crypto.c (ffffffff812cfec1)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
```
```
In fs/iomap.c (ffffffff812e2a4b)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff8132c599)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff813772ac)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff81387b38)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff81399353)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8152474a)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
**Symbols:**

```
ffffffff81249240-ffffffff81249271: lock_page (STB_LOCAL)
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
In kernel/futex.c (ffffffff81128490)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811e4a70)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811eddef)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff811fc355)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff81203725)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81206880)
Location: include/linux/pagemap.h:479
Inline: True
```
```
In mm/shmem.c (ffffffff81210cbd)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff8122644a)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8122cbde)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff81232fc7)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/swapfile.c (ffffffff8124c755)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81256a34)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff81261834)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff8127116f)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff81277816)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memory-failure.c (ffffffff8128a130)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff8128e3d1)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
```
```
In mm/hmm.c (ffffffff81291e0f)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_alloc_locked_page
```
```
In fs/read_write.c (ffffffff81297ebe)
Location: include/linux/pagemap.h:479
Inline: True
```
```
In fs/pipe.c (ffffffff812a37f4)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff812cf907)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff812da2ce)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/crypto/crypto.c (ffffffff812fa795)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
```
```
In fs/iomap.c (ffffffff8130dc63)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/iomap.c:page_cache_seek_hole_data
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff8135ab60)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff813a5fcd)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff813b67fe)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff813c8e03)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8155a4b9)
Location: include/linux/pagemap.h:479
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
In kernel/futex.c (ffffffff81133d72)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811f5133)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff811ff3ee)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff8120e855)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff81215ff5)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81219442)
Location: include/linux/pagemap.h:479
Inline: True
```
```
In mm/shmem.c (ffffffff81222ce7)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff8123a7a8)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8123d1e0)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff8124679c)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/swapfile.c (ffffffff81260c9f)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8126af94)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff81276098)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff8128577b)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff8128be33)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memory-failure.c (ffffffff8129f0da)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff812a3074)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In mm/hmm.c (ffffffff812a6dff)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_alloc_locked_page
```
```
In fs/read_write.c (ffffffff812acf8e)
Location: include/linux/pagemap.h:479
Inline: True
```
```
In fs/pipe.c (ffffffff812b8944)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff812e4c77)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff812ef7ac)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/crypto/crypto.c (ffffffff8130fb15)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
```
```
In fs/iomap.c (ffffffff81324b1e)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/iomap.c:page_cache_seek_hole_data
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff81372e20)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff813be9f3)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff813cfd4e)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff813e2183)
Location: include/linux/pagemap.h:479
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81571dc9)
Location: include/linux/pagemap.h:479
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
In kernel/futex.c (ffffffff8113ecb5)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff8120ce38)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81216480)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
```
```
In mm/page-writeback.c (ffffffff8121e375)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff812259f5)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81228c2f)
Location: include/linux/pagemap.h:466
Inline: True
```
```
In mm/shmem.c (ffffffff812330e7)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff8124babc)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124ee80)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff81258a54)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/swapfile.c (ffffffff8127bbd6)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8128628b)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff8129172c)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff812a0191)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812a706e)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memory-failure.c (ffffffff812ba4c3)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff812be38f)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/read_write.c (ffffffff812c9bd5)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffff812d5517)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff81303469)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff81310ff6)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffffffff8134b3ab)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffff8134e2dd)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff8139c27d)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff813e91b6)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff813fa933)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8140d9c4)
Location: include/linux/pagemap.h:466
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a228a)
Location: include/linux/pagemap.h:466
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
In kernel/futex.c (ffffffff8114a6df)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff8121a115)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81223d90)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
```
```
In mm/page-writeback.c (ffffffff8122be15)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff81233845)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81236acf)
Location: include/linux/pagemap.h:476
Inline: True
```
```
In mm/shmem.c (ffffffff81241307)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff81259fac)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125d460)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff81266f24)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/madvise.c (ffffffff81284fb2)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8128b6b6)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81295e6b)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff812a14ac)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff812b1531)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812b8533)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memory-failure.c (ffffffff812cbbf3)
Location: include/linux/pagemap.h:476
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
In mm/zsmalloc.c (ffffffff812d027f)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/read_write.c (ffffffff812db6b1)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffff812e7087)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff813164e9)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff81323fd6)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffffffff8136365b)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffff813665cd)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813b4d8d)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff81403256)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff81414803)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff81426bc4)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815c310a)
Location: include/linux/pagemap.h:476
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
In kernel/futex.c (ffffffff8115b22f)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81246a9b)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81252c37)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
```
```
In mm/page-writeback.c (ffffffff812587a5)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff81260f6a)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81265d7d)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff8126db59)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff812884cc)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8128beca)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_shared
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff8129719a)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/madvise.c (ffffffff812b717c)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812be598)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff812c9375)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_page_mapping_lock_write
```
```
In mm/ksm.c (ffffffff812d63bf)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff812e6f23)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812ecfba)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memory-failure.c (ffffffff8130264b)
Location: include/linux/pagemap.h:517
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
In mm/zsmalloc.c (ffffffff81306842)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/read_write.c (ffffffff8131165e)
Location: include/linux/pagemap.h:517
Inline: True
```
```
In fs/pipe.c (ffffffff8131e862)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/splice.c (ffffffff81350619)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/buffer.c (ffffffff8135d67f)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffffffff813aa46c)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffff813ae13e)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff81400219)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff81450ed9)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff81462b33)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff81477158)
Location: include/linux/pagemap.h:517
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8166d2c9)
Location: include/linux/pagemap.h:517
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
In kernel/futex.c (ffffffff81157370)
Location: include/linux/pagemap.h:606
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff812510fe)
Location: include/linux/pagemap.h:606
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8125d807)
Location: include/linux/pagemap.h:606
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
```
```
In mm/page-writeback.c (ffffffff81262dc0)
Location: include/linux/pagemap.h:606
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff8126b36a)
Location: include/linux/pagemap.h:606
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81270710)
Location: include/linux/pagemap.h:606
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff81279899)
Location: include/linux/pagemap.h:606
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff812921b5)
Location: include/linux/pagemap.h:606
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81296e4a)
Location: include/linux/pagemap.h:606
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:wp_page_shared
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff812a214a)
Location: include/linux/pagemap.h:606
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/madvise.c (ffffffff812c20ca)
Location: include/linux/pagemap.h:606
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812ca16f)
Location: include/linux/pagemap.h:606
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff812d4f94)
Location: include/linux/pagemap.h:606
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff812e1ed3)
Location: include/linux/pagemap.h:606
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff812f22be)
Location: include/linux/pagemap.h:606
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812f822e)
Location: include/linux/pagemap.h:606
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memory-failure.c (ffffffff8130daf7)
Location: include/linux/pagemap.h:606
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
In mm/zsmalloc.c (ffffffff81312582)
Location: include/linux/pagemap.h:606
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/pipe.c (ffffffff81329dc2)
Location: include/linux/pagemap.h:606
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/splice.c (ffffffff8135d6a9)
Location: include/linux/pagemap.h:606
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff813669de)
Location: include/linux/pagemap.h:606
Inline: True
```
```
In fs/buffer.c (ffffffff8136b260)
Location: include/linux/pagemap.h:606
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffffffff813bbabc)
Location: include/linux/pagemap.h:606
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffff813bf7ae)
Location: include/linux/pagemap.h:606
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff81412a21)
Location: include/linux/pagemap.h:606
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
In fs/hugetlbfs/inode.c (ffffffff8146d3f9)
Location: include/linux/pagemap.h:606
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff8147e633)
Location: include/linux/pagemap.h:606
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff81491f98)
Location: include/linux/pagemap.h:606
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8168d9e9)
Location: include/linux/pagemap.h:606
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
In kernel/futex.c (ffffffff81158784)
Location: include/linux/pagemap.h:622
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff812551fe)
Location: include/linux/pagemap.h:622
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812605ce)
Location: include/linux/pagemap.h:622
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff812677e0)
Location: include/linux/pagemap.h:622
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff8127045f)
Location: include/linux/pagemap.h:622
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81274cb0)
Location: include/linux/pagemap.h:622
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff8127e9f9)
Location: include/linux/pagemap.h:622
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff8129ca9a)
Location: include/linux/pagemap.h:622
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff812a79da)
Location: include/linux/pagemap.h:622
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/madvise.c (ffffffff812c8f6a)
Location: include/linux/pagemap.h:622
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812d0c52)
Location: include/linux/pagemap.h:622
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff812dbd4c)
Location: include/linux/pagemap.h:622
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff812e968e)
Location: include/linux/pagemap.h:622
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff812f8625)
Location: include/linux/pagemap.h:622
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff813004b6)
Location: include/linux/pagemap.h:622
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memory-failure.c (ffffffff81313d09)
Location: include/linux/pagemap.h:622
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/zsmalloc.c (ffffffff81318602)
Location: include/linux/pagemap.h:622
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/pipe.c (ffffffff8132fd82)
Location: include/linux/pagemap.h:622
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/splice.c (ffffffff81364149)
Location: include/linux/pagemap.h:622
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff8136d28e)
Location: include/linux/pagemap.h:622
Inline: True
```
```
In fs/buffer.c (ffffffff81371b00)
Location: include/linux/pagemap.h:622
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffffffff813c2bac)
Location: include/linux/pagemap.h:622
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff81418e81)
Location: include/linux/pagemap.h:622
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
In fs/hugetlbfs/inode.c (ffffffff81472a7c)
Location: include/linux/pagemap.h:622
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff81484103)
Location: include/linux/pagemap.h:622
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff81497158)
Location: include/linux/pagemap.h:622
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff816706d9)
Location: include/linux/pagemap.h:622
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
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
In kernel/futex.c (ffffffff8117d691)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81290c40)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8129cfbf)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff812a4340)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff812ae0f5)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff812b1f56)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff812bc578)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff812dd86a)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff812e8ffa)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/madvise.c (ffffffff8130df95)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff81316329)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81322f6f)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff813315c7)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff81342ce2)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff8134a128)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memory-failure.c (ffffffff8135efe9)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/zsmalloc.c (ffffffff81364b35)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/pipe.c (ffffffff8137d542)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/splice.c (ffffffff813b2939)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff813bbf6e)
Location: include/linux/pagemap.h:621
Inline: True
```
```
In fs/buffer.c (ffffffff813c0636)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffffffff81412d7c)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff8146c0b5)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff814c9549)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff814db783)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff814eea48)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff816e49a9)
Location: include/linux/pagemap.h:621
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
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
In kernel/futex/core.c (ffffffff811b270a)
Location: include/linux/pagemap.h:956
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff812e5f37)
Location: include/linux/pagemap.h:956
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/page-writeback.c (ffffffff812fc5df)
Location: include/linux/pagemap.h:956
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/memory.c (ffffffff8134254c)
Location: include/linux/pagemap.h:956
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_page_mkwrite
```
```
In mm/madvise.c (ffffffff81377325)
Location: include/linux/pagemap.h:956
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8138147b)
Location: include/linux/pagemap.h:956
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81390732)
Location: include/linux/pagemap.h:956
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff813a2439)
Location: include/linux/pagemap.h:956
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff813b5221)
Location: include/linux/pagemap.h:956
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:writeout
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff813c0ba4)
Location: include/linux/pagemap.h:956
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memory-failure.c (ffffffff813da091)
Location: include/linux/pagemap.h:956
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
```
In fs/pipe.c (ffffffff813fe36b)
Location: include/linux/pagemap.h:956
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/splice.c (ffffffff814389e2)
Location: include/linux/pagemap.h:956
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
```
```
In fs/buffer.c (ffffffff81448352)
Location: include/linux/pagemap.h:956
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/ext4/inode.c (ffffffff814ec09f)
Location: include/linux/pagemap.h:956
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff815556dc)
Location: include/linux/pagemap.h:956
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff81569322)
Location: include/linux/pagemap.h:956
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8157f173)
Location: include/linux/pagemap.h:956
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8180f397)
Location: include/linux/pagemap.h:956
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
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
In kernel/futex/core.c (ffffffff811f35aa)
Location: include/linux/pagemap.h:952
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In mm/page-writeback.c (ffffffff813668ef)
Location: include/linux/pagemap.h:952
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/memory.c (ffffffff813ba699)
Location: include/linux/pagemap.h:952
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_page_mkwrite
```
```
In mm/madvise.c (ffffffff813f4958)
Location: include/linux/pagemap.h:952
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff81411006)
Location: include/linux/pagemap.h:952
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff81422096)
Location: include/linux/pagemap.h:952
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff81433815)
Location: include/linux/pagemap.h:952
Inline: True
Inline callers:
  - mm/migrate.c:putback_movable_pages
```
```
In mm/migrate_device.c (ffffffff8143a424)
Location: include/linux/pagemap.h:952
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_coherent_page
```
```
In mm/huge_memory.c (ffffffff81442a04)
Location: include/linux/pagemap.h:952
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff81461833)
Location: include/linux/pagemap.h:952
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
```
In mm/memremap.c (ffffffff8146f851)
Location: include/linux/pagemap.h:952
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
```
```
In fs/pipe.c (ffffffff81487fdb)
Location: include/linux/pagemap.h:952
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/splice.c (ffffffff814c6fe2)
Location: include/linux/pagemap.h:952
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
```
```
In fs/buffer.c (ffffffff814d6f2f)
Location: include/linux/pagemap.h:952
Inline: True
Inline callers:
  - fs/buffer.c:block_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff81585e09)
Location: include/linux/pagemap.h:952
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ecryptfs/mmap.c (ffffffff8160ceb2)
Location: include/linux/pagemap.h:952
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff81624e40)
Location: include/linux/pagemap.h:952
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8193e137)
Location: include/linux/pagemap.h:952
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
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
In kernel/futex/core.c (ffffffff81207d60)
Location: include/linux/pagemap.h:973
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In mm/page-writeback.c (ffffffff81398f5f)
Location: include/linux/pagemap.h:973
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
```
```
In mm/memory.c (ffffffff813ef059)
Location: include/linux/pagemap.h:973
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_page_mkwrite
```
```
In mm/ksm.c (ffffffff81456d7f)
Location: include/linux/pagemap.h:973
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate_device.c (ffffffff8146fd74)
Location: include/linux/pagemap.h:973
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_coherent_page
```
```
In mm/memory-failure.c (ffffffff81497052)
Location: include/linux/pagemap.h:973
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_to_split_thp_page
```
```
In mm/memremap.c (ffffffff814a4031)
Location: include/linux/pagemap.h:973
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
```
```
In fs/pipe.c (ffffffff814bced3)
Location: include/linux/pagemap.h:973
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/splice.c (ffffffff814fc41d)
Location: include/linux/pagemap.h:973
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
```
```
In fs/ecryptfs/mmap.c (ffffffff81644d62)
Location: include/linux/pagemap.h:973
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8165d1c6)
Location: include/linux/pagemap.h:973
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81982637)
Location: include/linux/pagemap.h:973
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
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
In mm/page-writeback.c (ffffffff813c2d5f)
Location: include/linux/pagemap.h:1062
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
```
```
In mm/ksm.c (ffffffff81491883)
Location: include/linux/pagemap.h:1062
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate_device.c (ffffffff8149eff1)
Location: include/linux/pagemap.h:1062
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_coherent_page
```
```
In mm/memory-failure.c (ffffffff814c8750)
Location: include/linux/pagemap.h:1062
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_to_split_thp_page
```
```
In mm/memremap.c (ffffffff814d4ee1)
Location: include/linux/pagemap.h:1062
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
```
```
In fs/pipe.c (ffffffff814ef370)
Location: include/linux/pagemap.h:1062
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/ecryptfs/mmap.c (ffffffff8167e282)
Location: include/linux/pagemap.h:1062
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff81696f26)
Location: include/linux/pagemap.h:1062
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819c9db7)
Location: include/linux/pagemap.h:1062
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
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
In kernel/futex.c (ffff8000101b7b70)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffff8000102a5528)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffff8000102b1670)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
```
```
In mm/page-writeback.c (ffff8000102bc368)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffff8000102c3d1c)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffff8000102c8818)
Location: include/linux/pagemap.h:476
Inline: True
```
```
In mm/shmem.c (ffff8000102d36ec)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffff8000102f213c)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffff8000102f49a8)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffff8000102fe17c)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/madvise.c (ffff80001031f784)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffff800010326980)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffff800010334ae8)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffff800010340de4)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffff800010351c64)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffff800010358d9c)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memory-failure.c (ffff800010370248)
Location: include/linux/pagemap.h:476
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
In mm/zsmalloc.c (ffff800010374f08)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/read_write.c (ffff800010380584)
Location: include/linux/pagemap.h:476
Inline: True
```
```
In fs/pipe.c (ffff80001038fc3c)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffff8000103ce288)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffff8000103dd338)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffff80001042a3b4)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffff80001042dd4c)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffff80001048952c)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/hugetlbfs/inode.c (ffff8000104e1df8)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffff8000104f5f0c)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffff80001050b1a8)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffff80001074c08c)
Location: include/linux/pagemap.h:476
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
In kernel/futex.c (c0401904)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (c04d491c)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (c04de11c)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
```
```
In mm/page-writeback.c (c04e6d08)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (c04ee8ac)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (c04f5110)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (c04fb994)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (0)
Location: include/linux/pagemap.h:476
Inline: False
```
```
In mm/memory.c (c0516b58)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (c051ce44)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/swapfile.c (c053e154)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
```
```
In mm/ksm.c (c054702c)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (c0552d60)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
```
```
In mm/zsmalloc.c (c0561268)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/read_write.c (c056b4f8)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (c0576a44)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (c05a99e0)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (c05b6824)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (c05f31c4)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (c05f6cf0)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (c064b9f4)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ecryptfs/mmap.c (c06b3784)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (c06c6838)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (c08cecd4)
Location: include/linux/pagemap.h:476
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
In kernel/futex.c (c00000000021d010)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (c000000000358238)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (c0000000003670f0)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
```
```
In mm/page-writeback.c (c0000000003730f0)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (c00000000037e160)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (c000000000384900)
Location: include/linux/pagemap.h:476
Inline: True
```
```
In mm/shmem.c (c000000000392778)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (c0000000003b80f4)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003bb680)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (c0000000003c98a0)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/madvise.c (c0000000003f3e08)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (c0000000003fd3c8)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (c00000000040dfb0)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (c00000000041e640)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (c000000000437678)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (c0000000004411b4)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memory-failure.c (c000000000460c40)
Location: include/linux/pagemap.h:476
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
In mm/zsmalloc.c (c0000000004675f8)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/read_write.c (c000000000477124)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (c0000000004873a0)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (c0000000004ce8f0)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (c0000000004e2a74)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (c00000000053accc)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (c00000000053f020)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (c0000000005b055c)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/hugetlbfs/inode.c (c00000000061e79c)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (c000000000636d04)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (c00000000065099c)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (c0000000008ae108)
Location: include/linux/pagemap.h:476
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
In kernel/futex.c (ffffffe00013c856)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/filemap.c (ffffffe0001d6f0a)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
```
```
In mm/page-writeback.c (ffffffe0001dda9c)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffe0001e4952)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffe0001e71b4)
Location: include/linux/pagemap.h:476
Inline: True
```
```
In mm/shmem.c (ffffffe0001ef7a8)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (0)
Location: include/linux/pagemap.h:476
Inline: False
```
```
In mm/memory.c (ffffffe000205ea6)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffe00020c25c)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/swapfile.c (ffffffe000226a7c)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffe000230ab8)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffe000235546)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffe0002400a0)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
```
```
In mm/zsmalloc.c (ffffffe00024dd9a)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/read_write.c (ffffffe000255bc4)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffe00025f6b8)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffe00028a268)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffe00029540a)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffffffe0002c7efa)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffe0002ca778)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffe000310cf0)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/hugetlbfs/inode.c (ffffffe0003558e4)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffe000364d12)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffe000375ec4)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffe0004f9e6a)
Location: include/linux/pagemap.h:476
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
In kernel/futex.c (ffffffff81142cff)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81212765)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8121c3e0)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
```
```
In mm/page-writeback.c (ffffffff81224465)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff8122be95)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8122f11f)
Location: include/linux/pagemap.h:476
Inline: True
```
```
In mm/shmem.c (ffffffff81239957)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff812525fc)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81255ab0)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff8125f574)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/madvise.c (ffffffff8127d602)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff81283c96)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8128e44b)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff81299a8c)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff812a9b11)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812b0b13)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memory-failure.c (ffffffff812c41d3)
Location: include/linux/pagemap.h:476
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
In mm/zsmalloc.c (ffffffff812c885f)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/read_write.c (ffffffff812d3c91)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffff812df667)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff8130eac9)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8131c5b6)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffffffff8135bc3b)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffff8135ebad)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813ad36d)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff813fb836)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff8140cde3)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8141f1a4)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b725a)
Location: include/linux/pagemap.h:476
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
In kernel/futex.c (ffffffff8113605f)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff812054f5)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8120f5ca)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
```
```
In mm/page-writeback.c (ffffffff81217615)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff8121ef75)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff812221df)
Location: include/linux/pagemap.h:476
Inline: True
```
```
In mm/shmem.c (ffffffff8122c987)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff81245b15)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81248190)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff81251994)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/madvise.c (ffffffff8126f3d7)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff81275b1f)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff812801d0)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff8128b64c)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff8129b471)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812a21c5)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memory-failure.c (ffffffff812b5213)
Location: include/linux/pagemap.h:476
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
In mm/zsmalloc.c (ffffffff812b989f)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/read_write.c (ffffffff812c4911)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffff812d02a7)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff812ff6d9)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8130d156)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffffffff8134c8db)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffff8134f84d)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff8139ddfd)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff813ec2b6)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff813fd863)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8140fc24)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a603a)
Location: include/linux/pagemap.h:476
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
In kernel/futex.c (ffffffff81140baf)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81210505)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8121a180)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
```
```
In mm/page-writeback.c (ffffffff81222205)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff81229c35)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8122cebf)
Location: include/linux/pagemap.h:476
Inline: True
```
```
In mm/shmem.c (ffffffff812376f7)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff8125039c)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81253850)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff8125d314)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/madvise.c (ffffffff8127b3a2)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff81281aa6)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8128c25b)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff8129789c)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff812a7921)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812ae923)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memory-failure.c (ffffffff812c1fe3)
Location: include/linux/pagemap.h:476
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
In mm/zsmalloc.c (ffffffff812c666f)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/read_write.c (ffffffff812d1aa1)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffff812dd477)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff8130c8b9)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8131a086)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffffffff8135970b)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffff8135c67d)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813aabcd)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff813f8bb6)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff8140a163)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff8141b344)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b77ea)
Location: include/linux/pagemap.h:476
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
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff8121f452)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8122925c)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
```
```
In mm/page-writeback.c (ffffffff81231655)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff81239035)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8123c308)
Location: include/linux/pagemap.h:476
Inline: True
```
```
In mm/shmem.c (ffffffff81246c36)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffff8125fd25)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8126321e)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff8126ccff)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/madvise.c (ffffffff8128af70)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812917b7)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8129c045)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff812a7678)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff812b7c1e)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812bec73)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memory-failure.c (ffffffff812d2a83)
Location: include/linux/pagemap.h:476
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
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/read_write.c (ffffffff812e28c3)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffff812ee3f5)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/splice.c (ffffffff8131e0de)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8132bd4e)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/iomap/buffered-io.c (ffffffff8136ce0f)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/iomap/seek.c (ffffffff8136fdaf)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813bf51d)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/hugetlbfs/inode.c (ffffffff8140ea06)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff8141fe62)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/file.c (ffffffff81432374)
Location: include/linux/pagemap.h:476
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815d125a)
Location: include/linux/pagemap.h:476
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
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
