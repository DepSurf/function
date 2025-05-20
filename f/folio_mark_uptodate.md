# Function: <code>folio_mark_uptodate</code>

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
In mm/filemap.c (ffffffff812f1ea1)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - mm/filemap.c:page_endio
```
```
In mm/shmem.c (ffffffff8131b2e8)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (ffffffff8137a5ee)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff81385b5a)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (ffffffff813b08c3)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/khugepaged.c (ffffffff813c599a)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff8142c829)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_read_folio
```
```
In fs/buffer.c (ffffffff81447136)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff8144ba98)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff81463582)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/iomap/buffered-io.c (ffffffff8148a41a)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
```
```
In fs/ext4/inline.c (ffffffff814dc25d)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff814eaf4e)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffffffff814f3867)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff814fed9f)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff8150a60c)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffffffff8154eb51)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81550d66)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/file_direct.c (ffffffff81551589)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff815696c0)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffffffff81569a36)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff815771ae)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/dir.c (ffffffff81579002)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_symlink_read_folio
```
```
In fs/fuse/file.c (ffffffff8157f910)
Location: include/linux/page-flags.h:740
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
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
In mm/filemap.c (ffffffff8135bd5a)
Location: include/linux/page-flags.h:737
Inline: True
Inline callers:
  - mm/filemap.c:page_endio
```
```
In mm/shmem.c (ffffffff8138dcb5)
Location: include/linux/page-flags.h:737
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (ffffffff813f8097)
Location: include/linux/page-flags.h:737
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/zswap.c (ffffffff81403949)
Location: include/linux/page-flags.h:737
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (ffffffff81431437)
Location: include/linux/page-flags.h:737
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/khugepaged.c (ffffffff8144a3d8)
Location: include/linux/page-flags.h:737
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff814ba099)
Location: include/linux/page-flags.h:737
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_read_folio
```
```
In fs/buffer.c (ffffffff814d5296)
Location: include/linux/page-flags.h:737
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff814da127)
Location: include/linux/page-flags.h:737
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff814f2672)
Location: include/linux/page-flags.h:737
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/iomap/buffered-io.c (ffffffff8151de2b)
Location: include/linux/page-flags.h:737
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
```
```
In fs/ext4/inline.c (ffffffff8157520d)
Location: include/linux/page-flags.h:737
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81584afe)
Location: include/linux/page-flags.h:737
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffffffff8158de43)
Location: include/linux/page-flags.h:737
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff815995f9)
Location: include/linux/page-flags.h:737
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff815a5438)
Location: include/linux/page-flags.h:737
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/file.c (ffffffff815ef0b9)
Location: include/linux/page-flags.h:737
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff815f1ac1)
Location: include/linux/page-flags.h:737
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/file_direct.c (ffffffff815f255e)
Location: include/linux/page-flags.h:737
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff8160d24e)
Location: include/linux/page-flags.h:737
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffffffff8160d665)
Location: include/linux/page-flags.h:737
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8161b88e)
Location: include/linux/page-flags.h:737
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/dir.c (ffffffff8161e612)
Location: include/linux/page-flags.h:737
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_symlink_read_folio
```
```
In fs/fuse/file.c (ffffffff816255f0)
Location: include/linux/page-flags.h:737
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/readdir.c (ffffffff8162eeea)
Location: include/linux/page-flags.h:737
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
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
In mm/shmem.c (ffffffff813c23c9)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (ffffffff8142b0ce)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:__end_swap_bio_read
```
```
In mm/zswap.c (ffffffff8143789a)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (ffffffff81466db7)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/khugepaged.c (ffffffff81480365)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff814eef8d)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_read_folio
```
```
In fs/buffer.c (ffffffff8150b19f)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff8150e055)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:mpage_read_end_io
```
```
In fs/aio.c (ffffffff815292a8)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/iomap/buffered-io.c (ffffffff81555fc6)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
```
```
In fs/ext4/inline.c (ffffffff815aceff)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_folio
```
```
In fs/ext4/inode.c (ffffffff815bb4e8)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffffffff815c465c)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff815cff2c)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/readpage.c (ffffffff815dbd28)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:__read_end_io
```
```
In fs/squashfs/block.c (ffffffff81623ff3)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read_cached
  - fs/squashfs/block.c:squashfs_bio_read_cached
```
```
In fs/squashfs/file.c (ffffffff81627099)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81629bb1)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/file_direct.c (ffffffff8162a64d)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff8164510e)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffffffff81645524)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff816539f5)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/dir.c (ffffffff81656a42)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_symlink_read_folio
```
```
In fs/fuse/file.c (ffffffff8165d94e)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/readdir.c (ffffffff8166714d)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
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
In mm/shmem.c (ffffffff813ed14a)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_writepage
```
```
In mm/page_io.c (ffffffff814648bc)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - mm/page_io.c:swap_read_folio
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:__end_swap_bio_read
```
```
In mm/zswap.c (ffffffff81470095)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (ffffffff81496017)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/khugepaged.c (ffffffff814ae455)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff81522c0b)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_read_folio
```
```
In fs/buffer.c (ffffffff8153d2f8)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - fs/buffer.c:__block_commit_write
```
```
In fs/mpage.c (ffffffff81542bd7)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:mpage_read_end_io
```
```
In fs/aio.c (ffffffff8155e178)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/iomap/buffered-io.c (ffffffff8158b263)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/ext4/inline.c (ffffffff815e5caf)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_folio
```
```
In fs/ext4/inode.c (ffffffff815f42c8)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffffffff815fc8ff)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff816087a9)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/squashfs/block.c (ffffffff8165d093)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read_cached
  - fs/squashfs/block.c:squashfs_bio_read_cached
```
```
In fs/squashfs/file.c (ffffffff8166024c)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81662e01)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/file_direct.c (ffffffff81663971)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff8167e63b)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_writepage
```
```
In fs/ecryptfs/read_write.c (ffffffff8167ea1d)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8168d002)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/dir.c (ffffffff816902c2)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_symlink_read_folio
```
```
In fs/fuse/file.c (ffffffff8169768b)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
```
In fs/fuse/readdir.c (ffffffff816a149a)
Location: include/linux/page-flags.h:752
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
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
