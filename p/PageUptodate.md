# Function: <code>PageUptodate</code>

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
In mm/filemap.c (ffffffff8118cbe1)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - mm/filemap.c:wait_on_page_read
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/page-writeback.c (ffffffff8119a9f8)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - mm/page-writeback.c:__set_page_dirty_nobuffers
```
```
In mm/shmem.c (ffffffff811a6610)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_splice_read
```
```
In mm/memory.c (ffffffff811bfe50)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/mincore.c (ffffffff811c257f)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/ksm.c (ffffffff811e6d1c)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff811f1c36)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff811f73fa)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/libfs.c (ffffffff81234b18)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff8123e7c0)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:__generic_file_splice_read
  - fs/splice.c:__generic_file_splice_read
```
```
In fs/buffer.c (ffffffff812428c1)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:block_write_end
  - fs/buffer.c:__block_write_begin
  - fs/buffer.c:__block_write_begin
  - fs/buffer.c:__block_write_begin
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
```
```
In fs/mpage.c (ffffffff8124d71e)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inode.c (ffffffff812977af)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffffffff812ceda3)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_load_buddy
  - fs/ext4/mballoc.c:ext4_mb_load_buddy
  - fs/ext4/mballoc.c:ext4_mb_load_buddy
  - fs/ext4/mballoc.c:ext4_mb_load_buddy
  - fs/ext4/mballoc.c:ext4_mb_load_buddy
  - fs/ext4/mballoc.c:ext4_mb_load_buddy
```
```
In fs/ext4/move_extent.c (ffffffff812d6b0d)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff812e0903)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
```
In fs/ext4/readpage.c (ffffffff812e3401)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff81304196)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/dev.c (ffffffff8130e9d3)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff81316e6f)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_write_end
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
In mm/filemap.c (ffffffff811a13bc)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page-writeback.c (ffffffff811af312)
Location: include/linux/page-flags.h:415
Inline: True
```
```
In mm/shmem.c (ffffffff811c319a)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff811d9dfd)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff811de0aa)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/ksm.c (ffffffff81205d5e)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff81210618)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffffffff8121acf0)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/namei.c (ffffffff8123d9b1)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8125cfe8)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff81266ddb)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - fs/splice.c:__generic_file_splice_read
  - fs/splice.c:__generic_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8126e975)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_end
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty
```
```
In fs/mpage.c (ffffffff81276037)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inode.c (ffffffff812c6422)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff812ff2b3)
Location: include/linux/page-flags.h:415
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
In fs/ext4/move_extent.c (ffffffff81306800)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff813110a5)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/readpage.c (ffffffff81313346)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffff813223ec)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff81324e04)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff813387c4)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/dev.c (ffffffff81342d43)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff8134da98)
Location: include/linux/page-flags.h:415
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In mm/filemap.c (ffffffff811b0ff9)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page-writeback.c (ffffffff811bf9b2)
Location: include/linux/page-flags.h:431
Inline: True
```
```
In mm/shmem.c (ffffffff811d3219)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff811e9932)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff811edeba)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/ksm.c (ffffffff81217d6e)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff81222758)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffffffff8122c4e1)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/read_write.c (ffffffff81244588)
Location: include/linux/page-flags.h:431
Inline: True
```
```
In fs/namei.c (ffffffff812507ab)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81270505)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff81278d71)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff81281b8f)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_end
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty
```
```
In fs/mpage.c (ffffffff81289d37)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap.c (ffffffff812b183a)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_dirty_actor
```
```
In fs/ext4/inode.c (ffffffff812dbc7f)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff81315333)
Location: include/linux/page-flags.h:431
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
In fs/ext4/move_extent.c (ffffffff8131c7c0)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff81326f85)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/readpage.c (ffffffff813292e4)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffff8133827c)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8133ac5e)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff8134e564)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/dev.c (ffffffff81358b62)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff8136339d)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In mm/filemap.c (ffffffff811b8456)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page-writeback.c (ffffffff811c7b82)
Location: include/linux/page-flags.h:434
Inline: True
```
```
In mm/shmem.c (ffffffff811da895)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff811f4a7a)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff811f8ee8)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/ksm.c (ffffffff8122396a)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff8122e1f3)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffffffff81238d7f)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/read_write.c (ffffffff8124ffe8)
Location: include/linux/page-flags.h:434
Inline: True
```
```
In fs/namei.c (ffffffff8125c937)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8127dc25)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff812862e1)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8128f347)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_end
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty
```
```
In fs/mpage.c (ffffffff81296a12)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap.c (ffffffff812bec1b)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_dirty_actor
```
```
In fs/ext4/inline.c (ffffffff812faeda)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffffffff81300511)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff8130c793)
Location: include/linux/page-flags.h:434
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
In fs/ext4/move_extent.c (ffffffff8131533e)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff8131e919)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffff8134cf8c)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8134f8bc)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff813630de)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/dev.c (ffffffff8136d3cd)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff81377d17)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In mm/filemap.c (ffffffff811ccbbd)
Location: include/linux/page-flags.h:435
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff811dc9c2)
Location: include/linux/page-flags.h:435
Inline: True
```
```
In mm/shmem.c (ffffffff811f0628)
Location: include/linux/page-flags.h:435
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff8120c9cb)
Location: include/linux/page-flags.h:435
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff812111fc)
Location: include/linux/page-flags.h:435
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/ksm.c (ffffffff8123efaa)
Location: include/linux/page-flags.h:435
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812492c7)
Location: include/linux/page-flags.h:435
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff8125747d)
Location: include/linux/page-flags.h:435
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/read_write.c (ffffffff81271ed8)
Location: include/linux/page-flags.h:435
Inline: True
```
```
In fs/namei.c (ffffffff8127ec5a)
Location: include/linux/page-flags.h:435
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812a06d5)
Location: include/linux/page-flags.h:435
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff812a8d61)
Location: include/linux/page-flags.h:435
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff812b1f54)
Location: include/linux/page-flags.h:435
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_end
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty
```
```
In fs/mpage.c (ffffffff812b9c78)
Location: include/linux/page-flags.h:435
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap.c (ffffffff812e2629)
Location: include/linux/page-flags.h:435
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_dirty_actor
```
```
In fs/ext4/inline.c (ffffffff8131f5ca)
Location: include/linux/page-flags.h:435
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffffffff81324d34)
Location: include/linux/page-flags.h:435
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff8133136b)
Location: include/linux/page-flags.h:435
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
In fs/ext4/move_extent.c (ffffffff81339b4a)
Location: include/linux/page-flags.h:435
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff81342f40)
Location: include/linux/page-flags.h:435
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffff813715fa)
Location: include/linux/page-flags.h:435
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff81373f53)
Location: include/linux/page-flags.h:435
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff81387d6e)
Location: include/linux/page-flags.h:435
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/dev.c (ffffffff81391e56)
Location: include/linux/page-flags.h:435
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff8139cab7)
Location: include/linux/page-flags.h:435
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In mm/filemap.c (ffffffff811edcbd)
Location: include/linux/page-flags.h:442
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff811fca63)
Location: include/linux/page-flags.h:442
Inline: True
```
```
In mm/shmem.c (ffffffff81211d98)
Location: include/linux/page-flags.h:442
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff8122d4f2)
Location: include/linux/page-flags.h:442
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff81231d30)
Location: include/linux/page-flags.h:442
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/ksm.c (ffffffff8126275e)
Location: include/linux/page-flags.h:442
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff8126cd47)
Location: include/linux/page-flags.h:442
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff8127b3a3)
Location: include/linux/page-flags.h:442
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/read_write.c (ffffffff81297ea8)
Location: include/linux/page-flags.h:442
Inline: True
```
```
In fs/namei.c (ffffffff812a55ea)
Location: include/linux/page-flags.h:442
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812c6c54)
Location: include/linux/page-flags.h:442
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff812cf8f1)
Location: include/linux/page-flags.h:442
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff812d9e9c)
Location: include/linux/page-flags.h:442
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_end
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty
```
```
In fs/mpage.c (ffffffff812e280c)
Location: include/linux/page-flags.h:442
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap.c (ffffffff8130ddd8)
Location: include/linux/page-flags.h:442
Inline: True
Inline callers:
  - fs/iomap.c:page_cache_seek_hole_data
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_dirty_actor
```
```
In fs/ext4/inline.c (ffffffff8134d646)
Location: include/linux/page-flags.h:442
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffffffff81352f8c)
Location: include/linux/page-flags.h:442
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff8135f927)
Location: include/linux/page-flags.h:442
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
In fs/ext4/move_extent.c (ffffffff81368117)
Location: include/linux/page-flags.h:442
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff81370d09)
Location: include/linux/page-flags.h:442
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffff8139fff7)
Location: include/linux/page-flags.h:442
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813a29fb)
Location: include/linux/page-flags.h:442
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff813b69ee)
Location: include/linux/page-flags.h:442
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/dev.c (ffffffff813c0e90)
Location: include/linux/page-flags.h:442
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff813cbeb7)
Location: include/linux/page-flags.h:442
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In mm/filemap.c (ffffffff811ff2ec)
Location: include/linux/page-flags.h:459
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8120f5b3)
Location: include/linux/page-flags.h:459
Inline: True
```
```
In mm/shmem.c (ffffffff81223c35)
Location: include/linux/page-flags.h:459
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff81240a86)
Location: include/linux/page-flags.h:459
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff81245500)
Location: include/linux/page-flags.h:459
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/ksm.c (ffffffff81276fde)
Location: include/linux/page-flags.h:459
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff81281549)
Location: include/linux/page-flags.h:459
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff8128f9dd)
Location: include/linux/page-flags.h:459
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/read_write.c (ffffffff812acf78)
Location: include/linux/page-flags.h:459
Inline: True
```
```
In fs/namei.c (ffffffff812ba757)
Location: include/linux/page-flags.h:459
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812dbe24)
Location: include/linux/page-flags.h:459
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff812e4c61)
Location: include/linux/page-flags.h:459
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff812ef38a)
Location: include/linux/page-flags.h:459
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_end
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty
```
```
In fs/mpage.c (ffffffff812f7478)
Location: include/linux/page-flags.h:459
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap.c (ffffffff81324c8d)
Location: include/linux/page-flags.h:459
Inline: True
Inline callers:
  - fs/iomap.c:page_cache_seek_hole_data
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_write_end
  - fs/iomap.c:iomap_write_end
```
```
In fs/ext4/inline.c (ffffffff813657dd)
Location: include/linux/page-flags.h:459
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffffffff8136b0b9)
Location: include/linux/page-flags.h:459
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff81377dcd)
Location: include/linux/page-flags.h:459
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
In fs/ext4/move_extent.c (ffffffff81380599)
Location: include/linux/page-flags.h:459
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff813891ae)
Location: include/linux/page-flags.h:459
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffff813b8d84)
Location: include/linux/page-flags.h:459
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813bb7e3)
Location: include/linux/page-flags.h:459
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff813cff3e)
Location: include/linux/page-flags.h:459
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/dev.c (ffffffff813da1f0)
Location: include/linux/page-flags.h:459
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff813e4f77)
Location: include/linux/page-flags.h:459
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In mm/filemap.c (ffffffff81216352)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81221652)
Location: include/linux/page-flags.h:492
Inline: True
```
```
In mm/shmem.c (ffffffff81235464)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff81252ce0)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff81257583)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/ksm.c (ffffffff8129283f)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff8129d7da)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff812aaa57)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/read_write.c (ffffffff812c9c1e)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/namei.c (ffffffff812d7361)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812fa4cb)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff81303452)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff81310bda)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_end
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty
```
```
In fs/mpage.c (ffffffff81317aa7)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8134cdf9)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/seek.c (ffffffff8134e441)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inline.c (ffffffff8138eb9e)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffffffff813945c0)
Location: include/linux/page-flags.h:492
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
In fs/ext4/mballoc.c (ffffffff813a125b)
Location: include/linux/page-flags.h:492
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
In fs/ext4/move_extent.c (ffffffff813a9420)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff813b3379)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffff813e3bab)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813e607c)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff813fab2c)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/dev.c (ffffffff81405e33)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff814109e8)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In kernel/events/uprobes.c (ffffffff8121aafd)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff81223c62)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8122f102)
Location: include/linux/page-flags.h:492
Inline: True
```
```
In mm/shmem.c (ffffffff812436a4)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff81261240)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff81265ad3)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/ksm.c (ffffffff812a25bf)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812ad0f8)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff812bc008)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/read_write.c (ffffffff812db6fa)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/namei.c (ffffffff812e8ec1)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8130c24b)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff813164d2)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff81323bba)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_end
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty
```
```
In fs/mpage.c (ffffffff8132a922)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/verity/verify.c (ffffffff81351200)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/iomap/buffered-io.c (ffffffff813650c9)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/seek.c (ffffffff81366731)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inline.c (ffffffff813a75fe)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffffffff813acf40)
Location: include/linux/page-flags.h:492
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
In fs/ext4/mballoc.c (ffffffff813ba0de)
Location: include/linux/page-flags.h:492
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
In fs/ext4/move_extent.c (ffffffff813c2340)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff813cc549)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffff813fdbdb)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff814000df)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff814149fc)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/dev.c (ffffffff81420993)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff8142a5f8)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In kernel/events/uprobes.c (ffffffff81247559)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff81252bb9)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8125c18d)
Location: include/linux/page-flags.h:508
Inline: True
```
```
In mm/shmem.c (ffffffff8126f864)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff81291606)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff81295e0b)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/ksm.c (ffffffff812d6cca)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812e2c38)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff812f1528)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/read_write.c (ffffffff813114fe)
Location: include/linux/page-flags.h:508
Inline: True
```
```
In fs/namei.c (ffffffff81321571)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8134572d)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff81350602)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/buffer.c (ffffffff8135d272)
Location: include/linux/page-flags.h:508
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
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty
```
```
In fs/mpage.c (ffffffff8136465b)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/verity/enable.c (ffffffff81395c2c)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/verity/verify.c (ffffffff81397c45)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/iomap/buffered-io.c (ffffffff813ac351)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_end_inline
  - fs/iomap/buffered-io.c:__iomap_write_begin
```
```
In fs/iomap/seek.c (ffffffff813ae289)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inline.c (ffffffff813f381a)
Location: include/linux/page-flags.h:508
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
In fs/ext4/inode.c (ffffffff813f91b8)
Location: include/linux/page-flags.h:508
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
In fs/ext4/mballoc.c (ffffffff81405cdf)
Location: include/linux/page-flags.h:508
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
In fs/ext4/move_extent.c (ffffffff8140ea0b)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff81418796)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff8143bc96)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
```
In fs/squashfs/file.c (ffffffff8144b63c)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8144dbfe)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff81462c6c)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/dev.c (ffffffff8146fa2a)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff8147a799)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In kernel/events/uprobes.c (ffffffff81251bcf)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8125d789)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read_get_pages
  - mm/filemap.c:generic_file_buffered_read_pagenotuptodate
  - mm/filemap.c:generic_file_buffered_read_pagenotuptodate
  - mm/filemap.c:generic_file_buffered_read_readpage
  - mm/filemap.c:generic_file_buffered_read_readpage
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8126655d)
Location: include/linux/page-flags.h:512
Inline: True
```
```
In mm/shmem.c (ffffffff8127abd4)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff8129bf5b)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff812a117d)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/ksm.c (ffffffff812e285a)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812ee068)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff812fda80)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/namei.c (ffffffff8132cb11)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81351e67)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff8135d692)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff8136687e)
Location: include/linux/page-flags.h:512
Inline: True
```
```
In fs/buffer.c (ffffffff8136a75a)
Location: include/linux/page-flags.h:512
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
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty
```
```
In fs/mpage.c (ffffffff8137165d)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/verity/enable.c (ffffffff813a791b)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/verity/verify.c (ffffffff813a94c5)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/iomap/buffered-io.c (ffffffff813bd92e)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_end_inline
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/iomap/seek.c (ffffffff813bf8f9)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inline.c (ffffffff81405faa)
Location: include/linux/page-flags.h:512
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
In fs/ext4/inode.c (ffffffff8140b86d)
Location: include/linux/page-flags.h:512
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
In fs/ext4/mballoc.c (ffffffff81418f7a)
Location: include/linux/page-flags.h:512
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
In fs/ext4/move_extent.c (ffffffff81421f50)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff8142c2d9)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff81457ff1)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
```
In fs/squashfs/file.c (ffffffff81467d1c)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8146a1be)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff8147e76c)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/dev.c (ffffffff8148a2c2)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff814954a2)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In kernel/events/uprobes.c (ffffffff812559b8)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8126054c)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8126b0c2)
Location: include/linux/page-flags.h:512
Inline: True
```
```
In mm/shmem.c (ffffffff8127fd4d)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff812a11f6)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff812a6d98)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/ksm.c (ffffffff812e9fea)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812f3b58)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff81304a79)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/namei.c (ffffffff813326df)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81358b8e)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff81364132)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff8136d12e)
Location: include/linux/page-flags.h:512
Inline: True
```
```
In fs/buffer.c (ffffffff813712cf)
Location: include/linux/page-flags.h:512
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
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty
```
```
In fs/mpage.c (ffffffff8137892c)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/verity/enable.c (ffffffff813ae974)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/verity/verify.c (ffffffff813b0a05)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/iomap/buffered-io.c (ffffffff813c4b07)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/ext4/inline.c (ffffffff8140c2dc)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffffffff81411a1b)
Location: include/linux/page-flags.h:512
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
In fs/ext4/mballoc.c (ffffffff8141f82a)
Location: include/linux/page-flags.h:512
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
In fs/ext4/move_extent.c (ffffffff81428617)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff81432fd0)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff8145d9a9)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
```
In fs/squashfs/file.c (ffffffff8146d31e)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8146f797)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff814842fd)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/dev.c (ffffffff8148fe12)
Location: include/linux/page-flags.h:512
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff8149a502)
Location: include/linux/page-flags.h:512
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
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81291668)
Location: include/linux/page-flags.h:532
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8129cf3c)
Location: include/linux/page-flags.h:532
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff812a7ed4)
Location: include/linux/page-flags.h:532
Inline: True
Inline callers:
  - mm/page-writeback.c:__set_page_dirty
```
```
In mm/shmem.c (ffffffff812be05d)
Location: include/linux/page-flags.h:532
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff812e213e)
Location: include/linux/page-flags.h:532
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff812e8274)
Location: include/linux/page-flags.h:532
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/ksm.c (ffffffff81331f0a)
Location: include/linux/page-flags.h:532
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff8133e4f8)
Location: include/linux/page-flags.h:532
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff8134e7e9)
Location: include/linux/page-flags.h:532
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/namei.c (ffffffff8137fe6f)
Location: include/linux/page-flags.h:532
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff813a727e)
Location: include/linux/page-flags.h:532
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff813b2922)
Location: include/linux/page-flags.h:532
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff813bbe0e)
Location: include/linux/page-flags.h:532
Inline: True
```
```
In fs/buffer.c (ffffffff813bfbe8)
Location: include/linux/page-flags.h:532
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
In fs/mpage.c (ffffffff813c5276)
Location: include/linux/page-flags.h:532
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/verity/enable.c (ffffffff813fe514)
Location: include/linux/page-flags.h:532
Inline: True
Inline callers:
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/verity/verify.c (ffffffff814005ec)
Location: include/linux/page-flags.h:532
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/iomap/buffered-io.c (ffffffff81412e87)
Location: include/linux/page-flags.h:532
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
In fs/ext4/inline.c (ffffffff8145f1d4)
Location: include/linux/page-flags.h:532
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffffffff814648d6)
Location: include/linux/page-flags.h:532
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
In fs/ext4/mballoc.c (ffffffff81472f2c)
Location: include/linux/page-flags.h:532
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
In fs/ext4/move_extent.c (ffffffff8147c355)
Location: include/linux/page-flags.h:532
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff8148682d)
Location: include/linux/page-flags.h:532
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff814b2e69)
Location: include/linux/page-flags.h:532
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
```
In fs/squashfs/file.c (ffffffff814c3ba5)
Location: include/linux/page-flags.h:532
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff814c6201)
Location: include/linux/page-flags.h:532
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff814db97d)
Location: include/linux/page-flags.h:532
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/dev.c (ffffffff814e787f)
Location: include/linux/page-flags.h:532
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff814f1f6f)
Location: include/linux/page-flags.h:532
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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812e6ca2)
Location: include/linux/page-flags.h:729
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff8131a938)
Location: include/linux/page-flags.h:729
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffffffff81343d7b)
Location: include/linux/page-flags.h:729
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff813495e4)
Location: include/linux/page-flags.h:729
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/swapfile.c (ffffffff8137e885)
Location: include/linux/page-flags.h:729
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff813a3117)
Location: include/linux/page-flags.h:729
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/khugepaged.c (ffffffff813c4c8e)
Location: include/linux/page-flags.h:729
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/namei.c (ffffffff814007ec)
Location: include/linux/page-flags.h:729
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8142c785)
Location: include/linux/page-flags.h:729
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff81438991)
Location: include/linux/page-flags.h:729
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
```
```
In fs/buffer.c (ffffffff8144686b)
Location: include/linux/page-flags.h:729
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
```
```
In fs/mpage.c (ffffffff8144c207)
Location: include/linux/page-flags.h:729
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/verity/verify.c (ffffffff814745d6)
Location: include/linux/page-flags.h:729
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/ext4/inline.c (ffffffff814dda11)
Location: include/linux/page-flags.h:729
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
In fs/ext4/inode.c (ffffffff814e3ee5)
Location: include/linux/page-flags.h:729
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
In fs/ext4/mballoc.c (ffffffff814f4155)
Location: include/linux/page-flags.h:729
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
In fs/ext4/move_extent.c (ffffffff814feacc)
Location: include/linux/page-flags.h:729
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff8150a127)
Location: include/linux/page-flags.h:729
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff8153c5cc)
Location: include/linux/page-flags.h:729
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
```
In fs/squashfs/file.c (ffffffff8154e7d9)
Location: include/linux/page-flags.h:729
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff815511be)
Location: include/linux/page-flags.h:729
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff8156955e)
Location: include/linux/page-flags.h:729
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/dev.c (ffffffff81575c40)
Location: include/linux/page-flags.h:729
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff8157f8bb)
Location: include/linux/page-flags.h:729
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
In kernel/events/uprobes.c (ffffffff8135078b)
Location: include/linux/page-flags.h:726
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff8138cc0d)
Location: include/linux/page-flags.h:726
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/swapfile.c (ffffffff813fd2ae)
Location: include/linux/page-flags.h:726
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff81422d90)
Location: include/linux/page-flags.h:726
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/khugepaged.c (ffffffff814494c2)
Location: include/linux/page-flags.h:726
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/namei.c (ffffffff8148b26c)
Location: include/linux/page-flags.h:726
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff814b9ff5)
Location: include/linux/page-flags.h:726
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff814c6f91)
Location: include/linux/page-flags.h:726
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
```
```
In fs/buffer.c (ffffffff814d5980)
Location: include/linux/page-flags.h:726
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
```
```
In fs/mpage.c (ffffffff814da63a)
Location: include/linux/page-flags.h:726
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
```
```
In fs/verity/verify.c (ffffffff815067e7)
Location: include/linux/page-flags.h:726
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/ext4/inline.c (ffffffff81576a56)
Location: include/linux/page-flags.h:726
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
In fs/ext4/inode.c (ffffffff8157d415)
Location: include/linux/page-flags.h:726
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
In fs/ext4/mballoc.c (ffffffff8158e679)
Location: include/linux/page-flags.h:726
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
In fs/ext4/move_extent.c (ffffffff8159931c)
Location: include/linux/page-flags.h:726
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff815a4c4c)
Location: include/linux/page-flags.h:726
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff815dac8c)
Location: include/linux/page-flags.h:726
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
```
In fs/squashfs/file.c (ffffffff815ef299)
Location: include/linux/page-flags.h:726
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff815f231e)
Location: include/linux/page-flags.h:726
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff8160d13e)
Location: include/linux/page-flags.h:726
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffffffff8162559b)
Location: include/linux/page-flags.h:726
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_fill_write_pages
```
```
In fs/fuse/readdir.c (ffffffff8162f6d2)
Location: include/linux/page-flags.h:726
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
In kernel/events/uprobes.c (ffffffff81381943)
Location: include/linux/page-flags.h:720
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/swapfile.c (ffffffff8143055d)
Location: include/linux/page-flags.h:720
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff81457f15)
Location: include/linux/page-flags.h:720
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/khugepaged.c (ffffffff8147f6b3)
Location: include/linux/page-flags.h:720
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/namei.c (ffffffff814c0b98)
Location: include/linux/page-flags.h:720
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff814eef65)
Location: include/linux/page-flags.h:720
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff814fc401)
Location: include/linux/page-flags.h:720
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
```
```
In fs/mpage.c (ffffffff8150f1a1)
Location: include/linux/page-flags.h:720
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
```
```
In fs/ext4/inode.c (ffffffff815bb36a)
Location: include/linux/page-flags.h:720
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
```
In fs/ext4/mballoc.c (ffffffff815c5066)
Location: include/linux/page-flags.h:720
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
In fs/squashfs/block.c (ffffffff81624181)
Location: include/linux/page-flags.h:720
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In fs/squashfs/file.c (ffffffff81627279)
Location: include/linux/page-flags.h:720
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8162a40e)
Location: include/linux/page-flags.h:720
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff81644ffe)
Location: include/linux/page-flags.h:720
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffffffff8165d928)
Location: include/linux/page-flags.h:720
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_fill_write_pages
```
```
In fs/fuse/readdir.c (ffffffff81667945)
Location: include/linux/page-flags.h:720
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
In kernel/events/uprobes.c (ffffffff813aacde)
Location: include/linux/page-flags.h:741
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/khugepaged.c (ffffffff814ad72d)
Location: include/linux/page-flags.h:741
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/namei.c (ffffffff814f2fb8)
Location: include/linux/page-flags.h:741
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/ext4/mballoc.c (ffffffff815fd2e6)
Location: include/linux/page-flags.h:741
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
In fs/squashfs/block.c (ffffffff8165d221)
Location: include/linux/page-flags.h:741
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In fs/squashfs/file.c (ffffffff816603d9)
Location: include/linux/page-flags.h:741
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff81663738)
Location: include/linux/page-flags.h:741
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff8167e52e)
Location: include/linux/page-flags.h:741
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffffffff81697665)
Location: include/linux/page-flags.h:741
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_fill_write_pages
```
```
In fs/fuse/readdir.c (ffffffff816a1c89)
Location: include/linux/page-flags.h:741
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffff8000102a5ef4)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffff8000102b15f8)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffff8000102be388)
Location: include/linux/page-flags.h:492
Inline: True
```
```
In mm/shmem.c (ffff8000102d5978)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffff8000102f85fc)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffff8000102fccbc)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/ksm.c (ffff800010341f9c)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffff80001034f3c8)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffff80001035d318)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/read_write.c (ffff800010380430)
Location: include/linux/page-flags.h:492
Inline: True
```
```
In fs/namei.c (ffff800010393a38)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffff8000103c0a18)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffff8000103ce264)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffff8000103dcf3c)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_end
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty
```
```
In fs/mpage.c (ffff8000103e60dc)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/verity/verify.c (ffff800010413270)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/iomap/buffered-io.c (ffff80001042bc20)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/seek.c (ffff80001042de5c)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inline.c (ffff80001047ae94)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffff8000104816e8)
Location: include/linux/page-flags.h:492
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
In fs/ext4/mballoc.c (ffff8000104908f0)
Location: include/linux/page-flags.h:492
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
In fs/ext4/move_extent.c (ffff800010499d60)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffff8000104a4a44)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffff8000104dbc6c)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffff8000104de104)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffff8000104f61a8)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/dev.c (ffff800010503570)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffff80001050e5e0)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In kernel/events/uprobes.c (c04d4eec)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (c04de008)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (c04ea664)
Location: include/linux/page-flags.h:492
Inline: True
```
```
In mm/shmem.c (c04fdb18)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (c051ae70)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (c051c3d8)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/ksm.c (c0547d5c)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (c0551340)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/read_write.c (c056b5ac)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:vfs_dedupe_get_page
```
```
In fs/namei.c (c057980c)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (c059df34)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (c05a99c0)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (c05b645c)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_end
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty
```
```
In fs/mpage.c (c05bdbd8)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/verity/verify.c (c05df540)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/iomap/buffered-io.c (c05f50d0)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_inline_data
```
```
In fs/iomap/seek.c (c05f6e74)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inline.c (c063c7f0)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (c0642894)
Location: include/linux/page-flags.h:492
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
In fs/ext4/mballoc.c (c0651a58)
Location: include/linux/page-flags.h:492
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
In fs/ext4/move_extent.c (c065b578)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (c066661c)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (c069d458)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (c069fd38)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (c06b3ae4)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/dev.c (c06bfc08)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (c06c9d70)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In kernel/events/uprobes.c (c000000000358f60)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (c000000000366ea4)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (c000000000377264)
Location: include/linux/page-flags.h:492
Inline: True
```
```
In mm/shmem.c (c000000000395880)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (c0000000003c1a24)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (c0000000003c7c30)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/ksm.c (c00000000041f7dc)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (c0000000004317d0)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (c0000000004486a4)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/read_write.c (c00000000047719c)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:vfs_dedupe_get_page
```
```
In fs/namei.c (c00000000048ab40)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (c0000000004bf158)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (c0000000004ce8d0)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (c0000000004e2600)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_end
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty
```
```
In fs/mpage.c (c0000000004ec364)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/verity/verify.c (c000000000521080)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/iomap/buffered-io.c (c00000000053cf5c)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/seek.c (c00000000053f1a0)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inline.c (c00000000059dfec)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (c0000000005a5dd8)
Location: include/linux/page-flags.h:492
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
In fs/ext4/mballoc.c (c0000000005b808c)
Location: include/linux/page-flags.h:492
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
In fs/ext4/move_extent.c (c0000000005c3fec)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (c0000000005d1b48)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (c000000000616e1c)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (c000000000619de4)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (c000000000637060)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/dev.c (c0000000006480dc)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (c0000000006556d0)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In mm/filemap.c (ffffffe0001d6d4a)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffe0001e0dce)
Location: include/linux/page-flags.h:492
Inline: True
```
```
In mm/shmem.c (ffffffe0001f13ea)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffe000208b0a)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffe00020b918)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/ksm.c (ffffffe000236284)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffe00023e412)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/read_write.c (ffffffe000255c12)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:vfs_dedupe_get_page
```
```
In fs/namei.c (ffffffe0002614a6)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffe000281004)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffe00028a254)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffe000295106)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_end
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty
```
```
In fs/mpage.c (ffffffe00029b490)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/verity/verify.c (ffffffe0002badde)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/iomap/buffered-io.c (ffffffe0002c93c0)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/seek.c (ffffffe0002ca85a)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inline.c (ffffffe000305516)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffffffe00030a356)
Location: include/linux/page-flags.h:492
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
In fs/ext4/mballoc.c (ffffffe00031584a)
Location: include/linux/page-flags.h:492
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
In fs/ext4/move_extent.c (ffffffe00031d52a)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffe000325b8e)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffe00035091a)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffe000352b04)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffe000364fc2)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/dev.c (ffffffe0003703c0)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffe0003791e0)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In kernel/events/uprobes.c (ffffffff8121314d)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8121c2b2)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81227752)
Location: include/linux/page-flags.h:492
Inline: True
```
```
In mm/shmem.c (ffffffff8123bcf4)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff81259890)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8125e123)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/ksm.c (ffffffff8129ab9f)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812a56d8)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff812b45e8)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/read_write.c (ffffffff812d3cda)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/namei.c (ffffffff812e14a1)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8130482b)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff8130eab2)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8131c19a)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_end
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty
```
```
In fs/mpage.c (ffffffff81322f02)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/verity/verify.c (ffffffff813497e0)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/iomap/buffered-io.c (ffffffff8135d6a9)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/seek.c (ffffffff8135ed11)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inline.c (ffffffff8139fbde)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffffffff813a5520)
Location: include/linux/page-flags.h:492
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
In fs/ext4/mballoc.c (ffffffff813b26be)
Location: include/linux/page-flags.h:492
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
In fs/ext4/move_extent.c (ffffffff813ba920)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff813c4b29)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffff813f61bb)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813f86bf)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff8140cfdc)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/dev.c (ffffffff81418f73)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff81422bd8)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In kernel/events/uprobes.c (ffffffff81205ebd)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8120f4a2)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8121a8c2)
Location: include/linux/page-flags.h:492
Inline: True
```
```
In mm/shmem.c (ffffffff8122ecf4)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff8124bcd0)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff812505b3)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/ksm.c (ffffffff8128c75f)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812971a8)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff812a5665)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/read_write.c (ffffffff812c495a)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/namei.c (ffffffff812d20e1)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812f544b)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff812ff6c2)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8130cd3a)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_end
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty
```
```
In fs/mpage.c (ffffffff81313aa2)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/verity/verify.c (ffffffff8133a4c0)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/iomap/buffered-io.c (ffffffff8134e349)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/seek.c (ffffffff8134f9b1)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inline.c (ffffffff8139066e)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffffffff81395fb0)
Location: include/linux/page-flags.h:492
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
In fs/ext4/mballoc.c (ffffffff813a314e)
Location: include/linux/page-flags.h:492
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
In fs/ext4/move_extent.c (ffffffff813ab3b0)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff813b55a9)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffff813e6c3b)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813e913f)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff813fda5c)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/dev.c (ffffffff814099f3)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff81413658)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In kernel/events/uprobes.c (ffffffff81210eed)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8121a052)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff812254f2)
Location: include/linux/page-flags.h:492
Inline: True
```
```
In mm/shmem.c (ffffffff81239a94)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff81257630)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8125bec3)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/ksm.c (ffffffff812989af)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812a34e8)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff812b23f8)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/read_write.c (ffffffff812d1aea)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/namei.c (ffffffff812df2b1)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8130261b)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff8130c8a2)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff81319c6a)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_end
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty
```
```
In fs/mpage.c (ffffffff813209d2)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/verity/verify.c (ffffffff813472b0)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/iomap/buffered-io.c (ffffffff8135b179)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/seek.c (ffffffff8135c7e1)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inline.c (ffffffff8139d43e)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffffffff813a2d80)
Location: include/linux/page-flags.h:492
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
In fs/ext4/mballoc.c (ffffffff813aff1e)
Location: include/linux/page-flags.h:492
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
In fs/ext4/move_extent.c (ffffffff813b8180)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff813c1fb9)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffff813f353b)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813f5a3f)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff8140a35c)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/dev.c (ffffffff81415113)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff8141ed78)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
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
In kernel/events/uprobes.c (ffffffff8121fe32)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff81229143)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff812347f2)
Location: include/linux/page-flags.h:492
Inline: True
```
```
In mm/shmem.c (ffffffff81249184)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff81267017)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8126b8b3)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/ksm.c (ffffffff812a875f)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812b3cf8)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/khugepaged.c (ffffffff812c27ff)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/read_write.c (ffffffff812e28fe)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/namei.c (ffffffff812f06a1)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81313c37)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/splice.c (ffffffff8131e0c8)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8132b92a)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_write_end
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty
```
```
In fs/mpage.c (ffffffff813326f2)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/verity/verify.c (ffffffff8135a5b0)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/iomap/buffered-io.c (ffffffff8136e8f2)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/seek.c (ffffffff8136fee3)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inline.c (ffffffff813b19ae)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffffffff813b7460)
Location: include/linux/page-flags.h:492
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
In fs/ext4/mballoc.c (ffffffff813c497d)
Location: include/linux/page-flags.h:492
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
In fs/ext4/move_extent.c (ffffffff813cce80)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff813d7139)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffff8140914b)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8140b68f)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff8142004c)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/dev.c (ffffffff8142be90)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff81435ad8)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
```
</details>
</li>
</ul>

## Differences
