# Function: <code>i_blocksize</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811cd13b)
Location: include/linux/fs.h:671
Inline: True
```
```
In fs/stat.c (ffffffff81256413)
Location: include/linux/fs.h:671
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/buffer.c (ffffffff8128b682)
Location: include/linux/fs.h:671
Inline: True
Inline callers:
  - fs/buffer.c:generic_block_bmap
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
```
```
In fs/block_dev.c (ffffffff81290b0f)
Location: include/linux/fs.h:671
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/mpage.c (0)
Location: include/linux/fs.h:671
Inline: True
```
```
In fs/iomap.c (ffffffff812be18a)
Location: include/linux/fs.h:671
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_truncate_page
```
```
In fs/ext4/inode.c (ffffffff813073fc)
Location: include/linux/fs.h:671
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/mballoc.c (ffffffff8130bc46)
Location: include/linux/fs.h:671
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff8131535c)
Location: include/linux/fs.h:671
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/xattr.c (ffffffff8133b1bf)
Location: include/linux/fs.h:671
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In mm/truncate.c (ffffffff811e2474)
Location: include/linux/fs.h:675
Inline: True
```
```
In fs/stat.c (ffffffff81278653)
Location: include/linux/fs.h:675
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/buffer.c (ffffffff812ae202)
Location: include/linux/fs.h:675
Inline: True
Inline callers:
  - fs/buffer.c:generic_block_bmap
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
```
```
In fs/block_dev.c (ffffffff812b37ef)
Location: include/linux/fs.h:675
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/mpage.c (0)
Location: include/linux/fs.h:675
Inline: True
```
```
In fs/iomap.c (ffffffff812e1a8f)
Location: include/linux/fs.h:675
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_truncate_page
```
```
In fs/ext4/inode.c (ffffffff8132bfe5)
Location: include/linux/fs.h:675
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/mballoc.c (ffffffff81330796)
Location: include/linux/fs.h:675
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff81339b68)
Location: include/linux/fs.h:675
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/xattr.c (ffffffff8135f8f5)
Location: include/linux/fs.h:675
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In mm/truncate.c (ffffffff81203570)
Location: include/linux/fs.h:677
Inline: True
```
```
In fs/stat.c (ffffffff8129f07a)
Location: include/linux/fs.h:677
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/buffer.c (ffffffff812d6022)
Location: include/linux/fs.h:677
Inline: True
Inline callers:
  - fs/buffer.c:generic_block_bmap
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
```
```
In fs/block_dev.c (ffffffff812dcbb7)
Location: include/linux/fs.h:677
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/mpage.c (ffffffff812e3436)
Location: include/linux/fs.h:677
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap.c (ffffffff8130fcb8)
Location: include/linux/fs.h:677
Inline: True
Inline callers:
  - fs/iomap.c:iomap_bmap
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:page_cache_seek_hole_data
  - fs/iomap.c:iomap_truncate_page
```
```
In fs/ext4/inode.c (ffffffff8135a5dd)
Location: include/linux/fs.h:677
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:mpage_process_page_bufs
```
```
In fs/ext4/mballoc.c (ffffffff8135ed55)
Location: include/linux/fs.h:677
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff8136819a)
Location: include/linux/fs.h:677
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/xattr.c (ffffffff8138e690)
Location: include/linux/fs.h:677
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In mm/truncate.c (ffffffff812164b1)
Location: include/linux/fs.h:714
Inline: True
```
```
In fs/read_write.c (ffffffff812ad23b)
Location: include/linux/fs.h:714
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/stat.c (ffffffff812b405a)
Location: include/linux/fs.h:714
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/buffer.c (ffffffff812eb3f2)
Location: include/linux/fs.h:714
Inline: True
Inline callers:
  - fs/buffer.c:generic_block_bmap
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
```
```
In fs/block_dev.c (ffffffff812f2877)
Location: include/linux/fs.h:714
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/mpage.c (ffffffff812f8105)
Location: include/linux/fs.h:714
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap.c (ffffffff81326c49)
Location: include/linux/fs.h:714
Inline: True
Inline callers:
  - fs/iomap.c:iomap_bmap
  - fs/iomap.c:iomap_dio_bio_actor
  - fs/iomap.c:page_cache_seek_hole_data
  - fs/iomap.c:iomap_truncate_page
  - fs/iomap.c:iomap_set_range_uptodate
```
```
In fs/ext4/inode.c (ffffffff81372929)
Location: include/linux/fs.h:714
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:mpage_process_page_bufs
```
```
In fs/ext4/mballoc.c (ffffffff813771e7)
Location: include/linux/fs.h:714
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff8138061d)
Location: include/linux/fs.h:714
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/xattr.c (ffffffff813a6c50)
Location: include/linux/fs.h:714
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In mm/truncate.c (ffffffff81225e8a)
Location: include/linux/fs.h:729
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In fs/read_write.c (ffffffff812c9da9)
Location: include/linux/fs.h:729
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/stat.c (ffffffff812d0dba)
Location: include/linux/fs.h:729
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/buffer.c (ffffffff8130caa2)
Location: include/linux/fs.h:729
Inline: True
Inline callers:
  - fs/buffer.c:generic_block_bmap
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
```
```
In fs/block_dev.c (ffffffff81314422)
Location: include/linux/fs.h:729
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/mpage.c (ffffffff81318740)
Location: include/linux/fs.h:729
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8134b035)
Location: include/linux/fs.h:729
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/iomap/direct-io.c (ffffffff8134d834)
Location: include/linux/fs.h:729
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/iomap/fiemap.c (ffffffff8134dd79)
Location: include/linux/fs.h:729
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/iomap/seek.c (ffffffff8134e268)
Location: include/linux/fs.h:729
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff8139bd37)
Location: include/linux/fs.h:729
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:mpage_process_page_bufs
```
```
In fs/ext4/mballoc.c (ffffffff813a06f6)
Location: include/linux/fs.h:729
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff813a9473)
Location: include/linux/fs.h:729
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813b2d2c)
Location: include/linux/fs.h:729
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/xattr.c (ffffffff813d13c9)
Location: include/linux/fs.h:729
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In mm/truncate.c (ffffffff81233cdc)
Location: include/linux/fs.h:743
Inline: True
```
```
In fs/read_write.c (ffffffff812db51a)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/stat.c (ffffffff812e294a)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/buffer.c (ffffffff8131fab2)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/buffer.c:generic_block_bmap
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
```
```
In fs/block_dev.c (ffffffff81326d92)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/mpage.c (ffffffff8132b59e)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff813632d5)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/iomap/direct-io.c (ffffffff81365af2)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/iomap/fiemap.c (ffffffff81366069)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/iomap/seek.c (ffffffff81366558)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813b4833)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:mpage_process_page_bufs
```
```
In fs/ext4/mballoc.c (ffffffff813b9567)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff813c2393)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813cbd9a)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/xattr.c (ffffffff813eaaa9)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
```
In fs/ext4/verity.c (ffffffff813ef188)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In mm/truncate.c (ffffffff81261305)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In fs/read_write.c (ffffffff81311b02)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/stat.c (ffffffff81319cca)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/buffer.c (ffffffff813591f2)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/buffer.c:generic_block_bmap
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_expand_zero
```
```
In fs/block_dev.c (ffffffff81360f32)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/mpage.c (ffffffff8136522e)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff813ab6ca)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_finish_page_writeback
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
```
```
In fs/iomap/direct-io.c (ffffffff813acf51)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/iomap/fiemap.c (ffffffff813add55)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/iomap/seek.c (ffffffff813ae0c9)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813ffcd1)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:mpage_process_page_bufs
```
```
In fs/ext4/mballoc.c (ffffffff81405088)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff8140ea6b)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81417f31)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/xattr.c (ffffffff81438069)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
```
In fs/ext4/verity.c (ffffffff8143c0e8)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In mm/truncate.c (ffffffff8126b705)
Location: include/linux/fs.h:724
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In fs/stat.c (ffffffff8132535a)
Location: include/linux/fs.h:724
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/remap_range.c (ffffffff81366e89)
Location: include/linux/fs.h:724
Inline: True
Inline callers:
  - fs/remap_range.c:generic_remap_file_range_prep
```
```
In fs/buffer.c (ffffffff81366fc2)
Location: include/linux/fs.h:724
Inline: True
Inline callers:
  - fs/buffer.c:generic_block_bmap
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_expand_zero
```
```
In fs/mpage.c (ffffffff8137224a)
Location: include/linux/fs.h:724
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff813bc071)
Location: include/linux/fs.h:724
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/iomap/buffered-io.c:__iomap_write_begin
```
```
In fs/iomap/direct-io.c (ffffffff813be63e)
Location: include/linux/fs.h:724
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/iomap/fiemap.c (ffffffff813bf3c5)
Location: include/linux/fs.h:724
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/iomap/seek.c (ffffffff813bf739)
Location: include/linux/fs.h:724
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff814124e2)
Location: include/linux/fs.h:724
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:mpage_process_page_bufs
```
```
In fs/ext4/mballoc.c (ffffffff814182f3)
Location: include/linux/fs.h:724
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff81421fa5)
Location: include/linux/fs.h:724
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff8142bbb0)
Location: include/linux/fs.h:724
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/xattr.c (ffffffff81450b99)
Location: include/linux/fs.h:724
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
```
In fs/ext4/verity.c (ffffffff81458445)
Location: include/linux/fs.h:724
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In drivers/md/md-bitmap.c (ffffffff81977cc3)
Location: include/linux/fs.h:724
Inline: True
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
In mm/filemap.c (ffffffff81263336)
Location: include/linux/fs.h:725
Inline: True
Inline callers:
  - mm/filemap.c:mapping_seek_hole_data
```
```
In mm/truncate.c (ffffffff81270295)
Location: include/linux/fs.h:725
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In fs/stat.c (ffffffff8132b560)
Location: include/linux/fs.h:725
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/remap_range.c (ffffffff8136d7df)
Location: include/linux/fs.h:725
Inline: True
Inline callers:
  - fs/remap_range.c:generic_remap_file_range_prep
```
```
In fs/buffer.c (ffffffff8136d9b2)
Location: include/linux/fs.h:725
Inline: True
Inline callers:
  - fs/buffer.c:generic_block_bmap
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_expand_zero
```
```
In fs/mpage.c (ffffffff8137834e)
Location: include/linux/fs.h:725
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff813c354e)
Location: include/linux/fs.h:725
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/iomap/buffered-io.c:__iomap_write_begin
```
```
In fs/iomap/direct-io.c (ffffffff813c5c2e)
Location: include/linux/fs.h:725
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/iomap/fiemap.c (ffffffff813c6505)
Location: include/linux/fs.h:725
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/ext4/inode.c (ffffffff8141894c)
Location: include/linux/fs.h:725
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:mpage_process_page_bufs
```
```
In fs/ext4/mballoc.c (ffffffff8141eb56)
Location: include/linux/fs.h:725
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff81428658)
Location: include/linux/fs.h:725
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81432879)
Location: include/linux/fs.h:725
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/xattr.c (ffffffff814562d9)
Location: include/linux/fs.h:725
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
```
In fs/ext4/verity.c (ffffffff8145dde7)
Location: include/linux/fs.h:725
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In drivers/md/md-bitmap.c (ffffffff8195b7cd)
Location: include/linux/fs.h:725
Inline: True
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
In mm/filemap.c (ffffffff8129fa8a)
Location: include/linux/fs.h:737
Inline: True
Inline callers:
  - mm/filemap.c:mapping_seek_hole_data
```
```
In mm/truncate.c (ffffffff812ad525)
Location: include/linux/fs.h:737
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In fs/stat.c (ffffffff81378ccd)
Location: include/linux/fs.h:737
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/remap_range.c (ffffffff813bc4fa)
Location: include/linux/fs.h:737
Inline: True
Inline callers:
  - fs/remap_range.c:generic_remap_file_range_prep
```
```
In fs/buffer.c (ffffffff813bcf4e)
Location: include/linux/fs.h:737
Inline: True
Inline callers:
  - fs/buffer.c:generic_block_bmap
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_expand_zero
```
```
In fs/mpage.c (ffffffff813c4871)
Location: include/linux/fs.h:737
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff81413bf5)
Location: include/linux/fs.h:737
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/iomap/buffered-io.c:__iomap_write_begin
```
```
In fs/iomap/direct-io.c (ffffffff8141559a)
Location: include/linux/fs.h:737
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/iomap/fiemap.c (ffffffff81416295)
Location: include/linux/fs.h:737
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/ext4/inode.c (ffffffff8146bb4c)
Location: include/linux/fs.h:737
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:mpage_process_page_bufs
```
```
In fs/ext4/mballoc.c (ffffffff81472249)
Location: include/linux/fs.h:737
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff8147c387)
Location: include/linux/fs.h:737
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81486141)
Location: include/linux/fs.h:737
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/xattr.c (ffffffff814aa2d2)
Location: include/linux/fs.h:737
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
```
In fs/ext4/verity.c (ffffffff814b32fb)
Location: include/linux/fs.h:737
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In drivers/md/md-bitmap.c (ffffffff81a00fbd)
Location: include/linux/fs.h:737
Inline: True
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
In mm/filemap.c (ffffffff812f6b17)
Location: include/linux/fs.h:692
Inline: True
Inline callers:
  - mm/filemap.c:mapping_seek_hole_data
```
```
In mm/truncate.c (ffffffff81307fa5)
Location: include/linux/fs.h:692
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In fs/stat.c (ffffffff813f80f5)
Location: include/linux/fs.h:692
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/remap_range.c (ffffffff814422b1)
Location: include/linux/fs.h:692
Inline: True
Inline callers:
  - fs/remap_range.c:generic_remap_file_range_prep
```
```
In fs/buffer.c (ffffffff8144315e)
Location: include/linux/fs.h:692
Inline: True
Inline callers:
  - fs/buffer.c:generic_block_bmap
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_expand_zero
```
```
In fs/mpage.c (ffffffff8144b912)
Location: include/linux/fs.h:692
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/dax.c (ffffffff81467d95)
Location: include/linux/fs.h:692
Inline: True
Inline callers:
  - fs/dax.c:dax_truncate_page
```
```
In fs/crypto/inline_crypt.c (ffffffff81471781)
Location: include/linux/fs.h:692
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_dio_supported
```
```
In fs/iomap/buffered-io.c (ffffffff814897b1)
Location: include/linux/fs.h:692
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/iomap/buffered-io.c:__iomap_write_begin
```
```
In fs/iomap/direct-io.c (ffffffff8148ccf6)
Location: include/linux/fs.h:692
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/iomap/fiemap.c (ffffffff8148db56)
Location: include/linux/fs.h:692
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/ext4/inode.c (ffffffff814e0c79)
Location: include/linux/fs.h:692
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:mpage_process_page_bufs
```
```
In fs/ext4/mballoc.c (ffffffff814f318f)
Location: include/linux/fs.h:692
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff814feb57)
Location: include/linux/fs.h:692
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff8150979f)
Location: include/linux/fs.h:692
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/xattr.c (ffffffff81532671)
Location: include/linux/fs.h:692
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
```
In fs/ext4/verity.c (ffffffff8153bef7)
Location: include/linux/fs.h:692
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In drivers/md/md-bitmap.c (ffffffff81b68705)
Location: include/linux/fs.h:692
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
In mm/filemap.c (ffffffff813603d3)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - mm/filemap.c:mapping_seek_hole_data
```
```
In mm/truncate.c (ffffffff81371f55)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In fs/stat.c (ffffffff81481582)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/remap_range.c (ffffffff814d158e)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/remap_range.c:__generic_remap_file_range_prep
```
```
In fs/buffer.c (ffffffff814d24be)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/buffer.c:generic_block_bmap
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_expand_zero
```
```
In fs/mpage.c (ffffffff814da03a)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/dax.c (ffffffff814f8df5)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/dax.c:dax_truncate_page
```
```
In fs/iomap/buffered-io.c (ffffffff8151d68f)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/iomap/buffered-io.c:iomap_file_buffered_write_punch_delalloc
  - fs/iomap/buffered-io.c:__iomap_write_begin
```
```
In fs/iomap/direct-io.c (ffffffff8152020b)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/iomap/fiemap.c (ffffffff81521336)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/ext4/inode.c (ffffffff81580724)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dio_alignment
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:mpage_process_page_bufs
```
```
In fs/ext4/mballoc.c (ffffffff8158d7ae)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff815993a7)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff815a437f)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/xattr.c (ffffffff815d0b31)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
```
In fs/ext4/verity.c (ffffffff815da5a7)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In drivers/md/md-bitmap.c (ffffffff81d041a5)
Location: include/linux/fs.h:707
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
In mm/filemap.c (ffffffff81392957)
Location: include/linux/fs.h:722
Inline: True
Inline callers:
  - mm/filemap.c:mapping_seek_hole_data
```
```
In mm/truncate.c (ffffffff813a40f5)
Location: include/linux/fs.h:722
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In fs/stat.c (ffffffff814b615f)
Location: include/linux/fs.h:722
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/remap_range.c (ffffffff81507d04)
Location: include/linux/fs.h:722
Inline: True
Inline callers:
  - fs/remap_range.c:__generic_remap_file_range_prep
```
```
In fs/buffer.c (ffffffff81508f8e)
Location: include/linux/fs.h:722
Inline: True
Inline callers:
  - fs/buffer.c:generic_block_bmap
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_expand_zero
```
```
In fs/mpage.c (ffffffff8150dfa0)
Location: include/linux/fs.h:722
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/dax.c (ffffffff81530155)
Location: include/linux/fs.h:722
Inline: True
Inline callers:
  - fs/dax.c:dax_truncate_page
```
```
In fs/iomap/buffered-io.c (ffffffff81555936)
Location: include/linux/fs.h:722
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/iomap/buffered-io.c:iomap_file_buffered_write_punch_delalloc
  - fs/iomap/buffered-io.c:__iomap_write_begin
```
```
In fs/iomap/direct-io.c (ffffffff8155827b)
Location: include/linux/fs.h:722
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/iomap/fiemap.c (ffffffff81559376)
Location: include/linux/fs.h:722
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/ext4/inode.c (ffffffff815b7ce4)
Location: include/linux/fs.h:722
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dio_alignment
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:mpage_process_page_bufs
```
```
In fs/ext4/mballoc.c (ffffffff815c41ff)
Location: include/linux/fs.h:722
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff815cfd1e)
Location: include/linux/fs.h:722
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff815dacd4)
Location: include/linux/fs.h:722
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/ext4/xattr.c (ffffffff816082f4)
Location: include/linux/fs.h:722
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
```
In fs/ext4/verity.c (ffffffff8161237a)
Location: include/linux/fs.h:722
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In drivers/md/md-bitmap.c (ffffffff81d6cf35)
Location: include/linux/fs.h:722
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
In mm/filemap.c (ffffffff813bc615)
Location: include/linux/fs.h:755
Inline: True
Inline callers:
  - mm/filemap.c:mapping_seek_hole_data
```
```
In mm/truncate.c (ffffffff813cdc45)
Location: include/linux/fs.h:755
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In fs/stat.c (ffffffff814e8474)
Location: include/linux/fs.h:755
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/remap_range.c (ffffffff8153cb44)
Location: include/linux/fs.h:755
Inline: True
Inline callers:
  - fs/remap_range.c:__generic_remap_file_range_prep
```
```
In fs/buffer.c (ffffffff8153dc1e)
Location: include/linux/fs.h:755
Inline: True
Inline callers:
  - fs/buffer.c:generic_block_bmap
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_expand_zero
```
```
In fs/mpage.c (ffffffff81542b98)
Location: include/linux/fs.h:755
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/dax.c (ffffffff81565035)
Location: include/linux/fs.h:755
Inline: True
Inline callers:
  - fs/dax.c:dax_truncate_page
```
```
In fs/iomap/buffered-io.c (ffffffff8158bb9e)
Location: include/linux/fs.h:755
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/iomap/buffered-io.c:iomap_file_buffered_write_punch_delalloc
  - fs/iomap/buffered-io.c:__iomap_write_begin
```
```
In fs/iomap/direct-io.c (ffffffff8158e8ab)
Location: include/linux/fs.h:755
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
```
In fs/iomap/fiemap.c (ffffffff8158fb06)
Location: include/linux/fs.h:755
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/ext4/inode.c (ffffffff815f0a64)
Location: include/linux/fs.h:755
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dio_alignment
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:mpage_process_page_bufs
```
```
In fs/ext4/mballoc.c (ffffffff815fc4ff)
Location: include/linux/fs.h:755
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff8160859b)
Location: include/linux/fs.h:755
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81613520)
Location: include/linux/fs.h:755
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/ext4/xattr.c (ffffffff81641034)
Location: include/linux/fs.h:755
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
```
In fs/ext4/verity.c (ffffffff8164b04a)
Location: include/linux/fs.h:755
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/verity.c:ext4_end_enable_verity
```
```
In drivers/md/md-bitmap.c (ffffffff81e24164)
Location: include/linux/fs.h:755
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
In mm/truncate.c (ffff8000102c3b6c)
Location: include/linux/fs.h:743
Inline: True
```
```
In fs/read_write.c (ffff800010380a68)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/stat.c (ffff80001038a52c)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/stat.c:vfs_getattr_nosec
```
```
In fs/buffer.c (ffff8000103d75c8)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/buffer.c:generic_block_bmap
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
```
```
In fs/block_dev.c (ffff8000103e1cac)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/mpage.c (ffff8000103e6b9c)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffff80001042a1f8)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/iomap/direct-io.c (ffff80001042c998)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/iomap/fiemap.c (ffff80001042d72c)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/iomap/seek.c (ffff80001042dcfc)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffff800010488f48)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:mpage_process_page_bufs
```
```
In fs/ext4/mballoc.c (ffff80001048ff10)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffff800010499dc8)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffff8000104a4218)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/xattr.c (ffff8000104c38ec)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
```
In fs/ext4/verity.c (ffff8000104c84a4)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In mm/truncate.c (c04eec1c)
Location: include/linux/fs.h:743
Inline: True
```
```
In fs/read_write.c (c056b824)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/stat.c (c0572650)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/buffer.c (c05b1058)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/buffer.c:generic_block_bmap
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
```
```
In fs/block_dev.c (c05b7dd0)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/mpage.c (c05be928)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (c05f29f0)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/iomap/direct-io.c (c05f5584)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/iomap/fiemap.c (c05f6638)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/iomap/seek.c (c05f6c78)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (c064b470)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:mpage_process_page_bufs
```
```
In fs/ext4/mballoc.c (c0650ee8)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (c065b5d8)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (c0666018)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/xattr.c (c0687dc4)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
```
In fs/ext4/verity.c (c068c420)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In mm/truncate.c (c00000000037e7a0)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In fs/read_write.c (c000000000476eb4)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/stat.c (c000000000481570)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/buffer.c (c0000000004dba38)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/buffer.c:generic_block_bmap
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
```
```
In fs/block_dev.c (c0000000004e4b70)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/mpage.c (c0000000004ed088)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (c00000000053a560)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/iomap/direct-io.c (c00000000053e038)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/iomap/fiemap.c (c00000000053e7d0)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/iomap/seek.c (c00000000053efd4)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (c0000000005afd0c)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:mpage_process_page_bufs
```
```
In fs/ext4/mballoc.c (c0000000005b7098)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (c0000000005c4090)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (c0000000005d1408)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/xattr.c (c0000000005fb1bc)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
```
In fs/ext4/verity.c (c0000000006011e8)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In mm/truncate.c (ffffffe0001e4cf8)
Location: include/linux/fs.h:743
Inline: True
```
```
In fs/read_write.c (ffffffe000255ab0)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/stat.c (ffffffe00025c2e6)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/buffer.c (ffffffe000290eb6)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/buffer.c:generic_block_bmap
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
```
```
In fs/block_dev.c (ffffffe00029815e)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/mpage.c (ffffffe00029be7e)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffe0002c7b82)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/iomap/direct-io.c (ffffffe0002c9d6c)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/iomap/fiemap.c (ffffffe0002ca240)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/iomap/seek.c (ffffffe0002ca73e)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffe00031085c)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:mpage_process_page_bufs
```
```
In fs/ext4/mballoc.c (ffffffe000314e8e)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffe00031d56c)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffe000325688)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/xattr.c (ffffffe00033e6d4)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
```
In fs/ext4/verity.c (ffffffe000342346)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In mm/truncate.c (ffffffff8122c32c)
Location: include/linux/fs.h:743
Inline: True
```
```
In fs/read_write.c (ffffffff812d3afa)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/stat.c (ffffffff812daf2a)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/buffer.c (ffffffff81318092)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/buffer.c:generic_block_bmap
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
```
```
In fs/block_dev.c (ffffffff8131f372)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/mpage.c (ffffffff81323b7e)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8135b8b5)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/iomap/direct-io.c (ffffffff8135e0d2)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/iomap/fiemap.c (ffffffff8135e649)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/iomap/seek.c (ffffffff8135eb38)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813ace13)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:mpage_process_page_bufs
```
```
In fs/ext4/mballoc.c (ffffffff813b1b47)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff813ba973)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813c437a)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/xattr.c (ffffffff813e3089)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
```
In fs/ext4/verity.c (ffffffff813e7768)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In mm/truncate.c (ffffffff8121f40c)
Location: include/linux/fs.h:743
Inline: True
```
```
In fs/read_write.c (ffffffff812c477a)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/stat.c (ffffffff812cbbaa)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/buffer.c (ffffffff81308c82)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/buffer.c:generic_block_bmap
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
```
```
In fs/block_dev.c (ffffffff8130ff12)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/mpage.c (ffffffff8131471e)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8134c555)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/iomap/direct-io.c (ffffffff8134ed72)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/iomap/fiemap.c (ffffffff8134f2e9)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/iomap/seek.c (ffffffff8134f7d8)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff8139d8a3)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:mpage_process_page_bufs
```
```
In fs/ext4/mballoc.c (ffffffff813a25d7)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff813ab403)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813b4dfa)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/xattr.c (ffffffff813d3b09)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
```
In fs/ext4/verity.c (ffffffff813d81e8)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In mm/truncate.c (ffffffff8122a0cc)
Location: include/linux/fs.h:743
Inline: True
```
```
In fs/read_write.c (ffffffff812d190a)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/stat.c (ffffffff812d8d3a)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/buffer.c (ffffffff81315b62)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/buffer.c:generic_block_bmap
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
```
```
In fs/block_dev.c (ffffffff8131ce42)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/mpage.c (ffffffff8132164e)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff81359385)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/iomap/direct-io.c (ffffffff8135bba2)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/iomap/fiemap.c (ffffffff8135c119)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/iomap/seek.c (ffffffff8135c608)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813aa673)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:mpage_process_page_bufs
```
```
In fs/ext4/mballoc.c (ffffffff813af3a7)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff813b81d3)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813c180a)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/xattr.c (ffffffff813e0409)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
```
In fs/ext4/verity.c (ffffffff813e4ae8)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_end_enable_verity
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
In mm/truncate.c (ffffffff812394bc)
Location: include/linux/fs.h:743
Inline: True
```
```
In fs/read_write.c (ffffffff812e2737)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/stat.c (ffffffff812e9b6a)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/buffer.c (ffffffff813276d2)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/buffer.c:generic_block_bmap
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
```
```
In fs/block_dev.c (ffffffff8132d222)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/mpage.c (ffffffff813333a2)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8136ca85)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_truncate_page
  - fs/iomap/buffered-io.c:iomap_set_range_uptodate
```
```
In fs/iomap/direct-io.c (ffffffff8136f2f2)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
```
In fs/iomap/fiemap.c (ffffffff8136f869)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/fiemap.c:iomap_bmap
```
```
In fs/iomap/seek.c (ffffffff8136fd4f)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/ext4/inode.c (ffffffff813bef88)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:mpage_process_page_bufs
```
```
In fs/ext4/mballoc.c (ffffffff813c3db7)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff813cced3)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813d696a)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/xattr.c (ffffffff813f5829)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
```
In fs/ext4/verity.c (ffffffff813f9f38)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_end_enable_verity
```
</details>
</li>
</ul>

## Differences
