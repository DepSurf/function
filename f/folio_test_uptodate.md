# Function: <code>folio_test_uptodate</code>

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
In kernel/events/uprobes.c (ffffffff812e6cb6)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff812f4055)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:migration_entry_wait_on_locked
```
```
In mm/page-writeback.c (ffffffff81300466)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_mark_dirty
```
```
In mm/shmem.c (ffffffff8131a949)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff81343d83)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff813495f5)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/swapfile.c (ffffffff8137e899)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff813a312b)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff813b08bc)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/khugepaged.c (ffffffff813c4ca2)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/namei.c (ffffffff814007f9)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8142c799)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff814389a2)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff81441dd1)
Location: include/linux/page-flags.h:712
Inline: True
```
```
In fs/buffer.c (ffffffff81446880)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
```
```
In fs/mpage.c (ffffffff8144c219)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/verity/enable.c (ffffffff81472053)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/verity/verify.c (ffffffff814745f2)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/iomap/buffered-io.c (ffffffff8148a9a6)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/ext4/inline.c (ffffffff814dda25)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffffffff814e3ef9)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff814f4169)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff814feae0)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff8150a13b)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff8153c5dd)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
```
In fs/squashfs/file.c (ffffffff8154e7ea)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff815511d0)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff81569573)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/dev.c (ffffffff81575c54)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff8157f8d2)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_fill_write_pages
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
In kernel/events/uprobes.c (ffffffff8135079f)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8135e34a)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_read_folio
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
```
```
In mm/page-writeback.c (ffffffff8136ad96)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_mark_dirty
```
```
In mm/shmem.c (ffffffff8138da54)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff813bbf3c)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff813c10b9)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/swapfile.c (ffffffff813fd2c2)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff81422da4)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff81431430)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/khugepaged.c (ffffffff814494d6)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/namei.c (ffffffff8148b279)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff814ba009)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff814c6fa2)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff814d09aa)
Location: include/linux/page-flags.h:709
Inline: True
```
```
In fs/buffer.c (ffffffff814d5994)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
```
```
In fs/mpage.c (ffffffff814da64b)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/verity/enable.c (ffffffff81504092)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/verify.c (ffffffff815067f8)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/iomap/buffered-io.c (ffffffff8151e245)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/ext4/inline.c (ffffffff81576a6a)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffffffff8157d429)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff8158e68d)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff81599330)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff815a4c60)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff815daca0)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
```
In fs/squashfs/file.c (ffffffff815ef2aa)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff815f2330)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff8160d153)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/dev.c (ffffffff8161af2a)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff816255b2)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_fill_write_pages
```
```
In fs/fuse/readdir.c (ffffffff8162f6e6)
Location: include/linux/page-flags.h:709
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
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
In kernel/events/uprobes.c (ffffffff81381ae8)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff813910bd)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_read_folio
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
```
```
In mm/page-writeback.c (ffffffff8139cf26)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_mark_dirty
```
```
In mm/shmem.c (ffffffff813c1be7)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff813f096b)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff813f5dd7)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/swapfile.c (ffffffff8143056e)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff81457f29)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff81468706)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/khugepaged.c (ffffffff8147f6c7)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/namei.c (ffffffff814c0ba5)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff814eef79)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff814fc412)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff815070aa)
Location: include/linux/page-flags.h:703
Inline: True
```
```
In fs/buffer.c (ffffffff8150c20f)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_write_end
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:folio_zero_new_buffers
  - fs/buffer.c:folio_create_empty_buffers
  - fs/buffer.c:folio_create_empty_buffers
  - fs/buffer.c:folio_init_buffers
```
```
In fs/mpage.c (ffffffff8150eb7d)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/verity/verify.c (ffffffff8153e53e)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_data_blocks
```
```
In fs/iomap/buffered-io.c (ffffffff815563ab)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/ext4/inline.c (ffffffff815ae015)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffffffff815b47bc)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff815c507a)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff815cfd13)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff815db6d3)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff81611d83)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
```
In fs/squashfs/block.c (ffffffff81624195)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In fs/squashfs/file.c (ffffffff8162728a)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8162a420)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff81645013)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/dev.c (ffffffff8165309a)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff8165d93f)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_fill_write_pages
```
```
In fs/fuse/readdir.c (ffffffff81667959)
Location: include/linux/page-flags.h:703
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
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
In kernel/events/uprobes.c (ffffffff813aacf2)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff813bae5d)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_read_folio
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
```
```
In mm/page-writeback.c (ffffffff813c6c16)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_mark_dirty
```
```
In mm/shmem.c (ffffffff813ec964)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff814201d6)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff81421aa7)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/swapfile.c (ffffffff81468efb)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff814928ab)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff81497da6)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/khugepaged.c (ffffffff814ad742)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/namei.c (ffffffff814f2fc5)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81522c04)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff815301ed)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff8153c3c9)
Location: include/linux/page-flags.h:724
Inline: True
```
```
In fs/buffer.c (ffffffff81540e07)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_write_end
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:folio_zero_new_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:folio_init_buffers
```
```
In fs/mpage.c (ffffffff8154345a)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/verity/verify.c (ffffffff81573ade)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_data_blocks
```
```
In fs/iomap/buffered-io.c (ffffffff8158c877)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:ifs_free
  - fs/iomap/buffered-io.c:ifs_alloc
```
```
In fs/ext4/inline.c (ffffffff815e6dd5)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffffffff815ed5cc)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff815fd2fa)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff81608590)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff81613fa0)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff8164ab31)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
```
In fs/squashfs/block.c (ffffffff8165d235)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In fs/squashfs/file.c (ffffffff816603ea)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8166374a)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff8167e543)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/dev.c (ffffffff8168c6a7)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff8169767c)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_fill_write_pages
```
```
In fs/fuse/readdir.c (ffffffff816a1c9d)
Location: include/linux/page-flags.h:724
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
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
