# Function: <code>zero_user_segments</code>

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
In mm/truncate.c (ffffffff8119f233)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811a8b7a)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (ffffffff81234b63)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/buffer.c (ffffffff81244469)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_writepage
```
```
In fs/direct-io.c (ffffffff8124a4a0)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff8124dc51)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inode.c (ffffffff812976a1)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/page-io.c (ffffffff812a0041)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/move_extent.c (ffffffff812d682e)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff812e0532)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/readpage.c (ffffffff812e2ee0)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff813043bd)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffffffff8131659a)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_short_read
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
In mm/truncate.c (ffffffff811b4e8b)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811c0116)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (ffffffff8125d061)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/buffer.c (ffffffff8126cea3)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff81272e6e)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812763b5)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap.c (ffffffff8129c6a5)
Location: include/linux/highmem.h:193
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812c64a1)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff812ce9d2)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/move_extent.c (ffffffff813064cc)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff81310647)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/readpage.c (ffffffff81312db6)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff813388e6)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffffffff8134db31)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_short_read
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
In mm/truncate.c (ffffffff811c54ad)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811d02e0)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (ffffffff812705a7)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/buffer.c (ffffffff81280133)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff81286980)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff8128a0f5)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap.c (ffffffff812b13c5)
Location: include/linux/highmem.h:193
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812dbd4d)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff812e47cd)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/move_extent.c (ffffffff8131c48c)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff81326477)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/readpage.c (ffffffff81328d66)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff8134e686)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffffffff8136343c)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_short_read
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
In mm/truncate.c (ffffffff811cd956)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811d8d53)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (ffffffff8127dcb6)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/buffer.c (ffffffff8128da33)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff81294012)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff81296c5f)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap.c (ffffffff812be879)
Location: include/linux/highmem.h:193
Inline: True
```
```
In fs/ext4/inline.c (ffffffff812fa3fc)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81300591)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff81315037)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff8131e49c)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff8131e821)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff813631e7)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffffffff81377d8c)
Location: include/linux/highmem.h:193
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_short_read
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
In mm/truncate.c (ffffffff811e2c46)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811edfd3)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (ffffffff812a0793)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/buffer.c (ffffffff812b05ed)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff812b6f75)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812b9eca)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap.c (ffffffff812e22fd)
Location: include/linux/highmem.h:194
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8131ea2c)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81324db4)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff81339dd2)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff81342abc)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813431ac)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff81387eab)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffffffff8139cb59)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_short_read
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
In mm/truncate.c (ffffffff812041fc)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8120f436)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (ffffffff812c6d05)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/buffer.c (ffffffff812d83db)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff812e002d)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812e2c7c)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap.c (ffffffff8130ec59)
Location: include/linux/highmem.h:194
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8134ca81)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81353012)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff81368326)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff81370a0c)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81370f0f)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff813b6a2d)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffffffff813cbf64)
Location: include/linux/highmem.h:194
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_short_read
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
In mm/truncate.c (ffffffff81216bbc)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81221c68)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (ffffffff812dbed5)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/buffer.c (ffffffff812ed8ab)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff812f4b59)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812f78de)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap.c (ffffffff813251af)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/iomap.c:iomap_read_page_sync
  - fs/iomap.c:iomap_read_page_sync
  - fs/iomap.c:iomap_readpage_actor
  - fs/iomap.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff81364bc1)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8136b13f)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813807a9)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff81388ea1)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813893b1)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff813cff7d)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffffffff813e5024)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_short_read
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
In mm/truncate.c (ffffffff81226572)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81231510)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (ffffffff812fa57c)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/buffer.c (ffffffff8130f069)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff81315f11)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81317f29)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8134be5e)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff8138e421)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8139467f)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813a95da)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813b2fa5)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813b3584)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff813fab6c)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffffffff81410a9d)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_short_read
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
In mm/truncate.c (ffffffff812343de)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8123f5d0)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (ffffffff8130c2fc)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/buffer.c (ffffffff81323bf3)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff81328d91)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff8132ad9f)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8136412e)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff813a6e81)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813acfff)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813c24fa)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813cc027)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813cc77a)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff81414a3c)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffffffff8142a6ad)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
```
```
In block/bio.c (ffffffff814dfa2a)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - block/bio.c:bio_truncate
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
In mm/truncate.c (ffffffff812619ab)
Location: include/linux/highmem.h:287
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8126ce16)
Location: include/linux/highmem.h:287
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (ffffffff813457e2)
Location: include/linux/highmem.h:287
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/buffer.c (ffffffff8135ca63)
Location: include/linux/highmem.h:287
Inline: True
Inline callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:page_zero_new_buffers
```
```
In fs/direct-io.c (ffffffff81362e3c)
Location: include/linux/highmem.h:287
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff8136480b)
Location: include/linux/highmem.h:287
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff813aca7f)
Location: include/linux/highmem.h:287
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff813f2f67)
Location: include/linux/highmem.h:287
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813f932d)
Location: include/linux/highmem.h:287
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff8140ec0f)
Location: include/linux/highmem.h:287
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81418150)
Location: include/linux/highmem.h:287
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81418ae3)
Location: include/linux/highmem.h:287
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff81462cc2)
Location: include/linux/highmem.h:287
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffffffff8147a7f5)
Location: include/linux/highmem.h:287
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
```
```
In block/bio.c (ffffffff8153e93f)
Location: include/linux/highmem.h:287
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void zero_user_segments(struct page *page, unsigned int start1, unsigned int end1, unsigned int start2, unsigned int end2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/truncate.c (ffffffff8126ad80)
Location: include/linux/highmem.h:215
Inline: True
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81276e30)
Location: include/linux/highmem.h:215
Inline: True
Direct callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (ffffffff81351d50)
Location: include/linux/highmem.h:215
Inline: True
Direct callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/buffer.c (ffffffff813675d0)
Location: include/linux/highmem.h:215
Inline: True
Direct callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:page_zero_new_buffers
```
```
In fs/direct-io.c (ffffffff8136f3a0)
Location: include/linux/highmem.h:215
Inline: True
Direct callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff813712a0)
Location: include/linux/highmem.h:215
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff813bbc60)
Location: include/linux/highmem.h:215
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff814056bb)
Location: include/linux/highmem.h:215
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff814083e0)
Location: include/linux/highmem.h:215
Inline: True
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff81421d10)
Location: include/linux/highmem.h:215
Inline: True
Direct callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff8142aec0)
Location: include/linux/highmem.h:215
Inline: True
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff8142c67a)
Location: include/linux/highmem.h:215
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
Direct callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff8147e544)
Location: include/linux/highmem.h:215
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffffffff81491790)
Location: include/linux/highmem.h:215
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
```
```
In block/bio.c (ffffffff8155aab8)
Location: include/linux/highmem.h:215
Inline: True
```
**Symbols:**

```
ffffffff8126ad80-ffffffff8126ae1e: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81276e30-ffffffff81276f13: zero_user_segments (STB_LOCAL)
ffffffff81351d50-ffffffff81351e34: zero_user_segments (STB_LOCAL)
ffffffff813675d0-ffffffff813676b5: zero_user_segments (STB_LOCAL)
ffffffff8136f3a0-ffffffff8136f43f: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff813712a0-ffffffff81371399: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff813bbc60-ffffffff813bbd45: zero_user_segments (STB_LOCAL)
ffffffff81403f00-ffffffff81403ff9: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff814083e0-ffffffff814084c4: zero_user_segments (STB_LOCAL)
ffffffff81421d10-ffffffff81421daf: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff8142aec0-ffffffff8142afb9: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff8142bd10-ffffffff8142be09: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff8147df10-ffffffff8147e009: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81491790-ffffffff8149182e: zero_user_segments.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void zero_user_segments(struct page *page, unsigned int start1, unsigned int end1, unsigned int start2, unsigned int end2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/truncate.c (ffffffff8126ff30)
Location: include/linux/highmem.h:215
Inline: True
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8127be90)
Location: include/linux/highmem.h:215
Inline: True
Direct callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (ffffffff81358a70)
Location: include/linux/highmem.h:215
Inline: True
Direct callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/buffer.c (ffffffff8136e010)
Location: include/linux/highmem.h:215
Inline: True
Direct callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:page_zero_new_buffers
```
```
In fs/direct-io.c (ffffffff81375c50)
Location: include/linux/highmem.h:215
Inline: True
Direct callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81377c50)
Location: include/linux/highmem.h:215
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff813c38f0)
Location: include/linux/highmem.h:215
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff8140b9f9)
Location: include/linux/highmem.h:215
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
Direct callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8140e6f0)
Location: include/linux/highmem.h:215
Inline: True
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff81428510)
Location: include/linux/highmem.h:215
Inline: True
Direct callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81431a30)
Location: include/linux/highmem.h:215
Inline: True
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81433349)
Location: include/linux/highmem.h:215
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
Direct callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff81484018)
Location: include/linux/highmem.h:215
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/fuse/file.c (ffffffff814966b0)
Location: include/linux/highmem.h:215
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
```
```
In block/bio.c (ffffffff815630bf)
Location: include/linux/highmem.h:215
Inline: True
```
**Symbols:**

```
ffffffff8126ff30-ffffffff8126ffcf: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff8127be90-ffffffff8127bf78: zero_user_segments (STB_LOCAL)
ffffffff81358a70-ffffffff81358b58: zero_user_segments (STB_LOCAL)
ffffffff8136e010-ffffffff8136e0f8: zero_user_segments (STB_LOCAL)
ffffffff81375c50-ffffffff81375cef: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81377c50-ffffffff81377d49: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff813c38f0-ffffffff813c39d8: zero_user_segments (STB_LOCAL)
ffffffff8140a630-ffffffff8140a729: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff8140e6f0-ffffffff8140e7d8: zero_user_segments (STB_LOCAL)
ffffffff81428510-ffffffff814285af: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81431a30-ffffffff81431b29: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff814329d0-ffffffff81432ac9: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff814839e0-ffffffff81483ad9: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff814966b0-ffffffff8149674f: zero_user_segments.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void zero_user_segments(struct page *page, unsigned int start1, unsigned int end1, unsigned int start2, unsigned int end2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/truncate.c (0)
Location: include/linux/highmem.h:201
Inline: True
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff812ba0d0)
Location: include/linux/highmem.h:201
Inline: True
Direct callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (ffffffff813a7171)
Location: include/linux/highmem.h:201
Inline: True
Direct callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/buffer.c (ffffffff813bce42)
Location: include/linux/highmem.h:201
Inline: True
Direct callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (0)
Location: include/linux/highmem.h:201
Inline: True
Direct callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (0)
Location: include/linux/highmem.h:201
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff81412262)
Location: include/linux/highmem.h:201
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/ext4/inline.c (0)
Location: include/linux/highmem.h:201
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81461691)
Location: include/linux/highmem.h:201
Inline: True
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/highmem.h:201
Inline: True
Direct callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (0)
Location: include/linux/highmem.h:201
Inline: True
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/highmem.h:201
Inline: True
Direct callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff814db1ed)
Location: include/linux/highmem.h:201
Inline: True
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (0)
Location: include/linux/highmem.h:201
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
```
```
In block/bio.c (ffffffff815c6c5c)
Location: include/linux/highmem.h:201
Inline: True
```
**Symbols:**

```
ffffffff812ad320-ffffffff812ad3ff: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81cba5b8-ffffffff81cba5f1: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff812ba000-ffffffff812ba115: zero_user_segments (STB_LOCAL)
ffffffff81cba914-ffffffff81cba964: zero_user_segments.cold (STB_LOCAL)
ffffffff813a70a0-ffffffff813a71b7: zero_user_segments (STB_LOCAL)
ffffffff81cc40ae-ffffffff81cc4107: zero_user_segments.cold (STB_LOCAL)
ffffffff813bcd70-ffffffff813bce88: zero_user_segments (STB_LOCAL)
ffffffff81cc4355-ffffffff81cc43b7: zero_user_segments.cold (STB_LOCAL)
ffffffff813c2070-ffffffff813c2157: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81cc492b-ffffffff81cc497a: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff813c42d0-ffffffff813c4408: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81cc5000-ffffffff81cc5039: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff81412190-ffffffff814122a8: zero_user_segments (STB_LOCAL)
ffffffff81cc767c-ffffffff81cc76de: zero_user_segments.cold (STB_LOCAL)
ffffffff8145d240-ffffffff8145d378: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81cca692-ffffffff81cca6cb: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff814615c0-ffffffff814616d7: zero_user_segments (STB_LOCAL)
ffffffff81cca7d9-ffffffff81cca832: zero_user_segments.cold (STB_LOCAL)
ffffffff8147c200-ffffffff8147c2e7: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81ccc974-ffffffff81ccc9c3: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff81485240-ffffffff81485378: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81cccda8-ffffffff81cccde1: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff814864d0-ffffffff81486608: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81ccce78-ffffffff81ccceb1: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff814db160-ffffffff814db298: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81cd0b69-ffffffff81cd0ba2: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff814edf50-ffffffff814ee02f: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81cd206e-ffffffff81cd20a7: zero_user_segments.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void zero_user_segments(struct page *page, unsigned int start1, unsigned int end1, unsigned int start2, unsigned int end2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/truncate.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - mm/truncate.c:truncate_inode_partial_folio
```
```
In mm/shmem.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/secretmem.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - mm/secretmem.c:secretmem_free_folio
  - mm/secretmem.c:secretmem_free_folio
```
```
In fs/libfs.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_read_folio
```
```
In fs/buffer.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/ext4/inline.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
```
```
In block/bio.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - block/bio.c:guard_bio_eod
```
**Symbols:**

```
ffffffff81307c70-ffffffff81307e03: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81e6be15-ffffffff81e6be5e: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff81317640-ffffffff813178b5: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81e6c2b0-ffffffff81e6c2f0: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff813e36c0-ffffffff813e3847: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81e75baf-ffffffff81e75be8: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff8142c4f0-ffffffff8142c699: zero_user_segments (STB_LOCAL)
ffffffff81e769af-ffffffff81e76a07: zero_user_segments.cold (STB_LOCAL)
ffffffff814431f0-ffffffff814433c8: zero_user_segments (STB_LOCAL)
ffffffff81e76d12-ffffffff81e76d72: zero_user_segments.cold (STB_LOCAL)
ffffffff81448f50-ffffffff814490e3: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81e77335-ffffffff81e7737e: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff8144af80-ffffffff8144b145: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81e77a09-ffffffff81e77a42: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff81488100-ffffffff814882d8: zero_user_segments (STB_LOCAL)
ffffffff81e79ccb-ffffffff81e79d2b: zero_user_segments.cold (STB_LOCAL)
ffffffff814dbd90-ffffffff814dbf55: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81e7d3c9-ffffffff81e7d402: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff814e0720-ffffffff814e08c9: zero_user_segments (STB_LOCAL)
ffffffff81e7d63f-ffffffff81e7d697: zero_user_segments.cold (STB_LOCAL)
ffffffff814fe8a0-ffffffff814fea33: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81e7f863-ffffffff81e7f8ac: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff815085a0-ffffffff81508765: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81e7fc79-ffffffff81e7fcb2: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff81509970-ffffffff81509b35: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81e7fd55-ffffffff81e7fd8e: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff81554840-ffffffff815549d3: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81e8254e-ffffffff81e82597: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff81568d30-ffffffff81568ef5: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81e83de8-ffffffff81e83e21: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff8157d650-ffffffff8157d7b4: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81e85192-ffffffff81e851cb: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff81671bc0-ffffffff81671d53: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff81e8b352-ffffffff81e8b39b: zero_user_segments.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void zero_user_segments(struct page *page, unsigned int start1, unsigned int end1, unsigned int start2, unsigned int end2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/truncate.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - mm/truncate.c:truncate_inode_partial_folio
```
```
In mm/shmem.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_writepage
```
```
In mm/secretmem.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - mm/secretmem.c:secretmem_free_folio
  - mm/secretmem.c:secretmem_free_folio
```
```
In fs/libfs.c (0)
Location: include/linux/highmem.h:272
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_read_folio
```
```
In fs/buffer.c (0)
Location: include/linux/highmem.h:272
Inline: False
Direct callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/highmem.h:272
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/ext4/inline.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (0)
Location: include/linux/highmem.h:272
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
```
```
In block/bio.c (0)
Location: include/linux/highmem.h:272
Inline: True
Direct callers:
  - block/bio.c:guard_bio_eod
```
**Symbols:**

```
ffffffff81371380-ffffffff81371516: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff82062737-ffffffff82062780: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff8138a720-ffffffff8138a8ba: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff82062cf8-ffffffff82062d48: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff8146b090-ffffffff8146b21a: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff8206854a-ffffffff82068583: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff814b9b20-ffffffff814b9cc8: zero_user_segments (STB_LOCAL)
ffffffff82068d05-ffffffff82068d5d: zero_user_segments.cold (STB_LOCAL)
ffffffff814d2530-ffffffff814d26d8: zero_user_segments (STB_LOCAL)
ffffffff82068ec5-ffffffff82068f1d: zero_user_segments.cold (STB_LOCAL)
ffffffff814d7240-ffffffff814d73d6: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff8206931e-ffffffff82069367: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff814d97b0-ffffffff814d997d: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff82069a52-ffffffff82069a8b: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff8151bd80-ffffffff8151bf53: zero_user_segments (STB_LOCAL)
ffffffff8206ac02-ffffffff8206ac62: zero_user_segments.cold (STB_LOCAL)
ffffffff81574d10-ffffffff81574edd: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff8206d936-ffffffff8206d96f: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff81579980-ffffffff81579b28: zero_user_segments (STB_LOCAL)
ffffffff8206dbac-ffffffff8206dc04: zero_user_segments.cold (STB_LOCAL)
ffffffff815990e0-ffffffff81599276: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff8206fd55-ffffffff8206fd9e: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff815a3090-ffffffff815a325d: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff82070139-ffffffff82070172: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff815a45e0-ffffffff815a47ad: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff820701df-ffffffff82070218: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff815f6310-ffffffff815f64a6: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff82071877-ffffffff820718c0: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff8160c6a0-ffffffff8160c86d: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff82072499-ffffffff820724d2: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff81623150-ffffffff816232bc: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff820726a0-ffffffff820726d9: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff8172d480-ffffffff8172d616: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff82075bcc-ffffffff82075c15: zero_user_segments.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void zero_user_segments(struct page *page, unsigned int start1, unsigned int end1, unsigned int start2, unsigned int end2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/truncate.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - mm/truncate.c:truncate_inode_partial_folio
```
```
In mm/shmem.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_writepage
```
```
In mm/secretmem.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - mm/secretmem.c:secretmem_free_folio
```
```
In fs/libfs.c (0)
Location: include/linux/highmem.h:268
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_read_folio
```
```
In fs/buffer.c (0)
Location: include/linux/highmem.h:268
Inline: False
Direct callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:folio_zero_new_buffers
```
```
In fs/mpage.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/direct-io.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/highmem.h:268
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/ext4/inline.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_folio
```
```
In fs/ext4/inode.c (0)
Location: include/linux/highmem.h:268
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
```
```
In block/bio.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - block/bio.c:guard_bio_eod
```
**Symbols:**

```
ffffffff813a3550-ffffffff813a3628: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff820e1ed6-ffffffff820e1f25: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff813bcab0-ffffffff813bcbb1: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff820e2534-ffffffff820e258d: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff8149ff50-ffffffff814a0018: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff820e7e15-ffffffff820e7e57: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff814eeac0-ffffffff814eec26: zero_user_segments (STB_LOCAL)
ffffffff820e8627-ffffffff820e8680: zero_user_segments.cold (STB_LOCAL)
ffffffff81508ce0-ffffffff81508deb: zero_user_segments (STB_LOCAL)
ffffffff820e87e0-ffffffff820e8839: zero_user_segments.cold (STB_LOCAL)
ffffffff8150d810-ffffffff8150d8e8: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff820e8d52-ffffffff820e8da1: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff815102f0-ffffffff815103c8: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff820e93ab-ffffffff820e93fa: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff81554090-ffffffff8155419c: zero_user_segments (STB_LOCAL)
ffffffff820eab9b-ffffffff820eabfd: zero_user_segments.cold (STB_LOCAL)
ffffffff815acbe0-ffffffff815accb8: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff820ed5eb-ffffffff820ed63a: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff815b0910-ffffffff815b0a1b: zero_user_segments (STB_LOCAL)
ffffffff820ed71a-ffffffff820ed773: zero_user_segments.cold (STB_LOCAL)
ffffffff815cfbc0-ffffffff815cfc98: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff820ef8f3-ffffffff820ef942: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff815d9a70-ffffffff815d9b48: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff820efcae-ffffffff820efcfd: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff815daf20-ffffffff815daff8: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff820efde8-ffffffff820efe37: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff8162e490-ffffffff8162e568: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff820f14d9-ffffffff820f1528: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff81644590-ffffffff816446be: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff820f20b4-ffffffff820f20e6: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff8165b5d0-ffffffff8165b69c: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff820f2320-ffffffff820f2352: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff81769740-ffffffff81769818: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff820f5a17-ffffffff820f5a66: zero_user_segments.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void zero_user_segments(struct page *page, unsigned int start1, unsigned int end1, unsigned int start2, unsigned int end2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/truncate.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - mm/truncate.c:truncate_inode_partial_folio
```
```
In mm/shmem.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_writepage
```
```
In mm/secretmem.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - mm/secretmem.c:secretmem_free_folio
```
```
In fs/libfs.c (0)
Location: include/linux/highmem.h:268
Inline: False
Direct callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_read_folio
```
```
In fs/buffer.c (0)
Location: include/linux/highmem.h:268
Inline: False
Direct callers:
  - fs/buffer.c:block_write_full_folio
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:folio_zero_new_buffers
```
```
In fs/mpage.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/direct-io.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/highmem.h:268
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/ext4/inline.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (0)
Location: include/linux/highmem.h:268
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
```
```
In block/bio.c (0)
Location: include/linux/highmem.h:268
Inline: True
Direct callers:
  - block/bio.c:guard_bio_eod
```
**Symbols:**

```
ffffffff813cd100-ffffffff813cd1ce: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff821be8fa-ffffffff821be941: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff813e7900-ffffffff813e7a00: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff821bef2c-ffffffff821bef80: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff814cf6a0-ffffffff814cf765: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff821c4b5b-ffffffff821c4b9c: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff81522aa0-ffffffff81522baf: zero_user_segments (STB_LOCAL)
ffffffff821c5381-ffffffff821c53dd: zero_user_segments.cold (STB_LOCAL)
ffffffff8153dfa0-ffffffff8153e0af: zero_user_segments (STB_LOCAL)
ffffffff821c5657-ffffffff821c56b3: zero_user_segments.cold (STB_LOCAL)
ffffffff81542530-ffffffff815425fe: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff821c59ec-ffffffff821c5a33: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff815447a0-ffffffff8154486e: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff821c5f1e-ffffffff821c5f65: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff8158a070-ffffffff8158a17f: zero_user_segments (STB_LOCAL)
ffffffff821c7916-ffffffff821c7972: zero_user_segments.cold (STB_LOCAL)
ffffffff815e5b10-ffffffff815e5bd5: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff821ca72e-ffffffff821ca76f: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff815e9840-ffffffff815e994a: zero_user_segments (STB_LOCAL)
ffffffff821ca832-ffffffff821ca886: zero_user_segments.cold (STB_LOCAL)
ffffffff81608450-ffffffff8160851e: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff821cc9da-ffffffff821cca21: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff816127a0-ffffffff8161286e: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff821cce7b-ffffffff821ccec2: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff81613750-ffffffff8161381e: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff821ccfb7-ffffffff821ccffe: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff81667950-ffffffff81667a1e: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff821ce77b-ffffffff821ce7c2: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff8167dac0-ffffffff8167dbe3: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff821cf396-ffffffff821cf3c7: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff816952b0-ffffffff81695375: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff821cf5d1-ffffffff821cf602: zero_user_segments.constprop.0.cold (STB_LOCAL)
ffffffff817ab960-ffffffff817aba2e: zero_user_segments.constprop.0 (STB_LOCAL)
ffffffff821d2d0b-ffffffff821d2d52: zero_user_segments.constprop.0.cold (STB_LOCAL)
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
In mm/truncate.c (ffff8000102c4a00)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffff8000102d0de8)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (ffff8000103c0b08)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/buffer.c (ffff8000103dcf84)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffff8000103e42a8)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffff8000103e6410)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffff80001042b450)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffff80001047a664)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffff8000104818b0)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffff800010499f2c)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffff8000104a40a0)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffff8000104a4c04)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffff8000104f61ec)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffff80001050e6bc)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
```
```
In block/bio.c (ffff8000105dc598)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - block/bio.c:bio_truncate
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
In mm/truncate.c (c04ef2e8)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (c04fadac)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (c059e018)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/buffer.c (c05b4b04)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (c05bc1f8)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (c05bdf1c)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (c05f3e9c)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (c063c0b4)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (c064295c)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (c065b6f0)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (c0666088)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (c06668a0)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (c06b3cc0)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (c06c9e38)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
```
```
In block/bio.c (c0789a04)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - block/bio.c:bio_truncate
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
In mm/truncate.c (c00000000037f1a0)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (c0000000003910d4)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (c0000000004bf2b0)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/buffer.c (c0000000004e2650)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (c0000000004ea38c)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (c0000000004ec668)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (c00000000053c4a4)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (c00000000059d578)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (c0000000005a5e98)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (c0000000005c424c)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (c0000000005d12a0)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (c0000000005d1da4)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (c0000000006370ac)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (c000000000655830)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
```
```
In block/bio.c (c00000000076d63c)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - block/bio.c:bio_truncate
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
In mm/truncate.c (ffffffe0001e52aa)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffe0001ede9c)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (ffffffe0002810aa)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/buffer.c (ffffffe000295136)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffe000299d3c)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffe00029b730)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffe0002c8d4c)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffe000304f28)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffe00030a47c)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffe00031d59e)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffe000325574)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffe000325d08)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffe000365000)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffffffe00037927a)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
```
```
In block/bio.c (ffffffe00041f906)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - block/bio.c:bio_truncate
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
In mm/truncate.c (ffffffff8122ca2e)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81237c20)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (ffffffff813048dc)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/buffer.c (ffffffff8131c1d3)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff81321371)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff8132337f)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8135c70e)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff8139f461)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813a55df)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813baada)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813c4607)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813c4d5a)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff8140d01c)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffffffff81422c8d)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
```
```
In block/bio.c (ffffffff814d800a)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - block/bio.c:bio_truncate
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
In mm/truncate.c (ffffffff8121fb0e)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8122ac60)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (ffffffff812f54fc)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/buffer.c (ffffffff8130cd73)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff81311f11)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81313f1f)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8134d3ae)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff8138fef1)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8139606f)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813ab56a)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813b5087)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813b57da)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff813fda9c)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffffffff8141370d)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
```
```
In block/bio.c (ffffffff814c89ba)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - block/bio.c:bio_truncate
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
In mm/truncate.c (ffffffff8122a7ce)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff812359c0)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (ffffffff813026cc)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/buffer.c (ffffffff81319ca3)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff8131ee41)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81320e4f)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8135a1de)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff8139ccc1)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813a2e3f)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813b833a)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813c1a97)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813c21ea)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff8140a39c)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffffffff8141ee2d)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
```
```
In block/bio.c (ffffffff814d409a)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - block/bio.c:bio_truncate
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
In mm/truncate.c (ffffffff81239ba6)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81245c95)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In fs/libfs.c (ffffffff81313cec)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
```
```
In fs/buffer.c (ffffffff8132b963)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff81330b48)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81332b6f)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8136d90e)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff813b11d1)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813b7512)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813cd03a)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813d6bf7)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813d7374)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff8142008c)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffffffff81435b8d)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
```
```
In block/bio.c (ffffffff814ecc2a)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - block/bio.c:bio_truncate
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
