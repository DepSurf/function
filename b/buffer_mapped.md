# Function: <code>buffer_mapped</code>

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
In fs/ioctl.c (ffffffff8121fbf9)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff81242dbb)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:__find_get_block_slow
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
```
```
In fs/direct-io.c (ffffffff8124a5a2)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff8124d82a)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/dax.c (ffffffff8125dd8f)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/dax.c:__dax_fault
  - fs/dax.c:__dax_fault
  - fs/dax.c:dax_do_io
  - fs/dax.c:dax_zero_page_range
```
```
In fs/ext4/inode.c (ffffffff81295cf5)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_bh_unmapped
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
```
```
In fs/ext4/page-io.c (ffffffff8129fed5)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/move_extent.c (ffffffff812d6c01)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
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
In fs/ioctl.c (ffffffff8124746b)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff8126cf44)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/direct-io.c (ffffffff81272f7c)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff81275f8c)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/dax.c (ffffffff81286a85)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/dax.c:dax_zero_page_range
  - fs/dax.c:dax_fault
  - fs/dax.c:dax_fault
  - fs/dax.c:dax_do_io
```
```
In fs/ext4/inode.c (ffffffff812cdb0a)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff812ce7d1)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/move_extent.c (ffffffff813068e1)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
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
In fs/ioctl.c (ffffffff8125a44c)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff812801d4)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:init_page_buffers
```
```
In fs/direct-io.c (ffffffff81286a70)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff81289c76)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inode.c (ffffffff812e38e6)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff812e45b1)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/move_extent.c (ffffffff8131c885)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
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
In fs/ioctl.c (ffffffff81266dfd)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff8128dab4)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:init_page_buffers
```
```
In fs/direct-io.c (ffffffff812940fa)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff8129695b)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inode.c (ffffffff813079f0)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813153fb)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff8131e26e)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ioctl.c (ffffffff81289693)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff812b0671)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:init_page_buffers
```
```
In fs/direct-io.c (ffffffff812b702b)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812b9bbb)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inode.c (ffffffff8132c640)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_dio_get_block_overwrite
```
```
In fs/ext4/move_extent.c (ffffffff81339c07)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff8134288e)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ioctl.c (ffffffff812af9a8)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff812d8467)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:init_page_buffers
```
```
In fs/direct-io.c (ffffffff812df9ea)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812e272f)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inode.c (ffffffff8135ac15)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_dio_get_block_overwrite
```
```
In fs/ext4/move_extent.c (ffffffff8136821f)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff8137070e)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/super.c (ffffffff81383d51)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
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
In fs/ioctl.c (ffffffff812c4b69)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff812ed93a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:init_page_buffers
```
```
In fs/direct-io.c (ffffffff812f4517)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812f739b)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inode.c (ffffffff81372ed5)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_dio_get_block_overwrite
```
```
In fs/ext4/move_extent.c (ffffffff813806a2)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff81388b9d)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/super.c (ffffffff8139c831)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
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
In fs/ioctl.c (ffffffff812e1655)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff8130f10a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:init_page_buffers
```
```
In fs/direct-io.c (ffffffff81315e73)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff813179ca)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inode.c (ffffffff8139c31a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813a94f3)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813b2c8d)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/super.c (ffffffff813c6a8e)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffff813e006d)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ioctl.c (ffffffff812f3125)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff8132206a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:init_page_buffers
```
```
In fs/direct-io.c (ffffffff81328cf3)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff8132a84a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inode.c (ffffffff813b4e2a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813c2413)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813cbcfb)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/super.c (ffffffff813dfe4e)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffff813fa0ad)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ioctl.c (ffffffff8132b85a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff8135d84d)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/direct-io.c (ffffffff81362d9d)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff813644fe)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inode.c (ffffffff814002ab)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_add_bh_to_extent
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:do_journal_get_write_access
```
```
In fs/ext4/move_extent.c (ffffffff8140eb02)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81417e4c)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/journal.c (ffffffff8144766d)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ioctl.c (ffffffff81336e1a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff8136b43d)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/direct-io.c (ffffffff813700f3)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81371500)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inode.c (ffffffff81412aa5)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_should_update_i_disksize
  - fs/ext4/inode.c:mpage_add_bh_to_extent
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:do_journal_get_write_access
```
```
In fs/ext4/move_extent.c (ffffffff8142200a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff8142b951)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/journal.c (ffffffff81463ffb)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ioctl.c (ffffffff8133cf7a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff81371cdd)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/direct-io.c (ffffffff81376992)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff813787d0)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inode.c (ffffffff81418f05)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:do_journal_get_write_access
```
```
In fs/ext4/move_extent.c (ffffffff814286ce)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81432570)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/journal.c (ffffffff814696ab)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff813c0cfd)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/direct-io.c (ffffffff813c2f20)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff813c50e2)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inode.c (ffffffff8146c139)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:do_journal_get_write_access
```
```
In fs/ext4/move_extent.c (ffffffff8147c419)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81485e30)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/journal.c (ffffffff814bfb4b)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff814479aa)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/direct-io.c (ffffffff81449d68)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff8144c057)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inode.c (ffffffff814ec154)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:do_journal_get_write_access
```
```
In fs/ext4/move_extent.c (ffffffff814febf2)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81509410)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/super.c (ffffffff815254ea)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffff8154a2db)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff814d6506)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/direct-io.c (ffffffff814d852b)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff814da4e4)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inode.c (ffffffff81585ebe)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:write_end_fn
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:do_journal_get_write_access
```
```
In fs/ext4/move_extent.c (ffffffff81599440)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff815a3fce)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/super.c (ffffffff815c2b4a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffff815e9c3b)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff8150ca76)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:folio_init_buffers
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/mpage.c (ffffffff8150ea0a)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/direct-io.c (ffffffff8151138b)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/ext4/inode.c (ffffffff815bc79b)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:write_end_fn
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:do_journal_get_write_access
```
```
In fs/ext4/move_extent.c (ffffffff815cfd96)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff815daa29)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/ext4/super.c (ffffffff815fa2aa)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffff81621a2b)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff815416e6)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:folio_init_buffers
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/mpage.c (ffffffff8154331e)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/direct-io.c (ffffffff8154582b)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/ext4/inode.c (ffffffff815f557a)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:write_end_fn
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:do_journal_get_write_access
```
```
In fs/ext4/move_extent.c (ffffffff81608613)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81613236)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/ext4/super.c (ffffffff81632eaa)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffff81659f4b)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ioctl.c (ffff80001039de74)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffff8000103dadbc)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:init_page_buffers
```
```
In fs/direct-io.c (ffff8000103e41e8)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffff8000103e6024)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inode.c (ffff8000104895c4)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffff800010499e44)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffff8000104a3ea0)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/super.c (ffff8000104b8ea4)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffff8000104d6f20)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ioctl.c (c058318c)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (c05b416c)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:init_page_buffers
```
```
In fs/direct-io.c (c05bc0a8)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (c05bdb8c)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inode.c (c064bb0c)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (c065b640)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (c0665d24)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/super.c (c067c4ec)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (c069904c)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ioctl.c (c0000000004985f8)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (c0000000004e0008)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:init_page_buffers
```
```
In fs/direct-io.c (c0000000004ea2c0)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (c0000000004ec1a8)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inode.c (c0000000005b0628)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (c0000000005c4100)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (c0000000005d0fa8)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/super.c (c0000000005edf84)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (c000000000611a58)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ioctl.c (ffffffe000269722)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffe0002937e2)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:init_page_buffers
```
```
In fs/direct-io.c (ffffffe00029a018)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffe00029b406)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inode.c (ffffffe000310d70)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffe00031d5fc)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffe0003253f0)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/super.c (ffffffe0003357cc)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffe00034ceda)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ioctl.c (ffffffff812eb705)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff8131a64a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:init_page_buffers
```
```
In fs/direct-io.c (ffffffff813212d3)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81322e2a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inode.c (ffffffff813ad40a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813ba9f3)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813c42db)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/super.c (ffffffff813d842e)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffff813f268d)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ioctl.c (ffffffff812dc335)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff8130b1ea)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:init_page_buffers
```
```
In fs/direct-io.c (ffffffff81311e73)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff813139ca)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inode.c (ffffffff8139de9a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813ab483)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813b4d5b)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/super.c (ffffffff813c8eae)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffff813e310d)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ioctl.c (ffffffff812e9515)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff8131811a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:init_page_buffers
```
```
In fs/direct-io.c (ffffffff8131eda3)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff813208fa)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inode.c (ffffffff813aac6a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813b8253)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813c176b)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/super.c (ffffffff813d58be)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffff813efa0d)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/ioctl.c (ffffffff812fa504)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff81329d3a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:init_page_buffers
```
```
In fs/direct-io.c (ffffffff81330aa3)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff8133261a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inode.c (ffffffff813bf5b5)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813ccf53)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813d68cb)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/super.c (ffffffff813eab3e)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffff8140541d)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
```
</details>
</li>
</ul>

## Differences
